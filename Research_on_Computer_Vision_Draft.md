# Research on Computer Vision

List of definitions before work.

1. Artificial Intelligence (AI)
2. Machine Learning (ML)
3. Neural Network



## Introduction ..

A very compelling type artificial intelligence is that of the Computer Vision. Within the field of Artificial intelligence, Computer Vision is a sub field which deals with the identification, recognition and derivation of meaningful information from digital images and video data by teaching models and neural networks to accomplish this specific goals[1].

The human eye over the years with training would be able to tell objects apart by their distinct characteristics and features. It is able to tell the distance from an object or whether an object is moving or still.
Computer vision with a lot of data are trained to do the same thing a human eye would be capable of doing with greater precision and in faster time with image data from cameras and algorithms to surpass that of the human capabilities. This systems have wide area of usage in the industries i.e manufacturing to the automotive industry and growing - the market is valued to be at about USD 20.31 billion expected to grow to about USD 175.72 billion by 2032. [3]


## Definition ...

Computer Vision is a specialised field under Artificial intelligence that focuses on enabling machine to understand the visual world around them through the use of digital image and video data from cameras and deep learning. [2]
It focuses on replicating the complex function of recognition  of the human eye in machines allowing them to produce information from processing visual data (images and videos)


3. ---- Architecture 

	[ A very important aspect to the architecture of computer vision is the area of Deep learning. With the advancement of machine learning and neural networks in the recent years the area of computer vision has seen great leaps in achievements even surpassing humans in some tasks of accurate detection and recognition. ]
	
## Architecture ..
A great deal of computer vision is identifying and understanding patterns from visual data, but before this can be archived the model would have to be trained just like a human would have to be trained to distinguish between different visual data. This training would require a lot of data which could already have been labeled, [7].
To understand this image data being passed, the data would have to be analyzed because at its lowest level, computers only understand 1's and 0'. Convolutional neural networks help ML models see by fractionating images into pixels. Each pixel is given a label or tag to produce a matrix of this labels that the system can now interpret.
These labels are then collectively used to carry out convolutions, a mathematical process that combines two functions to produce a third function. Through this process, convolutional neural networks can process visual inputs. [11]
The model would have to run analysis of data repeatedly till it can recognise patterns and distinctions between them to match the label as accurately as possible.

Typically Computer Vision would be handled in the following steps:
1. Acquiring training data (Images and Videos) [2].
2. Processing the data [2].
3. Understanding the data processed to acquire meaningfully information [2].
	
### Computer Vision and Deep Learning: .
	Deep Learning:
	Deep learning is a subset of Machine learning (ML) where the complex decision-making power of the human brain is simulated with deep neural network which are multi-layered neural network. [6] UNFINISHED
	
	


## Case Study

One of the very important application of Computer Vision is object detection. At this use case, the goal is to precisely  locate object of interest in an image or video. The task would be to identify the position and boundaries of objects in images or videos. [8, 9]
One real world application of this model would be Google translate.

### Google Translate in language translation
_Google translate:_

This is an online service developed and provided by Google that allows a variety of translation services supporting over 100 languages using Neural Machine models for detection to precisely translate between languages and improve it self over time.
Visual Text translation offered by google translate uses Computer vision at it's core implementation, this done by the visual identification of the text character and precise handling of the information to give the end user a proper interpretation of the input data. Due to improvement in deep learning algorithms like convolutional neural networks google translate can not only detect an identify a dog in a picture but at it's currently trained level it is even able to detect and identify different dog breeds which older models would struggle to handle. [10]

#### Google translate working -- [fix heading]

The process of google translate identifying and accurately translating data for the user, a number of steps would taken to archive this.

1. Firstly, when the image is passed, google translate app tries to identify important parts of the image that might hold text to be translated, this involves looking for blobs of pixel that have similar color and near other similar blobs. This blobs searched would also be checked if they could be in a line so we can continuously read them.

2. After this blobs are read this is where google translate has to try recognizing what each letter actually is. This is done using the deep learning model, convolutional neural network. This network has been trained to accurately identify what different letters look like. This model has not just been trained on "precise-looking" letter images cause in the real world we'd be encountering all sort of dirty smudges or images marred by reflection, So to handle this cases the network was trained data generated by google to mimic this smudges and dirt that the real world input would include.

3. Knowing that the previous steps could potentially contain errors from recognition, the dictionary look-up of this recognised words would only be an approximation. Using this method, if an 'S' was read as '5' then the approximate word '5uper' would still be able to be looked up.

4. Finally the words translated from the dictionary look-up would be passed to the user either read-out or rendered to screen as the final result from all the computation of the previous steps.


### Challenges
1.  Data Quality and Quantity
- Data Annotation: The first issue that we face in computer vision is that a lot of training data are often needed for models to learn from. Annotation of data in fields like object detection and segmentation is a tedious and costly process (Gonzalez & Woods, 2018; Szeliski, 2022).
- Data Variability: The change of light, occlusion, and shift in the perspective are some of the factors affecting the performance of the computer vision systems. It is still a challenge even to date to sustain such a form of resistance against such fluctuations (Szeliski, 2022).

2.  Computational Complexity
- Resource Requirements: The deep learning models based on CNN generally require a significant amount of computational resources for training and to make predictions. This includes factors such as high-performance graphic processing units, large memory, and many others.
- Real-Time Processing: Real time computation for such jobs like video analysis and autonomous driving is challenging because of the higher demand for computational power (Krizhevsky, Sutskever & Hinton, 2012).

3.  Model Interpretability
- Black Box Nature: Shared characteristics of the deep learning models mean that the models are said to make their decisions in a black box. This is difficult particularly when it comes to certain applications like diagnosis of images in medicine or in automobiles that are self-driven (Ribeiro, Singh, & Guestrin, 2016).

4.  Generalization and transfer learning
- Domain Adaptation: It’s possible that some models, which work well in particular datasets, do not do so well when tested in other conditions – or on other datasets. This is why the concepts of domain adaptation and transfer learning exist, but they are still a thing to research (Pan & Yang, 2010).

5. Ethical and privacy Issues.
- Bias and Fairness: Introducing prejudice in the training data is quite risky because it births prejudice in the models which then results to prejudice. Prejudice is another challenge that has been highlighted several times (Buolamwini & Gebru, 2018).
- Privacy Issues: Computer vision in surveillance and facial recognition pose a great threat to the general publics right to privacy. Such development should be controlled in a manner that would still protect the personal freedoms of citizens including privacy (Harwell, 2019).



### Possibilities

1. Advanced Healthcare Applications
- Medical Imaging: Another way by which computer vision could transform the healthcare industry is through diagnosing illnesses in X-ray and MRI scans, and CT. Diagnostic assistance to the doctors is additional assistance that can be provided with the help of AI (Litjens et al. , 2017).

2. Autonomous Vehicles
- Self-Driving Cars: Autonomous vehicle would not be possible without computer vision as it helps to interpret the environment and then move within it. This will comprise of tasks such as objects detection, lane detection and traffic sign detection (Chen et al. , 2015).

3. Enhanced Security and Surveillance
- Intelligent Monitoring: Certain technologies like advanced computer vision systems can help in increasing security by performing monitoring/covert surveillance in real time as well as system anomaly detection. These systems can themselves detect and notify of emergent activities (Ren et al. , 2015).

4. Improved User Experience
- Augmented Reality (AR): In this publication we talked about how computer vision aids in language translation in an application like google translate. Computer vision is core to AR since it uses the camera to place virtual objects on a real environment in real-time. It can be applied in game and vectoring and in education aids (Azuma, 1997).
- Facial Recognition: Facial recognition application may improve user experience in the security aspects, socializing in the social media platforms, and customized services (Parkhi et al. , 2015).

5. Agricultural Automation
- Precision Agriculture: Moreover, through computer vision, crop health can be continuously monitored, pests can be identified and harvesting can be mechanized which all lead to better yields in agriculture (Kamilaris & Prenafeta-Boldú, 2018).












`Draft`
3. architecture, ....
4. models/techniques/algorithms used in those topics listed,....
5. Preseñt a case study used in the topic, ....
6. give us the possibilities and challenges on the topics then provide a conclusion and recommendations on them, 

