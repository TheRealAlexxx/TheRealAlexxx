<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f1a,50:1a1a2e,100:0f0f1a&height=280&section=header&text=ALEXXX&fontSize=90&fontColor=00fff2&animation=fadeIn&fontAlignY=38&desc=UK%20based%20developer%20%2F%20AI%2C%20agents%2C%20dev%20tools&descAlignY=58&descSize=18&descColor=8be9fd" width="100%"/>

<br/>

<a href="https://github.com/TheRealAlexxx">
  <img src="https://readme-typing-svg.demolab.com/?lines=hi%2C+I'm+alexxx;UK+%2F+developer;into+AI+agents+and+local+LLMs;deep+in+Hack+Club;just+shipped+TraceLens+%E2%9C%94&font=Fira+Code&center=true&width=550&height=60&duration=2500&pause=900&color=00FFF2&vCenter=true&size=22&background=00000000" alt="typing intro"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/status-actively_shipping-00fff2?style=for-the-badge&labelColor=0d0d0d" />
<img src="https://img.shields.io/badge/based_in-United_Kingdom-8be9fd?style=for-the-badge&labelColor=0d0d0d" />
<img src="https://img.shields.io/badge/community-Hack_Club-ff6b6b?style=for-the-badge&labelColor=0d0d0d" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `01` About

I'm alexxx, a developer from the UK. I care about AI agents, local LLMs, developer tools, and building things that make other people's building easier. Desktop apps, web apps, whatever the problem actually needs.

My GitHub used to be thin — most of what I'd shipped lived inside Hack Club rather than my own repos. That's closing. First line item below is live on PyPI right now.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `02` Hack Club

<div align="center">
<img src="https://assets.hackclub.com/flag-orpheus-top.svg" width="180"/>
</div>

Hack Club is where most of my actual work happens. It's a global network of teenage developers shipping real software, not tutorials, and I help run part of it.

<table width="100%">
<tr>
<td width="50%" valign="top">

**What I actually do there**

I run several YSWS (You Ship, We Ship) programs from the ground up. Scope the projects hackers build against. Unblock people directly when they're stuck. Work on infrastructure the wider community depends on.

</td>
<td width="50%" valign="top">

**Why I bother**

Teenagers can ship production grade software if you give them real ownership instead of a syllabus. I'd rather build the scaffolding that makes that possible than write another portfolio project.

</td>
</tr>
</table>

<div align="center">

[![Hack Club](https://img.shields.io/badge/Hack_Club-YSWS_Organiser-ec3750?style=for-the-badge&logo=hackclub&logoColor=white&labelColor=0d0d0d)](https://hackclub.com)
[![Hack Club](https://img.shields.io/badge/hackclub.com-8be9fd?style=for-the-badge&labelColor=0d0d0d)](https://hackclub.com)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `03` Right Now

Heads down on AI agents and where local LLMs genuinely beat API calls. Backing that belief with software, not just opinions: TraceLens runs a local model in a pip install and explains Python errors fully offline. Still running YSWS programs on the side.

<div align="center">
<img src="https://img.shields.io/badge/AI_Agents-00fff2?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Local_LLMs-00fff2?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Dev_Tools-00fff2?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Open_Source-00fff2?style=flat-square&labelColor=0d0d0d"/>
</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `04` Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,python,postgres,prisma,tailwind,docker,vercel,git&theme=dark" />

</div>

<table width="100%">
<tr>
<th align="left">Layer</th>
<th align="left">Tools</th>
</tr>
<tr>
<td>Languages</td>
<td>TypeScript, JavaScript, Python</td>
</tr>
<tr>
<td>Frontend</td>
<td>React, Next.js, Tailwind CSS</td>
</tr>
<tr>
<td>Backend</td>
<td>Node.js, tRPC, Prisma</td>
</tr>
<tr>
<td>Data</td>
<td>PostgreSQL</td>
</tr>
<tr>
<td>AI</td>
<td>LLM APIs, local inference (ONNX), agent pipelines</td>
</tr>
<tr>
<td>Tooling</td>
<td>Git, Docker, Vercel, GitHub Actions</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `05` Projects

### TraceLens — AI error assistant for Python

<div align="center">

[![PyPI](https://img.shields.io/badge/PyPI-tracelens--ai-00fff2?style=for-the-badge&labelColor=0d0d0d)](https://pypi.org/project/tracelens-ai/)
[![Source](https://img.shields.io/badge/source-github-8be9fd?style=for-the-badge&labelColor=0d0d0d)](https://github.com/TheRealAlexxx/tracelens)
[![Version](https://img.shields.io/badge/version-0.3.0-ff6b6b?style=for-the-badge&labelColor=0d0d0d)](https://pypi.org/project/tracelens-ai/)

</div>

One import changes how you hit Python errors. `import tracelens` hooks uncaught exceptions and explains them: the failing line, the cause, a suggested fix, a confidence score — with the original traceback always printed first. It never hides the error, it just stops leaving you alone with it.

<table width="100%">
<tr>
<td width="50%" valign="top">

**How it works**

Ships a Qwen2.5-0.5B local LLM as a ~780 MB ONNX package — fully offline, CPU only, no API keys, no data leaving the machine. The model downloads once on first use and caches locally.

</td>
<td width="50%" valign="top">

**The fallback**

A deterministic rule engine guarantees offline advice even when the model isn't cached or isn't reachable. No network, no model, still useful.

</td>
</tr>
</table>

Published to PyPI via a fully automated GitHub Actions pipeline using OpenID Connect trusted publishing — build and ship happens on a `git tag`, no tokens. CLI included: `tracelens demo | info | model | purge`.

> First line item. More where this came from.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

## `06` Philosophy

Ship the system, not the demo. Community is infrastructure, treat it like one. Build the thing that outlasts the reason you started it. If you're going to run a local model on the user's CPU anyway, make the whole product work without a network at all.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br/>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-TheRealAlexxx-0d0d0d?style=for-the-badge&logo=github&logoColor=00fff2)](https://github.com/TheRealAlexxx)
[![Hack Club](https://img.shields.io/badge/Hack_Club-0d0d0d?style=for-the-badge&logo=hackclub&logoColor=ec3750)](https://hackclub.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f1a,50:1a1a2e,100:0f0f1a&height=140&section=footer&animation=fadeIn" width="100%"/>

</div>