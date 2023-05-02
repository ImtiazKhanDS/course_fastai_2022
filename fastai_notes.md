#### LESSON-1

##### classification problem on bird vs forest.

	1. duckduckgo search
	2. data : 200 each of categories
	3. datablock
	4. cnn_learner
	5. learn.predict


##### Deep Learning Latest things.
	1.examples of diffusion models
	2.Pathways language model

##### pedagogy
	1.top down approach 
	2.make learning whole by david perkins.

##### visualizing neural networks by matt zeiler.
	1. image recognizer can also be used for audio recognition
	2. mouse movements fraud detection using images.

##### Myths
	lots of math
	lots of data
	lots of expensive computers

##### Framework choice
	pytorch - used heavily in research.
	fastai built on top of pytorch

##### Presentation in jupyter
	rise

##### Cloud notebook servers
	1. kaggle
	2. colab
	3. paperspace gradient
	4. lambda cloud

##### Documentation
	1. docs.fast.ai

##### Critical components
	1. DataBlock
	2. Learner

##### Deep Learning
	1. Image recognition
	2. Segmentation-classify each pixel
	3. Tabular data classification
	4. Colloborative filtering.



#### Lesson 2
1. Jupyter notebook extensions for navigate tab and collapsible sections
2. ? Brief overview of the method
3. ?? Source code of the method
4. doc(method name) documentation link
5. squishing an image means get all contents of image but compress it.
6. Cropping is get the centre part of image this loses some entities in the picture.
7. Random resized crop gets a different bits of image every time.
8. aug_transforms for augmentation of images
9. There no copies of images above , batch by batch these augmentations are created in memory.
10. Confusion matrix to view what category errors are present
11. classification interpretation object to plot top losses.
12. Loss is our measurement of how good our model is.
13. Image cleaner to view and edit correct or wrong categories from the top losses.
14. New paradigm idea , use a model to correct your data.
15. Huggingface spaces with gradio page by Tanishq Abraham
16. GitHub desktop is useful by hamel Hussain.
17. Windows terminal is good.
18. Go to power shell : wsl —install for Ubuntu on windows.
19. explorer.exe . in windows and on mac open . to open up the folder
20. code . to open vscode 
21. learn.export(“model.pkl ”) if you run this in Kaggle go to the data tab to view this file.
22. Take your unix system folder and pin it to quick access
23. For inference we use load_learner(“model.pkl”) and then we can do learn.predict.
24. predict returns the predict, index and probabilities.
25. nbdev #l export cells would be converted to scripts
26. #l default_exp app at the first cell makes the app with that file name app.py
27. Clone the fastsetup from fastai/fastsetup repo and run setup-conda.sh
28. API from huggingface app we can take and integrate in any Java script app.
29. More details we can find in Jeremy js classifier code.
30. GitHub pages we can create to create a website and then we can call api of the huggingface api.
31. Enable githubpages in settings in GitHub account.

#### LESSON 3
1. Watch the lecture
2. Run the notebook and experiment
3. Reproduce Results
4. Repeat with different dataset.
5. paperspace gradient has persistent storage.
6. Which image models are the best blog by jeremy howard.
7. convnext models worked better for paddy classification model.8. learn.export("model.pkl")
9. load_learner("model.pkl")
10.categories=learn.dls.vocab , gives the classification categoires.
11. torch.clip(y,0) any value of y less than zero will be clipped to zero.
12. We can use many relus combination and create any function we want.
13. Learning rate is a hyper parameter.
14. matrixmultiplication.xyz for visualizing matrix multiplication.
15. Getting started with NLP for absolute beginners NLP notebook by jeremy.

#### LESSON 4  
