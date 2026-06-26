<h1 align="center">Hi 👋, I'm Cahyono</h1>
<h3 align="center">Software Engineer · Frontend & Backend · UI/UX Enthusiast — Tangerang, Indonesia 🇮🇩</h3>

<p align="center">
  <a href="https://cahyono.my.id"><img src="https://img.shields.io/badge/Portfolio-cahyono.my.id-0E7C66?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/cahyono99/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:cahyono060799@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=yono99&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="profile views" />
</p>

---

### 🚀 About Me

- 🔭 Lagi ngerjain **platform belajar & tryout AI** (Next.js + Gemini + Prisma) untuk persiapan CPNS, UTBK & ujian sekolah
- 🌱 Lagi mendalami **testing frameworks**, **system design**, dan **UI/UX principles**
- 💬 Tanya gue soal **Vue / Nuxt / React / Next.js** atau diskusi CSS framework (gue udah coba 5+ 😅)
- 🎯 Fokus: bikin produk yang dipakai orang beneran, bukan cuma demo

---

### 🛠️ Tech Stack

**Frontend**

![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt.js-00DC82?style=flat&logo=nuxtdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**Backend & CMS**

![Node](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat&logo=wordpress&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

**Styling**

![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=flat&logo=vuetify&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

### 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=yono99&show_icons=true&count_private=true&hide_border=true&theme=tokyonight" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yono99&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=yono99&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=yono99&theme=tokyonight&no-frame=true&row=1&column=7" />
</p>

---

### 🧠 Case Study — Figural Engine (nilaia.com)

> Membangun engine **deterministik** untuk men-generate soal penalaran figural (Diagrammatic & Abstract Reasoning) gaya ujian CPNS/TIU — tanpa mengandalkan AI untuk menggambar.

<div align="center">
  <img src="assets/figural-demo.gif" width="640" alt="Demo output figural engine — soal analogi & diagrammatic reasoning ter-render otomatis" />
  <br/><sub>Output asli engine — tiap soal (visual + kunci jawaban) dihasilkan otomatis & deterministik.</sub>
</div>

**🔴 Masalah.** Soal figural (analogi gambar, deret gambar, ketidaksamaan, diagrammatic reasoning) butuh visual yang **presisi piksel** dan **kunci jawaban yang pasti benar**. Model AI generatif (image & SVG) konsisten gagal di sini: koordinat meleset, bentuk rusak, dan — yang paling fatal — **kunci jawabannya tidak bisa dipercaya**. Untuk produk ujian, satu kunci salah = kepercayaan pengguna hilang.

**🟢 Pendekatan.** Alih-alih "meminta AI menggambar", saya membalik masalahnya: **biarkan kode yang menggambar dan menghitung jawaban, AI hanya menyusun teks.**

```
config aturan  →  render SVG (kode)  →  hitung kunci jawaban (kode)  →  teks (AI, opsional)
   (deterministik, 0 token)              (dijamin benar)
```

- Visual & kunci jawaban dihasilkan **100% deterministik** oleh kode → **0 token AI**, reproducible, dan kunci jawaban **mustahil salah** karena dihitung dari aturan yang sama yang menggambarnya.
- AI hanya dipakai untuk merangkai *teks* pertanyaan/pembahasan pada sub-tipe tertentu — bukan untuk logika atau gambar.

**⚙️ Yang saya rancang.**
- Pustaka **80+ bentuk geometris** sebagai SVG primitif, dipakai lintas semua tipe soal dari satu sumber render.
- Sistem **rotasi anti-monoton** sehingga variasi soal maksimal dan pola tidak mudah ditebak/berulang.
- Beberapa keluarga aturan transformasi (rotasi, operator-chain, matriks) dengan **kontrol tingkat kesulitan** bertingkat.
- Distraktor (opsi pengecoh) yang dihasilkan terukur, bukan acak — agar soal pilihan ganda berkualitas.

**📊 Dampak.**
- Soal figural tak terbatas, **biaya AI ~nol** untuk komponen visual, dan **akurasi kunci jawaban 100%**.
- Menjadi pembeda teknis utama produk dibanding pendekatan berbasis AI murni yang rapuh di ranah visual.

<sub>💡 Konsep procedural reasoning generation memang dikenal di riset (Raven's Matrices, DeepMind PGM). Kontribusi saya: mengadaptasinya menjadi engine produksi TypeScript/SVG yang ter-tuned untuk **sub-tipe TIU otentik Indonesia** di dalam platform nyata. Kode bersifat proprietary — happy to discuss the approach.</sub>

---

### 📌 Featured Projects

| Project | Description | Tech |
|---|---|---|
| [**Nilaia — App Android**](https://github.com/yono99/nilaia-app) | Platform belajar & simulasi CAT (CPNS/UTBK) dengan AI question generation & figural reasoning engine · [nilaia.com](https://nilaia.com) | Next.js · Prisma · Gemini · Supabase |
| [**Vue Express TS Auth Starter**](https://github.com/yono99/vue-express-ts-auth-starter-TypeORM) | Boilerplate auth fullstack TypeScript dengan TypeORM | Vue · Express · TypeORM |

---

<p align="center"><i>⭐️ From <a href="https://github.com/yono99">yono99</a></i></p>
