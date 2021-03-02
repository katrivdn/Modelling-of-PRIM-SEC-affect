Computational modelling of the effects of affect on decision-making.
This study aimed to check and explain two main findings in the affective literature:
(1) affective objects are processed more efficiently compared to non-affective stimuli (=primary affective effects)
(2) affective objects have longterm consequences on the judgement of (non-related) stimuli (=secondary affective effects)

DESCRIPTION OF THE TASKS
We designed two experiments to investigate these findings, and modelled them using the hierarchical drift-diffusion
model (Wiecki, T. V. et al.(2013)). Our studies use the Mood of the Crowd paradigm (Bucher, A., & Voss, A. (2019)): subjects had to rate whether a particular emotion 
was more present among an array of 8 faces (study 1) or judge if an array of surprised faces were rather
positive or negative following an affective prime (study 2). Participants had to perform both experiments. 
We changed the task slightly between the two batches:
*In batch 1:*
- study 1: we merged over negative and positive affective faces and compared them to neutral facial expressions. 
- study 2: didn't allow participants to respond to the stimuli while it was presented on the screen.
*In batch 2:*
- study 1: we looked at negative, positive and neutral facial expressions apart from one another.
- study 2: allowed participants to respond to the stimuli while it was still on the screen.

Each experiment was analysed using a linear mixed model, and a DDM (hddm module) [see R & Python scripts]

Sources:
Wiecki, T. V., Sofer, I., & Frank, M. J. (2013). 
HDDM: Hierarchical Bayesian estimation of the drift-diffusion model in Python. 
Frontiers in neuroinformatics, 7, 14.
Bucher, A., & Voss, A. (2019). 
Judging the mood of the crowd: Attention is focused on happy faces. 
Emotion, 19(6), 1044.