# adversarial-machine-learning
attacking machine learning models

# STEPS: 
# Step 1: 
Some reading into adversarial ML – the type where we’re attacking ML by poisoning the training process or evading the trained classifier. Probably a good place to start is: 
  1. The taxonomy paper that outlines what kinds of attacks are out there:
     - Sufficient to look at the shorter conference version: http://dl.acm.org/citation.cfm?id=1128824
     - There is a longer version but only if interested at this point: http://dl.acm.org/citation.cfm?id=1860722
  2. One seminal paper demonstrating how to formulate evasion attacks (against the trained classifier) as an optimisation problem. In this case they were attacking the SVM. The take-away is that the attacks Yi and I are looking at can be done in similar ways. We won’t necessarily use this paper directly, so a brief skim should suffice: http://link.springer.com/chapter/10.1007/978-3-642-40994-3_25 not sure if that’s the right one, but would be interesting/relevant
  
# Step 2: 
Identifying the case study domain: Look at the main papers on predicting policing for example: 
  1. First step: Is there a “top paper” in the domain (v well cited older, or perhaps reporting great results) that specifies that model used, and links to a dataset?
  2. Sort of in parallel: Even if there’s no linked dataset, we could look for an available dataset on crime data and train same learner
  
# Step 3: 
Once we’ve done those preliminaries the research would be:
  1. Then apply attacks to demonstrate why ML is not such an easy panacea in the domain. More care (and a more robust learner) is needed
  2. I.e. a combination of experiments demonstrating we’ve replicated reported results on the same kind of system; demonstrating attack; writing up nicely
  
Depending on how it turns out, how fast we get through it, and your timeline and interests, could be a good thing to writeup as a conference/journal paper/popular article. If it goes that way, myself and Yi can help more with the writing (than supervisors would do for say the final report/thesis) since it is going above and beyond. 
