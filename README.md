<p align="center">
  <img src="https://raw.githubusercontent.com/rahulsangolli/uber-ride-demand-prediction/refs/heads/main/assets/afdae3cd-0a04-4d07-9d64-de3b92b5633d.png"
       alt="Banner" width="100%" style="max-height: 240px; object-fit: cover; display: block; margin: 0 auto;">
</p>

<div align="center">

<h1 style="font-size:42px; font-weight:800; margin-bottom:10px;">🚖 Uber Ride Demand Prediction</h1>

<p style="font-size:18px; max-width:850px; line-height:1.6;">
A machine-learning powered system that forecasts...high-demand pickup zones...across New York City — enabling ride-hailing drivers to plan smarter, reduce idle time, and reach customers faster.  
<br/><br/>
This project can serve as a powerful **startup-style solution** where drivers see exactly *where demand is rising*, ensuring more earnings for drivers and less waiting time for customers.
</p>

</div>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">📌 Overview</h2>

<p style="font-size:16px; line-height:1.6;">
This system predicts how many Uber rides will be requested at a specific <b>date</b>, <b>hour</b>, and <b>NYC region</b>.  
<br/><br/>

It is designed with a simple mission:
<br/><br/>

<p align="center">
<b style="font-size:20px;">✔️ Place drivers exactly where the next ride request is likely to happen.</b>
</p>

<p style="font-size:16px; line-height:1.6;">
By forecasting real-time demand hotspots:
<ul style="font-size:16px; line-height:1.7;">
  <li>Drivers maximize earnings by staying in high-demand areas</li>
  <li>Customers experience minimal wait-time for pickups</li>
  <li>Ride platforms achieve smoother traffic flow and reduced surge pricing</li>
</ul>

This project replicates how modern ride-hailing companies optimize supply & demand — but makes it accessible to anyone.
</p>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🧠 Tech Stack</h2>

<ul style="font-size:16px; line-height:1.8;">
<li><b>Languages:</b> Python</li>
<li><b>Libraries:</b> Pandas, NumPy, Scikit-Learn</li>
<li><b>Visualization:</b> Plotly</li>
<li><b>Modeling:</b> RandomForest, XGBoost</li>
<li><b>App Framework:</b> Streamlit</li>
<li><b>Data Versioning:</b> DVC</li>
</ul>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">⭐ Key Features</h2>

<ul style="font-size:16px; line-height:1.8;">
<li><b>Hourly Ride Prediction</b> — estimate demand instantly for any selected date & hour.</li>
<li><b>Region-wise Demand Forecasting</b> — NYC divided into ML-based clusters.</li>
<li><b>Interactive Map Visualization</b> — heatmap-based demand insights.</li>
<li><b>Feature-Rich Pipeline</b> — includes timestamp engineering & lag-based features.</li>
<li><b>Clean Modular Architecture</b> — ingestion → feature engineering → training → prediction.</li>
</ul>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🖼️ Application Screenshots</h2>

<h3 style="font-size:22px; font-weight:700;">1️⃣ Input Panel — Select Date & Time</h3>
<p>Users choose the target date & hour for prediction.</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/uber-ride-demand-prediction/refs/heads/main/assets/f6f810aa-0f3f-4d18-9006-ea0fa6e3a339.png" width="800px"/>

<h3 style="font-size:22px; font-weight:700;">2️⃣ Predicted Ride Demand Output</h3>
<p>Shows expected ride count for the selected input.</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/uber-ride-demand-prediction/refs/heads/main/assets/c4d21943-bc05-4fd4-a7af-09ebe8b6ca33.png" width="800px"/>

<h3 style="font-size:22px; font-weight:700;">3️⃣ NYC Region Clustering Map</h3>
<p>Displays ML-created clusters used for region-wise forecasting.</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/uber-ride-demand-prediction/refs/heads/main/assets/407816c1-c83d-4a2b-8b7a-78e37fafcde8.png" width="800px"/>

<h3 style="font-size:22px; font-weight:700;">4️⃣ Region-wise Demand Heatmap</h3>
<p>Visualizes predicted ride intensity using an interactive NYC map.</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/uber-ride-demand-prediction/refs/heads/main/assets/1f5a7a8d-a1b8-426d-b958-0f322d6b4297.png" width="800px"/>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🧩 Project Structure</h2>

<pre style="background:#111; color:#fff; padding:20px; border-radius:8px; font-size:15px;">
├── LICENSE
├── Makefile               <- Makefile with commands like `make data` or `make train`
├── README.md              <- The top-level README for developers using this project.
│
├── data
│   ├── external           <- Data from third-party sources.
│   ├── interim            <- Intermediate data that has been transformed.
│   ├── processed          <- Final, canonical data sets for modeling.
│   └── raw                <- Original, immutable data dump.
│
├── docs                   <- Sphinx documentation folder (auto-generated docs).
│
├── models                 <- Trained and serialized models, predictions, and summaries.
│
├── notebooks              <- Jupyter Notebooks.
│                               
│                             
│
├── references             <- Data dictionaries, manuals, and reference materials.
│
├── reports                <- Generated analysis outputs (HTML, PDF, LaTeX, etc.)
│   └── figures            <- Generated figures and graphics used in reporting.
│
├── requirements.txt       <- Reproducible environment dependencies 
│
├── setup.py               <- Makes the project pip-installable 
│
├── src                    <- Source code for this project.
│   ├── __init__.py        <- Makes src a Python package.
│   │
│   ├── data               <- Scripts to download or generate data.
│   │   └── make_dataset.py
│   │
│   ├── features           <- Scripts to create features from raw data.
│   │   └── build_features.py
│   │
│   ├── models             <- Model training and prediction scripts.
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization      <- Scripts for exploratory and result visualizations.
│       └── visualize.py
│
└── tox.ini                <- Configuration file for running tox tests.

</pre>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🔍 How the System Works 


<h3 style="font-size:22px; font-weight:700;">1️⃣ Collecting & Understanding Data</h3>
<p style="font-size:16px; line-height:1.6;">
We use historical Uber ride data containing:
<ul>
<li>Date and time</li>
<li>Pickup coordinates</li>
<li>Hourly ride counts</li>
</ul>
This forms the foundation of our prediction system.
</p>

<h3 style="font-size:22px; font-weight:700;">2️⃣ Cleaning the Data</h3>
<p style="font-size:16px; line-height:1.6;">
Raw data contains missing values, errors, and outliers.  
We fix issues by:
<ul>
<li>Removing incorrect entries</li>
<li>Handling extreme values</li>
<li>Formatting timestamps</li>
<li>Standardizing numeric fields</li>
</ul>
This ensures reliable model learning.
</p>

<h3 style="font-size:22px; font-weight:700;">3️⃣ Dividing NYC into Regions (Clustering)</h3>
<p style="font-size:16px; line-height:1.6;">
Different areas show different ride patterns. Example:
<br/>— Times Square: high  
<br/>— Residential zones: moderate  
<br/><br/>
Using clustering, NYC is divided into behavior-based regions.<br/>
This helps the model learn spatial patterns.
</p>

<h3 style="font-size:22px; font-weight:700;">4️⃣ Feature Engineering</h3>
<p style="font-size:16px; line-height:1.6;">
We convert raw timestamps into meaningful signals:
<ul>
<li><b>Hour</b></li>
<li><b>Day of week</b></li>
<li><b>Month</b></li>
<li><b>Weekend flag</b></li>
<li><b>Region/cluster</b></li>
<li><b>Lag demand values</b> (previous hour demand)</li>
</ul>
Good features = better predictions.
</p>

<h3 style="font-size:22px; font-weight:700;">5️⃣ Training Machine Learning Models</h3>
<p style="font-size:16px; line-height:1.6;">
We test models like:
<ul>
<li>Random Forest</li>
<li>XGBoost</li>
</ul>
The model learns patterns across:
<ul>
<li>Hour of day</li>
<li>Day of week</li>
<li>Region</li>
<li>Seasonal trends</li>
</ul>
We evaluate using:
<br/><br/>
<b>RMSE (Root Mean Squared Error)</b> — measures how close predictions are to actual values.
</p>

<h3 style="font-size:22px; font-weight:700;">6️⃣ Making Predictions (User Interaction)</h3>
<p style="font-size:16px; line-height:1.6;">
When the user selects a date, time, and region:
<ol>
<li>Inputs are converted into engineered features</li>
<li>Features passed into the trained model</li>
<li>Model predicts hourly demand</li>
<li>Results shown numerically & on interactive map</li>
</ol>
</p>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">📈 Results</h2>

<ul style="font-size:16px; line-height:1.8; text-align:left; max-width:900px; margin:0 auto;">

<li>Captures hourly + regional patterns accurately.</li>
<li>Allows smarter driver placement strategies.</li>
<li>Improves ride availability & reduces waiting time.</li>
</ul>

<hr/>

<div align="center">

<h2 style="font-size:32px; font-weight:800;">👨‍💻 Author</h2>

<strong style="font-size:24px;">Rahul Sangolli</strong><br/>
<em style="font-size:16px;">Data Science & Machine Learning Practitioner</em>

<p style="font-size:16px;">
  <a href="https://www.linkedin.com/in/rahul-sangolli-7420193a1/" target="_blank">
    <b>🌐 LinkedIn</b>
  </a>
  &nbsp;|&nbsp;
  <a href="mailto:rahulsangolli05@gmail.com">
    <b>✉️ Email</b>
  </a>
</p>

</div>

