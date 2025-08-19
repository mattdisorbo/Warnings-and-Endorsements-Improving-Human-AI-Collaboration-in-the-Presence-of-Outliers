# Warnings-and-Endorsements-Improving-Human-AI-Collaboration-in-the-Presence-of-Outliers


This repository contains the experimental data from the three experiments presented in the manuscript "Warnings and Endorsements: Improving Human-AI Collaboration in the Presence of Outliers". The authors are Matthew DosSantos DiSorbo, Kris Johnson Ferreira, Maya Balakrishnan and Jordan Tong. 

Any questions for the research team should be directed to mattdisorbo@gmail.com

The data is de-anonymized and only includes variables relevant to the analysis presented in our manuscript. Each row provides session data from one participant. Variable descriptions are as follows:

- Includes "_practice_prediction" string: indicates a participant's adjustment (in Experiment I) or prediction (in Experiments II and III) on a Practice Stage prediction.
- Includes "_Q220" string: indicates a participant's adjustment (in Experiment I) or prediction (in Experiments II and III) on a Final Stage prediction.
- condition: string that indicates the experimental condition the participant was assigned to
- task_x_vals, where, for instance, x might be "salespeople", "noise", etc.: comma-separated experimental values. Note that these include practice stage and then final stage values (in order). For example, in task_demand_vals gives the final demand values in the practice and final stages. Experiment III includes squared Mahalanobis distance values relative to the training set.
- comprehensionx (for x in 1, 2, or 3): indicates (=1) if a participant failed a comprehension check. In Experiment I, inattention_fail_first and inattention_final_ind indicate (=1) if participants answered incorrectly both times when calculating a potential bonus.
  
