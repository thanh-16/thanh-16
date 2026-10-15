<!-- ====================================================== -->
<!--                        HEADER                           -->
<!-- ====================================================== -->

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:0F2027,50:203A43,100:2C5364&text=Nguy%E1%BB%85n%20Quang%20Th%C3%A0nh&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Lead%20Backend%20Architect%20%E2%80%A2%20.NET%20Engineer%20%E2%80%A2%20Fullstack%20Developer&descAlignY=58&descSize=18" alt="Header Banner" />

  <!-- TYPING EFFECT -->
  <a href="https://github.com/thanh-16">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B+I'm+Nguy%E1%BB%85n+Quang+Th%C3%A0nh+(thanh-16);Software+Engineering+Student+%40+FPT+University+HCMC;Lead+Backend+Architect+%7C+.NET+8+%26+Clean+Architecture;Building+High-Concurrency+%26+AI-Powered+Systems;Always+Learning%2C+Shipping+%26+Solving+Real+Problems" alt="Typing SVG" />
  </a>

  <!-- SOCIAL BADGES -->
  <p align="center">
    <a href="mailto:nguyenquangthanhworking@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
    <a href="https://www.facebook.com/ThNah16" target="_blank">
      <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
    </a>
    <a href="https://github.com/thanh-16" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=thanh-16&label=PROFILE+VIEWS&style=for-the-badge&color=0e75b6" alt="Profile Views" />
  </p>
</div>

---

## 💫 About Me

```csharp
namespace FPTU.SoftwareEngineering;

public sealed class DeveloperProfile
{
    public string FullName     => "Nguyễn Quang Thành";
    public string Education    => "B.S. in Software Engineering — FPT University HCMC";
    public string CurrentRole  => "Team Leader & Lead Backend Architect (Capstone SEP490)";

    public string[] CoreArchitecture =>
    [
        ".NET 8 / .NET 10 (ASP.NET Core Web API)",
        "Clean Architecture & DDD (4-Layer Isolation)",
        "CQRS Pattern with MediatR & FluentValidation",
        "High-Concurrency Worker Queues (BoundedChannel) & Polly Resilience",
        "Realtime Bidirectional Communication (SignalR WebSockets)"
    ];

    public string[] TechInterests =>
    [
        "Distributed Backend Systems & Database Engineering (PostgreSQL / SQL Server)",
        "AI-Driven Pipelines (Google Gemini LLM, Whisper STT, Real-time Audio DSP)",
        "Modern Web & Mobile (React 19, Next.js 15, TypeScript, Flutter)",
        "Game Engineering (Godot 4, Unity, Custom Shaders)"
    ];

    public string Mission => "Write clean, resilient, zero-placeholder production code 🚀";
}
```

---

## 🚀 Tech Stack & Arsenal

<div align="center">

| **Category** | **Technologies & Tools** |
| :--- | :--- |
| **👨‍💻 Backend & Core** | <img src="https://skillicons.dev/icons?i=cs,dotnet,postgres,mysql,sqlite,redis,graphql" height="42" alt="Backend" /> |
| **🌐 Frontend & Web** | <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,html,css,vite" height="42" alt="Frontend" /> |
| **📱 Mobile & Game Dev** | <img src="https://skillicons.dev/icons?i=flutter,dart,godot,unity" height="42" alt="Mobile & Game" /> |
| **☁️ Cloud, DevOps & Tools** | <img src="https://skillicons.dev/icons?i=docker,aws,cloudflare,firebase,vercel,git,github,postman,visualstudio,vscode" height="42" alt="DevOps & Tools" /> |

</div>

---

## 🔥 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎙️ LLM Oral Examination System <code>Capstone SEP490</code></h3>
      <p><b>AI-Powered Viva Voce Practice & Assessment Platform for Software Engineering at FPT University.</b></p>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/PostgreSQL_16-316192?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
        <img src="https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
      </p>
      <ul>
        <li><b>Clean Architecture 4-Layer:</b> CQRS MediatR, FluentValidation, 30-table 3NF PostgreSQL Schema.</li>
        <li><b>Persist-First & Async Grading:</b> Sub-100ms submission sealing with <code>BoundedChannel</code> (1,000 slots), Polly Retry & Dead-Letter Queue (DLQ).</li>
        <li><b>Lab Kiosk Security:</b> Cryptographic SHA-256 audio sealing (<code>STT_MSSV.webm</code>), Waveform Evidence Panel & One-Way Grade Lock Interceptor.</li>
      </ul>
      <p>
        <a href="https://github.com/An-LLM-based-Oral-Examination/oral-exam-system" target="_blank">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏭 KCS-SmartFactory OS <code>AI Quality Control</code></h3>
      <p><b>Real-time Factory Quality Control (KCS), AI Defect Analysis & Automated Non-Conformance Report (NCR) System.</b></p>
      <p>
        <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/SignalR-008272?style=flat-square&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white" />
        <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <ul>
        <li><b>AI NCR Auto-Draft:</b> Automated defect classification & severity scoring with 8s Fail-Safe Fallback.</li>
        <li><b>Atomic Lot Locking:</b> ACID database transactions with Two-Phase orphan file cleanup & binary Magic Bytes validation.</li>
        <li><b>SignalR Andon Beacon:</b> Real-time WebSocket alarm system, Pareto 80/20 analytics & 50/50 automated xUnit tests passing.</li>
      </ul>
      <p>
        <a href="https://github.com/thanh-16/SmartFactory" target="_blank">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏮 HanziVibe (汉字韵) <code>EdTech & Real-time DSP</code></h3>
      <p><b>High-Tech Chinese Learning Web Platform with Real-Time Voice Pitch Contour DSP & Interactive SVG Calligraphy.</b></p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/TypeScript_5.7-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Web_Audio_DSP-FF6F00?style=flat-square&logo=html5&logoColor=white" />
        <img src="https://img.shields.io/badge/Vitest_360%2F360-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
      </p>
      <ul>
        <li><b>Real-time Pitch Contour (F0):</b> Pure TypeScript YIN DSP algorithm (<1ms latency) mapped to Chao's 5-level Mandarin tone system.</li>
        <li><b>Interactive Calligraphy Canvas:</b> Vector stroke-order quiz, backward-stroke detection & Apple Pencil palm rejection.</li>
        <li><b>Smart Retention:</b> SuperMemo SM-2 Spaced Repetition, 60s Time-Attack Battle & Gemini 1.5 Flash Sino-Vietnamese etymology.</li>
      </ul>
      <p>
        <a href="https://github.com/thanh-16/Web-h-c-ti-ng-trung-" target="_blank">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚔️ Game Tây Sơn & Sử Đại Việt <code>Game & Backend</code></h3>
      <p><b>Vietnamese Historical 2D Action RPG in Godot Engine & Cultural Ecosystem Backend API.</b></p>
      <p>
        <img src="https://img.shields.io/badge/Godot_Engine_4-478CBF?style=flat-square&logo=godot-engine&logoColor=white" />
        <img src="https://img.shields.io/badge/GDScript_%26_Shaders-355570?style=flat-square&logo=godot-engine&logoColor=white" />
        <img src="https://img.shields.io/badge/.NET_Web_API-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/PayOS_VietQR-00A86B?style=flat-square" />
      </p>
      <ul>
        <li><b>Game Tây Sơn (Godot 4):</b> Custom combat mechanics, state machines, hub world exploration & custom GDShaders.</li>
        <li><b>Sử Đại Việt Backend (.NET):</b> RESTful API architecture, PostgreSQL migrations, Dockerized deployment & PayOS payment webhook integration.</li>
      </ul>
      <p>
        <a href="https://github.com/thanh-16/GameTaySon" target="_blank">
          <img src="https://img.shields.io/badge/Game_Tây_Sơn-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white" alt="GameTaySon" />
        </a>
        <a href="https://github.com/thanh-16/BE_SuDaiViet" target="_blank">
          <img src="https://img.shields.io/badge/BE_Sử_Đại_Việt-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="BE_SuDaiViet" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

## 📊 GitHub Analytics & Activity

<div align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=thanh-16&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thanh-16&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<div align="center">
  <img height="175" src="https://streak-stats.demolab.com?user=thanh-16&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=thanh-16&theme=tokyonight" alt="Profile Summary" />
</div>

---

## 📈 Contribution Graph

<p align="center">
  <img width="98%" src="https://github-readme-activity-graph-eight.vercel.app/graph?username=thanh-16&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img width="98%" src="https://github-profile-trophy-ivory.vercel.app/?username=thanh-16&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&row=1&column=7" alt="GitHub Trophies" />
</p>

---

## 🎯 2026 Engineering Milestones

- ✅ **Lead Backend Architect** for Capstone Project **SEP490 (FA26SE166)** — *LLM-based Oral Examination System*
- ✅ Ship production-grade fullstack & AI systems (**KCS-SmartFactory OS**, **HanziVibe**, **Sử Đại Việt**)
- 🔄 Master High-Concurrency .NET Architecture, Distributed Messaging & Cloud-Native DevOps
- 🔄 Expand Open-Source Contributions & Technical System Design Portfolio

---

## 🌟 Developer Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Dev Quote" />
</p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="mailto:nguyenquangthanhworking@gmail.com">
    <img src="https://img.shields.io/badge/nguyenquangthanhworking@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.facebook.com/ThNah16" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
  </a>
  <a href="https://github.com/thanh-16" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0F2027,50:203A43,100:2C5364" alt="Footer Banner" />
</p>
