<h1>💳 Credit Card Approval Prediction</h1>
<p><b>A Machine Learning + FastAPI Project to Predict Credit Card Application Approval</b></p>

<hr>

<h2> Project Overview</h2>
<p>
This project predicts whether a credit card application will be <b>Approved</b> or <b>Rejected</b> based on applicant data.<br>
A <b>DecisionTreeClassifier</b> model is trained on structured financial data, and the prediction system is deployed using <b>FastAPI</b>.
</p>

<hr>

<h2> Features</h2>
<ul>
  <li>🔍 Data preprocessing with scaling</li>
  <li>🌳 Machine Learning using DecisionTreeClassifier</li>
  <li>⚡ FastAPI backend for real-time predictions</li>
  <li>🖥️ Web UI using HTML template (index.html)</li>
</ul>

<hr>

<h2> Tech Stack</h2>
<p>
<img src="https://img.shields.io/badge/Python-3.11-blue">
<img src="https://img.shields.io/badge/FastAPI-Framework-brightgreen">
<img src="https://img.shields.io/badge/Scikit--Learn-ML-orange">
<img src="https://img.shields.io/badge/DecisionTree-Model-yellow">
</p>

<ul>
  <li>Python</li>
  <li>FastAPI</li>
  <li>Uvicorn</li>
  <li>Scikit-Learn</li>
  <li>Pandas, NumPy</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
Credit_Card_Approval_Prediction/
│
├── code/
│    └── Credit_Card_Approval_code.ipynb
│
├── model/
│    └── model.pkl
│
├── scaler/
│    └── scaler.pkl
│
├── templates/
│    └── index.html
│
├── app.py
├── requirements.txt
└── README.md
</pre>

<hr>

<h2>🧠 Model Details</h2>
<ul>
  <li><b>Model Used:</b> DecisionTreeClassifier</li>
  <li>Saved as: <code>model.pkl</code></li>
  <li>Scaler used for preprocessing</li>
  <li>Input: Applicant's financial and demographic features</li>
  <li>Output: <b>Approved</b> or <b>Rejected</b></li>
</ul>

<hr>

<h2>📥 Installation</h2>

<h3>1️⃣ Clone the Repository</h3>
<pre>
git clone https://github.com/AzeemAIDev/Credit_Card_Approval_Prediction.git
</pre>

<h3>2️⃣ Open Project Folder</h3>
<pre>
cd Credit_Card_Approval_Prediction
</pre>

<h3>3️⃣ Install Requirements</h3>
<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>▶️ How to Run the Project</h2>

<h3>Start the FastAPI Server</h3>
<pre>
uvicorn app:app --reload --port 8001
</pre>

<h3>Open the Web UI</h3>
<p>
After running the command, go to the terminal and click on the provided link, or open:
</p>

<pre>
http://127.0.0.1:8001
</pre>

<p>This opens the main interface (index.html) where you can enter applicant data and get predictions.</p>

<hr>

<h2>⭐ Author</h2>
<p><b>Muhammad Azeem</b><br>
Machine Learning & AI Learner<br>
GitHub: <a href="https://github.com/AzeemAIDev" target="_blank">AzeemAIDev</a></p>
