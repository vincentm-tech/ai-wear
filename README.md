<h1 align="center">AI-WEAR: Text Reader Glasses for Visually Impaired Students Using Raspberry Pi with Audio-Visual Call and Google Assistance</h1>

## 📌 Overview
<p>
AI-WEAR is an assistive technology designed to help visually impaired students by integrating <strong>Optical Character Recognition (OCR)</strong>, <strong>Text-to-Speech (TTS)</strong>, and <strong>Google Assistant</strong> features into smart glasses.  
The device uses OCR to recognize text in front of the user, converts it into speech via TTS, enables interaction with teachers via video calls, and provides real-time information—all through a Raspberry Pi-based system.
</p>

<ul>
  <li>📖 <strong>Text Reader</strong> – Converts printed text to speech using OpenCV, Tesseract OCR & Text-to-speech (TTS).</li>
  <li>🎤 <strong>Voice Assistance</strong> – Google Assistant integration for hands-free interaction.</li>
  <li>📹 <strong>Video Call Support</strong> – Real-time video streaming via Jitsi Meet.</li>
  <li>🔘 <strong>Braille-Based Controls</strong> – User-friendly buttons with Braille engraving.</li>
  <li>📶 <strong>GSM/Wi-Fi Connectivity</strong> – Works even without Wi-Fi using a mobile data module.</li>
  <li>🔋 <strong>Long Battery Life</strong> – Runs for up to 8 hours on a single charge.</li>
</ul>

<h2>🔗 Project Details</h2>
<p>This project integrates <strong>Optical Character Recognition (OCR)</strong>, <strong>Text-to-Speech (TTS)</strong>, <strong>Google Assistant</strong> and <strong>Video Call Support</strong> to assist visually impaired students in reading and communication.</p>
<p>For technical insights, explore the <a href="#⚙️-system-architecture"><strong>System Architecture</strong></a> and <a href="#🛠️-tech-stack"><strong>Tech Stack</strong></a> sections.</p>


<h2>📷 Project Images</h2>
<h3>🔹 System Prototype</h3>
<p>This image showcases the physical prototype of the AI-WEAR device, including its key components such as the Raspberry Pi, camera module, speaker, and control buttons.</p>
<p><img src="images/System Prototype.jpg" alt="System Prototype" width="600"></p>
<h3>🔹 System Block Diagram</h3>
<p>The block diagram illustrates the architecture of AI-WEAR, highlighting how different hardware and software components interact to process text, generate speech, and enable communication.</p>
<p><img src="images/System Block Diagram.png" alt="System Block Diagram" width="600"></p>

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
  <li>Pico TTS</li>
  <li>Jitsi Meet API (Video Conferencing)</li>
  <li>Python (Main Programming Language)</li>
</ul>

<h3>Operating System & Software:</h3>
<ul>
  <li><strong>Operating System:</strong> Raspberry Pi OS (Raspbian)</li>
  <li><strong>Remote Access:</strong> VNC Viewer</li>
</ul>

<h2>⚙️ System Architecture</h2>
<p><img src="images/RPI System Flow Chart.png" alt="RPI System Flowchart" width="600"></p>

<p>The AI-WEAR system is designed as a compact, self-contained assistive device that integrates 
hardware components with intelligent software to process and deliver real-time text-to-speech conversion and communication features. 
The system follows a structured workflow to ensure seamless functionality for visually impaired users.</p>

<h3>📌 System Workflow:</h3>
<ol>
  <li><strong>Image Acquisition:</strong> The Pi Camera captures an image of the text.</li>
  <li><strong>Preprocessing:</strong> OpenCV enhances the image by converting it to grayscale, 
      binarizing it, and removing noise to improve OCR accuracy.</li>
  <li><strong>Text Extraction:</strong> Tesseract OCR processes the image and extracts readable text.</li>
  <li><strong>Text-to-Speech Conversion:</strong> The extracted text is passed to Pico TTS, which 
      converts it into an audio output.</li>
  <li><strong>Audio Output:</strong> The system plays the generated speech through the connected 
      speaker or headset.</li>
  <li><strong>Online Assistance (Optional):</strong> If users need further help, they can interact 
      with Google Assistant for additional information.</li>
  <li><strong>Video Conferencing (Optional):</strong> If necessary, users can initiate a real-time 
      video call with their teachers using Jitsi Meet.</li>
</ol>

<h3>📡 Connectivity:</h3>
<ul>
  <li>The system connects to the internet via <strong>Wi-Fi</strong> or <strong>GSM/GPRS Module</strong> 
      to enable Google Assistant and video conferencing.</li>
  <li>If no internet connection is available, the text-to-speech function still operates offline.</li>
</ul>

<h3>🔋 Power Management:</h3>
<ul>
  <li>The device is powered by a <strong>10,000mAh power bank</strong>, allowing extended usage of up to 8 hours.</li>
  <li>Battery optimization techniques ensure efficient power consumption while running multiple processes.</li>
</ul>

<p>This architecture ensures that AI-WEAR operates efficiently both online and offline, providing 
a reliable assistive solution for visually impaired students.</p>

<h2>🎯 Future Improvements</h2>
<ul>
  <li>Develop a <strong>lighter and more compact version</strong> by improving the casing design.</li>
  <li>Enhance camera features by integrating:
    <ul>
      <li>HD Lens for improved image quality.</li>
      <li>Wide Lens for capturing a larger field of view.</li>
    </ul>
  </li>
  <li>Implement a <strong>camera alignment notification</strong> to assist users in capturing text at the correct angle and distance.</li>
  <li>Increase <strong>text detection capabilities</strong> by supporting more words and font styles.</li>
  <li>Add <strong>mathematical equation detection</strong> for better accessibility in STEM learning.</li>
  <li>Implement a <strong>Braille system reader</strong> for enhanced accessibility.</li>
  <li>Use alternative <strong>voice synthesizers</strong> for clearer speech output in both English and Filipino.</li>
  <li>Explore alternative <strong>cellular data technologies</strong> instead of the GSM module for improved connectivity.</li>
  <li>Enhance object recognition features, including <strong>bill detection</strong> for currency identification.</li>
  <li>Optimize battery efficiency for extended device usage.</li>
</ul>


<h2>📩 Contact & Contributions</h2>
<p>Developed by: <strong>Vincent Manlesis & Andrey Manguiat</strong></p>

