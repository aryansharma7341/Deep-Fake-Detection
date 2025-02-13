<h1>Deepfake Detection using Deep Learning (ResNext and LSTM)</h1>

<h2>🚀 Introduction</h2>
<p>This project aims to detect video deepfakes using deep learning techniques like <strong>ResNext</strong> and <strong>LSTM</strong>. Our approach leverages <strong>transfer learning</strong>, where a pre-trained <strong>ResNext CNN</strong> extracts feature vectors from video frames, and an <strong>LSTM layer</strong> is trained on these features to classify deepfakes accurately.</p>

<p>📄 For more details, refer to the <a href="https://github.com/aryansharma7341/Deep-Fake-Detection/tree/main/Documentation">Documentation</a>.</p>

<hr>

<h2>📂 Directory Structure</h2>
<p>The project is organized as follows:</p>

<pre>
Deepfake_Detection_Using_Deep_Learning
│
├── Django_Application
│   ├── Frontend UI for video upload
│   ├── Backend Model Integration
│   └── Result Display
│
├── Model_Creation
│   ├── Data Preprocessing
│   ├── Feature Extraction (ResNext)
│   ├── LSTM Training
│   └── Model Evaluation
│
└── Documentation
    ├── Project Reports
    ├── Technical Insights
    └── Research References
</pre>

<ul>
  <li><strong>Django Application</strong>: Provides a user-friendly web interface where users can upload videos for deepfake detection.</li>
  <li><strong>Model Creation</strong>: Contains scripts for dataset preparation, feature extraction using ResNext, LSTM-based classification, and model training.</li>
  <li><strong>Documentation</strong>: Includes technical reports and insights into the research and implementation.</li>
</ul>

<hr>

<h2>🏗️ System Architecture</h2>
<p align="center">
  <img src="https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/blob/master/github_assets/System%20Architecture.png" alt="System Architecture" width="75%"/>
</p>

<hr>

<h2>🎬 Demo</h2>

<p align="center">
  <img src="https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/blob/master/github_assets/fakegif.gif" alt="Deepfake Detection Demo" width="75%"/>
</p>

<hr>

<h2>📊 Results</h2>

<table>
  <tr>
    <th>Model Name</th>
    <th>No. of Videos</th>
    <th>No. of Frames</th>
    <th>Accuracy</th>
  </tr>
  <tr>
    <td>model_89_acc_40_frames_final_data.pt</td>
    <td>6000</td>
    <td>40</td>
    <td><strong>89.35%</strong></td>
  </tr>
  <tr>
    <td>model_93_acc_100_frames_final_data.pt</td>
    <td>6000</td>
    <td>100</td>
    <td><strong>93.59%</strong></td>
  </tr>
</table>

<p>Our final trained model achieves an impressive <strong>93.59% accuracy</strong> on 100-frame video samples, demonstrating its effectiveness in detecting deepfake content.</p>

<hr>

<h2>⚡ Installation & Setup</h2>
<h3>Prerequisites</h3>
<ul>
  <li>Python 3.8+</li>
  <li>Django</li>
  <li>PyTorch</li>
  <li>OpenCV</li>
  <li>NumPy</li>
</ul>

<h3>Steps</h3>
<pre>
# Clone the repository
git clone https://github.com/aryansharma7341/Deep-Fake-Detection.git
cd Deep-Fake-Detection

# Install required dependencies
pip install -r requirements.txt

# Run the Django application
cd Django_Application
python manage.py runserver
</pre>


<hr>

<h2>🏆 Contributors</h2>
<p>👤 <strong>Aryan Sharma</strong><br>
📧 <a href="aryansharma7341.as@gmail.com">Email</a><br>
🔗 <a href="https://github.com/aryansharma7341">GitHub</a><br>
🔗 <a href="www.linkedin.com/in/aryansharma7341">LinkedIn</a></p>

<hr>

<hr>

<p>🌟 <strong>If you find this project useful, don't forget to ⭐ the repository!</strong></p>
