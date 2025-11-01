<h1 align="center">Lossless Image Compressor & Converter</h1>

<p align="center">
  <b>A simple Python GUI application to convert and compress images without quality loss.</b><br>
  Built with <b>Tkinter</b> for an intuitive interface and <b>Pillow (PIL)</b> for image processing.
</p>

<hr>

<h2>➤ Project Overview</h2>
<p>
This project provides a user-friendly <b>Image Converter and Compressor</b> built in Python.<br>
It allows users to <b>upload an image</b> and convert it into <b>PNG</b>, <b>JPG</b>, or <b>PDF</b> formats easily.<br>
The app uses <b>Pillow (PIL)</b> for lossless image conversion and <b>Tkinter</b> for the GUI interface.<br>
All conversions are done <b>locally</b> with zero data loss.
</p>

<hr>

<h2>➤ Features</h2>
<ul>
  <li> Upload and preview images directly in the app window.</li>
  <li> Convert images to <b>PNG</b>, <b>JPG</b>, or <b>PDF</b> with a single click.</li>
  <li> Uses <b>lossless compression</b> for high-quality image conversion.</li>
  <li> Simple GUI built using <b>Tkinter</b> for easy use.</li>
  <li> Cross-platform — works on Windows, macOS, and Linux.</li>
</ul>

<hr>

<h2>➤ Tech Stack / Requirements</h2>
<ul>
  <li> <b>Language:</b> Python 3.x</li>
  <li> <b>GUI Library:</b> Tkinter (built-in with Python)</li>
  <li> <b>Image Processing:</b> Pillow (PIL)</li>
  <li> <b>Modules Used:</b> tkinter, filedialog, messagebox, os, PIL (Image, ImageTk)</li>
  <li> <b>Operating System:</b> Works on Windows, macOS, and Linux</li>
</ul>

<hr>

<h2>➤ Installation and Setup</h2>

<ol>
  <li><b>Clone the Repository</b>
    <pre>
git clone https://github.com/Ravi6888/Image_Converter.git
cd Image_Converter
    </pre>
  </li>

  <li><b>Install Required Packages</b>
    <pre>
pip install pillow
    </pre>
  </li>

  <li><b>Run the Application</b>
    <pre>
python ImageConverterApp.py
    </pre>
  </li>
</ol>

<hr>

<h2>➤ How It Works</h2>
<ul>
  <li> Launch the application window.</li>
  <li> Click <b>Upload Image</b> to select a file (PNG, JPG, JPEG, BMP, or GIF).</li>
  <li> The selected image preview appears in the center frame.</li>
  <li> Choose your desired format:
    <ul>
      <li> <b>Convert to PNG</b> — Saves the file as .png</li>
      <li> <b>Convert to JPG</b> — Saves as .jpg (optimized and high quality)</li>
      <li> <b>Convert to PDF</b> — Converts image to a .pdf file</li>
    </ul>
  </li>
  <li> The converted image is saved in the same directory as the original.</li>
</ul>

<hr>

<h2>➤ GUI Preview</h2>
<p align="center"><i><img width="453" height="400" alt="image" src="https://github.com/user-attachments/assets/9b15e363-e036-4faf-90dc-03d8b241d9c4" />
</i></p>

<hr>

<h2>➤ Example Output</h2>
<pre>
[INFO] Launching Lossless Image Converter...
Selected File: sample.jpg
Image saved as sample.png
Image saved as sample.pdf
Image saved as sample.jpeg
</pre>

<hr>

<h2>➤ File Details</h2>
<table>
  <tr><th>File</th><th>Description</th></tr>
  <tr><td>ImageConverterApp.py</td><td>Main script containing GUI and conversion logic.</td></tr>
  <tr><td>Pillow (PIL)</td><td>Used for image opening, compression, and conversion.</td></tr>
  <tr><td>Tkinter</td><td>Used for the user interface, buttons, and image preview display.</td></tr>
</table>

<hr>

<h2>➤ Customization Ideas</h2>
<ul>
  <li> Add support for additional image formats (e.g., TIFF, WEBP).</li>
  <li> Include drag-and-drop functionality for faster uploads.</li>
  <li> Add progress indicators for large images.</li>
  <li> Integrate batch conversion (convert multiple images at once).</li>
  <li> Include image compression level settings for advanced users.</li>
</ul>

<hr>



<hr>

<p align="center">
⭐ <i>If you found this project useful, consider giving it a star!</i> ⭐
</p>
