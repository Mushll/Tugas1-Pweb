# Tugas1-Pweb

link blogspot: https://mushallin.blogspot.com/2026/09/foto-mushallina-dzikri-rozana.html

## Sketsa 
<img width="581" height="575" alt="Screenshot 2026-09-09 142541" src="https://github.com/user-attachments/assets/52b0b68a-4c4f-4c6a-b2b2-4b7b4dbfd52d" />

## KODE FULL 

```
<style>
  .cvport * { box-sizing: border-box; }
  .cvport {
    font-family: 'Georgia', 'Times New Roman', serif;
    color: #1c1c1c;
    background: #faf8f4;
    max-width: 960px;
    margin: 0 auto;
    padding: 0 20px 60px;
    line-height: 1.6;
  }
  .cvport h1, .cvport h2, .cvport h3 { font-family: 'Georgia', serif; font-weight: 400; margin: 0; }
  .cvport a { color: inherit; }

  /* NAVBAR */
  .cvport-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 24px 0;
    border-bottom: 1px solid #e2ddd2;
    flex-wrap: wrap;
    gap: 12px;
  }
  .cvport-nav .brand { font-size: 22px; font-style: italic; color: #234339; }
  .cvport-nav ul { list-style: none; display: flex; gap: 24px; margin: 0; padding: 0; font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 14px; letter-spacing: 0.03em; }
  .cvport-nav a { text-decoration: none; }
  .cvport-nav .home-btn { background: #234339; color: #fff !important; padding: 8px 18px; border-radius: 3px; }

  /* HERO */
  .cvport-hero {
    display: grid;
    grid-template-columns: 220px 1fr 220px;
    gap: 32px;
    padding: 56px 0 40px;
    align-items: start;
  }
  .cvport-photo-wrap { text-align: center; }
  .cvport-photo {
    width: 190px; height: 190px; border-radius: 50%;
    object-fit: cover; background: #ddd6c8;
    border: 1px solid #e2ddd2;
    display: block; margin: 0 auto 14px;
  }
  .cvport-status { font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 12px; letter-spacing: 0.12em; color: #7a7364; }

  .cvport-hero-main h1 { font-size: 40px; margin-bottom: 8px; }
  .cvport-hero-main .desc { font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 14px; color: #55503f; margin-bottom: 22px; }
  .cvport-hero-buttons { display: flex; gap: 12px; margin-bottom: 8px; }
  .cvport-btn { font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 13px; padding: 10px 20px; border-radius: 3px; text-decoration: none; display: inline-block; border: 1px solid transparent; }
  .cvport-btn.primary { background: #234339; color: #fff; }
  .cvport-btn.secondary { background: #efece3; color: #1c1c1c; }

  .cvport-hero-image { width: 100%; aspect-ratio: 4/3; object-fit: cover; background: #ddd6c8; border-radius: 4px; }

  /* SECTION LABEL */
  .cvport-label { font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 13px; letter-spacing: 0.1em; color: #234339; margin-bottom: 14px; }

  /* BODY GRID: tentang saya / skill / toolset / kontak */
  .cvport-body { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 40px; padding-top: 20px; border-top: 1px solid #e2ddd2; }
  .cvport-col p { font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 14px; color: #3c382d; }

  .cvport-skill-item, .cvport-contact-item {
    font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 14px;
    background: #efece3; border-radius: 3px; padding: 12px 14px; margin-bottom: 12px;
  }
  .cvport-contact-item a { text-decoration: none; }

  .cvport-toolset-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-top: 6px; }
  .cvport-tool { background: #efece3; border-radius: 3px; aspect-ratio: 1; display: flex; align-items: center; justify-content: center; font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 11px; text-align: center; color: #3c382d; padding: 4px; }

  @media (max-width: 800px) {
    .cvport-hero { grid-template-columns: 1fr; }
    .cvport-body { grid-template-columns: 1fr; }
  }
</style>

<div class="cvport">

  <!--NAVBAR-->
  <nav class="cvport-nav">
    <div class="brand">Alin</div> <!--inisial-->
    <ul>
      <li><a href="#tentang">About</a></li>
      <li><a href="#skill">Skill</a></li>
      <li><a href="#kontak">Contact</a></li>
      <li><a class="home-btn" href="#">Home</a></li>
    </ul>
  </nav>

<!--HERO-->
<section class="cvport-hero">

  <div class="cvport-photo-wrap">
    
    <img alt="Foto Mushallina Dzikri Rozana" border="0" height="210" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgIa3uj45pos5o1nge0JWvkBO0Sz7JV9WnVVLp4yE9_MWlh5XugLfs0yRZr2ZAyrCx2USg_VjdFxoBkoOSKdYsjTqgg6OV9Wy1bQTNSgkG5AoJMZs-viyIT6QxqGcAP_Y61tvj6EvezvTX56xpWz5ohggHvtdR3DNTeqGh54JQSGpWG5eWoa1WkUMix3-IN/w157-h210/Untitled%20design%20(14).png" width="157" /></div><div class="cvport-hero-main"><h1>Mushallina Dzikri Rozana</h1>
    <div class="desc">
      
      Saya adalah mahasiswa Departemen Teknik Informatika Institut Teknologi Sepuluh Nopember (ITS)
      angkatan 2025</div>
   
  </div>

</section>

  <!--TENTANG SAYA / SKILL / TOOLSET / KONTAK-->
  <section class="cvport-body">

    <div class="cvport-col" id="tentang">
      <div class="cvport-label"><br /></div><div class="cvport-label"><br /></div><div class="cvport-label"><b><span style="font-family: georgia;">TENTANG SAYA<br /></span></b></div><div class="cvport-label"><br /></div><div class="cvport-label"><span id="docs-internal-guid-a5395556-7fff-53f0-682c-e5e77542f192"><p dir="ltr" style="line-height: 1.2; margin-bottom: 0pt; margin-left: 5.95pt; margin-right: 6.25pt; margin-top: 0.1pt; margin: 0.1pt 6.25pt 0pt 5.95pt; text-align: justify;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; font-variant: normal; vertical-align: baseline; white-space: pre-wrap;">&nbsp;Saya merupakan pribadi yang kreatif, inovatif, dan adaptif dalam menghadapi perkembangan teknologi, serta memiliki </span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; font-style: italic; font-variant: normal; vertical-align: baseline; white-space: pre-wrap;">passion</span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; font-variant: normal; vertical-align: baseline; white-space: pre-wrap;"> untuk menciptakan solusi berbasis teknologi yang mampu memberi dampak positif bagi lingkungan sekitar. S</span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">aya memiliki ketertarikan kuat dalam bidang teknologi digital, khususnya pada&nbsp;</span><em style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">software development</em><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">,</span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">&nbsp;</span><em style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">UI/UX</em><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 11pt; text-align: left; white-space: pre-wrap;">, dan multimedia kreatif.</span></p></span></div><div class="cvport-label"><br /></div><div class="cvport-label"><b><span style="font-family: georgia;">TOOLSET</span></b></div>
      <div class="cvport-toolset-grid">
        <div class="cvport-tool">VS Code</div>
        <div class="cvport-tool">Figma</div>
        <div class="cvport-tool">Git</div>
        <div class="cvport-tool">Canva</div>
        <div class="cvport-tool">MS Office</div>
      </div> <!--toolss-->
    </div>

    <div class="cvport-col" id="skill">
      <div class="cvport-label"><b>SKILL</b></div>
      <div class="cvport-skill-item">HTML &amp; CSS</div>
      <div class="cvport-skill-item">Dasar JavaScript</div>
      <div class="cvport-skill-item">Microsoft Office</div>
      <div class="cvport-skill-item">Komunikasi &amp; Presentasi</div>
      <!--: sesuaikan skill-->
    </div>

    <div class="cvport-col" id="kontak">
      <div class="cvport-label"><b><span style="font-family: georgia;">INFORMASI KONTAK</span></b></div>
      <div class="cvport-contact-item">Email: rosarozana10@gmail.com</div>
      <div class="cvport-contact-item">No. HP: 081212827398</div>
      <div class="cvport-contact-item">
        LinkedIn: <a href="#" target="_blank">https://www.linkedin.com/feed/</a>
      </div>
    </div>

  </section>
</div>
```
