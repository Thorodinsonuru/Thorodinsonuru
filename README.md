<!-- README.md -->

<!-- Header banner (capsule-render) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7f2fff&height=220&section=header&text=Thor%20OdinSon&fontSize=55&fontColor=ffffff&animation=fadeIn" alt="Thor OdinSon Banner"/>
</p>

<h1 align="center">⚡️ THOR ODINSON — GOD OF THUNDER</h1>

<p align="center">
  <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank">
    <img alt="GitHub - YOUR_GITHUB_USERNAME" src="https://img.shields.io/badge/GitHub-@YOUR_GITHUB_USERNAME-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

<!-- Animated typewriter tags (SVG + animation) -->
<p align="center">
  <!-- Inline SVG used to create a typing / cursor animation. This works in many Markdown renderers that allow inline SVG. -->
  <svg xmlns='http://www.w3.org/2000/svg' width='760' height='120' viewBox='0 0 760 120' role='img' aria-label='typing-tags' preserveAspectRatio='xMidYMid meet'>
    <style>
      .t{ font: 18px "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; fill:#e6eefc; }
      .tag{ font-weight:700; fill:#ffffff; font-size:20px; }
    </style>

    <!-- background -->
    <rect width='100%' height='100%' fill='transparent'/>

    <!-- Line 1: Realm -->
    <g transform='translate(20,28)'>
      <text class='t' x='0' y='0'>Realm:&nbsp;</text>
      <!-- reveal mask for typing effect -->
      <mask id='m1'>
        <rect x='0' y='-18' width='0' height='30' fill='white'>
          <animate attributeName='width' from='0' to='220' dur='1.6s' begin='0.2s' fill='freeze' />
        </rect>
      </mask>
      <g mask='url(#m1)'>
        <text class='tag' x='90' y='0'>Asgard</text>
      </g>
    </g>

    <!-- Line 2: Weapons -->
    <g transform='translate(20,62)'>
      <text class='t' x='0' y='0'>Weapons:&nbsp;</text>
      <mask id='m2'>
        <rect x='0' y='-18' width='0' height='30' fill='white'>
          <animate attributeName='width' from='0' to='340' dur='2.4s' begin='1.9s' fill='freeze' />
        </rect>
      </mask>
      <g mask='url(#m2)'>
        <text class='tag' x='110' y='0'>Mjölnir ⚒️  &  Stormbreaker ⚔️</text>
      </g>
    </g>

    <!-- Line 3: Title -->
    <g transform='translate(20,96)'>
      <text class='t' x='0' y='0'>Title:&nbsp;</text>
      <mask id='m3'>
        <rect x='0' y='-18' width='0' height='30' fill='white'>
          <animate attributeName='width' from='0' to='240' dur='1.8s' begin='4.4s' fill='freeze' />
        </rect>
      </mask>
      <g mask='url(#m3)'>
        <text class='tag' x='70' y='0'>God_of_Thunder</text>
      </g>
    </g>

    <!-- Blinking cursor that moves down as lines complete -->
    <rect id='cursor' x='0' y='6' width='10' height='20' fill='#ffffff' opacity='1'>
      <!-- initial blink while first line types -->
      <animate attributeName='opacity' values='1;0;1' dur='0.9s' repeatCount='indefinite' begin='0s'/>
      <!-- move to end of line1 when m1 finishes -->
      <animate attributeName='x' from='110' to='110' begin='0.2s' dur='0.001s' fill='freeze'/>
      <!-- move to end of line2 when m2 finishes -->
      <animate attributeName='x' from='110' to='350' begin='2.05s' dur='0.001s' fill='freeze'/>
      <!-- move to line3 x-position -->
      <animate attributeName='x' from='350' to='310' begin='4.55s' dur='0.001s' fill='freeze'/>
      <!-- move down to next line after second begins -->
      <animate attributeName='y' from='6' to='40' begin='2.05s' dur='0.001s' fill='freeze'/>
      <animate attributeName='y' from='40' to='74' begin='4.55s' dur='0.001s' fill='freeze'/>
      <!-- keep blinking after final position -->
    </rect>

    <!-- final subtle glow line behind text -->
    <defs>
      <filter id='glow' x='-50%' y='-50%' width='200%' height='200%'>
        <feGaussianBlur stdDeviation='2' result='coloredBlur'/>
        <feMerge>
          <feMergeNode in='coloredBlur'/>
          <feMergeNode in='SourceGraphic'/>
        </feMerge>
      </filter>
    </defs>

  </svg>
</p>

<!-- Quick info table (same tags as animated) -->
| Attribute | Description |
|---|---|
| **Realm** | Asgard |
| **Weapons** | Mjölnir ⚒️ & Stormbreaker ⚔️ |
| **Title** | God_of_Thunder |
| **Alignment** | Protector_of_the_Nine_Realms |

<p align="center">
  <a href="https://github.com/YOUR_GITHUB_USERNAME?tab=repositories">View my projects</a>
</p>

<!-- Footer badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Realm-Asgard-blue?style=for-the-badge&logo=nordvpn" alt="Realm"/>
  <img src="https://img.shields.io/badge/Weapons-Mj%C3%B6lnir_&_Stormbreaker-brightgreen?style=for-the-badge" alt="Weapons"/>
  <img src="https://img.shields.io/badge/Title-God_of_Thunder-yellow?style=for-the-badge" alt="Title"/>
</p>
