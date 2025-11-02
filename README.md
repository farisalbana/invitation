<!doctype html>
<html lang="id">

<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
  <title>Undangan Digital — PT. Mandiri Sejahtera Sentosa</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link
    href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Montserrat:wght@300;400;600&family=Great+Vibes&display=swap"
    rel="stylesheet">

  <style>
    :root {
      --accent: #d6c49a;
      --bg: #083822;
      --muted: #e6d9be;
      --card: rgba(0, 0, 0, 0.18);
    }

    html,
    body,
    #app {
      height: 100%;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    body {
      touch-action: manipulation;
      -webkit-text-size-adjust: 100%;
      -ms-text-size-adjust: 100%;
      text-size-adjust: 100%;
      overflow-y: auto;
      background: var(--bg);
      font-family: Montserrat, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color: var(--muted);
    }

    * {
      box-sizing: border-box;
    }

    .slider {
      width: 100%;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .slides {
      display: flex;
      height: 100%;
      transition: transform 600ms cubic-bezier(.2, .8, .2, 1);
    }

    .slide {
      min-width: 100%;
      height: 100%;
      padding: 28px;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      color: var(--muted);
      position: relative;
    }

    .bg-decor {
      background: linear-gradient(180deg, rgba(0, 0, 0, 0.08), rgba(0, 0, 0, 0.08)),
        url('Gemini_Generated_Image_s1sqhis1sqhis1sq.png') center/cover no-repeat;
    }

    .card {
      max-width: 820px;
      width: 100%;
      background: linear-gradient(180deg, rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.18));
      border-radius: 18px;
      padding: 28px;
    }

    .pop-in {
      animation: popIn .6s both;
    }

    @keyframes popIn {
      from {
        opacity: 0;
        transform: translateY(12px) scale(.995);
      }

      to {
        opacity: 1;
        transform: none;
      }
    }

    .title-hero {
      font-family: 'Playfair Display', serif;
      font-weight: 700;
      color: var(--muted);
    }

    .subtitle {
      color: var(--muted);
      opacity: 0.95;
    }

    .open-btn {
      background: var(--muted);
      color: var(--bg);
      padding: 12px 26px;
      border-radius: 28px;
      font-weight: 700;
      box-shadow: 0 8px 24px rgba(0, 0, 0, .25);
      display: inline-block;
    }

    .logos {
      display: flex;
      gap: 14px;
      align-items: center;
      justify-content: center;
    }

    .logos img {
      height: 62px;
      border-radius: 8px;
      border: 3px solid rgba(255, 255, 255, .06);
      background: rgba(0, 0, 0, .06);
    }

    .photo-frame {
      width: 86px;
      height: 98px;
      border-radius: 6px;
      overflow: hidden;
      border: 3px solid rgba(255, 255, 255, .12);
      background: #fff;
      margin-bottom: 12px;
    }

    .photo-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .hero-block {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      margin-top: 6px;
    }

    .hero h1 {
      font-size: 26px;
    }

    .hero .lead {
      font-family: 'Playfair Display', serif;
      font-size: 20px;
    }

    @media(min-width:900px) {
      .slide {
        padding: 48px;
      }

      .card {
        padding: 36px;
      }

      .hero h1 {
        font-size: 36px;
      }

      .photo-frame {
        width: 110px;
        height: 140px;
      }

      .logos img {
        height: 76px;
      }
    }

    .date-box {
      display: flex;
      align-items: center;
      gap: 28px;
    }

    .date-big {
      font-family: 'Playfair Display', serif;
      font-weight: 700;
      font-size: 68px;
      line-height: 1;
    }

    .muted-small {
      font-size: 13px;
      opacity: 0.95;
    }

    /* Tombol Navigasi */
    .nav-btns {
      position: absolute;
      bottom: 22px;
      left: 0;
      right: 0;
      display: flex;
      justify-content: space-between;
      padding: 0 24px;
      z-index: 10;
    }

    .btn-next,
    .btn-prev {
      background: rgba(230, 217, 190, 0.9);
      color: var(--bg);
      border: none;
      border-radius: 24px;
      padding: 8px 18px;
      font-weight: 600;
      cursor: pointer;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.25);
      transition: all 0.3s ease;
    }

    .btn-next:hover,
    .btn-prev:hover {
      transform: translateY(-2px);
    }
  </style>
</head>

<body>
  <div id="app" class="slider">
    <div id="slides" class="slides">

      <section class="slide bg-decor" id="slide-0"
        style="background: linear-gradient(180deg, rgba(0,0,0,0.1), rgba(0,0,0,0.1)), url('Milad Perusahaan PT. Mandiri Sejahtera Sentosa (5).png') center/cover no-repeat;">
        <div class="card text-center pop-in mx-auto" style="background:transparent;box-shadow:none;padding-top:36px">

          <!-- Logo Animasi -->
          <div class="logos mt-2 mb-4 animate-fadeIn delay-200">
            <img src="logooo (1) (1).png" />
            <img src="logooo (2) (1).png" />
          </div>

          <!-- Hero Text Animasi -->
          <div class="hero-block mt-2 mb-4 px-4">
            <div class="title-hero text-2xl md:text-3xl animate-fadeIn delay-400">Milad Perusahaan</div>
            <div class="title-hero text-2xl md:text-3xl animate-fadeIn delay-600">PT. Mandiri Sejahtera Sentosa Ke-12
            </div>
            <div class="title-hero text-2xl md:text-3xl animate-fadeIn delay-800">Peresmian Yayasan Mandiri Sejahtera
              Sentosa</div>
            <div class="title-hero text-2xl md:text-3xl animate-fadeIn delay-1000">Haul Alm. Bapa H. Sungeb & Almh. Ibu
              Hj. Rogayah</div>
          </div>

          <!-- Kepada Yth -->
          <div class="mt-6 text-sm animate-fadeIn delay-1200">
            <div style="font-family:'Great Vibes', cursive;">Kepada Yth:</div>
            <div style="font-weight:600;">Tamu Undangan</div>
          </div>

          <!-- Button Open Invitation -->
          <div class="mt-8 animate-fadeIn delay-1400">
            <button id="openInvite" class="open-btn">Open Invitation</button>
          </div>
        </div>

        <!-- Tombol Navigasi -->
        <div class="nav-btns" style="justify-content:end;">
          <button class="btn-next" onclick="nextSlide()">Lanjut ➜</button>
        </div>
      </section>

      <style>
        /* Animasi Fade In dengan delay */
        .animate-fadeIn {
          opacity: 0;
          transform: translateY(12px);
          animation: fadeInAnim 0.6s forwards;
        }

        .animate-zoomIn {
          opacity: 0;
          transform: scale(0.95);
          animation: zoomInAnim 0.6s forwards;
        }

        /* Delay custom */
        .delay-200 {
          animation-delay: 0.2s;
        }

        .delay-400 {
          animation-delay: 0.4s;
        }

        .delay-600 {
          animation-delay: 0.6s;
        }

        .delay-800 {
          animation-delay: 0.8s;
        }

        .delay-1000 {
          animation-delay: 1s;
        }

        .delay-1200 {
          animation-delay: 1.2s;
        }

        .delay-1400 {
          animation-delay: 1.4s;
        }

        @keyframes fadeInAnim {
          to {
            opacity: 1;
            transform: translateY(0);
          }
        }

        @keyframes zoomInAnim {
          to {
            opacity: 1;
            transform: scale(1);
          }
        }
      </style>
      <!-- Slide 2 -->
      <section class="slide bg-decor" id="slide-1">
        <div class="card pop-in mx-auto" style="max-width:760px;background:transparent;padding:32px">
          <div class="text-center px-6" style="line-height:1.6">
            <h2 class="title-hero text-3xl mb-4">Dengan Hormat,</h2>
            <p class="muted-small text-justify">
              Segala puji syukur kehadirat Tuhan Yang Maha Esa atas rahmat dan karunia-Nya yang senantiasa menyertai
              langkah kita.
            </p>
            <div class="mt-6 muted-small text-justify">
              Sehubungan dengan peringatan Milad Perusahaan PT. Mandiri Sejahtera Sentosa yang ke-12, Peresmian Yayasan
              Mandiri Sejahtera Sentosa sekaligus Haul Alm. Bapa H. Sungeb &amp; Almh. Ibu Hj. Rogayah, kami mengundang
              Bapak/Ibu/Saudara/i untuk hadir dalam acara syukur dan doa bersama.
            </div>
          </div>
        </div>
        <div class="nav-btns">
          <button class="btn-prev" onclick="prevSlide()">⬅️ Kembali</button>
          <button class="btn-next" onclick="nextSlide()">Lanjut ➜</button>
        </div>
      </section>

      <!-- Slide 3 -->
      <section class="slide bg-decor" id="slide-2">
        <div class="card pop-in mx-auto text-center" style="max-width:760px;padding:36px;background:transparent">
          <h3 class="title-hero text-xl" style="color:var(--accent)">WAKTU</h3>
          <div class="mt-6 date-box justify-center">
            <div class="muted-small">SABTU</div>
            <div style="display:flex;flex-direction:column;align-items:center">
              <div class="date-big" style="color:var(--muted)">08</div>
              <div style="font-size:12px">2025</div>
            </div>
            <div class="muted-small">NOVEMBER</div>
          </div>
          <div class="mt-4 muted-small">Pukul 14.00 WIB</div>
          <h3 class="title-hero text-xl mt-8" style="color:var(--accent)">LOKASI</h3>
          <p class="mt-3">Yayasan Mandiri Sejahtera Sentosa<br>Blok V Rt/Rw 03/10 Desa Cikalahang, Kec. Dukupuntang,
            Kab. Cirebon</p>
          <div class="mt-4 mb-4">
            <a href="https://maps.app.goo.gl/gza7PCHDvi557Zk16" target="_blank" class="open-btn">
              Buka di Google Maps
            </a>
          </div>

          <p class="mt-6 muted-small text-justify" style="max-width:680px;margin:auto;">
            Kehadiran dan doa restu Bapak/Ibu/Saudara/i akan menjadi kehormatan dan energi positif bagi kami untuk terus
            berinovasi dan berkontribusi bagi bangsa.
          </p>
        </div>
        <div class="nav-btns">
          <button class="btn-prev" onclick="prevSlide()">⬅️ Kembali</button>
          <button class="btn-next" onclick="nextSlide()">Lanjut ➜</button>
        </div>
      </section>

      <!-- Slide 4 -->
      <section class="slide bg-decor" id="slide-3">
        <div class="card pop-in mx-auto text-center" style="max-width:760px;padding:36px;background:transparent">
          <div class="logos mt-2 mb-4"><img src="logooo (1) (1).png" /><img src="logooo (2) (1).png" /></div>
          <h2 class="title-hero text-4xl mb-4">TERIMA KASIH</h2>
          <p class="muted-small text-lg mb-6">Kami berharap Bapak/Ibu dapat menghadiri acara istimewa ini</p>
          <p class="muted-small mb-4">Silakan isi formulir konfirmasi kehadiran melalui tautan di bawah ini:</p>
          <div class="mt-4">
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSetVjpdEXeyau6_AXkpjkfeacnjBqHqKsZKiMQKIXuy94bXyQ/viewform?usp=header"
              target="_blank" class="open-btn">Link Google Form</a>
          </div>
        </div>
        <div class="nav-btns" style="justify-content:start;">
          <button class="btn-prev" onclick="prevSlide()">⬅️ Kembali</button>
        </div>
      </section>

    </div>
  </div>

  <script>
    const SLIDE_COUNT = 4;
    const slidesEl = document.getElementById('slides');
    let current = 0;

    function goTo(index) {
      if (index < 0) index = 0;
      if (index >= SLIDE_COUNT) index = SLIDE_COUNT - 1;
      current = index;
      slidesEl.style.transform = `translateX(-${index * 100}%)`;
    }

    function nextSlide() {goTo(current + 1);}
    function prevSlide() {goTo(current - 1);}

    document.getElementById('openInvite').addEventListener('click', () => goTo(1));

    let startX = 0, dx = 0, dragging = false;
    const container = document.getElementById('app');
    container.addEventListener('touchstart', e => {startX = e.touches[0].clientX; dragging = true;});
    container.addEventListener('touchmove', e => {
      if (!dragging) return;
      dx = e.touches[0].clientX - startX;
      slidesEl.style.transform = `translateX(calc(-${current * 100}% + ${dx}px))`;
    });
    container.addEventListener('touchend', e => {
      dragging = false;
      if (Math.abs(dx) > 60) {if (dx < 0) goTo(current + 1); else goTo(current - 1);}
      else goTo(current);
      dx = 0;
    });

    goTo(0);
  </script>
</body>

</html>
