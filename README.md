<style>
  /* ── Table Row Hover ── */
  table tbody tr:hover {
    background: #1E1F22 !important;
    border-left: 3px solid #D4915D;
    transition: all 0.3s ease;
  }

  /* ── Table Header Charging Line ── */
  .charging-line {
    height: 3px;
    background: linear-gradient(90deg, #D4915D, #F0A868);
    animation: charge 2.5s ease-in-out infinite;
    border-radius: 2px;
  }
  @keyframes charge {
    0%   { width: 0%; }
    50%  { width: 100%; }
    100% { width: 0%; }
  }

  /* ── Projects Table Gradient Pan on Hover ── */
  .projects-table tr:hover td {
    background: linear-gradient(135deg, #1E1F22 0%, #2A2C30 50%, #1E1F22 100%);
    background-size: 200% 200%;
    animation: pan 1.5s ease infinite;
  }
  @keyframes pan {
    0%   { background-position: 0% 50%; }
    50%  { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  /* ── Section Divider Draw Animation ── */
  .divider-line {
    stroke-dasharray: 1000;
    stroke-dashoffset: 1000;
    animation: draw 3s ease-in-out forwards;
  }
  @keyframes draw {
    to { stroke-dashoffset: 0; }
  }
</style>

<!-- ═══════════════════════════════════════════════ -->
<!--              BANNER + BADGE OVERLAP             -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <table align="center" style="border: none; border-collapse: collapse; max-width: 900px;">
    <tr>
      <td align="center" style="border: none; padding: 0; line-height: 0;">
        <img src="./assets/banner.svg?v=1#gh-dark-mode-only" width="100%" style="margin-bottom: -150px; display: block;">
        <img src="./assets/banner-light.svg?v=1#gh-light-mode-only" width="100%" style="margin-bottom: -150px; display: block;">
      </td>
    </tr>
    <tr>
      <td align="center" style="border: none; padding: 0; line-height: 0;">
        <img src="./assets/workshop-badge.svg?v=1" width="350px" style="display: block; position: relative; z-index: 2;">
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--                   ABOUT ME                      -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/About_Me-36373B?style=for-the-badge&logo=starship&logoColor=D4915D&labelColor=36373B" alt="About Me"/>
  </h2>

  <div class="charging-line" style="width: 60%; margin: 0 auto;"></div>

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

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (1)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--                    SKILLS                       -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/Skills-36373B?style=for-the-badge&logo=react&logoColor=D4915D&labelColor=36373B" alt="Skills"/>
  </h2>

  <div class="charging-line" style="width: 60%; margin: 0 auto;"></div>

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

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (2)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--               STATS ROW (3 cards)               -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/GitHub_Stats-36373B?style=for-the-badge&logo=github&logoColor=D4915D&labelColor=36373B" alt="Stats"/>
  </h2>

  <div class="charging-line" style="width: 60%; margin: 0 auto;"></div>

  <br/>

  <table align="center"><tr>
    <td align="center"><img src="./assets/stats.svg?v=1" alt="Stats"></td>
    <td align="center"><img src="./assets/langs.svg?v=1" alt="Languages"></td>
    <td align="center"><img src="./assets/trophies.svg?v=1" alt="Trophies"></td>
  </tr></table>
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--              SECTION DIVIDER (3)                -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='600' height='20' viewBox='0 0 600 20'><line class='divider-line' x1='0' y1='10' x2='600' y2='10' stroke='%23D4915D' stroke-width='2' fill='none' stroke-dasharray='1000' stroke-dashoffset='1000'><animate attributeName='stroke-dashoffset' from='1000' to='0' dur='3s' fill='freeze'/></line></svg>" alt="divider" width="600"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--                   CONTACT                       -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <h2>
    <img src="https://img.shields.io/badge/Contact_Me-36373B?style=for-the-badge&logo=mail.ru&logoColor=D4915D&labelColor=36373B" alt="Contact"/>
  </h2>

  <div class="charging-line" style="width: 60%; margin: 0 auto;"></div>

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

<br/>

<!-- ═══════════════════════════════════════════════ -->
<!--              PROFILE VIEWS COUNTER              -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=jeet1511&color=D4915D&style=flat-square" alt="Profile views"/>
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
