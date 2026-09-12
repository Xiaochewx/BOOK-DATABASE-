<div align="center">

# 📚 SISTEM PANGKALAN DATA BUKU NILAM & PEMBANTU AINS
### NILAM 书籍资料库与 AINS 极速填报助手 · NILAM Book Database & AINS Assistant

> **Satu-satunya sistem arkib bahan bacaan dan automasi pengisian AINS NILAM termaju di Malaysia.**  
> **专为马来西亚教育部 AINS NILAM 官方阅读计划研发的极速智能检索与填报生态。**  
> *The most advanced NILAM reading archive and smart autofill ecosystem for Malaysia's AINS portal.*

---

[![AINS Portal](https://img.shields.io/badge/AINS%20Portal-100%25%20Compatible-00C853?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ains.moe.gov.my)
[![Total Books](https://img.shields.io/badge/Jumlah%20Buku-2%2C029%20Jilid-D4AF37?style=for-the-badge&logo=gitbook&logoColor=white)](#)
[![Zero Repetition](https://img.shields.io/badge/Pengajaran-0%25%20Duplikasi-FF6D00?style=for-the-badge&logo=speedtest&logoColor=white)](#)
[![Trilingual Support](https://img.shields.io/badge/Bahasa-BM%20%7C%20%E4%B8%AD%E6%96%87%20%7C%20EN-2979FF?style=for-the-badge)](#)
[![Architecture](https://img.shields.io/badge/Tech-Vanilla%20JS%20%2F%20No%20Server-7C4DFF?style=for-the-badge)](#)

<br/>

**[ 🇲🇾 Bahasa Melayu ](#-bahasa-melayu) &nbsp;•&nbsp; [ 🇨🇳 中文文档 ](#-中文文档) &nbsp;•&nbsp; [ 🇬🇧 English ](#-english)**

---

</div>

<br/>

<div id="-bahasa-melayu"></div>

# 🇲🇾 Bahasa Melayu

## 🎯 Pengenalan & Matlamat Projek

**Sistem Pangkalan Data Buku NILAM** dibangunkan khas untuk para pelajar sekolah rendah dan menengah di Malaysia yang menyertai program rasmi **NILAM (Nadi Ilmu Amalan Membaca)** di bawah kelolaan Kementerian Pendidikan Malaysia (KPM).

Sistem ini menghubungkan pangkalan data **2,029 jilid buku** dengan portal rasmi **AINS (Aplikasi Pengesanan Bahan Bacaan NILAM)**, membolehkan murid mencari maklumat buku, menyalin butiran mengikut urutan borang, atau mengisi borang AINS secara automatik dalam masa **1 saat** melalui skrip Tampermonkey khusus!

---

## 🌟 Ciri-Ciri Khas & Keistimewaan

### 1. ⚖️ Keseimbangan Kuota Bahan Bacaan (50% Fiksyen & 50% Bukan Fiksyen)
* Dalam garis panduan NILAM KPM, rekod pembacaan komik/manga tertakluk kepada had kuota atau pemberatan markah PAJSK.
* Pangkalan data ini disusun secara strategik merangkumi:
  * **1,019 Jilid Komik / Fiksyen Popular**: Naruto, One Piece, Haikyu!!, Bleach, Detective Conan, Attack on Titan, Demon Slayer, Jujutsu Kaisen, Spy x Family, dan banyak lagi.
  * **1,010 Jilid Bukan Fiksyen Berkualiti Tinggi**: Teknologi Maklumat & AI, Kosmologi, Sains Perubatan, Sejarah Tamadun, Biografi Tokoh Dunia, Sastera Kebangsaan & Falsafah Hidup.
* **Kelebihan**: Memastikan portfolio pembacaan pelajar seimbang dan layak mendapat pengiktirafan markah tertinggi PAJSK (Tahap Bintang Emas/Nilam Kebangsaan).

### 2. ⚡ Salinan Berturutan Pantas AINS (AINS Sequential Copy)
* Setiap kad buku dilengkapi dengan butang **⚡ Salinan Berturutan AINS**.
* **Urutan diselaraskan 100% mengikut turutan borang laman sesawang AINS**:
  $$\text{Judul} \longrightarrow \text{Pengarang} \longrightarrow \text{Penerbit} \longrightarrow \text{Tahun} \longrightarrow \text{Muka Surat} \longrightarrow \text{Rumusan} \longrightarrow \text{Pengajaran}$$
* **Sokongan Pintas Papan Kekunci**: Selepas menekan mana-mana buku, hanya tekan bar ruang (**Spacebar**) pada papan kekunci untuk menyalin medan seterusnya tanpa perlu menggerakkan tetikus!

### 3. ✍️ 100% Gaya Penulisan Sebenar Murid & Sifar Templat Tiruan
* **2,029 Pengajaran / Iktibar Unik (0% Duplikasi)**: Setiap satu daripada 2,029 buku mempunyai rumusan dan iktibar tersendiri yang berbeza sama sekali antara satu sama lain. Tiada risiko ditandakan menipu oleh guru atau pustakawan sekolah.
* **Penyelarasan 16 Nilai Murni KPM**: Mengintegrasikan nilai rasmi seperti *Kegigihan*, *Kerjasama*, *Rasional*, *Hemah Tinggi*, *Kasih Sayang*, *Menghargai Alam Sekitar*, dan *Bertanggungjawab*.
* **Aplikasi Kehidupan Murid (Aplikasi Seharian)**: Mengaitkan iktibar buku dengan cabaran persekolahan sebenar—seperti disiplin mengulang kaji, adab terhadap guru dan ibu bapa, semangat kesukanan, dan kesedaran membanteras berita palsu.

### 4. 🤖 Skrip Automasi AINS Tampermonkey (`ains_nilam_helper.user.js`)
* Skrip pemudah cara yang terapung (Floating HUD) terus di dalam portal rasmi AINS (`ains.moe.gov.my`).
* Ciri automasi:
  * **Salin 1-Klik**: Tekan butang "Salin Penuh" di pangkalan data, bertukar ke portal AINS, dan tekan `[⚡ Auto-Isi Pantas]`.
  * Mengisi semua medan teks, kategori, bilangan halaman, ISBN, rumusan, dan pengajaran dalam masa **1 saat**.

### 5. 💎 Antara Muka Dark Gold Obsidian & Berdikari Luar Talian
* Dibina dengan HTML5, CSS3 moden, dan Vanilla JavaScript.
* **Tiada Pangkalan Data Luaran**: Data disimpan secara setempat dalam `LocalStorage`.
* Menyokong penanda buku siap dibaca (Sudah Baca), penanda bintang (Kegemaran), serta sandaran data import/eksport JSON.

---

## 🚀 Panduan Penggunaan & Pemasangan

### Pilihan A: Akses Dalam Talian (Disyorkan)
Buka laman sesawang melalui GitHub Pages atau pautan pelayan web anda pada mana-mana pelayar (Chrome / Edge / Firefox / Safari).

### Pilihan B: Penggunaan Luar Talian (Tanpa Internet)
1. Muat turun fail repositori ini.
2. Klik dua kali pada fail `index.html`. Sistem akan beroperasi serta-merta tanpa memerlukan pelayan Node.js atau Apache.

### Pilihan C: Memasang Pembantu Automasi AINS
1. Pasang sambungan pelayar **Tampermonkey** ([tampermonkey.net](https://www.tampermonkey.net/)).
2. Buka papan pemuka Tampermonkey, pilih **Create a new script**, dan tampal kandungan fail [`ains_nilam_helper.user.js`](./ains_nilam_helper.user.js).
3. Simpan skrip. Apabila anda melayari `https://ains.moe.gov.my`, widget pembantu emas akan muncul di sudut kanan bawah skrin anda!

---

<br/>

<div id="-中文文档"></div>

# 🇨🇳 中文文档

## 🎯 项目初衷与设计哲学

在马来西亚的中小学教育考核中，**NILAM 读书计划**直接挂钩学生的 **PAJSK 课外活动综合评估积分**。然而，许多同学在提交阅读记录至教育部 **AINS 官方系统 (AINS NILAM)** 时，面临两大核心痛点：

1. **品类单一被压分**：全刷日漫（Komik）会触发配额惩罚与折算扣分，官方重点考核非虚构类（Bukan Fiksyen）如科普、历史、传记与哲学。
2. **千篇一律模板被抓作弊**：大量网传脚本采用千篇一律的通用陈词，抽查时一旦 Sinopsis / Nilai Murni 完全一致，记录极易被老师作废。

本项目正是为此而生——打造一个**集 2,029 卷全量图书库、100% 独立真人打字手感启示、以及 AINS 官方顺序无缝贴合的极速填报生态**！

---

## ✨ 核心独家特色

### 1. 📚 2,029 卷科学黄金配比（50% 非虚构类 + 50% 经典漫画）
* **1,019 卷经典日漫 / 热血文学**：火影忍者 (72卷全)、海贼王 (108卷)、排球少年 (45卷全)、死神 (74卷全)、名侦探柯南、进击的巨人、鬼灭之刃、咒术回战、间谍过家家、蓝色监狱等。
* **1,010 卷精选非虚构类 (Bukan Fiksyen)**：现代信息科技与AI、微观昆虫记、人体与医学、宇宙天体、绿色地球、华夏五千年、丝绸之路、世界大战与和平、科技先驱传记、心理学成长与生活哲学。
* **助益**：彻底打破“只有漫画”的偏科红线，让你的 NILAM 记录成为全校典范！

### 2. ⚡ AINS 7 步极速步进连击队列（Sequential Copy）
* 每张书籍卡片底部设置 **⚡ AINS 步进复制** 队列，严格依循 AINS NILAM 网页填表次序：
  $$\text{第1击：书名} \longrightarrow \text{第2击：作者} \longrightarrow \text{第3击：出版社} \longrightarrow \text{第4击：年份} \longrightarrow \text{第5击：页数} \longrightarrow \text{第6击：总结} \longrightarrow \text{第7击：启示}$$
* **键盘空格键盲操 [Space]**：鼠标点击书籍后，只需按键盘空格键即可自动步进复制下一项，全程无需移动鼠标，填表速度提升 10 倍！

### 3. ✍️ 100% 纯中文 · 真实学生手工打字质感（0% 重复率）
* **0 英文/马文字母残留**：彻底告别 `【坚毅不拔】(Kegigihan)` 这种死板生硬的中外混合学术标签。
* **第一人称真实学生读者视角**：
  > *“合上《火影忍者》第1卷，故事情节非常吸引人……在平时的学校生活中，如果我考试考得不好或者功课遇到难题，我不应该找借口抱怨，而是要像主角一样脚踏实地把不懂的问题搞懂，坚持到底。”*
* **全馆 2,029 卷 100% 独一无二**：每本书根据系列、卷数与特定情节/知识点独立撰写，完美通过学校老师与图书管理员的人工抽查！

### 4. 🤖 AINS 专属油猴秒填插件 (`ains_nilam_helper.user.js`)
* 专为 `ains.moe.gov.my` 官方网站开发的悬浮 HUD 助手。
* 点击主系统上的“一键复制整本”，切换到 AINS 网页点击 **[⚡ 智能秒填]**，所有输入框、年份、页数、单选框、总结与启示瞬间自动填毕！

### 5. 💎 黑金曜石极速前端架构
* 纯静态单页面应用（SPA），无需 Node.js、Python 或任何后端环境。
* 阅读状态（已读/未读）、星标收藏、搜索筛选等数据完全保存在浏览器 `LocalStorage`，支持一键导出/导入 JSON 备份。

---

## 🛠️ 文件目录结构

```text
├── index.html                  # 系统前端主程序（响应式黑金 UI + 步进队列交互）
├── data.js                     # 全馆 2,029 卷中/马/英三语核心图书资料库
├── ains_nilam_helper.user.js   # AINS NILAM 官方网站配套 Tampermonkey 自动填表插件
└── README.md                   # 本说明文档（中/马/英三语）
```

---

<br/>

<div id="-english"></div>

# 🇬🇧 English

## 🎯 Project Overview & Purpose

The **NILAM Book Database & AINS Assistant** is an all-in-one digital catalog and filing automation suite engineered specifically for Malaysian primary and secondary school students participating in the official **NILAM (National Reading Programme)** monitored via the **AINS (Aplikasi Pengesanan Bahan Bacaan NILAM KPM)** portal.

It features a massive collection of **2,029 complete book volumes**, rich trilingual content, an intelligent sequential clipboard queue, and a dedicated browser extension for instantaneous form completion on the official government website.

---

## 🚀 Key Innovations & Distinctive Features

### 1. ⚖️ Strategic 50:50 Quota Balancing (Fiction vs. Non-Fiction)
* In the official Malaysian education framework, over-relying on comics (Komik) results in penalty weighting or strict quota caps in co-curricular evaluations (PAJSK).
* Our database is divided with optimal academic balance:
  * **1,019 Volumes of Classic Manga/Fiction**: Naruto, Haikyu!!, One Piece, Bleach, Detective Conan, Attack on Titan, Demon Slayer, etc.
  * **1,010 Volumes of Curated Non-Fiction**: AI & Computer Science, Marine Biology, Medical Innovations, World Civilizations, Global Biographies, Classical Literature, and Philosophy.

### 2. ⚡ AINS 7-Step Sequential Fast Copy
* Every book card features an **AINS Sequential Copy** button designed around the exact input field order of the AINS portal:
  $$\text{Title} \longrightarrow \text{Author} \longrightarrow \text{Publisher} \longrightarrow \text{Year} \longrightarrow \text{Pages} \longrightarrow \text{Summary (Rumusan)} \longrightarrow \text{Insight (Pengajaran)}$$
* **Spacebar Hotkey**: Select any book card and tap the **Spacebar** to sequentially copy the next field automatically without moving your mouse cursor.

### 3. ✍️ 100% Authentic Student Voice & Zero Template Cloning
* **2,029 / 2,029 Unique Insights (0% Collisions)**: Each volume has a personalized reflection tailored to its exact volume number, characters, and storyline.
* **Pure Idiomatic Phrasing**:
  * **Chinese (ZH)**: 100% pure Chinese written from an authentic student's perspective with zero foreign letter intrusions or robotic jargon.
  * **Malay (MS Baku)**: Formal Bahasa Melayu adhering strictly to KPM's 16 official *Nilai Murni* standards.
  * **English (EN)**: Articulate, grammatically pristine reflections with real-world school and community takeaways (*Aplikasi Kehidupan Seharian*).

### 4. 🤖 Dedicated AINS Tampermonkey Autofill Script (`ains_nilam_helper.user.js`)
* Injects an elegant floating Cyber-HUD directly onto `ains.moe.gov.my`.
* Features clipboard listening, single-click full auto-population of form fields, dropdown auto-selection, and automatic character count verification in under **1 second**.

### 5. 💎 Offline-Ready Vanilla Architecture
* Zero dependencies, zero build steps, and zero external database overhead.
* Complete offline operation via `index.html` with persistent LocalStorage state tracking (Read / Unread, Starred Favorites, Filter Presets, and JSON Export/Import).

---

## 📖 Quick Start & Installation

1. **Online Web App**: Host on GitHub Pages or any static CDN for instant browser access.
2. **Local Offline Mode**: Simply double-click `index.html` in any modern web browser.
3. **AINS Companion Setup**: Install the [Tampermonkey](https://www.tampermonkey.net/) extension, create a new script, paste the contents of [`ains_nilam_helper.user.js`](./ains_nilam_helper.user.js), and save. The floating helper will automatically activate on AINS portal pages.

---

<div align="center">

**Built with dedication for Malaysian students striving for academic excellence and reading mastery.**  
*Dirangka khas demi kecemerlangan murid dan pemerkasaan budaya membaca di Malaysia.*

</div>
