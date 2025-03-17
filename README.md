<svg width="400" height="200" xmlns="http://www.w3.org/2000/svg">
  <style>
    .banner {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      overflow: hidden;
    }
    
    .banner::before {
      content: '';
      position: absolute;
      inset: 0;
      background-image: url('img/valentin-petrov-m-mal-01.jpg');
      background-size: cover;
      background-position: center;
      animation: bgZoomIn 4s ease-in-out 1 forwards;
      z-index: -1;
      pointer-events: none;
    }

    .banner::after {
      content: '';
      position: absolute;
      inset: 0;
      background-image: url('img/after.png');
      background-size: cover;
      background-position: top;
      transform: scale(2);
      animation: bgZoomOut 4s ease-in-out 1 forwards;
      z-index: -1;
      pointer-events: none;
    }

    @keyframes bgZoomIn {
      from { transform: scale(1.2); }
      to { transform: scale(1); }
    }

    @keyframes bgZoomOut {
      from { transform: scale(1); }
      to { transform: scale(2); }
    }

    .text path {
      fill: transparent;
      stroke: #fff;
      stroke-width: 0.1;
      stroke-dasharray: 50;
      stroke-dashoffset: 50;
      animation: textAnimation 4s ease-in-out 1 forwards;
    }

    @keyframes textAnimation {
      0% { stroke-dashoffset: 50; }
      80% { fill: transparent; }
      100% { fill: #fff; stroke-dashoffset: 0; }
    }
  </style>

  <g class="text">
    <path d="M10 80 C 40 10, 65 10, 95 80 S 150 150, 180 80" />
    <text x="50" y="150" font-size="32" fill="#fff">SVG Animation</text>
  </g>
</svg>
## Hi there, I am Raghav. 👋
![Profile view counter on GitHub](https://komarev.com/ghpvc/?username=Phoenix-tear)

<!--
**Phoenix-tear/Phoenix-Tear** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
