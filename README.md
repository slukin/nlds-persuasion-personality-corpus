# The Persuasion and Personality Corpus

Version: Version 1.0. Updated January 13, 2017.

This page was migrated from [https://nlds.soe.ucsc.edu/](https://nlds.soe.ucsc.edu/) on Sept 2023.

## Overview 
Americans spend about a third of their time online, with many participating in online conversations on social and political issues. We hypothesize that social media arguments on such issues may be more engaging and persuasive than traditional media summaries, and that particular types of people may be more or less convinced by particular styles of argument, e.g. emotional arguments may resonate with some personalities while factual arguments resonate with others. We report a set of experiments testing at large scale how audience variables interact with argument style to affect the persuasiveness of an argument, an under-researched topic within natural language processing. We show that belief change is affected by personality factors, with conscientious, open and agreeable people being more convinced by emotional arguments.

## The Data
Included in this corpus are a subset of user-generated dialogs from the Internet Argument Corpus exploring the role of affect in persuasive arguments, 637 subjects profiled for the Big Five personality traits and prior beliefs about socio-political issues, and the subjects' response after exposure to user-generated, factual vs. emotional dialogic exchanges compared to the effects on belief change to balanced, curated arguments. 

Short Survey on Personality, Demographic, and Opinions
- screening_survey_encoding.csv: A guide to the questions and how to interpret responses to the screening survey
- screening_survey_response.csv: Responses to screening survey including TIPI, demographic, prior beliefs about 5 topics, and post beliefs after being shown monologue_prompts
- monologue_prompts.csv: Curated, monologic information about 5 topics
- tipi_counts.csv: Computed Big Five counts
- tipi_average.csv: Compares the average computed Big Five  scores from our survey against the national average

Personal Opinions on Ideological Debate Exchanges ('fact/feeling experiment')
- ffpage_results.csv: results from the fact/feeling experiment; includes all the features discussed in the paper
- ffpage: quote, response, fact/feeling information, and IAC unique IDs. Positive 'ffvalues' are factual responses, and negative 'ffvalues' are feeling responses from the IAC.

Worker Partitions (in anon_worker_partitions/)
- neutral_baseline_[topic].csv: workers determined to be 'neutral' in screening experiment
- neutral_[topic].csv: workers determined to be 'neutral' in fact/feeling experiment
- workers_exp1L.csv: workers determined to be entrenched to the left side of the scale, i.e. 'no' side, after the screening experiment
- workers_exp1M.csv: workers determined to be neutral after the screening experiment
- workers_exp1L.csv: workers determined to be entrenched to the right side of the scale, i.e. 'yes' side, after the screening experiment

## Citation
If you use this data in your research, please refer to and cite: 

Stephanie Lukin, Pranav Anand, Marilyn Walker and Steve Whittaker. ["Argument Strength is in the Eye of the Beholder: Audience Effects in Persuasion."](https://www.researchgate.net/profile/Stephanie-Lukin/publication/318740304_Argument_Strength_is_in_the_Eye_of_the_Beholder_Audience_Effects_in_Persuasion/links/59f001b7aca272a250013864/Argument-Strength-is-in-the-Eye-of-the-Beholder-Audience-Effects-in-Persuasion.pdf) 15th European Chapter of the Association for Computational Linguistics (EACL), Valencia, Spain, 2017.

## Related Papers:
- Marilyn A. Walker, Pranav Anand, Jean E. Fox Tree, Rob Abbott, Joseph King. ["A Corpus for Research on Deliberation and Debate."](http://www.lrec-conf.org/proceedings/lrec2012/pdf/1078_Paper.pdf) In Proceedings of the 8th International Conference on Language Resources and Evaluation (LREC), Istanbul, Turkey, 2012.
  

