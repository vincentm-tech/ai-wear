<h1 align="center">AI-WEAR: Text Reader Glasses for Visually Impaired Students</h1>
<h3 align="center">Using Raspberry Pi with Audio-Visual Call and Google Assistance</h3>

## 📌 Overview
<p>
AI-WEAR is an assistive technology designed to help visually impaired students by integrating 
<strong>Optical Character Recognition (OCR)</strong>, <strong>Text-to-Speech (TTS)</strong>, and 
<strong>Google Assistant</strong> features into smart glasses. 
The device enables users to read text, interact with teachers via video calls, 
and access real-time information—all through a <strong>Raspberry Pi-based system</strong>.
</p>

<ul>
  <li>📖 <strong>Text Reader</strong> – Converts printed text to speech using OpenCV & Tesseract OCR.</li>
  <li>🎤 <strong>Voice Assistance</strong> – Google Assistant integration for hands-free interaction.</li>
  <li>📹 <strong>Video Call Support</strong> – Real-time video streaming via Jitsi Meet.</li>
  <li>🔘 <strong>Braille-Based Controls</strong> – User-friendly buttons with Braille engraving.</li>
  <li>📶 <strong>GSM/Wi-Fi Connectivity</strong> – Works even without Wi-Fi using a mobile data module.</li>
  <li>🔋 <strong>Long Battery Life</strong> – Runs for up to 8 hours on a single charge.</li>
</ul>

<h2>🔗 Project Details</h2>
<p>For more details, check the full <a href="./docs/README.md"><strong>Project Documentation</strong></a>.</p>

<h2>📷 Project Images</h2>
<p><img src="<insert system prototype image>" alt="System Prototype" width="600"></p>
<p><img src="<insert system block diagram image>" alt="System Block Diagram" width="600"></p>

<h2>🛠️ Tech Stack</h2>
<h3>Hardware:</h3>
<ul>
  <li>Raspberry Pi 4 Model B</li>
  <li>Pi Camera Module</li>
  <li>GSM/GPRS Module</li>
  <li>USB Microphone & Speaker</li>
  <li>Power Bank (10,000mAh)</li>
</ul>

<h3>Software & Libraries:</h3>
<ul>
  <li>OpenCV (Image Processing)</li>
  <li>Tesseract OCR (Optical Character Recognition)</li>
  <li>Google Assistant API</li>
  <li>Jitsi Meet (Video Conferencing)</li>
  <li>Python (Main Programming Language)</li>
</ul>

<h2>⚙️ System Architecture</h2>
<p><img src="<insert RPI system flowchart image>" alt="RPI System Flowchart" width="600"></p>
<p>The system captures images, processes text via OCR, converts text to speech, 
and allows users to communicate with teachers through real-time video conferencing.</p>

<h2>📖 How It Works</h2>
<ol>
  <li><strong>Text Recognition:</strong> The camera captures an image of text.</li>
  <li><strong>OCR Processing:</strong> OpenCV & Tesseract extract text from the image.</li>
  <li><strong>Text-to-Speech:</strong> The system reads aloud the extracted text.</li>
  <li><strong>Online Assistance:</strong> Users can access Google Assistant for additional support.</li>
  <li><strong>Video Calling:</strong> Students can connect with their teachers in real-time.</li>
</ol>

<h2>🚀 Installation & Setup</h2>
<pre>
1. Clone the repository:
   <code>git clone https://github.com/yourusername/ai-wear.git</code>
   <code>cd ai-wear</code>

2. Install Dependencies:
   <code>sudo apt-get update</code>
   <code>sudo apt-get install tesseract-ocr python3-opencv</code>
   <code>pip install speechrecognition gtts opencv-python google-api-python-client</code>

3. Run the Application:
   <code>python main.py</code>
</pre>

<h2>📝 Research Paper</h2>
<p>📄 <a href="./docs/AI-WEAR_Research.pdf"><strong>Full Research Paper (PDF)</strong></a></p>

<h2>🎯 Future Improvements</h2>
<ul>
  <li>Enhance camera resolution for better text recognition.</li>
  <li>Implement <strong>Braille system reader</strong> for better accessibility.</li>
  <li>Add <strong>mathematical equation detection</strong> for STEM learning.</li>
  <li>Optimize battery efficiency for longer usage.</li>
</ul>

<h2>📩 Contact & Contributions</h2>
<p>Want to contribute or ask questions? Reach out via:</p>
<ul>
  <li>📧 Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
  <li>🔗 LinkedIn: <a href="https://linkedin.com/in/yourname">Your Profile</a></li>
</ul>
