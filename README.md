<p align="center"><img src="https://socialify.git.ci/adnan760/Image_Caption_Generation/image?description=1&amp;font=Inter&amp;name=1&amp;pattern=Floating%20Cogs&amp;theme=Auto" alt="project-image"></p>
 
  
<h2>Features</h2>

Here're some of the project's best features:

*   Caption Generation in global language: English
*   Caption Generation in regional language: Hindi

<h2>Dataset</h2>

[Flickr 8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k)
<p></p>

[Flickr8k Hindi captions](https://www.kaggle.com/datasets/dsmeena/flickr8k-hindi-captions)

<h2>Modules</h2>

*   numpy
*  matplotlib
*  keras
*  tensorflow
*  nltk

<h2>Caption Generation process</h2>

<p>1. Importing required modules.</p>

<p>2. Loading dataset consisting of images and captions.</p>

<p>3. Loading images from dataset and extracting respective features using CNN with the use of VGG-16 model.</p>

<p>4. Loading caption file which consists of the name of the image followed by a space and the description of the image in CSV format.</p>

<p>5. Cleaning the captions so as to remove noise i.e. to remove special characters such as hashtags punctuation and numbers.</p>

<p>6. Creating vocabulary which is a set of unique words which are present in the text corpus.</p>

<p>7. Tokenizing all the words present in the vocabulary.</p>

<p>8. Initialising embedding matrix to store the relations between words in the vocabulary.</p>

<p>9. Providing step 7 &amp; 8 as an input to LSTM for word sequence generation.</p>

<p>10. Combining CNN and LSTM for generating captions on an input image</p>

<h2>Architecture</h2>

<img src="https://user-images.githubusercontent.com/94967712/218268680-c436e73f-8ba2-4929-b68a-8598bf19c6a7.png" width="65%" height="65%/">

<h2>Results</h2>
English Caption
<img src="https://user-images.githubusercontent.com/94967712/218273174-d3044086-63eb-4e04-b348-e5c556d12e72.png" width="65%" height="65%/">
Hindi Caption
<img src="https://user-images.githubusercontent.com/94967712/218273296-2350acd6-341d-4013-b78f-7d8917c75b3e.png" width="65%" height="65%/">

<h2>Reference</h2>

[Image Caption Generator - Flickr Dataset](https://github.com/aswintechguy/Deep-Learning-Projects/tree/main/Image%20Caption%20Generator%20-%20Flickr%20Dataset)
