<div align="center">
  <h2 align="center">Product Recognition</h2>
  <a href="https://www.kaggle.com/c/shopee-product-detection-student">Competition link</a> | 
  <a href="Guidelines.pdf">Complete PDF guideline</a>
</div>

<h4>Task</h4>

<ul>
<li>Build a 42-class image classification model to classify images of products on Shopee.
</li>
</ul>

<h4>Data</h4>

* train.csv
<div align="left">
  <img src="images/train.png" alt="data" width="300">
</div>
<br>

* images
<div align="left">
  <img src="images/images.png" alt="images">
</div>

<h4>Solution Outline</h4>

<ol>
    <li>
      <a href="ExploratoryDataAnalysis.ipynb">Exploratory Data Analysis</a>
      <ul>
        <li>Display images</li>
        <li>Explore class distribution</li>
        <li>Explore image dimension</li>
      </ul>
    </li>
    <li>
      <a href="Preprocessing.ipynb">Pre-processing</a>
      <ul>
        <li>Remove blank images</li>
        <li>Identify duplicated or highly similar images by using p-hashes</li>
        <li>Remove only duplicated images that belong to the same class</li>
        <li>Resample minority classes through image augmentation</li>
      </ul>
    </li>
      <li>
      <a href="Training.ipynb">Training</a>
      <ul>
        <li>Instantiate a base model with pre-trained weights</li>
        <li>Freeze the base model</li>
        <li>Add layers on top of the base model</li>
        <li>Compile the model</li>
        <li>Train the model</li>
      </ul>
    </li>
    <li>
      <a href="Classification.ipynb">Classification</a>
      <ul>
        <li>Predict the classes of the images</li>
      </ul>
    </li>
</ol>