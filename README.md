<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sylvester Hayes — GitHub Profile</title>
<style>
  :root {
    --blue: #1F4E79;
    --blue-light: #2E75B6;
    --gray: #595959;
    --bg: #f5f5f5;
    --card: #ffffff;
    --border: #e0e0e0;
    --text: #1a1a1a;
    --muted: #555;
    --badge-red: #c0392b;
    --badge-gold: #b8860b;
    --badge-blue: #1a5276;
    --tag-bg: #eaf3fb;
    --tag-text: #1a5276;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --border: #30363d;
      --text: #c9d1d9;
      --muted: #8b949e;
      --blue: #58a6ff;
      --blue-light: #79c0ff;
      --tag-bg: #1c2d3f;
      --tag-text: #79c0ff;
    }
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    padding: 32px 16px;
    line-height: 1.6;
  }
  .container { max-width: 860px; margin: 0 auto; }

  /* Header */
  .header { text-align: center; margin-bottom: 32px; }
  .header h1 { font-size: 32px; color: var(--blue); font-weight: 700; margin-bottom: 6px; }
  .header h2 { font-size: 16px; color: var(--muted); font-weight: 400; margin-bottom: 16px; }
  .badges { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-bottom: 8px; }
  .badge {
    display: inline-block;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 12px;
    font-weight: 600;
    text-decoration: none;
    color: white;
  }
  .badge.linkedin { background: #0A66C2; }
  .badge.red { background: #c0392b; }
  .badge.gold { background: #9a7d0a; }
  .badge.blue { background: #1a5276; }

  /* Divider */
  hr { border: none; border-top: 1px solid var(--border); margin: 24px 0; }

  /* Section */
  section { margin-bottom: 32px; }
  section h3 {
    font-size: 18px;
    color: var(--blue);
    margin-bottom: 14px;
    padding-bottom: 6px;
    border-bottom: 2px solid var(--blue-light);
  }

  /* About bullets */
  .about-list { list-style: none; padding: 0; }
  .about-list li { padding: 5px 0; font-size: 15px; color: var(--text); }
  .about-list li span { margin-right: 8px; }

  /* Tech stack table */
  table { width: 100%; border-collapse: collapse; font-size: 14px; }
  th {
    text-align: left;
    padding: 8px 12px;
    background: var(--card);
    color: var(--blue);
    font-weight: 600;
    border-bottom: 2px solid var(--border);
  }
  td {
    padding: 8px 12px;
    border-bottom: 1px solid var(--border);
    color: var(--text);
    vertical-align: top;
  }
  td:first-child { font-weight: 600; white-space: nowrap; width: 180px; }
  tr:last-child td { border-bottom: none; }
  tbody tr:nth-child(even) td { background: var(--card); }

  /* Project cards */
  .project-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-left: 4px solid var(--blue-light);
    border-radius: 8px;
    padding: 20px 24px;
    margin-bottom: 16px;
  }
  .project-card h4 { font-size: 16px; margin-bottom: 6px; }
  .project-card h4 a { color: var(--blue); text-decoration: none; }
  .project-card h4 a:hover { text-decoration: underline; }
  .project-card blockquote {
    font-size: 14px;
    color: var(--muted);
    border-left: 3px solid var(--border);
    padding-left: 12px;
    margin: 10px 0;
    font-style: italic;
  }
  .project-meta { font-size: 13px; margin-top: 10px; }
  .project-meta strong { color: var(--blue-light); }
  .tag {
    display: inline-block;
    background: var(--tag-bg);
    color: var(--tag-text);
    border-radius: 4px;
    padding: 2px 8px;
    font-size: 12px;
    margin: 2px 2px 2px 0;
    font-weight: 500;
  }

  /* Certs table */
  .cert-table { width: 100%; border-collapse: collapse; font-size: 14px; }
  .cert-table th {
    text-align: left;
    padding: 8px 12px;
    background: var(--card);
    color: var(--blue);
    font-weight: 600;
    border-bottom: 2px solid var(--border);
  }
  .cert-table td { padding: 8px 12px; border-bottom: 1px solid var(--border); }
  .cert-table tr:last-child td { border-bottom: none; }
  .status-earned { color: #2e7d32; font-weight: 600; }
  .status-progress { color: #b8860b; font-weight: 600; }

  /* Connect */
  .connect-list { list-style: none; padding: 0; }
  .connect-list li { padding: 5px 0; font-size: 15px; }
  .connect-list a { color: var(--blue-light); text-decoration: none; }
  .connect-list a:hover { text-decoration: underline; }

  /* Footer quote */
  .footer-quote {
    text-align: center;
    font-style: italic;
    color: var(--muted);
    font-size: 14px;
    margin-top: 32px;
    padding-top: 16px;
    border-top: 1px solid var(--border);
  }
</style>
</head>
<body>
<div class="container">

  <!-- Header -->
  <div class="header">
    <h1>Hi, I'm Sylvester Hayes 👋</h1>
    <h2>Linux Engineer | IT Automation | Cybersecurity</h2>
    <div class="badges">
      <a href="https://www.linkedin.com/in/sylvesterhayes" class="badge linkedin">LinkedIn — sylvesterhayes</a>
      <a href="https://www.credly.com/badges/fa804184-9900-4d45-99b0-685aede9a5f7/public_url" class="badge red">CompTIA Security+</a>
      <a href="https://www.credly.com/badges/fa804184-9900-4d45-99b0-685aede9a5f7/public_url" class="badge red">CompTIA A+</a>
      <span class="badge red">CompTIA Network+</span>
      <span class="badge gold">LPI Linux Essentials</span>
      <span class="badge blue">ITIL4 IT Service Management</span>
    </div>
  </div>

  <hr>

  <!-- About -->
  <section>
    <h3>About Me</h3>
    <p style="font-size:15px; margin-bottom:14px; color:var(--muted);">
      IT professional with hands-on experience supporting enterprise healthcare infrastructure, transitioning into Linux Administration and IT Automation. I work in high-compliance environments and bring a security-first mindset to everything I build.
    </p>
    <ul class="about-list">
      <li><span>🏥</span><strong>Currently:</strong> Tech Analyst @ <strong>Atrium Health</strong> — resolving 60–70 technical support requests daily across hardware, software, and network systems</li>
      <li><span>🎓</span><strong>Pursuing:</strong> B.S. Cybersecurity &amp; Information Assurance @ <strong>WGU</strong> (expected 2025)</li>
      <li><span>🔭</span><strong>Targeting:</strong> Linux Admin / Ansible Automation roles in <strong>Government, Healthcare, and Finance</strong></li>
      <li><span>🧪</span><strong>Currently studying:</strong> RHCSA · LPI Linux 1</li>
    </ul>
  </section>

  <hr>

  <!-- Tech Stack -->
  <section>
    <h3>🛠️ Tech Stack</h3>
    <table>
      <thead><tr><th>Category</th><th>Tools</th></tr></thead>
      <tbody>
        <tr><td>Operating Systems</td><td>RHEL, CentOS, Ubuntu, Windows Server</td></tr>
        <tr><td>Automation</td><td>Ansible, Bash, YAML, Shell scripting</td></tr>
        <tr><td>Containers</td><td>Docker, Kubernetes (learning), OpenShift (learning)</td></tr>
        <tr><td>ITSM</td><td>ServiceNow, ITIL4</td></tr>
        <tr><td>Monitoring</td><td>Grafana, Prometheus (learning), Splunk (learning)</td></tr>
        <tr><td>Networking</td><td>TCP/IP, DNS, DHCP, VPN, network troubleshooting</td></tr>
        <tr><td>Security</td><td>CompTIA Security+, HIPAA compliance, change management</td></tr>
        <tr><td>Scripting</td><td>Bash, Python (in progress), PowerShell</td></tr>
      </tbody>
    </table>
  </section>

  <hr>

  <!-- Projects -->
  <section>
    <h3>📁 Projects</h3>

    <div class="project-card">
      <h4>🔧 <a href="https://github.com/Sylvester-Hayes/ansible-user-provisioning">Ansible User Provisioning Automation</a></h4>
      <blockquote>Automate Linux user creation, SSH key deployment, and sudo access management across multiple hosts using Ansible playbooks.</blockquote>
      <div class="project-meta">
        <strong>Skills:</strong><br>
        <span class="tag">Ansible</span><span class="tag">YAML</span><span class="tag">Linux user management</span><span class="tag">SSH</span><span class="tag">Privilege escalation</span><span class="tag">Idempotency</span>
      </div>
      <div class="project-meta" style="margin-top:8px;">
        <strong>Relevant to:</strong> Enterprise Ansible Automation Platform roles in finance and government
      </div>
    </div>

    <div class="project-card">
      <h4>🔐 <a href="https://github.com/Sylvester-Hayes/linux-hardening-cis">Linux Hardening Baseline (CIS Benchmark)</a></h4>
      <blockquote>Bash script that audits and hardens a RHEL/CentOS system against CIS Level 1 security benchmarks — covering SSH config, file permissions, account policies, and logging.</blockquote>
      <div class="project-meta">
        <strong>Skills:</strong><br>
        <span class="tag">Bash scripting</span><span class="tag">CIS benchmarks</span><span class="tag">Linux security hardening</span><span class="tag">auditd</span><span class="tag">syslog</span>
      </div>
      <div class="project-meta" style="margin-top:8px;">
        <strong>Relevant to:</strong> Security-focused Linux Admin roles in healthcare and government
      </div>
    </div>

    <div class="project-card">
      <h4>📊 <a href="https://github.com/Sylvester-Hayes/system-health-monitor">System Health Monitoring Dashboard (Bash + Cron)</a></h4>
      <blockquote>Lightweight monitoring script that collects CPU, memory, disk, and service health data on a schedule via cron, outputs structured reports, and sends alerts when thresholds are exceeded.</blockquote>
      <div class="project-meta">
        <strong>Skills:</strong><br>
        <span class="tag">Bash</span><span class="tag">Cron scheduling</span><span class="tag">System monitoring</span><span class="tag">Log parsing</span><span class="tag">Alerting logic</span>
      </div>
      <div class="project-meta" style="margin-top:8px;">
        <strong>Relevant to:</strong> Platform ops roles requiring production system monitoring
      </div>
    </div>

    <div class="project-card">
      <h4>🐳 <a href="https://github.com/Sylvester-Hayes/docker-nginx-app">Containerized Web App Deployment with Docker + Nginx</a></h4>
      <blockquote>Deploy a simple web application inside a Docker container fronted by an Nginx reverse proxy — including a Dockerfile, docker-compose.yml, and a runbook for common operational tasks.</blockquote>
      <div class="project-meta">
        <strong>Skills:</strong><br>
        <span class="tag">Docker</span><span class="tag">Nginx</span><span class="tag">docker-compose</span><span class="tag">Container networking</span><span class="tag">Operational runbooks</span>
      </div>
      <div class="project-meta" style="margin-top:8px;">
        <strong>Relevant to:</strong> OpenShift/Kubernetes platform roles and DevOps-adjacent Linux Admin positions
      </div>
    </div>
  </section>

  <hr>

  <!-- Certifications -->
  <section>
    <h3>📜 Certifications</h3>
    <table class="cert-table">
      <thead><tr><th>Certification</th><th>Status</th></tr></thead>
      <tbody>
        <tr><td>CompTIA A+</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>CompTIA Network+</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>CompTIA Security+</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>Linux Essentials (LPI)</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>ITIL4 IT Service Management</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>Google IT Support Professional</td><td class="status-earned">✅ Earned</td></tr>
        <tr><td>RHCSA</td><td class="status-progress">🔄 In progress</td></tr>
        <tr><td>LPI Linux 1</td><td class="status-progress">🔄 In progress</td></tr>
      </tbody>
    </table>
  </section>

  <hr>

  <!-- Connect -->
  <section>
    <h3>📫 Connect</h3>
    <ul class="connect-list">
      <li>💼 <a href="https://www.linkedin.com/in/sylvesterhayes">LinkedIn — linkedin.com/in/sylvesterhayes</a></li>
      <li>📧 sylvester.hayes@icloud.com</li>
      <li>📍 Charlotte, NC</li>
    </ul>
  </section>

  <div class="footer-quote">
    "Building the skills to automate infrastructure the right way — secure, repeatable, and documented."
  </div>

</div>
</body>
</html>
