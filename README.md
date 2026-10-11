<!-- Animated wave header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Zafira%20Nur%20Kamila&fontSize=42&fontColor=fff&animation=fadeIn&fontAlignY=38" alt="header" />

<!-- Header: 2-column layout, photo vertically centered -->
<table>
  <tr>
    <td width="65%" valign="top">
      <h1>Hi, I'm Zafira 👋</h1>
      <a href="https://github.com/zafiranurkamila">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00F0FF&width=520&lines=Final-year+student+from+Indonesia;Building+web%2C+mobile+%26+AI+projects;Currently%3A+ECG+%2B+CNN+research;Always+learning+something+new" alt="Typing SVG" />
      </a>
      <p>
        <img src="https://komarev.com/ghpvc/?username=zafiranurkamila&label=Profile%20views&color=00f0ff&style=flat" alt="Profile views" />
        <a href="https://github.com/zafiranurkamila?tab=followers">
          <img src="https://img.shields.io/github/followers/zafiranurkamila?label=Followers&style=flat&color=00f0ff" alt="Followers" />
        </a>
      </p>
      <p>Mahasiswa tingkat akhir di Indonesia 🇮🇩 yang suka membangun sesuatu dari ujung ke ujung — mulai dari API, tampilan web & mobile, pengujian, sampai model deep learning.</p>
      <p>Saat ini sedang menyelesaikan tugas akhir tentang <b>lokalisasi PVC dari sinyal EKG 12-lead menggunakan CNN</b>, sambil iseng bikin <b>portfolio 3D berbentuk desa voxel</b>.</p>
      <p>📫 <b>zafiranurkamila@gmail.com</b></p>
    </td>
    <td width="35%" valign="middle" align="center">
      <img width="260" style="border-radius: 12px;" src="https://raw.githubusercontent.com/zafiranurkamila/zafiranurkamilaa/main/WIN_20250410_15_12_35_Pro.jpg" alt="Zafira Nur Kamila" />
      <br/><br/>
      <a href="https://www.linkedin.com/in/zafiranurkamila/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
      <a href="mailto:zafiranurkamila@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
    </td>
  </tr>
</table>

---

## About Me

```yaml
name: Zafira Nur Kamila
location: Indonesia
currently_working_on:
  - "Tugas akhir: PVC localization (RVOT vs LVOT) dengan CNN + fitur PSD, Wavelet & HOS"
  - "Portfolio interaktif 3D dengan React Three Fiber"
experience:
  - "Membangun REST API dengan Laravel & Spring Boot"
  - "Membuat aplikasi web dengan Next.js & React, serta aplikasi mobile dengan Flutter"
  - "Menulis automated test (PHPUnit, Katalon) & melakukan API testing"
  - "Melatih model computer vision & sinyal (TensorFlow, PyTorch, YOLOv8)"
currently_learning:
  - "Explainable AI (SHAP, permutation importance)"
  - "Evaluasi model yang lebih rigor (patient-level CV, multi-seed, bootstrap)"
  - "3D di web dengan Three.js"
fun_fact: "Portfolio-ku bisa dijelajahi sambil main mini game 🎮"
```

---

## Tech Stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,java,php,typescript,javascript,dart,cpp&theme=dark" />
</p>

### Web & Mobile
<p>
  <img src="https://skillicons.dev/icons?i=laravel,spring,nodejs,nextjs,react,vite,threejs,tailwind,flutter,html,css&theme=dark" />
</p>

### AI / Machine Learning
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" />
  <br/>
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" />
  <img src="https://img.shields.io/badge/SHAP-FF0051?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Signal_Processing-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

### Testing
<p>
  <img src="https://img.shields.io/badge/PHPUnit-6DB33F?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Katalon_Studio-2E96FF?style=for-the-badge&logo=katalon&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</p>

### Database & Tools
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,git,github,docker,maven,vscode,idea&theme=dark" />
</p>

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>PVC Localization — CNN + ECG Features 🫀</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/pvc-localization-cnn">
          <img src="https://img.shields.io/badge/Research-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
          <img src="https://img.shields.io/badge/Tugas_Akhir-2026-6C63FF?style=flat-square" />
        </a>
      </p>
      <p>Perbandingan fitur <b>PSD, Wavelet (CWT), dan Higher-Order Statistics</b> pada CNN multi-branch untuk menentukan asal PVC (RVOT vs LVOT) dari EKG 12-lead (329 pasien). Validasi 5-fold per pasien, multi-seed CV, bootstrap CI, dan XAI dengan SHAP. Model terbaik (PSD+Wavelet) mencapai <b>Macro F1 0,876</b> di data test.</p>
      <p><b>Stack:</b> Python, PyTorch, SciPy, PyWavelets, scikit-learn, SHAP</p>
    </td>
    <td width="50%" valign="top">
      <h3>Voxel Village Portfolio 🏡</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/portfolio">
          <img src="https://img.shields.io/badge/React-Three.js-000?style=flat-square&logo=threedotjs&logoColor=white" />
          <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
        </a>
      </p>
      <p>Portfolio interaktif berbentuk desa voxel: jalan-jalan dengan karakter, masuk ke bangunan untuk membaca isinya, ngobrol dengan warga, selesaikan quest, dan main 3 mini game. Tekstur, karakter, dan suara semuanya dibuat lewat kode; panggung "Sedang Dikerjakan" otomatis menarik repo terbaru dari GitHub.</p>
      <p><b>Stack:</b> React, React Three Fiber, drei, Tailwind CSS, Web Audio API</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Woundify — AI Wound Classification 🤖</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/woundify">
          <img src="https://img.shields.io/badge/Backend-Java-ED8B00?style=flat-square&logo=openjdk" />
          <img src="https://img.shields.io/badge/Mobile-Flutter-02569B?style=flat-square&logo=flutter" />
          <img src="https://img.shields.io/badge/AI-Python-3776AB?style=flat-square&logo=python" />
        </a>
      </p>
      <p>Aplikasi mobile untuk klasifikasi jenis luka menggunakan deep learning, dengan inference dari kamera pengguna dan backend Java untuk pengelolaan data.</p>
      <p><b>Stack:</b> Java, Flutter, Python, TensorFlow</p>
    </td>
    <td width="50%" valign="top">
      <h3>Finansialin — Personal Finance App</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/finansialin-backend-laravel">
          <img src="https://img.shields.io/badge/API-Laravel-777BB4?style=flat-square&logo=laravel" />
        </a>
        <a href="https://github.com/zafiranurkamila/finansialin-frontend">
          <img src="https://img.shields.io/badge/Web-Next.js-000?style=flat-square&logo=nextdotjs" />
        </a>
      </p>
      <p>REST API + aplikasi web untuk manajemen keuangan pribadi: auth token (access + refresh), pencatatan transaksi, budget planning, notifikasi, dan fitur AI, lengkap dengan feature tests.</p>
      <p><b>Stack:</b> Laravel 12, Next.js 14, PostgreSQL, PHPUnit, Google Generative AI</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>BooQu — Library Management</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/booqu-spring-restful-api">
          <img src="https://img.shields.io/badge/API-Spring_Boot-6DB33F?style=flat-square&logo=spring" />
        </a>
        <a href="https://github.com/zafiranurkamila/booqu-frontend">
          <img src="https://img.shields.io/badge/Web-JavaScript-F7DF1E?style=flat-square&logo=javascript" />
        </a>
      </p>
      <p>Sistem manajemen perpustakaan: peminjaman buku, autentikasi JWT, pelacakan keterlambatan, serta validasi & error handling di setiap endpoint.</p>
      <p><b>Stack:</b> Spring Boot, JPA/Hibernate, Spring Security, PostgreSQL, Maven</p>
    </td>
    <td width="50%" valign="top">
      <h3>Smoking Detection — YOLOv8</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/smoking-detection-yolov8">
          <img src="https://img.shields.io/badge/CV-YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black" />
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        </a>
      </p>
      <p>Model object detection untuk mendeteksi aktivitas merokok pada gambar/video menggunakan YOLOv8.</p>
      <p><b>Stack:</b> Python, YOLOv8, OpenCV</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>TeluCup — Tournament Platform</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/telucup-backend">
          <img src="https://img.shields.io/badge/Laravel-Blade-777BB4?style=flat-square&logo=laravel" />
        </a>
      </p>
      <p>Platform turnamen untuk penjadwalan pertandingan, pendaftaran tim, dan pengelolaan bracket.</p>
      <p><b>Stack:</b> PHP, Laravel, Blade, MySQL</p>
    </td>
    <td width="50%" valign="top">
      <h3>GYMFIT — Fitness Landing Page</h3>
      <p>
        <a href="https://github.com/zafiranurkamila/GYMFIT">
          <img src="https://img.shields.io/badge/HTML/CSS-E34F26?style=flat-square&logo=html5&logoColor=white" />
        </a>
      </p>
      <p>Landing page responsif untuk brand fitness dengan animasi halus, dark theme, dan layout mobile-first.</p>
      <p><b>Stack:</b> HTML5, CSS3, JavaScript</p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/zafiranurkamila?tab=repositories">
    <img src="https://img.shields.io/badge/View_All_Repositories-0e75b6?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=zafiranurkamila&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00F0FF&icon_color=00F0FF&text_color=fff" />
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=zafiranurkamila&layout=compact&theme=radical&hide_border=true&langs_count=8&bg_color=0D1117&title_color=00F0FF&text_color=fff" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=zafiranurkamila&theme=radical&hide_border=true&background=0D1117&stroke=00F0FF&ring=00F0FF&fire=FF00E5&currStreakLabel=00F0FF" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=zafiranurkamila&custom_title=Coding%20Activity%20Graph&theme=react-dark&hide_border=true&bg_color=0D1117&color=00F0FF&line=FF00E5&point=FFFFFF&area=true&area_color=00F0FF" width="98%" />
</div>

---

## Journey

```
2026  ▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰  Tugas akhir (ECG + CNN + XAI), portfolio 3D, Woundify
2025  ▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰▰░░░░  Spring Boot, Next.js, YOLOv8 & API testing
2024  ▰▰▰▰▰▰▰▰▰▰▰▰░░░░░░░░  Laravel, web development & integrasi frontend
2023  ▰▰▰▰▰▰▰▰░░░░░░░░░░░░  Java, PHP, C++ & dasar database
2022  ▰▰▰▰▰░░░░░░░░░░░░░░░  Mulai belajar ngoding
```

---

## Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/zafiranurkamila/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://instagram.com/kamila.zafira" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="mailto:zafiranurkamila@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/zafiranurkamila" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <i>"We are what we repeatedly do." — Aristotle</i>
</p>

<!-- Animated wave footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="footer" />
