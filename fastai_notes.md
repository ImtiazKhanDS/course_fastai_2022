#### LESSON-1
1. duckduckgo search
2. data : 200 each of categories
3. datablock
4. cnn_learner
5. learn.predict
6. examples of diffusion models
7. Pathways language model
8. top down approach 
9. make learning whole by david perkins.
10. image recognizer can also be used for audio recognition
11. mouse movements fraud detection using images.
12. lots of math
13. lots of data
14. lots of expensive computers
15. pytorch - used heavily in research.
16. fastai built on top of pytorch
17. rise
18. kaggle
19. colab
20. paperspace gradient
21. lambda cloud
22. docs.fast.ai
23. DataBlock
24. Learner
25. Image recognition
26. Segmentation-classify each pixel
27. Tabular data classification
28. Colloborative filtering.

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

1. ULMFit , train a language model on wikitext , finetune language model on IMDB and then create a classification model on imdb.
2. US patent phrase to phrase matching problem kaggle.
3. numpy, matplotlib, pandas and pytorch
4. python for data analysis by wes mckinney.
5. Tokenization : split each text up into words.
6. Numericalization : convert each workd into a number.
7. rust library is used for tokenization.
8. np.corrcoef to get the correlation between all variables in data frame.
9. If you set num_labels=1 in AutoModelForSequenceClassificationit will convert into a regression problem.

#### LESSON 5
1. modes=df.mode().iloc[0] gives the mode from each column.
2. df.fillna(modes,inplace=true) simplest way to fill na values.
3. Broadcasting an array in python.
4. sympy package takes a function as string and plots that function
5. fastai always creates an other category so that it can be handled in test set if there are other categories which are not in train data. 
6. learn.lr_find(suggest_funcs=(slide,valley)) choose any learning rate between slide and valley in the graph.
7. Random forests are very difficult to mess up as apposed to logistic or linear regressions. 

#### LESSON 6

1. For tabular data we always use random forests.
2. Feature importance plot tells us  is which feature is important.
3. Jeremy as a rule of thumb uses not more than 100 trees.
4. OOB error.
5. Partial dependence plot gives the relationship between two variables keeping all variables constant.
6. Python packages treeinterpreter and waterfallcharts
7. Explained.ai gradient boosting
8. Iterate like a grand master.
9. fastkaggle package for downloading data
10. Road to the top Model notebooks on paddy classification


#### LESSON 7

1. Gradient accumulation is a method we can use if we have little gpu memory.
2. Road to the top part 4 notebook discussion with multiple categoryblocks and one Imageblock.  
3. For each movie we want to find out what movie is it in terms of latent factors.
4. If user 1 likes the movie in terms of latent factors and if user2 is similar in taste to user1 then we can recommend this movie to the user2.
5. Embedding is nothing but matrix multiplication of a matrix with a one hot encoded vector.
6. Add movie bias and user bias to the model as a trick.

#### LESSON 8
1. Colloborative filtering using fastai collab learner.
2. Embeddings can be used for text data , tabular data and collaborative model.
3. Entity embeddings of categorical variables paper by Cheng Guo and Felix Berkhahn Neokami Inc april 25 2016.
4. Convolution is sliding dot products of pixels of image with the filters under consideration.
5. drop some activations based on a probability : dropout.
6. The way we implement a dropout is multiply the image with the dropout mask. 
7. Read meta learning book by radek osmulski
8. Do projects with your own data.
9. Join study groups.
