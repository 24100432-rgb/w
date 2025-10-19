-- index.html --
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Trang chủ — Dự án CSS</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a href="#main" class="skip-link">Chuyển đến nội dung chính</a>

  <header class="site-header">
    <div class="container">
      <a class="logo" href="index.html">Dự án CSS</a>
      <nav class="main-nav" aria-label="Chính">
        <ul>
          <li><a href="index.html">Trang chủ</a></li>
          <li><a href="gallery.html">Bộ sưu tập</a></li>
          <li><a href="about.html">Giới thiệu</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main" class="container">
    <h1>Chào mừng đến với Dự án CSS</h1>
    <p>Ví dụ trang web nhỏ minh họa các kỹ thuật CSS: skip link, accessible nav, flex, grid, box model, hover, nth-child, focus styling.</p>

    <section class="features">
      <article>
        <h2>Thiết kế đáp ứng</h2>
        <p>Sử dụng Flexbox và Grid để bố trí rõ ràng trên mọi màn hình.</p>
      </article>
      <article>
        <h2>Khả năng truy cập</h2>
        <p>Liên kết "Chuyển đến nội dung chính" chỉ hiện khi tập trung; điều hướng có thể dùng bàn phím.</p>
      </article>
    </section>

    <a class="cta" href="gallery.html">Xem bộ sưu tập ảnh</a>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 Dự án CSS — Đã xây dựng cho bài tập</p>
    </div>
  </footer>
</body>
</html>

-- gallery.html --
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Bộ sưu tập — Dự án CSS</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a href="#main" class="skip-link">Chuyển đến nội dung chính</a>

  <header class="site-header">
    <div class="container">
      <a class="logo" href="index.html">Dự án CSS</a>
      <nav class="main-nav" aria-label="Chính">
        <ul>
          <li><a href="index.html">Trang chủ</a></li>
          <li><a href="gallery.html">Bộ sưu tập</a></li>
          <li><a href="about.html">Giới thiệu</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main" class="container">
    <h1>Bộ sưu tập ảnh</h1>
    <p>Trang này chứa hơn 5 ảnh để đáp ứng yêu cầu bài tập.</p>

    <section class="photo-grid" aria-label="Bộ sưu tập hình ảnh">
      <figure class="photo"><img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=1200&q=80" alt="Phong cảnh núi"/><figcaption>Núi</figcaption></figure>
      <figure class="photo"><img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=1200&q=80" alt="Biển khi hoàng hôn"/><figcaption>Hoàng hôn biển</figcaption></figure>
      <figure class="photo"><img src="https://images.unsplash.com/photo-1495567720989-cebdbdd97913?w=1200&q=80" alt="Rừng xanh"/><figcaption>Rừng</figcaption></figure>
      <figure class="photo"><img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e?w=1200&q=80" alt="Thành phố về đêm"/><figcaption>Thành phố</figcaption></figure>
      <figure class="photo"><img src="https://images.unsplash.com/photo-1493244040629-496f6d136cc3?w=1200&q=80" alt="Cánh đồng hoa"/><figcaption>Hoa</figcaption></figure>
      <figure class="photo"><img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=1200&q=80" alt="Cầu cổ"/><figcaption>Cầu</figcaption></figure>
    </section>

    <p class="note">Mẹo: Dùng tab để điều hướng qua liên kết - skip link sẽ xuất hiện khi tập trung.</p>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 Dự án CSS</p>
    </div>
  </footer>
</body>
</html>

-- about.html --
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Giới thiệu — Dự án CSS</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a href="#main" class="skip-link">Chuyển đến nội dung chính</a>

  <header class="site-header">
    <div class="container">
      <a class="logo" href="index.html">Dự án CSS</a>
      <nav class="main-nav" aria-label="Chính">
        <ul>
          <li><a href="index.html">Trang chủ</a></li>
          <li><a href="gallery.html">Bộ sưu tập</a></li>
          <li><a href="about.html">Giới thiệu</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main" class="container">
    <h1>Giới thiệu dự án</h1>
    <p>Trang này mô tả các kỹ thuật đã áp dụng: semantic HTML, responsive layouts, accessible navigation, và kiểm tra W3C/WAVE.</p>

    <section class="tech-grid">
      <div class="card">
        <h3>Grid</h3>
        <p>Phần gallery dùng CSS Grid với nhiều cột.</p>
      </div>
      <div class="card">
        <h3>Flex</h3>
        <p>Điều hướng sử dụng flex để căn chỉnh và phân phối không gian.</p>
      </div>
      <div class="card">
        <h3>Box model</h3>
        <p>Tất cả hình ảnh có padding, border, và border-radius.</p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 Dự án CSS</p>
    </div>
  </footer>
</body>
</html>

-- styles.css --
/* Reset cơ bản */
*{box-sizing:border-box}
html,body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;line-height:1.4;color:#222}
.container{max-width:1000px;margin:0 auto;padding:1rem}

/* Skip link: chỉ hiển thị khi được tập trung */
.skip-link{position:absolute;left:0;top:0;background:#000;color:#fff;padding:.5rem .75rem;transform:translateY(-120%);transition:transform .18s ease;z-index:999}
.skip-link:focus, .skip-link:focus-visible{transform:translateY(0%);outline:3px solid #ff0;color:#000;background:#fff}

/* Header + nav (flex) */
.site-header{background:linear-gradient(90deg,#0f172a,#1e293b);color:#fff}
.site-header .container{display:flex;align-items:center;justify-content:space-between}
.logo{font-weight:700;color:#fff;text-decoration:none;padding:.5rem 0}
.main-nav ul{display:flex;gap:1rem;list-style:none;margin:0;padding:0}
.main-nav a{color:#cbd5e1;text-decoration:none;padding:.5rem 0.75rem;border-radius:8px;display:inline-block}
/* hover hấp dẫn */
.main-nav a:hover{transform:translateY(-3px) scale(1.02);text-decoration:underline;transition:transform .15s ease}
/* focus rõ ràng cho điều hướng */
.main-nav a:focus{outline:3px solid #facc15}

/* Hero + cta */
main h1{font-size:2rem;margin-top:.5rem}
.cta{display:inline-block;margin-top:1rem;padding:.6rem 1rem;background:#ef4444;color:#fff;border-radius:8px;text-decoration:none}
.cta:hover{transform:scale(1.03)}

/* Features (flex) */
.features{display:flex;gap:1rem;margin-top:1rem}
.features article{flex:1;padding:1rem;background:#f8fafc;border-radius:10px}

/* Photo grid (CSS Grid) */
.photo-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1rem;margin-top:1rem}
.photo{background:#fff;padding:.5rem;border-radius:12px;border:4px solid #e2e8f0;display:flex;flex-direction:column;align-items:center}
.photo img{width:100%;height:200px;object-fit:cover;padding:8px;border-radius:8px;border:4px solid #cbd5e1}
.photo figcaption{margin-top:.5rem}

/* Box model demo for all images */
img{border-radius:6px;padding:6px;border:3px solid #ddd}

/* nth-child: mọi ảnh chẵn có border-radius khác */
.photo:nth-child(2n) img{border-radius:24px}

/* Hover effect trên thẻ photo toàn bộ */
.photo:hover{transform:translateY(-6px) rotate(-.5deg);box-shadow:0 12px 24px rgba(0,0,0,.12);transition:transform .25s ease, box-shadow .25s ease}

/* About cards grid */
.tech-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem}
.card{background:#fff;padding:1rem;border-radius:10px;border:2px solid #e6eef8}

/* Footer */
.site-footer{background:#0b1220;color:#98a8c7;padding:1rem 0;margin-top:2rem}

/* Responsive tweaks */
@media (max-width:700px){
  .features{flex-direction:column}
  .site-header .container{padding:.5rem}
}

/* Small accessibility helper */
.note{font-size:.9rem;color:#334155}

/* Make focus visible for any interactive element */
:focus{outline-offset:3px}
