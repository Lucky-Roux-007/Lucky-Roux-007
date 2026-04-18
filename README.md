<div align="center">

<!-- Animated Banner with Matrix-style Name -->
<svg width="100%" height="160" viewBox="0 0 800 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradient for glow effect -->
    <linearGradient id="glow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff41" stop-opacity="0.2"/>
      <stop offset="50%" stop-color="#00ff41" stop-opacity="1"/>
      <stop offset="100%" stop-color="#00ff41" stop-opacity="0.2"/>
    </linearGradient>
    <filter id="blur">
      <feGaussianBlur stdDeviation="2"/>
    </filter>
  </defs>
  
  <!-- Background grid -->
  <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
    <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#00ff41" stroke-width="0.3" opacity="0.15"/>
  </pattern>
  <rect width="100%" height="160" fill="url(#grid)"/>
  
  <!-- Glitch text effect - Name -->
  <text x="400" y="65" font-family="monospace" font-size="42" font-weight="bold" fill="#00ff41" text-anchor="middle" filter="url(#blur)" opacity="0.6">
    <tspan>UNKNOWN USER</tspan>
    <animate attributeName="x" values="400;402;398;400" dur="0.3s" repeatCount="indefinite"/>
  </text>
  
  <text x="400" y="65" font-family="monospace" font-size="42" font-weight="bold" fill="#00ff41" text-anchor="middle">
    <tspan>UNKNOWN USER</tspan>
    <animate attributeName="opacity" values="1;0.8;1;0.9;1" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Glitch offset layer -->
  <text x="400" y="65" font-family="monospace" font-size="42" font-weight="bold" fill="#ff0040" text-anchor="middle" opacity="0.4">
    <tspan>UNKNOWN USER</tspan>
    <animate attributeName="x" values="400;396;404;400" dur="0.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0.4;0;0.2;0" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Animated subtitle -->
  <text x="400" y="100" font-family="monospace" font-size="16" fill="#00ccff" text-anchor="middle" opacity="0.9">
    <tspan>[ Cybersecurity Engineer &amp; Network Architect ]</tspan>
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Status line -->
  <text x="400" y="130" font-family="monospace" font-size="12" fill="#888" text-anchor="middle">
    <tspan>STATUS: </tspan>
    <tspan fill="#00ff41">
      <animate attributeName="textContent" values="ONLINE;ONLINE.;ONLINE..;ONLINE...;ONLINE..;ONLINE.;ONLINE" dur="1.5s" repeatCount="indefinite"/>
    </tspan>
  </text>
  
  <!-- Corner brackets -->
  <path d="M 20 20 L 20 35 M 20 20 L 35 20" stroke="#00ff41" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
  </path>
  <path d="M 780 20 L 780 35 M 780 20 L 765 20" stroke="#00ff41" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite" begin="0.5s"/>
  </path>
  <path d="M 20 140 L 20 125 M 20 140 L 35 140" stroke="#00ff41" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite" begin="1s"/>
  </path>
  <path d="M 780 140 L 780 125 M 780 140 L 765 140" stroke="#00ff41" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite" begin="1.5s"/>
  </path>
</svg>

<!-- Animated Divider - Data Stream -->
<svg width="100%" height="30" viewBox="0 0 800 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="stream" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff41" stop-opacity="0"/>
      <stop offset="30%" stop-color="#00ff41" stop-opacity="0.8"/>
      <stop offset="70%" stop-color="#00ccff" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#00ccff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <text x="400" y="20" font-family="monospace" font-size="10" fill="url(#stream)" text-anchor="middle" letter-spacing="3">
    <tspan>01001000 01100101 01101100 01101100 01101111 00100000 01010111 01101111 01110010 01101100 01100100</tspan>
    <animateTransform attributeName="transform" type="translate" from="800 0" to="-800 0" dur="8s" repeatCount="indefinite"/>
  </text>
</svg>

</div>

<!-- About Me Section - Terminal Style -->
```bash
$ whoami
> Cybersecurity enthusiast & Network Engineering student

$ uname -a
> ENSA-Khouribga 1337-Coding-School GNU/Linux kernel-enthusiast

$ echo $INTERESTS
> Reverse-Engineering Cryptography CTF Linux Network-Programming

$ cat /etc/motd
```

<div align="center">

<!-- Typing SVG -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Breaking+things+to+understand+them...;Building+secure+systems+from+scratch...;Pwning+binaries+at+3AM...;Simulating+networks+in+GNS3...;Always+learning%2C+always+evolving..." />

</div>

---

## <img src="https://media.giphy.com/media/juua9i2c2fA0QLpwmk/giphy.gif" width="25"> `System_Info`

```yaml
Name:         UNKNOWN USER
Education:    
  - Intelligent Networks Engineering & Cybersecurity @ ENSA Khouribga
  - 1337 Coding School (42 Network) - Khouribga Campus
Mission:      Master the art of secure systems & network architecture
Status:       Currently pwning challenges and building things
Philosophy:   "Understand the system. Break it. Fix it. Secure it."
```

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="25"> `Tech_Stack`

<div align="center">

<!-- Programming Languages -->
**`Programming_Languages:`**

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" title="C"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" title="Java"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" title="Bash"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powershell/powershell-original.svg" title="PowerShell"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" title="MySQL"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" title="MATLAB"></code>

**`Security_Tools:`**

<code><img height="30" src="https://img.shields.io/badge/Ghidra-0055A4?style=flat-square&logo=ghidra&logoColor=white" title="Ghidra"></code>&nbsp;
<code><img height="30" src="https://img.shields.io/badge/IDA%20Pro-000000?style=flat-square&logoColor=white" title="IDA Pro"></code>&nbsp;
<code><img height="30" src="https://img.shields.io/badge/GNS3-0055A4?style=flat-square&logoColor=white" title="GNS3"></code>&nbsp;
<code><img height="30" src="https://img.shields.io/badge/Packet%20Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white" title="Packet Tracer"></code>

**`Operating_Systems:`**

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" title="Linux"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redhat/redhat-original.svg" title="Red Hat"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" title="Ubuntu"></code>&nbsp;
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" title="Windows"></code>

**`Certifications:`**

<code><img height="25" src="https://img.shields.io/badge/CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" title="CCNA"></code>&nbsp;
<code><img height="25" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" title="AWS"></code>&nbsp;
<code><img height="25" src="https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white" title="Red Hat"></code>

</div>

---

## <img src="https://media.giphy.com/media/WFZvB7VIXBgiz3oDXE/giphy.gif" width="25"> `Battle_Zone`

<div align="center">

<!-- Animated Battle Stats -->
<svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="ctfGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff41"/>
      <stop offset="100%" stop-color="#00ccff"/>
    </linearGradient>
  </defs>
  
  <!-- Background Panel -->
  <rect x="50" y="10" width="700" height="160" rx="10" fill="#0d1117" stroke="#30363d" stroke-width="1"/>
  
  <!-- Title -->
  <text x="400" y="40" font-family="monospace" font-size="18" font-weight="bold" fill="#00ff41" text-anchor="middle">
    <tspan>ACTIVE ENGAGEMENTS</tspan>
    <animate attributeName="opacity" values="1;0.5;1" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Divider -->
  <line x1="100" y1="55" x2="700" y2="55" stroke="#30363d" stroke-width="1"/>
  
  <!-- CTF Icon and Text -->
  <text x="130" y="90" font-family="monospace" font-size="40" fill="url(#ctfGrad)">
    <tspan>CTF</tspan>
    <animate attributeName="opacity" values="1;0.7;1" dur="1.5s" repeatCount="indefinite"/>
  </text>
  
  <text x="130" y="115" font-family="monospace" font-size="12" fill="#888">CAPTURE THE FLAG</text>
  
  <!-- Status Indicators -->
  <g transform="translate(350, 75)">
    <!-- Reverse Engineering -->
    <circle cx="0" cy="0" r="6" fill="#00ff41">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/>
    </circle>
    <text x="15" y="5" font-family="monospace" font-size="14" fill="#c9d1d9">Reverse Engineering</text>
    <text x="15" y="25" font-family="monospace" font-size="11" fill="#00ff41">Ghidra | IDA Pro</text>
    
    <!-- Cryptography -->
    <circle cx="0" cy="45" r="6" fill="#00ccff">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.4s" repeatCount="indefinite"/>
    </circle>
    <text x="15" y="50" font-family="monospace" font-size="14" fill="#c9d1d9">Cryptography</text>
    <text x="15" y="70" font-family="monospace" font-size="11" fill="#00ccff">Breaking ciphers daily</text>
  </g>
  
  <g transform="translate(560, 75)">
    <!-- Network Programming -->
    <circle cx="0" cy="0" r="6" fill="#ff6b35">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/>
    </circle>
    <text x="15" y="5" font-family="monospace" font-size="14" fill="#c9d1d9">Network Programming</text>
    <text x="15" y="25" font-family="monospace" size="11" fill="#ff6b35">C | Python sockets</text>
    
    <!-- Competitive -->
    <circle cx="0" cy="45" r="6" fill="#ffd93d">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    <text x="15" y="50" font-family="monospace" font-size="14" fill="#c9d1d9">Competitive Programming</text>
    <text x="15" y="70" font-family="monospace" font-size="11" fill="#ffd93d">Hackathons & Challenges</text>
  </g>
</svg>

</div>

---

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="25"> `Network_Topology`

<div align="center">

<!-- Interactive Skills Network Graph -->
<svg width="100%" height="320" viewBox="0 0 800 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradients -->
    <radialGradient id="nodeGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00ff41" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#00ff41" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="linkGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff41" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#00ccff" stop-opacity="0.6"/>
    </linearGradient>
  </defs>
  
  <!-- Background -->
  <rect width="100%" height="320" fill="#0d1117" rx="10"/>
  
  <!-- Central Node - Security -->
  <circle cx="400" cy="160" r="35" fill="#161b22" stroke="#00ff41" stroke-width="2">
    <animate attributeName="r" values="35;38;35" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="160" r="50" fill="url(#nodeGlow)">
    <animate attributeName="r" values="50;55;50" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="400" y="155" font-family="monospace" font-size="11" font-weight="bold" fill="#00ff41" text-anchor="middle">CYBER</text>
  <text x="400" y="170" font-family="monospace" font-size="11" font-weight="bold" fill="#00ff41" text-anchor="middle">SECURITY</text>
  
  <!-- Animated Connection Lines -->
  <!-- To Reverse Engineering -->
  <line x1="370" y1="130" x2="200" y2="60" stroke="url(#linkGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,300;300,0" dur="2s" repeatCount="indefinite"/>
  </line>
  
  <!-- To Networking -->
  <line x1="430" y1="130" x2="600" y2="60" stroke="url(#linkGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,300;300,0" dur="2.5s" repeatCount="indefinite"/>
  </line>
  
  <!-- To Programming -->
  <line x1="365" y1="190" x2="150" y2="260" stroke="url(#linkGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,350;350,0" dur="3s" repeatCount="indefinite"/>
  </line>
  
  <!-- To Databases -->
  <line x1="435" y1="190" x2="650" y2="260" stroke="url(#linkGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,350;350,0" dur="2.2s" repeatCount="indefinite"/>
  </line>
  
  <!-- To Systems -->
  <line x1="400" y1="195" x2="400" y2="280" stroke="url(#linkGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,200;200,0" dur="1.8s" repeatCount="indefinite"/>
  </line>
  
  <!-- Satellite Node 1 - Reverse Engineering -->
  <circle cx="200" cy="60" r="30" fill="#161b22" stroke="#ff6b35" stroke-width="2">
    <animate attributeName="r" values="30;32;30" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <text x="200" y="55" font-family="monospace" font-size="10" fill="#ff6b35" text-anchor="middle" font-weight="bold">REVERSE</text>
  <text x="200" y="68" font-family="monospace" font-size="10" fill="#ff6b35" text-anchor="middle" font-weight="bold">ENGINEERING</text>
  
  <!-- Satellite Node 2 - Networking -->
  <circle cx="600" cy="60" r="30" fill="#161b22" stroke="#00ccff" stroke-width="2">
    <animate attributeName="r" values="30;32;30" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <text x="600" y="55" font-family="monospace" font-size="10" fill="#00ccff" text-anchor="middle" font-weight="bold">NETWORK</text>
  <text x="600" y="68" font-family="monospace" font-size="10" fill="#00ccff" text-anchor="middle" font-weight="bold">ENGINEERING</text>
  
  <!-- Satellite Node 3 - Programming -->
  <circle cx="150" cy="260" r="28" fill="#161b22" stroke="#ffd93d" stroke-width="2">
    <animate attributeName="r" values="28;30;28" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <text x="150" y="255" font-family="monospace" font-size="10" fill="#ffd93d" text-anchor="middle" font-weight="bold">PROGRAMMING</text>
  <text x="150" y="268" font-family="monospace" font-size="9" fill="#ffd93d" text-anchor="middle">C | Python | Java</text>
  
  <!-- Satellite Node 4 - Databases -->
  <circle cx="650" cy="260" r="28" fill="#161b22" stroke="#a855f7" stroke-width="2">
    <animate attributeName="r" values="28;30;28" dur="2.6s" repeatCount="indefinite"/>
  </circle>
  <text x="650" y="255" font-family="monospace" font-size="10" fill="#a855f7" text-anchor="middle" font-weight="bold">DATABASES</text>
  <text x="650" y="268" font-family="monospace" font-size="9" fill="#a855f7" text-anchor="middle">MySQL | Oracle</text>
  
  <!-- Satellite Node 5 - Systems -->
  <circle cx="400" cy="280" r="25" fill="#161b22" stroke="#00ff41" stroke-width="2">
    <animate attributeName="r" values="25;27;25" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="400" y="277" font-family="monospace" font-size="10" fill="#00ff41" text-anchor="middle" font-weight="bold">LINUX</text>
  <text x="400" y="290" font-family="monospace" font-size="9" fill="#00ff41" text-anchor="middle">Systems</text>
  
  <!-- Data Packets Animation -->
  <circle r="4" fill="#00ff41">
    <animateMotion path="M370,130 L200,60" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle r="4" fill="#00ccff">
    <animateMotion path="M430,130 L600,60" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle r="4" fill="#ffd93d">
    <animateMotion path="M365,190 L150,260" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle r="4" fill="#a855f7">
    <animateMotion path="M435,190 L650,260" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <circle r="4" fill="#00ff41">
    <animateMotion path="M400,195 L400,280" dur="1.8s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

---

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25"> `Access_Logs`

<!-- GitHub Stats with Cyber Theme -->
<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Lucky-Roux-007&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&ring_color=00ff41" />
<img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=Lucky-Roux-007&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=00ff41&ring=00ff41&fire=ff6b35&currStreakNum=00ff41&sideNums=00ccff&currStreakLabel=c9d1d9&sideLabels=c9d1d9" />

<br/>

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucky-Roux-007&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&langs_count=8" />

</div>

---

## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="25"> `Encrypted_Message`

<div align="center">

<!-- Animated Quote Decryption -->
<svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="quoteGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff41"/>
      <stop offset="50%" stop-color="#00ccff"/>
      <stop offset="100%" stop-color="#00ff41"/>
    </linearGradient>
  </defs>
  
  <!-- Terminal Box -->
  <rect x="100" y="20" width="600" height="140" rx="8" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  
  <!-- Terminal Header -->
  <rect x="100" y="20" width="600" height="25" rx="8" fill="#21262d"/>
  <circle cx="120" cy="32" r="6" fill="#ff5f56"/>
  <circle cx="140" cy="32" r="6" fill="#ffbd2e"/>
  <circle cx="160" cy="32" r="6" fill="#27c93f"/>
  <text x="680" y="37" font-family="monospace" font-size="11" fill="#888" text-anchor="end">decrypt.sh</text>
  
  <!-- Decrypting Text Animation -->
  <text x="400" y="80" font-family="monospace" font-size="15" fill="url(#quoteGrad)" text-anchor="middle" font-style="italic">
    <tspan>"I am the punishment of God...</tspan>
  </text>
  
  <text x="400" y="110" font-family="monospace" font-size="15" fill="url(#quoteGrad)" text-anchor="middle" font-style="italic">
    <tspan>If you had not committed great sins,</tspan>
  </text>
  
  <text x="400" y="140" font-family="monospace" font-size="15" fill="url(#quoteGrad)" text-anchor="middle" font-style="italic">
    <tspan>God would not have sent a punishment</tspan>
  </text>
  
  <!-- Cursor blink -->
  <rect x="555" y="128" width="8" height="18" fill="#00ff41">
    <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- Author Attribution -->

```
  ___ _  _ ___   ___ _   _ _____ ___  
 / __| || | __| | _ \ | | |_   _/ _ \ 
| (__| __ | _|  |   / |_| | | || (_) |
 \___|_||_|___| |_|_\\___/  |_| \___/ 
```

**Genghis Khan**

</div>

---

## <img src="https://media.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif" width="25"> `Connection_Ports`

<div align="center">

<!-- Contact / Social Section -->

**Let's establish a secure connection:**

<a href="mailto:yassine.aqasbi@usms.ac.ma"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" /></a>

</div>

---

<div align="center">

<!-- Footer - Terminal Shutdown Sequence -->
<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <text x="400" y="40" font-family="monospace" font-size="14" fill="#00ff41" text-anchor="middle">
    <tspan>[ SESSION TERMINATED ]</tspan>
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- System Stats -->
  <text x="400" y="65" font-family="monospace" font-size="11" fill="#888" text-anchor="middle">
    <tspan>1337 Coding School | ENSA Khouribga | 42 Network</tspan>
  </text>
  
  <text x="400" y="85" font-family="monospace" font-size="11" fill="#00ccff" text-anchor="middle">
    <tspan>STATUS: READY FOR DEPLOYMENT</tspan>
  </text>
  
  <!-- Final blinking cursor -->
  <text x="400" y="110" font-family="monospace" font-size="14" fill="#00ff41" text-anchor="middle">
    <tspan>root@1337:~$ _</tspan>
  </text>
  <rect x="528" y="97" width="10" height="18" fill="#00ff41">
    <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- Visitor Counter -->
<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=00ff41&style=flat-square&label=SYSTEM+ACCESSES" />

</div>
