<!-- README for ScannerSavvy -->

<h1 id="title">🔬 Scanner-Savvy</h1>

<p>
Your go-to guide for <strong>scanner know-how</strong> in the lab:
<ul>
  <li><strong>Coil Inventory</strong> — what coils are available, specs, and typical uses</li>
  <li><strong>Acquisition Basics</strong> — how to set up and run standard MRI scans</li>
  <li><strong>Specialized Sequences</strong> — introductions to advanced methods and tips to get started</li>
</ul>
</p>

<hr/>

<nav>
  <h2>📑 Table of Contents</h2>
  <ol>
    <li><a href="#coils">Coil Inventory</a></li>
    <li><a href="#acquisition">Acquisition Basics</a></li>
    <li><a href="#troubleshooting">Troubleshooting & Error Reporting</a></li>
    <li><a href="#best pratices">Best Practices for Efficient & Reliable Scanning</a></li>
    <li><a href="#specialized">Specialized Sequences</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License & Disclaimer</a></li>
  </ol>
</nav>

<hr/>

<h2 id="coils">🌀 Coil Inventory</h2>
<p>
A list of coils currently available on our scanner. Each coil entry should include:
</p>
<ul>
  <li><strong>Name/Type</strong> (e.g. 16-channel receive, volume TxRx, surface coil, custom loop)</li>
  <li><strong>Typical use cases</strong> (e.g. DTI, fMRI, spectroscopy, vascular imaging)</li>
  <li><strong>Specs</strong> (channels, field strength compatibility, SNR characteristics)</li>
  <li><strong>Notes</strong> (setup quirks, known issues, recommended phantom)</li>
</ul>

<p><em>See <code>/docs/coils/</code> for detailed PDFs, photos, and setup diagrams.</em></p>

<hr/>

<h2 id="acquisition">📷 Acquisition Basics</h2>
<p>
Step-by-step guidelines for running standard acquisitions:
</p>
<ul>
  <li>How to set up the scanner and coils safely (patient table, coil selection, plugging pre-amps)</li>
  <li>Standard localizer → anatomy → functional/structural scan workflow</li>
  <li>Sequence parameters to check (TR, TE, flip angle, voxel size, bandwidth)</li>
  <li>Basic troubleshooting: shimming, center frequency, FOV setup</li>
</ul>

<p><em>Detailed walkthroughs in <code>/docs/acquisition/</code>.</em></p>

<hr/>

<h2 id="troubleshooting">📝 Troubleshooting & Error Logging</h2>

<p>
Maintaining scanner health and reliability is a <strong>shared responsibility</strong>. 
Every user benefits from accurate error reporting — it ensures problems are diagnosed quickly, 
reduces downtime, and protects data quality across studies. 
</p>

<p>
If you encounter <strong>any unusual scanner behavior</strong> (error messages, abnormal noises, failed sequences, unexpected image artifacts, etc.), it is your responsibility to <strong>log the issue immediately</strong>. 
Even small problems can point to larger underlying hardware or software issues.
</p>

<h3>🚩 What to Report</h3>
<ul>
  <li>Scanner error codes, warnings, or crashes</li>
  <li>Unusual sounds (gradient noise changes, coil clicks, fans)</li>
  <li>Acquisition failures (unexpected sequence termination, missing channels)</li>
  <li>Image artifacts that are new or unexplained</li>
  <li>Safety-related events (coil heating, strong smells, emergency stops)</li>
</ul>

<h3>🛠️ How to Report</h3>
<ol>
  <li>Pause scanning safely (do not force reset unless required).</li>
  <li>Note the time, sequence name, coil in use, and subject/phantom if applicable.</li>
  <li>Take screenshots/photos if possible.</li>
  <li>Submit a report using our <a href="YOUR_ONEDRIVE_SURVEY_LINK" target="_blank"><strong>Scanner Error Logging Form</strong></a>.</li>
  <li>Follow up with lab staff if the error prevents continued scanning.</li>
</ol>

<p>
<strong>Remember:</strong> Logging errors is not optional — it is a <em>lab-wide policy</em> that ensures fairness, 
prevents repeated wasted scan time, and helps our technical staff and PIs keep the scanner safe and operational.  
</p>


<h2 id="best-practices">🌟 Best Practices for Efficient & Reliable Scanning</h2>

<p>
Beyond technical setup, <strong>good scanning habits</strong> ensure that experiments run smoothly, 
animals spend less time under anesthesia, and scanner resources are used effectively.  
These practices are expected of all scanner users.  
</p>

<h3>📊 Data & Image Review</h3>
<ul>
  <li><strong>Check images as soon as they are acquired</strong> — verify orientation, coverage, and quality before moving on.</li>
  <li>Look for <em>obvious artifacts</em> (motion, ghosting, missing slices) immediately so issues can be corrected on the spot.</li>
</ul>

<h3>⏱️ Reducing Downtime (Especially in Animal Imaging)</h3>
<ul>
  <li>Prepare and queue your sequences <strong>before</strong> starting scans to avoid idle time.</li>
  <li><strong>Edit or adjust sequences only while another scan is already running</strong> — this keeps the scanner busy at all times.</li>
  <li>Use localizers strategically: run a localizer several sequences before your target imaging so that setup is not blocking data acquisition.</li>
</ul>

<h3>🧠 Example: CASL Imaging Workflow</h3>
<ul>
  <li>Step 1: Acquire a carotid image to visualize vessel location.</li>
  <li>Step 2: Place the labeling plane accurately on the carotids.</li>
  <li>Step 3: Set up the actual ASL imaging slice and run the sequence.</li>
  <li><em>Tip:</em> While CASL labeling setup is being adjusted, ensure other sequences (e.g. localizer, scout scans) are already running to minimize idle scanner time.</li>
</ul>

<h3>⚡ General Efficiency Tips</h3>
<ul>
  <li>Save parameter sets for commonly used sequences to avoid repetitive setup.</li>
  <li>Group related scans together to minimize table adjustments and shim recalibration.</li>
  <li>Communicate with your team — plan your sequence order before the subject/animal is in the bore.</li>
</ul>

<p>
<strong>Remember:</strong> Efficient scanning reduces stress on animals, 
saves valuable scanner time, and improves the reproducibility of your experiments.
</p>

<hr/>

<hr/>

<h2 id="specialized">⚡ Specialized Sequences</h2>
<p>
Getting started with advanced or less-common methods:
</p>
<ul>
  <li><strong>ASL (CASL/FAIR)</strong> — labeling setup, timing, recommended TR/TE ranges</li>
  <li><strong>TOF Angiography</strong> — parameters, flow suppression, slab planning</li>
  <li><strong>DWI/DTI</strong> — b-value sets, directions, EPI artifact reduction tips</li>
  <li><strong>QSM/STI</strong> — multi-echo GRE setup, phase unwrapping pointers</li>
  <li><strong>fMRI</strong> — block/event design basics, typical TRs, physiological monitoring</li>
</ul>

<p><em>Each sequence has its own guide under <code>/docs/sequences/</code> with parameter tables and example screenshots.</em></p>

<hr/>

<h2 id="contributing">🤝 Contributing</h2>
<p>
To add or update content:
</p>
<ol>
  <li>Create a new Markdown or HTML page in <code>/docs/coils</code>, <code>/docs/acquisition</code>, or <code>/docs/sequences</code>.</li>
  <li>Include photos, diagrams, or parameter tables where possible.</li>
  <li>Submit a pull request with a short summary of the update.</li>
</ol>

<hr/>

<h2 id="license">📄 License & Disclaimer</h2>
<p>
Content is licensed under <strong>CC BY 4.0</strong> for educational/research use.  
Always follow vendor safety protocols and your institution’s MR safety officer guidance.  
This repo is <strong>not</strong> a substitute for official training or manuals.
</p>

<hr/>

<footer>
  <p><em>Maintainer:</em> Your Name • <em>Lab:</em> Your Lab • <em>Contact:</em> your.email@domain</p>
</footer>
