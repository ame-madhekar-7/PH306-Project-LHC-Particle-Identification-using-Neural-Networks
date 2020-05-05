PH306-Project---LHC-Particle-Identification-using-Neural-Networks

I have trained a classifier (neural network) to identify the type of a particle. 
There are six particle types: electron, proton, muon, kaon, pion and ghost. Ghost is a particle with type other than the first five or a detector noise. 
Different particle types give different responses in the detector systems or sub detectors. There are five systems: tracking system, ring imaging Cherenkov detector (RICH), electromagnetic and hadronic calorimeters, and muon system. I had to identify a particle type using the responses in the detector systems.

Note : In this Machine Learning model, we have to minimize the log loss to improve the accuracy.
