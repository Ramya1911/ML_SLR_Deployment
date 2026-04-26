# ML_SLR_Deployment
<h1 align="center">📊 Simple Linear Regression Model</h1>

<p align="center">
  <b>Machine Learning Project | Data Science Portfolio</b>
</p>

<hr>

<h2>🚀 Project Overview</h2>
<p>
This project demonstrates a <b>Simple Linear Regression (SLR)</b> model to analyze relationships between variables and make predictions using Machine Learning.
</p>

<hr>

<h2>🎯 Objectives</h2>
<ul>
  <li>Understand Linear Regression concepts</li>
  <li>Build and train a predictive model</li>
  <li>Evaluate model performance</li>
  <li>Save and reuse the trained model</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<p>
Python 🐍 | NumPy | Pandas | Matplotlib | Scikit-learn | Pickle
</p>

<hr>

<h2>📂 Project Structure</h2>
<pre>
SLR_Model.pkl
dataset.csv
model_training.py
prediction.py
README.md
</pre>

<hr>

<h2>⚙️ How It Works</h2>
<ol>
  <li>Load dataset</li>
  <li>Perform preprocessing</li>
  <li>Train Linear Regression model</li>
  <li>Evaluate performance</li>
  <li>Save model using Pickle</li>
</ol>

<hr>

<h2>📈 Model Formula</h2>
<p><b>y = mx + c</b></p>

<ul>
  <li>y → Dependent variable</li>
  <li>x → Independent variable</li>
  <li>m → Slope</li>
  <li>c → Intercept</li>
</ul>

<hr>

<h2>💻 Usage</h2>

<h3>Install dependencies</h3>
<pre>pip install numpy pandas matplotlib scikit-learn</pre>

<h3>Run training</h3>
<pre>python model_training.py</pre>

<h3>Load model</h3>
<pre>
import pickle

model = pickle.load(open('SLR_Model.pkl', 'rb'))
prediction = model.predict([[value]])
print(prediction)
</pre>

<hr>

<h2>📊 Results</h2>
<ul>
  <li>Accurate predictions on test data</li>
  <li>Learns relationship between variables</li>
</ul>

<hr>

<h2>🔍 Future Improvements</h2>
<ul>
  <li>Multiple Linear Regression</li>
  <li>Deploy using Streamlit</li>
  <li>Improve accuracy</li>
</ul>

<hr>

<h2>👤 Author</h2>
<p><b>Your Name</b><br>
Data Science | Machine Learning</p>

<hr>


