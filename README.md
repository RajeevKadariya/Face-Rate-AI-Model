# Face-Rate-AI-Model
<h2>A trained model to rate faces</h2>
<h3>purpose:</h3>
<p>this program Uses a pretrained ai model trained on general objects and faces as a backbone. A dataset of around 5,500 faces of variying race annd demographics were used to train and fine-tune the models. and is capable of harshly judging someones appearance on a scale of 1-5 and 1-10. 
<bold><br><br>For geeks, this is how the model performs on training data</bold>
  <br><ul>
      <li>MAE  (mean absolute error): 0.2815</li>
      <li>RMSE (root mean sq error): 0.3625</li>
      <li>Pearson correlation: 0.8593</li></ul>
</p> 

<h2>How to run</h2>
<br><br>
<ul>
  <li>Running this on a virtual evironment is recomended. Run this on python 3.11</li>
  <li>download the required packages and modules mentioned in the file requirerments.txt via pip <br>use command "pip install torch torchvision --index-url https://download.pytorch.org/whl/cu124" 
<br>"pip install -r requirements.txt" in order </li>
  
  <li>run python -m predict.py "path to your image to be rated"</li>
  
</ul>
<br>
<p>this gives two ratings as output 
</p>


