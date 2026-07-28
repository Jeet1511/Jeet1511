<style>
  /* Table row hover */
  table tr { transition: all 0.3s ease; }
  table tr:hover { background-color: #1E1F22; }
  table tr:hover td:first-child { border-left: 3px solid #D4915D; }

  /* Header charging line */
  table th { position: relative; padding-bottom: 8px; }
  table th::after {
    content: '';
    position: absolute;
    bottom: 0; left: 0;
    width: 0%; height: 2px;
    background: #D4915D;
    animation: chargeLine 2s ease-in-out infinite;
  }
  @keyframes chargeLine {
    0% { width: 0%; }
    50% { width: 100%; }
    100% { width: 0%; }
  }

  /* Project card hover */
  .project-card { transition: transform 0.3s ease; }
  .project-card:hover { transform: scale(1.02); }

  /* Section divider draw */
  .divider-line {
    stroke-dasharray: 1000;
    stroke-dashoffset: 1000;
    animation: draw 3s ease-in-out forwards;
  }
  @keyframes draw { to { stroke-dashoffset: 0; } }
</style>

<!-- ═══════════════════════════════════════════════ -->
<!--                     BANNER                      -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="./assets/banner.svg?v=2#gh-dark-mode-only" width="100%" style="display: block;">
  <img src="./assets/banner-light.svg?v=2#gh-light-mode-only" width="100%" style="display: block;">
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--               ORBIT / TECH STACK                -->
<!-- ═══════════════════════════════════════════════ -->

<br>
<div align="center">
  <img src="./assets/orbit.svg?v=1" alt="Tech Stack" width="890">
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--                    PROJECTS                     -->
<!-- ═══════════════════════════════════════════════ -->

<br>
<div align="center">

## Projects

<table align="center"><tr>
  <td align="center"><img src="./assets/project-vm-manager.svg?v=1" width="440" alt="VM Manager"></td>
  <td align="center"><img src="./assets/project-healthfy.svg?v=1" width="440" alt="Healthfy"></td>
</tr><tr>
  <td align="center"><img src="./assets/project-expressbasket.svg?v=1" width="440" alt="ExpressBasket"></td>
  <td align="center"><img src="./assets/project-elitezero.svg?v=1" width="440" alt="EliteZero"></td>
</tr></table>

</div>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (1)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--                    ABOUT ME                     -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/About_Me-36373B?style=for-the-badge&logo=starship&logoColor=D4915D&labelColor=36373B" alt="About Me"/>
  </h2>

  <br/>

  <table align="center" style="border-collapse: collapse; max-width: 600px;">
    <tbody>
      <tr>
        <td style="padding: 10px 20px; color: #D4915D; font-weight: bold; border-bottom: 1px solid #36373B;">Name</td>
        <td style="padding: 10px 20px; color: #E8E8E8; border-bottom: 1px solid #36373B;">Jeet Mondal</td>
      </tr>
      <tr>
        <td style="padding: 10px 20px; color: #D4915D; font-weight: bold; border-bottom: 1px solid #36373B;">Role</td>
        <td style="padding: 10px 20px; color: #E8E8E8; border-bottom: 1px solid #36373B;">Full Stack Dev</td>
      </tr>
      <tr>
        <td style="padding: 10px 20px; color: #D4915D; font-weight: bold; border-bottom: 1px solid #36373B;">Email</td>
        <td style="padding: 10px 20px; border-bottom: 1px solid #36373B;">
          <a href="mailto:jeetmondal1685@gmail.com" style="color: #E8E8E8; text-decoration: none;">jeetmondal1685@gmail.com</a>
        </td>
      </tr>
      <tr>
        <td style="padding: 10px 20px; color: #D4915D; font-weight: bold; border-bottom: 1px solid #36373B;">GitHub</td>
        <td style="padding: 10px 20px; border-bottom: 1px solid #36373B;">
          <a href="https://github.com/jeet1511" style="color: #E8E8E8; text-decoration: none;">@jeet1511</a>
        </td>
      </tr>
      <tr>
        <td style="padding: 10px 20px; color: #D4915D; font-weight: bold; border-bottom: 1px solid #36373B;">LinkedIn</td>
        <td style="padding: 10px 20px; border-bottom: 1px solid #36373B;">
          <a href="https://linkedin.com/in/jeet1511" style="color: #E8E8E8; text-decoration: none;">@jeet1511</a>
        </td>
      </tr>
    </tbody>
  </table>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (2)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--                    SKILLS                       -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/Skills-36373B?style=for-the-badge&logo=react&logoColor=D4915D&labelColor=36373B" alt="Skills"/>
  </h2>

  <br/>

  <table align="center" style="border-collapse: collapse; max-width: 800px;">
    <thead>
      <tr>
        <th style="padding: 12px 20px; color: #D4915D; border-bottom: 2px solid #D4915D; text-align: center;">Frontend</th>
        <th style="padding: 12px 20px; color: #D4915D; border-bottom: 2px solid #D4915D; text-align: center;">Backend</th>
        <th style="padding: 12px 20px; color: #D4915D; border-bottom: 2px solid #D4915D; text-align: center;">Languages</th>
        <th style="padding: 12px 20px; color: #D4915D; border-bottom: 2px solid #D4915D; text-align: center;">Tools</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 12px 20px; color: #E8E8E8; text-align: center; vertical-align: top; border-bottom: 1px solid #36373B;">
          React<br/>JavaScript<br/>HTML / CSS
        </td>
        <td style="padding: 12px 20px; color: #E8E8E8; text-align: center; vertical-align: top; border-bottom: 1px solid #36373B;">
          Node.js<br/>Python<br/>MERN Stack
        </td>
        <td style="padding: 12px 20px; color: #E8E8E8; text-align: center; vertical-align: top; border-bottom: 1px solid #36373B;">
          JavaScript<br/>Python<br/>Java<br/>C<br/>Shell
        </td>
        <td style="padding: 12px 20px; color: #E8E8E8; text-align: center; vertical-align: top; border-bottom: 1px solid #36373B;">
          Git<br/>Docker<br/>VS Code<br/>MongoDB
        </td>
      </tr>
    </tbody>
  </table>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (3)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--               STATS ROW (3 cards)               -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/GitHub_Stats-36373B?style=for-the-badge&logo=github&logoColor=D4915D&labelColor=36373B" alt="Stats"/>
  </h2>

  <br/>

  <table align="center"><tr>
    <td align="center"><img src="./assets/stats.svg?v=1" alt="Stats"></td>
    <td align="center"><img src="./assets/langs.svg?v=1" alt="Languages"></td>
    <td align="center"><img src="./assets/trophies.svg?v=1" alt="Trophies"></td>
  </tr></table>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (4)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--                   CONTACT                       -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/Contact_Me-36373B?style=for-the-badge&logo=mail.ru&logoColor=D4915D&labelColor=36373B" alt="Contact"/>
  </h2>

  <br/>

  <a href="https://github.com/jeet1511">
    <img src="https://img.shields.io/badge/GitHub-jeet1511-36373B?style=for-the-badge&logo=github&logoColor=D4915D" alt="GitHub"/>
  </a>

  <a href="https://linkedin.com/in/jeet1511">
    <img src="https://img.shields.io/badge/LinkedIn-jeet1511-36373B?style=for-the-badge&logo=linkedin&logoColor=D4915D" alt="LinkedIn"/>
  </a>

  <a href="mailto:jeetmondal1685@gmail.com">
    <img src="https://img.shields.io/badge/Email-jeetmondal1685@gmail.com-36373B?style=for-the-badge&logo=gmail&logoColor=D4915D" alt="Email"/>
  </a>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--              PROFILE VIEWS COUNTER              -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=jeet1511&color=D4915D&style=flat-square" alt="Profile views">
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--                    FOOTER                       -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <p style="color: #888; font-size: 14px;">
    <em>Built with passion by Jeet Mondal — Code. Coffee. Repeat.</em>
  </p>
</div>
