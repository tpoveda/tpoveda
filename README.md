<!-- ![alt text](https://github.com/tpoveda/tpoveda/blob/master/splash.png)
 -->
<p align="center">
  <img
    src="images/header-banner.svg"
    alt="Header banner: Tomás Poveda — Software Developer & Pipeline TD"
  />
</p>

<p align="center">
  <a href="https://www.tomipoveda.com"><img src="https://img.shields.io/badge/Portfolio-0EA5E9?logo=google-chrome&logoColor=white" alt="Website"/></a>
  <a href="https://github.com/tpoveda"><img src="https://img.shields.io/github/followers/tpoveda?label=Follow&style=social" alt="GitHub Follow"/></a>
  <a href="https://github.com/tpoveda"><img src="https://komarev.com/ghpvc/?username=tpoveda&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/></a>
  <a href="https://www.linkedin.com/in/tpoveda/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/tomipoveda"><img src="https://img.shields.io/badge/X%20(Twitter)-000000?logo=x&logoColor=white" alt="X (Twitter)"/></a>
  <a href="https://vimeo.com/tpoveda"><img src="https://img.shields.io/badge/Vimeo-1ab7ea?logo=vimeo&logoColor=white" alt="Vimeo"/></a>
  <a href="https://open.spotify.com/"><img src="https://img.shields.io/badge/Spotify-1DB954?logo=spotify&logoColor=white" alt="Spotify"/></a>
</p>

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

from dataclasses import dataclass


@dataclass(frozen=True)
class SoftwareDeveloperPipelineTD:
    name: str = "Tomás Poveda"
    roles: tuple[str, ...] = ("Software Developer", "Pipeline TD")
    languages: tuple[str, ...] = ("es_ES", "en_US")
    programming_languages: tuple[str, ...] = (
        "Python", "C++", "C#", "JavaScript/TypeScript",
    )

    dcc_focus: tuple[str, ...] = (
        "Maya", "Unreal Engine", "Houdini", "USD", "Qt/PySide",
    )
    services_stack: tuple[str, ...] = (
        "FastAPI", "Node.js", "TypeScript", "React",
        "Postgres/Redis", "Docker", "CI/CD",
    )
    interests: tuple[str, ...] = (
        "DCC-agnostic Python tooling",
        "Asset-management pipelines",
        "Unreal plugin development",
        "Cinematic & animation pipelines",
        "Service-oriented backends • observability • testing",
    )

    def say_hi(self) -> str:
        return (
            "Thanks for dropping by — I build artist-friendly tools, robust "
            "pipelines, and reliable services so teams can move faster."
        )


me = SoftwareDeveloperPipelineTD()
print(me.say_hi())
```

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

<h3>
  <img src="images/wrench.svg" width="20" height="20" style="vertical-align:text-bottom;margin-right:6px;" alt="Tech icon"/>
  Tech I use and enjoy
</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,postman,pycharm,cpp,cs,cmake,clion,rider,visualstudio,js,ts,html,css,react,nextjs,vite,electron,tailwind,sass,materialui,nodejs,npm,vscode,webstorm,graphql,postgres,redis,mongodb,sqlite,mysql,prisma,powershell,md,regex,docker,git,github,githubactions,jenkins,gitlab,qt,unreal,blender,windows,stackoverflow,sentry,threejs&perline=12" alt="Tech stack" />
</p>

<p align="center">
  <img alt="Maya" src="https://img.shields.io/badge/Maya-088389?logo=Autodesk&logoColor=white" />
  <img alt="Houdini" src="https://img.shields.io/badge/Houdini-FF4713?logo=Houdini&logoColor=white" />
  <img alt="USD" src="https://img.shields.io/badge/USD%20(Pixar)-111?logo=usd&logoColor=white" />
  <img alt="Perforce Helix" src="https://img.shields.io/badge/Perforce%20Helix-00AEEF?logo=perforce&logoColor=white" />
</p>

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

<h3>
  <img src="images/trending-up.svg" width="20" height="20" style="vertical-align:text-bottom;margin-right:6px;" alt="Interests icon"/>
  What I'm into lately
</h3>

- DCC‑agnostic Python tooling and scalable asset‑management pipelines.
- Unreal plugin development; cinematic and animation pipelines.
- Service‑oriented backends with FastAPI, robust CI/CD, observability, and testing.

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

<h3>
  <img src="images/briefcase.svg" width="20" height="20" style="vertical-align:text-bottom;margin-right:6px;" alt="Career icon"/>
  Career highlights
</h3>

<div align="center">
  <table border="0" style="border-collapse:collapse;border-spacing:0;border:none;outline:none;border-radius:12px;overflow:hidden;">
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>That's No Moon</b> — Senior Animation TD<br/>
        <sub>Feb 2023 – Present · Remote (Los Angeles)</sub>
        <ul>
          <li>Animation/rigging tooling and pipeline automation across DCCs and Unreal Engine (Control Rig).</li>
          <li>Driving scalable, artist‑friendly workflows and standards for next‑gen production.</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/tnm.jpeg" alt="That's No Moon — Project" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
      </td>
    </tr>
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>Counterplay Games</b> — Senior Technical Animator<br/>
        <sub>Apr 2021 – Dec 2022 · Freelance</sub>
        <ul>
          <li>Built a modular, DCC‑agnostic, multi‑project pipeline from the ground up.</li>
          <li>Integrated a new modular rigging builder; streamlined rigging/animation workflows.</li>
          <li>Unreal: Control Rig, custom importers/exporters, physics assets; custom rig components + skinning.</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/godfall.webp" alt="Godfall" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
        <img src="images/armatus.jpg" alt="Armatus" style="margin-top:6px;max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
      </td>
    </tr>
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>Ubisoft</b> — Technical Artist<br/>
        <sub>Oct 2017 – Sep 2019 · Barcelona (On‑site)</sub>
        <ul>
          <li>Beyond Good & Evil 2: character pipeline tooling; cross‑DCC data I/O (MaxScript/MEL/Python).</li>
          <li>Assassin’s Creed III Remastered: outfit rigging, in‑engine cloth; MaxScript/C# tools.</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/bge2.webp" alt="Beyond Good &amp; Evil 2" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
        <img src="images/ac3remastered.avif" alt="Assassin’s Creed III Remastered" style="margin-top:6px;max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
      </td>
    </tr>
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>Promethean AI</b> — Senior Technical Artist<br/>
        <sub>May 2020 – Apr 2021 · Freelance</sub>
        <ul>
          <li>Contributed to first public release; Maya and 3ds Max plugin integrations.</li>
          <li>Improved CLI tooling; custom installer & deployment (PyInstaller + Cython).</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/prometheanai.jpg" alt="Promethean AI" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
      </td>
    </tr>
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>Artella</b> — Software Developer<br/>
        <sub>May 2020 – Jul 2021 · Freelance</sub>
        <ul>
          <li>Re‑implemented Python Artella Client and a DCC‑agnostic plugin framework.</li>
          <li>Shipped Artella Maya plugin and custom plugins installer.</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/artella.jpg" alt="Artella Client &amp; Plugins" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
        <br/>
        <a href="https://github.com/artella" title="Artella on GitHub" aria-label="Artella on GitHub">
          <img src="https://img.shields.io/badge/GitHub-artella-181717?logo=github&logoColor=white" alt="Artella on GitHub" style="margin-top:8px;"/>
        </a>
      </td>
    </tr>
    <tr>
      <td width="60%" valign="top" style="border:none;">
        <b>mcsGear</b> — ueGear Developer<br/>
        <sub>Dec 2022 – Feb 2023 · Freelance</sub>
        <ul>
          <li>ueGear plugin development for Maya and Unreal Engine.</li>
        </ul>
      </td>
      <td width="40%" valign="top" align="center" style="border:none;">
        <img src="images/uegear.jpg" alt="ueGear Plugin" style="max-width:100%;height:auto;border-radius:10px;" loading="lazy"/>
        <br/>
        <a href="https://github.com/mgear-dev/ueGear" title="ueGear repository" aria-label="ueGear repository">
          <img src="https://img.shields.io/badge/GitHub-ueGear-181717?logo=github&logoColor=white" alt="ueGear repository" style="margin-top:8px;"/>
        </a>
      </td>
  </tr>
  </table>
</div>

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

<h3>
  <img src="images/chart-line.svg" width="20" height="20" style="vertical-align:text-bottom;margin-right:6px;" alt="Metrics icon"/>
  Featured metrics
</h3>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tpoveda&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tpoveda&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tpoveda&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=tpoveda&theme=onedark&no-frame=true&margin-w=10&margin-h=10" alt="Trophies" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tpoveda&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Activity Graph"/>
</p>

<p align="center">
  <img src="images/divider.svg" alt="Section divider" width="100%" height="2"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tpoveda/" aria-label="LinkedIn" title="LinkedIn" style="margin:0 10px;">
    <img src="images/linkedin.svg" width="26" height="26" style="vertical-align:middle;" alt="LinkedIn"/>
  </a>
  <a href="https://www.tomipoveda.com" aria-label="Website/Portfolio" title="Website/Portfolio" style="margin:0 10px;">
    <img src="images/web.svg" width="26" height="26" style="vertical-align:middle;" alt="Website"/>
  </a>
  <a href="https://twitter.com/tomipoveda" aria-label="X (Twitter)" title="X (Twitter)" style="margin:0 10px;">
    <img src="images/twitter.svg" width="26" height="26" style="vertical-align:middle;" alt="Twitter"/>
  </a>
  <a href="https://vimeo.com/tpoveda" aria-label="Vimeo" title="Vimeo" style="margin:0 10px;">
    <img src="images/vimeo.svg" width="26" height="26" style="vertical-align:middle;" alt="Vimeo"/>
  </a>
</p>

<p align="center" style="margin-top:24px;">
  <img src="images/footer-banner.svg" alt="Made with love ❤️ by Tomi" />
  
</p>
