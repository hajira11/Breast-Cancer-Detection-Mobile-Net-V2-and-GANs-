#GANs for data augmentation in Breast Cancer detection system

Medical images, in general, are hard to obtain due to privacy concerns. Medical data collection is a time-consuming and costly process that necessitates the participation of researchers and radiologists. For these reasons, researchers have come up with data augmentation techniques such as image rotation, image flipping and image scaling. However, the variations using these techniques are relatively low, thus paving the need for image generation using deep learning techniques

Through this project, it was successfully demonstrated that images generated using Deep Convolutional GAN (DCGAN) can indeed improve the performance of a system comprising of MobileNet V2 model.

Data Set source : https://scholar.cu.edu.eg/?q=afahmy/pages/dataset

	Existing System	New System with K fold(System 1)	New System with K fold+ New images (System 2)
	B	M	N	B	M	N	B	M	N
Sensitivity	0.86	0.95	0.56	0.89	0.90	0.93	0.96	0.94	0.96
Specificity	0.93	0.81	0.99	0.95	0.95	0.96	0.97	0.98	0.98
Accuracy Train	95.65	98.713	98.958
Accuracy Test	87.50	93.432	94.929
B = Benign ; M = Malignant ; N = Normal
![image](https://github.com/hajira11/Breast-Cancer-Detection-Mobile-Net-V2-and-GANs-/assets/28599955/74b96401-b2f0-4d85-b0c2-2185a622c4c3)

