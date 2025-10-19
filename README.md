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
