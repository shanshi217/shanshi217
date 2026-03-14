## Hi there 👋

<!--
**shanshi217/shanshi217** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
**Hi there, Welcome!👋**
-->


Hello, I'm **Shanshi**.

🔭 I’m currently studying at Chongqing University for master's degree.

🌱 I’m currently learning **Machine Learning and AI**

🤔 I’m intrested in **Autonomotivate vehicle** 

📫 How to reach me: **202307021159T@cqu.stu.edu.cn**

😄 Pronouns:He/His


<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="600" height="600" viewBox="0 0 600 600" role="img" aria-label="shanshi217 - Autonomous driving and ML avatar">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#0ea5e9"/>
      <stop offset="1" stop-color="#7c3aed"/>
    </linearGradient>
    <radialGradient id="r1" cx="40%" cy="30%" r="80%">
      <stop offset="0" stop-color="rgba(255,255,255,0.12)"/>
      <stop offset="1" stop-color="rgba(0,0,0,0)"/>
    </radialGradient>
    <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feBlend in="SourceGraphic" in2="b"/>
    </filter>
  </defs>

  <!-- 背景 -->
  <rect width="100%" height="100%" rx="40" fill="url(#g1)"/>
  <rect width="100%" height="100%" rx="40" fill="url(#r1)" />

  <!-- 软光点 -->
  <g filter="url(#soft)" opacity="0.12">
    <circle cx="460" cy="120" r="80" fill="#fff" />
  </g>

  <!-- 神经网络节点（左上） -->
  <g transform="translate(60,60)" stroke="#ffffffaa" stroke-width="2" fill="#ffffffcc">
    <line x1="0" y1="50" x2="80" y2="0" />
    <line x1="30" y1="90" x2="120" y2="40" />
    <circle cx="0" cy="50" r="6" />
    <circle cx="30" cy="90" r="6" />
    <circle cx="80" cy="0" r="6" />
    <circle cx="120" cy="40" r="6" />
  </g>

  <!-- 小车轮廓（中心） -->
  <g transform="translate(120,230) scale(1.4)">
    <path d="M60 80 L480 80 C500 80 520 95 520 120 L520 220 C520 250 490 270 460 270 L180 270 C150 270 120 250 120 220 L120 160 C120 140 130 100 60 80 Z"
          fill="#02112466" stroke="#ffffff55" stroke-width="3" />
    <!-- 车顶部 -->
    <path d="M160 80 Q230 40 360 70 Q420 85 480 80" fill="#ffffff22" stroke="#ffffff55" stroke-width="2"/>
    <!-- 车轮 -->
    <circle cx="200" cy="280" r="30" fill="#00000066"/>
    <circle cx="440" cy="280" r="30" fill="#00000066"/>
    <circle cx="200" cy="280" r="12" fill="#7c3aed"/>
    <circle cx="440" cy="280" r="12" fill="#7c3aed"/>
  </g>

  <!-- LiDAR 扇形（右侧，表现扫描） -->
  <g transform="translate(460,240)">
    <path d="M0 0 L120 -60 A220 220 0 0 1 120 60 Z" fill="#00fff699" opacity="0.18" />
    <path d="M0 0 L80 -40 A150 150 0 0 1 80 40 Z" fill="#00fff933" opacity="0.18" />
    <circle cx="0" cy="0" r="4" fill="#fff" />
  </g>

  <!-- 用户标识文字 -->
  <g transform="translate(40,520)">
    <rect x="0" y="-16" width="520" height="48" rx="8" fill="#00000033"/>
    <text x="20" y="20" font-family="Verdana,Segoe UI,Arial" font-size="28" fill="#fff">shanshi217</text>
    <text x="220" y="20" font-family="Verdana,Segoe UI,Arial" font-size="14" fill="#e6e6e6">Chongqing Univ · Autonomous Driving · ML/AI</text>
  </g>
</svg>

