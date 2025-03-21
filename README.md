# CODA-model-with-labelling
 
This repository was created to support the manuscript 'The effect of community-bounded social learning on political discourse'. It contains the following 

1) ODD protocol
2) Supporting information
3) Data used to generate all plots in the main manuscript and supporting information:
3a) All the files "timeplot….csv" allow to plot timeevolution of cosine similiratiny and Shannon-Wiener index, as presented in the main manuscript; they contain the following colummns: 
'timestep','num-issues','num-choices','num-labels','strenght-of-influence', 'multi-issue-discourse','ignorring','prob-droping-label','SW-index','cosine-similarity'
3b) "labels_level.csv" describes the time evolution of the distribution of agents holding a given preferred choice within the labels; the columns are:
'timestep',label', 'choices-distribution'. 
The latter is a vector of number of agents with given preferred choice. 
3c) "agents_level.csv" contains data on how the strength of each choice evolves for individual agents; the columns are:
'timestep','agent','label','pref_choice','strenght-of-choices', where 'pref-choice' denotes preferred choice (the one with highest strength), 'strenght-of-choices' is a vector of strengths of each choice. 