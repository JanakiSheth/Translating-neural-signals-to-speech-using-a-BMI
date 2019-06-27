# Translating-neural-signals-to-speech-using-a-BMI
This is an ongoing research project, with the aim being to eventually aid patients who have faltering communication abilities. While there is current literature on this, there are multiple constraints on existing systems. We through our work seek to overcome such constraints. Since research is a collaborative effort, we appreciate ideas and improvements to the network. 

Currently the network comprises of 1. deciphering input features from neural signals using coordinate descent and supervised learning. (this is using code that was modified from STRFLab http://strflab.berkeley.edu/)
2. input features are fed into the recurrent neural network to give probabilities for each phoneme that the subject utters. (this is using the python code uploaded here)
3. the probabilities are used to traverse a language model that outputs the resulting word. (collaborator's code, working towards replacing this using an alternative neural network)
