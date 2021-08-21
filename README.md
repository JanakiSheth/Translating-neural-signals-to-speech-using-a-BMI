# Translating-neural-signals-to-speech-using-a-BMI
This is an ongoing research project, with the aim being to eventually aid patients who have faltering communication abilities. While there is cutting edge research, there are multiple constraints on existing systems. We through our work seek to overcome some of these constraints. Since research is a collaborative effort, we appreciate ideas and improvements to the network. 

Currently the network comprises of 1. deciphering input features from neural signals using coordinate descent and supervised learning. (this is using code that was modified from STRFLab http://strflab.berkeley.edu/)

2. input features are fed into the recurrent neural network to give probabilities for each phoneme that the subject utters. (this is using the python code uploaded here)

3. the probabilities are used to traverse a language model that outputs the resulting word. (collaborator's code, working towards replacing this using an alternative neural network)

Update 11-08-2019: Our paper using the above network for retrospective analysis of individual words is currently under review, (https://arxiv.org/abs/1907.04265). 

Current efforts are being directed towards replicating similar analysis on continuous prose, the corresponding python code to which is in the rnn_continuousdata file. The approach to this code is less to do with applying multiple deep networks but more on the lines of interpreting what they learn in terms of underlying speech. So, consonants are presently split based on voicing, vowels based on the vowel triangle and semivowels based on whether they are glides or liquids. 

Update 21-08-2021: Corresponding paper is published in Biomedical Physics & Engineering Express, https://iopscience.iop.org/article/10.1088/2057-1976/abf6ab/meta


