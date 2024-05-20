Ideas from

Architecture:
. Explain how computer vision systems aim to mimic human vision and interpret visual data
. Discuss fundamental image processing techniques. [Edge detection, morphological operations]
. Explain how this techniques are used to process images before passing them to computer vision algorithms

. Discuss methods for extracting information from from the images
. Deep learning architecture for computer vision CNN
	. CNN architecture
	. layers and components of CNN
. Training and optimization
	. training process using labeled database
	. optimization techniques
		1. data augmentation
		2. transfer learning
		3. fine tuning to improve performance
		
		
	
Data Acquisition
Prepossessing
Feature Extraction
Model Selection
Model Training
Model Evaluation
Inference
Post-Processing
Integration
Deployment



//// Copy past work --- ``Delete If Needed``


 -- Spice work article -- 
Convolutional neural networks help ML models see by fractionating images into pixels. Each pixel is given a label or tag to produce a matrix of this labels that the system can now interpret. These labels are then collectively used to carry out convolutions, a mathematical process that combines two functions to produce a third function. Through this process, convolutional neural networks can process visual inputs. [11]

To see images just like a human would, neural networks execute convolutions and examine the accuracy of the output in numerous iterations. Just like humans would discern an object far away, a convolutional neural network begins by identifying rudimentary shapes and hard edges. Once this is done, the model patches the gaps in its data and executes iterations of its output. This goes on until the output accurately ‘predicts’ what is going to happen.

While a convolutional neural network understands single images, a recurrent neural network processes video inputs to enable computers to ‘learn’ how a series of pictures relate to each other.
