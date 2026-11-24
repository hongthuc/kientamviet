<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT | Cửa Nhôm Xingfa Đà Nẵng - kientamviet.com</title>
  <meta name="description" content="CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT chuyên thiết kế, gia công và thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Hotline: 0932.456.012." />

  <!-- Thẻ Open Graph & Thumbnail khi chia sẻ link trang web (lấy ảnh logo công ty) -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://kientamviet.com/" />
  <meta property="og:title" content="CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT - Cửa Nhôm Kính Đà Nẵng" />
  <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa chính hãng, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0932.456.012" />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w1000" />
  <meta property="og:image:width" content="1000" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="KIẾN TÂM VIỆT - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta name="twitter:description" content="11 Đồng Bài 1, Phường Liên Chiểu, TP Đà Nẵng - Hotline: 0932.456.012" />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w1000" />
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w256" />

  <!-- Font chữ Inter chuẩn giao diện hiện đại & Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    /* Cấu hình bảng màu chủ đạo đồng bộ nhận diện thương hiệu & logo Kiến Tâm Việt */
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              DEFAULT: '#0A4D8C',
              dark: '#073766',
              light: '#1668B8',
              soft: '#EEF5FC',
            },
            accent: {
              DEFAULT: '#D97706',
              dark: '#B45309',
              light: '#F59E0B',
            },
          },
        },
      },
    };
  </script>

  <style>
    /* Cố định chống tràn viền ngang và lệch trang trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      scroll-behavior: smooth;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
    }

    /* Chiều ngang khung giao diện trên máy tính bằng 95% kích thước màn hình */
    .ktv-container {
      width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 640px) {
      .ktv-container {
        padding-left: 16px;
        padding-right: 16px;
      }
    }
    @media (min-width: 1024px) {
      .ktv-container {
        width: 95%;
        max-width: 1720px;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Dropdown menu mượt mà kiểu Flatsome */
    .nav-dropdown-parent:hover .nav-dropdown-menu,
    .nav-dropdown-parent:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    /* Đường gạch chân tiêu đề phong cách Flatsome UX Builder */
    .flatsome-title::after {
      content: '';
      display: block;
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, #0A4D8C, #D97706);
      margin: 10px auto 0;
      border-radius: 9999px;
    }

    /* Hiệu ứng chuyển mượt cho 2 banner đồng kích thước */
    .banner-slide {
      grid-area: 1 / 1 / 2 / 2;
      transition: opacity 0.65s ease, transform 0.65s ease;
    }
    .banner-slide.is-active {
      opacity: 1;
      transform: translateX(0);
      pointer-events: auto;
      z-index: 10;
    }
    .banner-slide.is-inactive {
      opacity: 0;
      transform: translateX(18px);
      pointer-events: none;
      z-index: 1;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes phonePulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.45); }
      50% { box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
    }
    .hotline-pulse {
      animation: phonePulse 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- PHẦN 1: TOP BAR THÔNG TIN DOANH NGHIỆP (Gọn sạch, chuẩn Flatsome)     -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
    <div class="ktv-container flex flex-wrap items-center justify-between gap-x-4 gap-y-1">
      <div class="flex items-center gap-1.5 min-w-0">
        <svg class="w-3.5 h-3.5 text-accent-light shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
        </svg>
        <span class="truncate">11 Đồng Bài 1, Phường Liên Chiểu, TP Đà Nẵng</span>
      </div>
      <div class="hidden sm:flex items-center gap-4 shrink-0 text-slate-200">
        <span class="flex items-center gap-1">
          <svg class="w-3.5 h-3.5 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
          </svg>
          Làm việc: 07:30 - 20:00 (T2 - CN)
        </span>
        <span class="text-white/30">|</span>
        <span class="font-medium text-white">kientamviet.com</span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- PHẦN 2: HEADER & MENU ĐIỀU HƯỚNG (Logo gọn, không nút gọi, 1 hàng)   -->
  <!-- ===================================================================== -->
  <header id="main-header" class="sticky top-0 z-40 bg-white/98 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="ktv-container">
      <div class="flex items-center justify-between gap-3 py-2.5">
        <!-- Logo công ty chỉnh gọn nhỏ -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Kiến Tâm Việt">
          <img
            src="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w500"
            data-drive-id="1PfYK86koYVW8G8ll7ju8ymXl1leaarwY"
            alt="Logo Công ty TNHH Đầu Tư Và Xây Dựng Kiến Tâm Việt"
            class="h-9 sm:h-10 lg:h-11 w-auto max-w-[130px] object-contain rounded"
            onerror="handleDriveImageError(this, 'KIẾN TÂM VIỆT')"
          />
          <div class="leading-tight hidden xl:block">
            <div class="text-xs font-extrabold text-brand tracking-tight uppercase whitespace-nowrap">KIẾN TÂM VIỆT</div>
            <div class="text-[10px] font-medium text-slate-500 whitespace-nowrap">Cửa Nhôm Kính Đà Nẵng</div>
          </div>
        </a>

        <!-- Menu trên máy tính: chữ gọn, viết liền không xuống dòng tên danh mục -->
        <nav class="hidden lg:flex items-center justify-end flex-1 min-w-0" aria-label="Menu chính">
          <ul class="flex flex-wrap items-center justify-end gap-x-1 xl:gap-x-2 gap-y-1 text-[12px] xl:text-[13px] font-semibold text-slate-700">
            <li class="shrink-0">
              <a href="#trang-chu" class="inline-block px-2 xl:px-2.5 py-2 rounded-md text-brand bg-brand-soft/70 hover:bg-brand-soft whitespace-nowrap transition">
                Trang chủ
              </a>
            </li>
            <li class="shrink-0">
              <a href="#gioi-thieu" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Giới thiệu
              </a>
            </li>

            <!-- Dropdown: Cửa nhôm xingfa -->
            <li class="relative shrink-0 nav-dropdown-parent">
              <a href="#san-pham" onclick="filterProducts('xingfa')" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                <span>Cửa nhôm xingfa</span>
                <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                </svg>
              </a>
              <ul class="nav-dropdown-menu absolute left-0 top-full mt-1 w-56 bg-white rounded-lg shadow-lg border border-slate-100 py-1.5 z-50">
                <li><a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
                <li><a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
                <li><a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
                <li><a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
                <li><a href="#san-pham" onclick="filterProducts('xingfa', 'xếp trượt')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
              </ul>
            </li>

            <li class="shrink-0">
              <a href="#san-pham" onclick="filterProducts('kinh-cuong-luc')" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Cửa kính cường lực
              </a>
            </li>

            <!-- Dropdown: Sản phẩm -->
            <li class="relative shrink-0 nav-dropdown-parent">
              <a href="#danh-muc" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                <span>Sản phẩm</span>
                <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                </svg>
              </a>
              <ul class="nav-dropdown-menu absolute left-0 top-full mt-1 w-52 bg-white rounded-lg shadow-lg border border-slate-100 py-1.5 z-50">
                <li><a href="#san-pham" onclick="filterProducts('xingfa')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhôm xingfa</a></li>
                <li><a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa nhựa lõi thép</a></li>
                <li><a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cửa kính tự động</a></li>
                <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Cầu thang kính</a></li>
                <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Kính ốp bếp</a></li>
                <li><a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand whitespace-nowrap">Phòng tắm kính</a></li>
              </ul>
            </li>

            <li class="shrink-0">
              <a href="#cong-trinh" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Công trình
              </a>
            </li>
            <li class="shrink-0">
              <a href="#bao-gia" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Báo giá
              </a>
            </li>
            <li class="shrink-0">
              <a href="#tin-tuc" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Tin tức
              </a>
            </li>
            <li class="shrink-0">
              <a href="#lien-he" class="inline-block px-2 xl:px-2.5 py-2 rounded-md hover:text-brand hover:bg-slate-50 whitespace-nowrap transition">
                Liên hệ
              </a>
            </li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại / máy tính bảng -->
        <button
          id="mobile-menu-btn"
          type="button"
          onclick="toggleMobileMenu()"
          class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition"
          aria-label="Mở menu danh mục"
          aria-expanded="false"
        >
          <svg id="menu-icon-open" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
          <svg id="menu-icon-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Menu xổ xuống tối ưu cho điện thoại -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 max-h-[80vh] overflow-y-auto shadow-lg">
      <div class="ktv-container py-3 space-y-1 text-sm font-semibold text-slate-700">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg bg-brand-soft/60 text-brand">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Giới thiệu</a>

        <!-- Mobile accordion: Cửa nhôm xingfa -->
        <div class="border border-slate-100 rounded-lg overflow-hidden">
          <button type="button" onclick="toggleSubmenu('mob-sub-xingfa')" class="w-full flex items-center justify-between px-3 py-2.5 text-left hover:bg-slate-50">
            <span>Cửa nhôm xingfa</span>
            <svg class="w-4 h-4 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
            </svg>
          </button>
          <div id="mob-sub-xingfa" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 text-xs font-medium text-slate-600">
            <a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa 1 cánh</a>
            <a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa 2 cánh</a>
            <a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa 3 cánh</a>
            <a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa 4 cánh</a>
            <a href="#san-pham" onclick="filterProducts('xingfa', 'xếp trượt'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa 5 cánh</a>
          </div>
        </div>

        <a href="#san-pham" onclick="filterProducts('kinh-cuong-luc'); closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Cửa kính cường lực</a>

        <!-- Mobile accordion: Sản phẩm -->
        <div class="border border-slate-100 rounded-lg overflow-hidden">
          <button type="button" onclick="toggleSubmenu('mob-sub-sanpham')" class="w-full flex items-center justify-between px-3 py-2.5 text-left hover:bg-slate-50">
            <span>Sản phẩm</span>
            <svg class="w-4 h-4 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
            </svg>
          </button>
          <div id="mob-sub-sanpham" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 text-xs font-medium text-slate-600">
            <a href="#san-pham" onclick="filterProducts('xingfa'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhôm xingfa</a>
            <a href="#san-pham" onclick="filterProducts('nhua-loi-thep'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa nhựa lõi thép</a>
            <a href="#san-pham" onclick="filterProducts('cua-tu-dong'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cửa kính tự động</a>
            <a href="#san-pham" onclick="filterProducts('cau-thang-kinh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Cầu thang kính</a>
            <a href="#san-pham" onclick="filterProducts('kinh-op-bep'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Kính ốp bếp</a>
            <a href="#san-pham" onclick="filterProducts('phong-tam-kinh'); closeMobileMenu()" class="block py-2 pl-2 border-l-2 border-brand/30 hover:text-brand">Phòng tắm kính</a>
          </div>
        </div>

        <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Công trình</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-slate-50">Liên hệ</a>
      </div>
    </div>
  </header>

  <!-- ===================================================================== -->
  <!-- PHẦN 3: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP ĐỒNG KÍCH THƯỚC              -->
  <!-- Chữ và ảnh nằm hoàn toàn bên trong, cách xa viền, không mất chữ       -->
  <!-- ===================================================================== -->
  <section id="trang-chu" class="py-3 sm:py-4 bg-slate-50">
    <div class="ktv-container">
      <div
        id="hero-slider"
        class="relative w-full rounded-xl overflow-hidden shadow-md bg-brand-dark select-none"
        onmouseenter="pauseSlider()"
        onmouseleave="resumeSlider()"
      >
        <!-- Khung Grid đồng bộ kích thước: 2 slide luôn có chiều cao & chiều rộng bằng nhau tuyệt đối -->
        <div class="grid grid-cols-1 w-full">

          <!-- BANNER 1 -->
          <div class="banner-slide is-active relative w-full bg-gradient-to-br from-brand-dark via-brand to-[#1363B0]" data-slide="0">
            <div class="w-full h-full px-10 py-8 sm:px-14 sm:py-10 md:px-16 md:py-12 lg:px-20 lg:py-14 flex items-center">
              <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                <!-- Khối nội dung chữ cách xa viền banner -->
                <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-amber-300">
                    CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT
                  </p>
                  <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                    CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG TẠI ĐÀ NẴNG
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed">
                    Thiết kế, gia công và lắp đặt đồng bộ phụ kiện Kinlong. Cách âm, cách nhiệt, chịu lực gió bão vượt trội cho nhà phố, biệt thự và khách sạn Miền Trung.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3">
                    <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-5 py-2.5 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold shadow transition">
                      Nhận báo giá ngay
                    </a>
                    <a href="#san-pham" class="inline-flex items-center justify-center px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                      Xem sản phẩm
                    </a>
                  </div>
                </div>
                <!-- Khối ảnh sản phẩm nằm gọn trong banner -->
                <div class="md:col-span-5">
                  <div class="w-full aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-lg bg-white/10">
                    <img
                      src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w1000"
                      data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                      alt="Thi công cửa nhôm Xingfa chính hãng Kiến Tâm Việt"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImageError(this, 'Cửa Nhôm Xingfa Đà Nẵng')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="banner-slide is-inactive relative w-full bg-gradient-to-br from-[#0B355C] via-[#0A4D8C] to-[#0E5D9E]" data-slide="1">
            <div class="w-full h-full px-10 py-8 sm:px-14 sm:py-10 md:px-16 md:py-12 lg:px-20 lg:py-14 flex items-center">
              <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                <!-- Khối nội dung chữ cách xa viền banner -->
                <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-amber-300">
                    NHÀ THẦU NHÔM KÍNH UY TÍN MIỀN TRUNG
                  </p>
                  <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                    GIẢI PHÁP CỬA KÍNH CƯỜNG LỰC &amp; CÔNG TRÌNH CAO CẤP
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed">
                    Chuyên thi công Cửa kính tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính và hệ mặt dựng cho khách sạn, resort 4 sao với giá xuất xưởng cạnh tranh.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3">
                    <a href="#cong-trinh" class="inline-flex items-center justify-center px-4 sm:px-5 py-2.5 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold shadow transition">
                      Xem công trình tiêu biểu
                    </a>
                    <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                      Bảng giá tham khảo
                    </a>
                  </div>
                </div>
                <!-- Khối ảnh dự án nằm gọn trong banner -->
                <div class="md:col-span-5">
                  <div class="w-full aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-lg bg-white/10">
                    <img
                      src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                      data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                      alt="Dự án nhôm kính cao cấp Đà Nẵng - Kiến Tâm Việt"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImageError(this, 'Dự Án Nhôm Kính Đà Nẵng')"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển slide trái / phải (nhỏ gọn sát mép, không đè chữ) -->
        <button
          type="button"
          onclick="prevSlide()"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/25 hover:bg-black/45 text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M15 19l-7-7 7-7"/>
          </svg>
        </button>
        <button
          type="button"
          onclick="nextSlide()"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/25 hover:bg-black/45 text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M9 5l7 7-7 7"/>
          </svg>
        </button>

        <!-- Chấm chỉ báo vị trí banner -->
        <div class="absolute bottom-2.5 sm:bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Banner 2" class="w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 4: GIỚI THIỆU CÔNG TY & CON SỐ ẤN TƯỢNG (Mẫu Flatsome)          -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
    <div class="ktv-container">
      <div class="text-center max-w-4xl mx-auto mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT
        </h2>
        <p class="mt-4 text-xs sm:text-sm md:text-[15px] text-slate-600 leading-relaxed">
          <strong>Kiến Tâm Việt</strong> là đơn vị chuyên thiết kế, gia công và thi công lắp đặt các hạng mục nhôm kính hàng đầu tại Đà Nẵng và khu vực Miền Trung. Với dây chuyền máy móc hiện đại và đội ngũ kỹ thuật lành nghề, chúng tôi cung cấp các dòng sản phẩm chính hãng: <strong>Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính</strong>. Phương châm của chúng tôi là <em>“Uy tín – Chất lượng – Thẩm mỹ – Bền vững cho mọi công trình”</em>.
        </p>
      </div>

      <!-- 4 chỉ số năng lực (cấu trúc 4 cột UX Builder dễ dựng lại) -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-brand-soft/60 border border-brand/10 rounded-xl p-4 sm:p-5 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand">150+</div>
          <div class="mt-1 text-xs sm:text-sm font-semibold text-slate-700">Dự án đã hoàn thành</div>
        </div>
        <div class="bg-brand-soft/60 border border-brand/10 rounded-xl p-4 sm:p-5 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand">50+</div>
          <div class="mt-1 text-xs sm:text-sm font-semibold text-slate-700">Kỹ thuật viên kinh nghiệm</div>
        </div>
        <div class="bg-brand-soft/60 border border-brand/10 rounded-xl p-4 sm:p-5 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand">100+</div>
          <div class="mt-1 text-xs sm:text-sm font-semibold text-slate-700">Mẫu cửa nhôm kính đẹp</div>
        </div>
        <div class="bg-brand-soft/60 border border-brand/10 rounded-xl p-4 sm:p-5 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-accent">100%</div>
          <div class="mt-1 text-xs sm:text-sm font-semibold text-slate-700">Khách hàng hài lòng</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 5: DANH MỤC SẢN PHẨM NỔI BẬT (6 danh mục web mẫu, chữ gọn đẹp)  -->
  <!-- ===================================================================== -->
  <section id="danh-muc" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-100">
    <div class="ktv-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          DANH MỤC SẢN PHẨM NỔI BẬT
        </h2>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên tablet, 6 cột trên máy tính -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Danh mục 1: Cửa nhôm Xingfa -->
        <a href="#san-pham" onclick="filterProducts('xingfa')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w800"
              data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
              alt="Cửa nhôm Xingfa Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Cửa Nhôm Xingfa')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa Nhôm Xingfa
            </h3>
          </div>
        </a>

        <!-- Danh mục 2: Cửa nhựa lõi thép -->
        <a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&sz=w800"
              data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
              alt="Cửa nhựa lõi thép Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Cửa Nhựa Lõi Thép')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa Nhựa Lõi Thép
            </h3>
          </div>
        </a>

        <!-- Danh mục 3: Cửa kính tự động -->
        <a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&sz=w800"
              data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
              alt="Cửa kính tự động Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Cửa Kính Tự Động')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cửa Kính Tự Động
            </h3>
          </div>
        </a>

        <!-- Danh mục 4: Cầu thang kính -->
        <a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&sz=w800"
              data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
              alt="Cầu thang kính cường lực Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Cầu Thang Kính')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Cầu Thang Kính
            </h3>
          </div>
        </a>

        <!-- Danh mục 5: Kính ốp bếp -->
        <a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w800"
              data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
              alt="Kính ốp bếp đẹp Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Kính Ốp Bếp')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Kính Ốp Bếp
            </h3>
          </div>
        </a>

        <!-- Danh mục 6: Phòng tắm kính -->
        <a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w800"
              data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
              alt="Phòng tắm kính cường lực Đà Nẵng"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Phòng Tắm Kính')"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-snug">
              Phòng Tắm Kính
            </h3>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 6: SẢN PHẨM NỔI BẬT (2 cột mobile, giá & % giảm góc trên trái)  -->
  <!-- ===================================================================== -->
  <section id="san-pham" class="py-10 sm:py-14 bg-white">
    <div class="ktv-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          BÁO GIÁ CỬA NHÔM XINGFA &amp; SẢN PHẨM NỔI BẬT
        </h2>
      </div>

      <!-- Bộ lọc danh mục sản phẩm gọn gàng, tối ưu cả điện thoại & máy tính -->
      <div id="product-filter-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
        <button type="button" onclick="filterProducts('all')" data-cat="all" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand text-white transition whitespace-nowrap">
          Tất cả
        </button>
        <button type="button" onclick="filterProducts('xingfa')" data-cat="xingfa" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Cửa nhôm Xingfa
        </button>
        <button type="button" onclick="filterProducts('kinh-cuong-luc')" data-cat="kinh-cuong-luc" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Cửa kính cường lực
        </button>
        <button type="button" onclick="filterProducts('nhua-loi-thep')" data-cat="nhua-loi-thep" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Cửa nhựa lõi thép
        </button>
        <button type="button" onclick="filterProducts('cua-tu-dong')" data-cat="cua-tu-dong" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Cửa kính tự động
        </button>
        <button type="button" onclick="filterProducts('cau-thang-kinh')" data-cat="cau-thang-kinh" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Cầu thang kính
        </button>
        <button type="button" onclick="filterProducts('kinh-op-bep')" data-cat="kinh-op-bep" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Kính ốp bếp
        </button>
        <button type="button" onclick="filterProducts('phong-tam-kinh')" data-cat="phong-tam-kinh" class="product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap">
          Phòng tắm kính
        </button>
      </div>

      <!-- Lưới sản phẩm: 2 cột chuẩn trên điện thoại, 3-4 cột trên máy tính -->
      <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Dữ liệu sản phẩm được render tự động từ JS bên dưới -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 7: BẢNG BÁO GIÁ THAM KHẢO CỬA NHÔM XINGFA ĐÀ NẴNG               -->
  <!-- ===================================================================== -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-100">
    <div class="ktv-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          BẢNG BÁO GIÁ THI CÔNG NHÔM KÍNH TẠI ĐÀ NẴNG
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600">
          Nhôm Xingfa nhập khẩu tem đỏ Quảng Đông chính hãng – Phụ kiện Kinlong đồng bộ – Miễn phí khảo sát và lắp đặt nội thành Đà Nẵng.
        </p>
      </div>

      <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
        <div class="w-full overflow-x-auto">
          <table class="w-full text-left border-collapse min-w-[540px]">
            <thead>
              <tr class="bg-brand text-white text-xs sm:text-sm">
                <th class="py-3 px-4 font-bold w-12 text-center">STT</th>
                <th class="py-3 px-4 font-bold">Hạng mục hệ cửa &amp; kính</th>
                <th class="py-3 px-4 font-bold">Hệ nhôm / Quy cách</th>
                <th class="py-3 px-4 font-bold text-right">Đơn giá (VNĐ/m²)</th>
              </tr>
            </thead>
            <tbody class="divide-y divide-slate-100 text-xs sm:text-sm text-slate-700">
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">1</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Cửa sổ mở quay / mở hất nhôm Xingfa</td>
                <td class="py-3 px-4">Hệ 55 dày 1.4mm, kính an toàn 6.38mm</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">1.950.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">2</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Cửa đi mở quay 1 cánh – 2 cánh nhôm Xingfa</td>
                <td class="py-3 px-4">Hệ 55 dày 2.0mm, kính cường lực 8mm</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">3</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Cửa đi mở quay 3 cánh – 4 cánh nhôm Xingfa</td>
                <td class="py-3 px-4">Hệ 55 dày 2.0mm, phụ kiện Kinlong</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">4</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Cửa đi xếp trượt nhôm Xingfa (4 – 6 cánh)</td>
                <td class="py-3 px-4">Hệ 63 / 93 dày 2.0mm – 2.5mm</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">5</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Cửa kính cường lực &amp; Phòng tắm kính</td>
                <td class="py-3 px-4">Kính cường lực 10mm – 12mm, phụ kiện Inox 304</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">850.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-soft/40">
                <td class="py-3 px-4 text-center font-semibold">6</td>
                <td class="py-3 px-4 font-semibold text-slate-900">Kính màu ốp bếp cường lực 8mm</td>
                <td class="py-3 px-4">Kính Hải Long / Chu Lai sơn nhiệt cao cấp</td>
                <td class="py-3 px-4 text-right font-bold text-accent-dark">750.000 ₫/md</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 8: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 dự án từ Google Drive)    -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="py-10 sm:py-14 bg-white">
    <div class="ktv-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600">
          Những công trình khách sạn, resort và nhà phố nổi bật được Kiến Tâm Việt đồng hành thiết kế &amp; thi công hạng mục nhôm kính.
        </p>
      </div>

      <div id="project-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6">
        <!-- Render danh sách 6 dự án Đà Nẵng từ JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 9: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY TRANG CHỦ                 -->
  <!-- ===================================================================== -->
  <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-dark text-white">
    <div class="ktv-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <!-- Thông tin cam kết dịch vụ -->
        <div class="lg:col-span-5 space-y-4">
          <h2 class="text-xl sm:text-2xl font-extrabold uppercase leading-snug">
            ĐĂNG KÝ NHẬN BÁO GIÁ &amp; KHẢO SÁT MIỄN PHÍ
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Để lại thông tin công trình của quý khách, đội ngũ kỹ sư <strong>Kiến Tâm Việt</strong> sẽ liên hệ tư vấn phương án cửa nhôm kính tối ưu chi phí và gửi bảng dự toán chi tiết trong vòng 15 phút.
          </p>
          <ul class="space-y-2.5 text-xs sm:text-sm text-slate-100">
            <li class="flex items-start gap-2.5">
              <svg class="w-5 h-5 text-amber-400 shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
              </svg>
              <span>Đo đạc, khảo sát và tư vấn mẫu nhôm tận công trình hoàn toàn miễn phí.</span>
            </li>
            <li class="flex items-start gap-2.5">
              <svg class="w-5 h-5 text-amber-400 shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
              </svg>
              <span>Cam kết nhôm Xingfa chính hãng, phụ kiện đồng bộ, bảo hành dài hạn.</span>
            </li>
            <li class="flex items-start gap-2.5">
              <svg class="w-5 h-5 text-amber-400 shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
              </svg>
              <span>Hotline tư vấn trực tiếp: <a href="tel:0932456012" class="font-bold text-amber-300 underline">0932.456.012</a></span>
            </li>
          </ul>
        </div>

        <!-- Form nhập liệu sạch đẹp -->
        <div class="lg:col-span-7">
          <form id="quote-form" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-name" class="block text-xs font-bold text-slate-700 mb-1.5">Họ và tên *</label>
                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/20" />
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-bold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                <input id="q-phone" type="tel" required placeholder="VD: 0932.456.012" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/20" />
              </div>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-service" class="block text-xs font-bold text-slate-700 mb-1.5">Hạng mục quan tâm</label>
                <select id="q-service" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/20">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1 - 5 cánh, xếp trượt)</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                </select>
              </div>
              <div>
                <label for="q-address" class="block text-xs font-bold text-slate-700 mb-1.5">Địa điểm công trình</label>
                <input id="q-address" type="text" placeholder="Quận/Huyện tại Đà Nẵng hoặc tỉnh lân cận" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/20" />
              </div>
            </div>
            <div>
              <label for="q-note" class="block text-xs font-bold text-slate-700 mb-1.5">Yêu cầu chi tiết (kích thước dự kiến, số lượng bộ cửa...)</label>
              <textarea id="q-note" rows="3" placeholder="Nhập mô tả nhu cầu của quý khách..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/20"></textarea>
            </div>
            <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-accent hover:bg-accent-dark text-white text-sm font-bold shadow transition">
              Gửi yêu cầu báo giá ngay
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 10: DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ           -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="py-10 sm:py-14 bg-slate-50 border-b border-slate-100">
    <div class="ktv-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH
        </h2>
      </div>

      <!-- Danh mục bài viết trang chủ -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
        <button type="button" onclick="filterArticles('all')" data-art="all" class="article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand text-white transition whitespace-nowrap">
          Tất cả bài viết
        </button>
        <button type="button" onclick="filterArticles('kien-thuc')" data-art="kien-thuc" class="article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white border border-slate-200 text-slate-700 hover:text-brand transition whitespace-nowrap">
          Kiến thức nhôm Xingfa
        </button>
        <button type="button" onclick="filterArticles('tu-van')" data-art="tu-van" class="article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white border border-slate-200 text-slate-700 hover:text-brand transition whitespace-nowrap">
          Tư vấn lựa chọn cửa
        </button>
        <button type="button" onclick="filterArticles('kinh-nghiem')" data-art="kinh-nghiem" class="article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white border border-slate-200 text-slate-700 hover:text-brand transition whitespace-nowrap">
          Kinh nghiệm thi công
        </button>
      </div>

      <div id="article-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Render danh sách bài viết từ JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 11: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ    -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="py-10 sm:py-14 bg-white">
    <div class="ktv-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE FACEBOOK
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột trái: Google Map trực tiếp địa chỉ công ty -->
        <div class="lg:col-span-7 flex flex-col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="px-4 py-3 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div>
              <h3 class="text-sm font-bold text-brand uppercase">Bản đồ Google Maps – Kiến Tâm Việt</h3>
              <p class="text-xs text-slate-600">11 Đồng Bài 1, Phường Liên Chiểu, TP Đà Nẵng</p>
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=11+%C4%90%E1%BB%93ng+B%C3%A0i+1,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="text-xs font-semibold text-brand hover:text-accent underline whitespace-nowrap"
            >
              Mở Google Maps →
            </a>
          </div>
          <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Công ty TNHH Đầu Tư Và Xây Dựng Kiến Tâm Việt"
              src="https://maps.google.com/maps?q=11%20%C4%90%E1%BB%93ng%20B%C3%A0i%201,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen
            ></iframe>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook chính thức -->
        <div class="lg:col-span-5 flex flex-col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="px-4 py-3 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
            <div>
              <h3 class="text-sm font-bold text-brand uppercase">Fanpage Facebook Chính Thức</h3>
              <p class="text-xs text-slate-600">Cửa Nhôm Kính Miền Trung – Kiến Tâm Việt</p>
            </div>
            <a
              href="https://www.facebook.com/cuanhomkinhmientrung"
              target="_blank"
              rel="noopener noreferrer"
              class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-[#1665D8] text-white text-xs font-semibold whitespace-nowrap transition"
            >
              Theo dõi trang
            </a>
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between gap-3">
            <!-- Nhúng plugin Fanpage Facebook -->
            <div class="w-full rounded-lg overflow-hidden bg-white border border-slate-200 min-h-[260px] flex items-center justify-center">
              <iframe
                title="Fanpage Facebook Cửa Nhôm Kính Miền Trung - Kiến Tâm Việt"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fcuanhomkinhmientrung&tabs=timeline&width=500&height=280&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                class="w-full h-[280px] border-0 overflow-hidden"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
            <!-- Liên kết nhanh dự phòng đẹp mắt -->
            <div class="flex items-center justify-between gap-3 bg-white rounded-lg p-3 border border-slate-200">
              <div class="flex items-center gap-2.5 min-w-0">
                <img
                  src="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w200"
                  data-drive-id="1PfYK86koYVW8G8ll7ju8ymXl1leaarwY"
                  alt="Fanpage Kiến Tâm Việt"
                  class="w-10 h-10 rounded-lg object-contain border border-slate-200 p-1 bg-white shrink-0"
                  onerror="handleDriveImageError(this, 'KTV')"
                />
                <div class="min-w-0">
                  <div class="text-xs font-bold text-slate-800 truncate">facebook.com/cuanhomkinhmientrung</div>
                  <div class="text-[11px] text-slate-500">Cập nhật hình ảnh thi công thực tế mỗi ngày</div>
                </div>
              </div>
              <a
                href="https://www.facebook.com/cuanhomkinhmientrung"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-bold text-[#1877F2] hover:underline shrink-0"
              >
                Xem ngay
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 12: ĐỐI TÁC CỦA CHÚNG TÔI (6 ảnh logo đối tác từ Google Drive)  -->
  <!-- ===================================================================== -->
  <section class="py-10 bg-slate-50 border-t border-slate-200">
    <div class="ktv-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand uppercase">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w500" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác Kiến Tâm Việt 1" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 1')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w500" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác Kiến Tâm Việt 2" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 2')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w500" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác Kiến Tâm Việt 3" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 3')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w500" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác Kiến Tâm Việt 4" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 4')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w500" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác Kiến Tâm Việt 5" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 5')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand/40 transition">
          <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w500" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác Kiến Tâm Việt 6" class="max-h-full max-w-full object-contain" onerror="handleDriveImageError(this, 'Đối tác 6')" />
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- PHẦN 13: FOOTER 4 CỘT CHUẨN FLATSOME                                  -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6 border-t-4 border-accent">
    <div class="ktv-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="inline-block bg-white rounded-lg px-3 py-1.5">
            <img
              src="https://drive.google.com/thumbnail?id=1PfYK86koYVW8G8ll7ju8ymXl1leaarwY&sz=w400"
              data-drive-id="1PfYK86koYVW8G8ll7ju8ymXl1leaarwY"
              alt="Logo Kiến Tâm Việt"
              class="h-9 w-auto object-contain"
              onerror="handleDriveImageError(this, 'KIẾN TÂM VIỆT')"
            />
          </div>
          <h3 class="text-sm font-extrabold text-white uppercase leading-snug">
            CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT
          </h3>
          <ul class="space-y-1.5 text-xs text-slate-300 leading-relaxed">
            <li><strong class="text-white">Địa chỉ:</strong> 11 Đồng Bài 1, Phường Liên Chiểu, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0932456012" class="text-amber-300 font-bold hover:underline">0932.456.012</a></li>
            <li><strong class="text-white">Website:</strong> <a href="https://kientamviet.com" class="hover:text-white underline">kientamviet.com</a></li>
            <li><strong class="text-white">Fanpage:</strong> <a href="https://www.facebook.com/cuanhomkinhmientrung" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">Cửa Nhôm Kính Miền Trung</a></li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa 1 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa 2 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa 3 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa 4 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', 'xếp trượt')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa 5 cánh / xếp trượt</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', 'mở hất')" class="hover:text-amber-300 transition">• Cửa sổ mở hất nhôm Xingfa</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm & dịch vụ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Danh Mục Dịch Vụ
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham" onclick="filterProducts('xingfa')" class="hover:text-amber-300 transition">• Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="hover:text-amber-300 transition">• Cửa nhựa lõi thép Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="hover:text-amber-300 transition">• Cửa kính tự động Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="hover:text-amber-300 transition">• Cầu thang kính Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="hover:text-amber-300 transition">• Kính ốp bếp Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="hover:text-amber-300 transition">• Phòng tắm kính Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh & Hỗ trợ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">• Giới thiệu Kiến Tâm Việt</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">• Dự án đã thi công tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">• Bảng báo giá thi công mới nhất</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">• Đăng ký khảo sát đo đạc miễn phí</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">• Tin tức &amp; kinh nghiệm chọn cửa</a></li>
          </ul>
        </div>
      </div>

      <!-- Bản quyền chân trang -->
      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <div>Copyright 2026 © <strong class="text-white">CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT</strong></div>
        <div>Website: <strong class="text-slate-200">kientamviet.com</strong> | Hotline: <strong class="text-amber-300">0932.456.012</strong></div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO - FACEBOOK - HOTLINE (Mobile & PC)     -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/cuanhomkinhmientrung"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Facebook Kiến Tâm Việt"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464CC] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24">
        <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0932456012"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo 0932.456.012"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline -->
    <a
      href="tel:0932456012"
      aria-label="Gọi Hotline 0932.456.012"
      class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-extrabold pr-1 whitespace-nowrap">0932.456.012</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT                       -->
  <!-- ===================================================================== -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/60 p-3 sm:p-5" onclick="closeModalOnBackdrop(event)">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
      <div class="sticky top-0 bg-white border-b border-slate-100 px-5 py-3.5 flex items-center justify-between gap-3">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand leading-snug"></h3>
        <button type="button" onclick="closeModal()" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100 hover:text-slate-800 transition" aria-label="Đóng">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>
      </div>
      <div id="modal-body" class="p-5 space-y-4 text-sm text-slate-700"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- THÔNG BÁO TOAST (Thay thế hoàn toàn alert())                          -->
  <!-- ===================================================================== -->
  <div id="toast-box" class="fixed top-20 right-4 z-50 hidden max-w-sm bg-brand-dark text-white px-4 py-3 rounded-xl shadow-xl border border-amber-400/40 text-xs sm:text-sm font-medium"></div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT XỬ LÝ DỮ LIỆU, SLIDER, BỘ LỌC & TƯƠNG TÁC                 -->
  <!-- ===================================================================== -->
  <script>
    /* Hàm xử lý dự phòng ảnh Google Drive: thử chuyển sang lh3 trước khi dùng ảnh placeholder */
    function handleDriveImageError(imgEl, labelText) {
      try {
        const driveId = imgEl.getAttribute('data-drive-id');
        const step = Number(imgEl.getAttribute('data-fallback-step') || '0');
        if (driveId && step === 0) {
          imgEl.setAttribute('data-fallback-step', '1');
          imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId;
          return;
        }
        if (step < 2) {
          imgEl.setAttribute('data-fallback-step', '2');
          const safeText = encodeURIComponent(labelText || 'Kiến Tâm Việt');
          imgEl.src = 'https://placehold.co/800x600/0A4D8C/FFFFFF?text=' + safeText;
        }
      } catch (err) {
        console.error('Lỗi tải ảnh dự phòng:', err);
      }
    }

    /* Dữ liệu toàn bộ sản phẩm kèm ảnh thực tế từ Google Drive, giá gốc, giá giảm & % giảm */
    const PRODUCTS = [
      {
        id: 1,
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: 'xingfa',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.350.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-11%',
        specs: [
          'Thanh nhôm: Profile Xingfa hệ 55 nhập khẩu chính hãng tem đỏ',
          'Độ dày nhôm: 2.0mm (+-5%), sơn tĩnh điện cao cấp ngoài trời',
          'Kính sử dụng: Kính an toàn 6.38mm hoặc kính cường lực 8mm – 10mm',
          'Phụ kiện: Kinlong đồng bộ nhập khẩu, gioăng EPDM kín khít tuyệt đối',
          'Bảo hành: 5 năm thanh nhôm, 2 năm phụ kiện'
        ]
      },
      {
        id: 2,
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: 'xingfa',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.450.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-14%',
        specs: [
          'Thanh nhôm: Profile Xingfa hệ 55 nhập khẩu Quảng Đông',
          'Độ dày nhôm: 2.0mm, màu nâu sần, đen tuyền, trắng sứ, xám ghi, vân gỗ',
          'Kính sử dụng: Kính cường lực 8mm – 10mm hoặc kính hộp cách âm',
          'Phụ kiện: Bản lề 3D, khóa đa điểm Kinlong chính hãng',
          'Ứng dụng: Cửa chính, cửa ban công, cửa thông phòng sang trọng'
        ]
      },
      {
        id: 3,
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: 'xingfa',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.500.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-16%',
        specs: [
          'Thanh nhôm: Nhôm Xingfa hệ 55 nhập khẩu tem đỏ chính hãng',
          'Độ dày: 2.0mm kết cấu khoang trống có đường gân gia cường',
          'Keo sử dụng: Keo ép góc PU88 & keo Dow Corning chịu nước tuyệt đối',
          'Phụ kiện: Kinlong đồng bộ, ốc vít Inox 304 chống han gỉ vùng biển Đà Nẵng'
        ]
      },
      {
        id: 4,
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: 'xingfa',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.550.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-18%',
        specs: [
          'Thanh nhôm: Profile Xingfa hệ 55 dày 2.0mm chịu áp lực gió lên đến 1600 Pascal',
          'Thiết kế mở quay 4 cánh tối ưu không gian mặt tiền nhà phố & biệt thự',
          'Kính sử dụng: Kính cường lực 8mm – 12mm an toàn tuyệt đối',
          'Phụ kiện: Bộ khóa đa điểm, chốt âm và bản lề 3D Kinlong chính hãng'
        ]
      },
      {
        id: 5,
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xingfa',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.600.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-19%',
        specs: [
          'Thanh nhôm: Profile Xingfa hệ 63 / 93 nhập khẩu dày 1.8mm – 2.5mm',
          'Tùy chọn từ 4 cánh, 5 cánh đến 8 cánh xếp gọn sang một bên',
          'Hệ ray treo, bánh xe chống nhấc, vận hành êm ái không rung lắc',
          'Phù hợp cho khách sạn, resort, biệt thự sân vườn mở rộng tối đa tầm nhìn'
        ]
      },
      {
        id: 6,
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'xingfa',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.300.000 ₫',
        salePrice: '1.950.000 ₫',
        discount: '-15%',
        specs: [
          'Thanh nhôm: Profile Xingfa hệ 55 dày 1.4mm chính hãng',
          'Góc mở tối đa 45 độ, chống hắt mưa hiệu quả cho khí hậu Miền Trung',
          'Thanh định vị giữ góc mở chắc chắn, tránh nguy cơ gió dập',
          'Gioăng kép EPDM kín khít giúp tiết kiệm điện năng điều hòa'
        ]
      },
      {
        id: 7,
        name: 'Cửa nhựa lõi thép uPVC cao cấp cách âm',
        category: 'nhua-loi-thep',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        oldPrice: '2.100.000 ₫',
        salePrice: '1.800.000 ₫',
        discount: '-14%',
        specs: [
          'Thanh nhựa uPVC Sparlee / Rehau có lõi thép gia cường mạ kẽm',
          'Khả năng cách âm, cách nhiệt vượt trội, không cong vênh mối mọt',
          'Phụ kiện kim khí GQ / Roto đồng bộ, bền bỉ theo thời gian'
        ]
      },
      {
        id: 8,
        name: 'Cửa kính cường lực tự động Hàn Quốc',
        category: 'cua-tu-dong',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        oldPrice: '24.500.000 ₫',
        salePrice: '21.000.000 ₫',
        discount: '-14%',
        specs: [
          'Động cơ trượt tự động nhập khẩu Hàn Quốc / Nhật Bản vận hành êm',
          'Mắt thần cảm biến hồng ngoại siêu nhạy, tự đảo chiều khi gặp vật cản',
          'Kết hợp kính cường lực 10mm – 12mm an toàn cho showroom, khách sạn, văn phòng'
        ]
      },
      {
        id: 9,
        name: 'Cầu thang kính cường lực tay vịn gỗ',
        category: 'cau-thang-kinh',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        oldPrice: '1.550.000 ₫',
        salePrice: '1.350.000 ₫',
        discount: '-13%',
        specs: [
          'Kính cường lực dày 10mm – 12mm trong suốt mở rộng không gian nhà phố',
          'Trụ Inox 304 đặc chống gỉ kết hợp tay vịn gỗ lim Nam Phi cao cấp',
          'Thi công chuẩn kỹ thuật, chắc chắn và thẩm mỹ hiện đại'
        ]
      },
      {
        id: 10,
        name: 'Kính màu ốp bếp cường lực 8mm đẹp',
        category: 'kinh-op-bep',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        oldPrice: '880.000 ₫',
        salePrice: '750.000 ₫',
        discount: '-15%',
        specs: [
          'Kính cường lực 8mm chịu nhiệt cao, chống bám dầu mỡ dễ lau chùi',
          'Bảng màu đa dạng: xanh ngọc, xanh non, vàng chanh, trắng sữa, kim sa',
          'Đo cắt CNC chuẩn xác từng ổ điện, lắp đặt hoàn thiện trong ngày'
        ]
      },
      {
        id: 11,
        name: 'Phòng tắm kính cường lực vách ngăn 10mm',
        category: 'phong-tam-kinh',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        oldPrice: '1.350.000 ₫',
        salePrice: '1.150.000 ₫',
        discount: '-15%',
        specs: [
          'Kính cường lực 10mm trong suốt, phụ kiện VVP / Hafele Inox 304 chính hãng',
          'Gioăng từ chắn nước tuyệt đối giúp khu vực vệ sinh luôn khô ráo sạch sẽ',
          'Thiết kế mở quay 90°, 135°, 180° hoặc cửa lùa tiết kiệm diện tích'
        ]
      },
      {
        id: 12,
        name: 'Cửa kính cường lực bản lề sàn 12mm',
        category: 'kinh-cuong-luc',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        oldPrice: '1.050.000 ₫',
        salePrice: '890.000 ₫',
        discount: '-15%',
        specs: [
          'Kính cường lực tiêu chuẩn 10mm – 12mm chịu va đập gấp 5 lần kính thường',
          'Bản lề thủy lực VVP / Adler chính hãng đóng mở nhẹ nhàng hai chiều',
          'Phù hợp mặt tiền cửa hàng, showroom, văn phòng, sảnh khách sạn'
        ]
      }
    ];

    /* Dữ liệu 6 dự án thực tế tại Đà Nẵng từ Google Drive */
    const PROJECTS = [
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        location: 'Quảng Nam – Đà Nẵng',
        scope: 'Cung cấp & lắp đặt toàn bộ hệ cửa đi xếp trượt nhôm Xingfa, vách kính mặt dựng và phòng tắm kính cường lực tiêu chuẩn 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công trọn gói hệ cửa sổ mở hất, cửa đi ban công nhôm Xingfa hệ 55 chống gió biển và vách kính phòng tắm khách sạn.'
      },
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        location: 'TP. Đà Nẵng',
        scope: 'Gia công và lắp đặt hệ cửa nhôm kính Xingfa cách âm chuẩn quốc tế, cửa kính cường lực sảnh chính và lan can kính.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        location: 'Ven biển Mỹ Khê, Đà Nẵng',
        scope: 'Thi công mặt dựng kính hộp cách âm, cửa nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển và phụ kiện Inox 304.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        location: 'TP. Đà Nẵng',
        scope: 'Hoàn thiện hạng mục cửa nhôm kính Xingfa toàn bộ các tầng phòng nghỉ, cửa kính tự động sảnh lễ tân và cabin tắm kính.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        location: 'TP. Đà Nẵng',
        scope: 'Thiết kế & thi công hệ cửa kính cường lực khổ lớn, cửa đi nhôm Xingfa màu đen tuyền sang trọng và cầu thang kính.'
      }
    ];

    /* Dữ liệu các bài viết chia theo danh mục trang chủ */
    const ARTICLES = [
      {
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu mưa bão Miền Trung không?',
        category: 'kien-thuc',
        categoryLabel: 'Kiến thức nhôm Xingfa',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Cửa nhôm Xingfa nhập khẩu tem đỏ kết hợp gioăng kép EPDM chịu áp lực gió lên đến 1600 Pascal, ngăn nước tuyệt đối trong mùa mưa bão Đà Nẵng.',
        content: 'Với đặc thù khí hậu ven biển nhiều nắng gắt và mưa bão tại Đà Nẵng, cửa nhôm Xingfa nhập khẩu hệ 55 và hệ 93 là giải pháp tối ưu nhờ bề mặt sơn tĩnh điện ngoài trời chống oxy hóa, hệ rãnh thoát nước thông minh hướng ra ngoài và kết cấu khoang trống có gân gia cường chịu áp lực gió mạnh.'
      },
      {
        title: 'Cửa nhôm Xingfa có tiết kiệm năng lượng và cách âm tốt không?',
        category: 'tu-van',
        categoryLabel: 'Tư vấn lựa chọn cửa',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        excerpt: 'Nhờ công nghệ ép góc tiên tiến cùng hệ gioăng cao su kín khít, cửa nhôm Xingfa giúp giảm thất thoát nhiệt điều hòa và hạn chế tiếng ồn hiệu quả.',
        content: 'Sự kết hợp giữa thanh profile nhôm Xingfa đa khoang, kính dán an toàn hoặc kính hộp bơm khí trơ và hệ phụ kiện khóa đa điểm Kinlong tạo nên độ kín khít gần như tuyệt đối, giúp không gian phòng luôn yên tĩnh và tiết kiệm từ 20% đến 30% chi phí điện điều hòa.'
      },
      {
        title: 'Kinh nghiệm phân biệt nhôm Xingfa Quảng Đông tem đỏ chính hãng',
        category: 'kinh-nghiem',
        categoryLabel: 'Kinh nghiệm thi công',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        excerpt: 'Hướng dẫn kiểm tra tem mã QR, độ dày nhôm tiêu chuẩn 1.4mm – 2.0mm và lớp ánh kim sắc nét bên trong thanh nhôm Xingfa chính hãng.',
        content: 'Khi lựa chọn cửa nhôm Xingfa, gia chủ nên kiểm tra trực tiếp mặt cắt thanh nhôm có lớp mạ crom ánh kim sáng, độ dày đúng tiêu chuẩn 1.4mm cho cửa sổ và 2.0mm cho cửa đi, tem đỏ sắc nét có mã QR truy xuất nguồn gốc cùng bộ phụ kiện Kinlong có logo dập chìm chuẩn.'
      },
      {
        title: 'Nên chọn kính ốp bếp và phòng tắm kính cường lực độ dày bao nhiêu?',
        category: 'tu-van',
        categoryLabel: 'Tư vấn lựa chọn cửa',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        excerpt: 'Tư vấn chi tiết cách chọn độ dày kính cường lực 8mm cho bếp và 10mm cho phòng tắm giúp đảm bảo an toàn, bền đẹp và tối ưu chi phí.',
        content: 'Đối với kính màu ốp bếp, độ dày tiêu chuẩn đẹp và kinh tế nhất là kính cường lực 8mm chịu nhiệt cao. Đối với vách kính phòng tắm (cabin tắm), nên sử dụng kính cường lực 10mm kết hợp phụ kiện Inox 304 chống han gỉ trong môi trường ẩm ướt.'
      }
    ];

    /* ================= RENDER SẢN PHẨM ================= */
    function renderProducts(cat = 'all', keyword = '') {
      const grid = document.getElementById('product-grid');
      if (!grid) return;

      let list = PRODUCTS;
      if (cat !== 'all') {
        list = list.filter(p => p.category === cat);
      }
      if (keyword) {
        const kw = keyword.toLowerCase();
        const matched = list.filter(p => p.name.toLowerCase().includes(kw));
        if (matched.length > 0) list = matched;
      }

      grid.innerHTML = list.map(p => `
        <article class="group bg-white rounded-xl border border-slate-200 hover:border-brand/50 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col">
          <div class="relative aspect-[4/3] w-full bg-slate-100 overflow-hidden">
            <!-- Hiển thị % giảm giá ở góc trên bên trái sản phẩm -->
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-red-600 text-white text-[11px] sm:text-xs font-extrabold shadow">
              ${p.discount}
            </span>
            <img
              src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w800"
              data-drive-id="${p.driveId}"
              alt="${p.name}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300 cursor-pointer"
              onclick="openProductModal(${p.id})"
              onerror="handleDriveImageError(this, '${p.name.replace(/'/g, '')}')"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2.5">
            <!-- Tên sản phẩm đầy đủ, không bị tràn hoặc cắt thiếu chữ -->
            <h3
              onclick="openProductModal(${p.id})"
              class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug break-words cursor-pointer"
            >
              ${p.name}
            </h3>
            <div class="space-y-2">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-[15px] font-extrabold text-red-600">${p.salePrice}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>
              <div class="grid grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="openProductModal(${p.id})"
                  class="px-2 py-1.5 rounded-lg border border-brand text-brand hover:bg-brand hover:text-white text-[11px] sm:text-xs font-semibold transition"
                >
                  Chi tiết
                </button>
                <a
                  href="#form-bao-gia"
                  onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}')"
                  class="px-2 py-1.5 rounded-lg bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-semibold text-center transition"
                >
                  Báo giá
                </a>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(cat, keyword = '') {
      document.querySelectorAll('.product-tab').forEach(btn => {
        const isCurrent = btn.getAttribute('data-cat') === cat;
        btn.className = isCurrent
          ? 'product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand text-white transition whitespace-nowrap'
          : 'product-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition whitespace-nowrap';
      });
      renderProducts(cat, keyword);
    }

    /* ================= RENDER DỰ ÁN ĐÀ NẴNG ================= */
    function renderProjects() {
      const grid = document.getElementById('project-grid');
      if (!grid) return;

      grid.innerHTML = PROJECTS.map((proj, idx) => `
        <article onclick="openProjectModal(${idx})" class="group bg-white rounded-xl border border-slate-200 hover:border-brand/50 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col cursor-pointer">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img
              src="https://drive.google.com/thumbnail?id=${proj.driveId}&sz=w900"
              data-drive-id="${proj.driveId}"
              alt="${proj.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImageError(this, 'Dự Án Đà Nẵng')"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between gap-2">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug">
              ${proj.title}
            </h3>
            <p class="text-xs text-slate-500 leading-relaxed">${proj.scope}</p>
          </div>
        </article>
      `).join('');
    }

    /* ================= RENDER BÀI VIẾT TRANG CHỦ ================= */
    function renderArticles(cat = 'all') {
      const grid = document.getElementById('article-grid');
      if (!grid) return;
      const list = cat === 'all' ? ARTICLES : ARTICLES.filter(a => a.category === cat);

      grid.innerHTML = list.map((art, idx) => {
        const realIdx = ARTICLES.indexOf(art);
        return `
          <article onclick="openArticleModal(${realIdx})" class="group bg-white rounded-xl border border-slate-200 hover:border-brand/50 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col cursor-pointer">
            <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
              <img
                src="https://drive.google.com/thumbnail?id=${art.driveId}&sz=w800"
                data-drive-id="${art.driveId}"
                alt="${art.title}"
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                onerror="handleDriveImageError(this, 'Tin Tức Kiến Tâm Việt')"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between gap-2">
              <div class="space-y-1.5">
                <div class="text-[11px] font-bold text-accent uppercase">${art.categoryLabel}</div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug">
                  ${art.title}
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">${art.excerpt}</p>
              </div>
              <span class="text-xs font-bold text-brand group-hover:underline pt-1 inline-block">Đọc tiếp →</span>
            </div>
          </article>
        `;
      }).join('');
    }

    function filterArticles(cat) {
      document.querySelectorAll('.article-tab').forEach(btn => {
        const isCurrent = btn.getAttribute('data-art') === cat;
        btn.className = isCurrent
          ? 'article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand text-white transition whitespace-nowrap'
          : 'article-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white border border-slate-200 text-slate-700 hover:text-brand transition whitespace-nowrap';
      });
      renderArticles(cat);
    }

    /* ================= MODAL CHI TIẾT ================= */
    function openModal(title, htmlContent) {
      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-body').innerHTML = htmlContent;
      const modal = document.getElementById('detail-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function closeModalOnBackdrop(e) {
      if (e.target.id === 'detail-modal') closeModal();
    }

    function openProductModal(productId) {
      const p = PRODUCTS.find(item => item.id === productId);
      if (!p) return;
      const specsHtml = p.specs.map(s => `<li class="flex items-start gap-2"><span class="text-accent font-bold">•</span><span>${s}</span></li>`).join('');
      openModal(p.name, `
        <div class="relative aspect-[16/10] w-full rounded-xl overflow-hidden bg-slate-100">
          <span class="absolute top-3 left-3 px-2.5 py-1 rounded-md bg-red-600 text-white text-xs font-extrabold shadow">${p.discount}</span>
          <img src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w1000" data-drive-id="${p.driveId}" alt="${p.name}" class="w-full h-full object-cover" onerror="handleDriveImageError(this, '${p.name.replace(/'/g, '')}')" />
        </div>
        <div class="flex flex-wrap items-baseline gap-3">
          <span class="text-xl font-extrabold text-red-600">${p.salePrice}</span>
          <span class="text-sm text-slate-400 line-through">${p.oldPrice}</span>
          <span class="text-xs text-slate-500">(Giá tham khảo theo m² / bộ)</span>
        </div>
        <div>
          <h4 class="font-bold text-slate-800 mb-2">Thông số kỹ thuật nổi bật:</h4>
          <ul class="space-y-1.5 text-xs sm:text-sm text-slate-600">${specsHtml}</ul>
        </div>
        <div class="pt-2 flex flex-wrap gap-2.5">
          <a href="tel:0932456012" class="flex-1 text-center px-4 py-2.5 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold transition">Gọi 0932.456.012</a>
          <a href="#form-bao-gia" onclick="closeModal(); selectProductForQuote('${p.name.replace(/'/g, "\\'")}')" class="flex-1 text-center px-4 py-2.5 rounded-lg bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold transition">Nhận báo giá chi tiết</a>
        </div>
      `);
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      openModal(proj.title, `
        <div class="aspect-[16/10] w-full rounded-xl overflow-hidden bg-slate-100">
          <img src="https://drive.google.com/thumbnail?id=${proj.driveId}&sz=w1000" data-drive-id="${proj.driveId}" alt="${proj.title}" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'Dự Án Đà Nẵng')" />
        </div>
        <div class="text-xs sm:text-sm space-y-2">
          <p><strong class="text-brand">Địa điểm:</strong> ${proj.location}</p>
          <p><strong class="text-brand">Đơn vị thi công:</strong> CÔNG TY TNHH ĐẦU TƯ VÀ XÂY DỰNG KIẾN TÂM VIỆT</p>
          <p><strong class="text-brand">Hạng mục thực hiện:</strong> ${proj.scope}</p>
        </div>
      `);
    }

    function openArticleModal(index) {
      const art = ARTICLES[index];
      if (!art) return;
      openModal(art.title, `
        <div class="aspect-[16/10] w-full rounded-xl overflow-hidden bg-slate-100">
          <img src="https://drive.google.com/thumbnail?id=${art.driveId}&sz=w1000" data-drive-id="${art.driveId}" alt="${art.title}" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'Tin Tức')" />
        </div>
        <div class="text-xs font-bold text-accent uppercase">${art.categoryLabel}</div>
        <p class="text-sm text-slate-700 leading-relaxed">${art.excerpt}</p>
        <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
        <div class="pt-2 border-t border-slate-100 text-xs text-slate-500">
          Liên hệ tư vấn kỹ thuật miễn phí tại Kiến Tâm Việt Đà Nẵng – Hotline: <strong class="text-brand">0932.456.012</strong>.
        </div>
      `);
    }

    /* ================= ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT ================= */
    let currentSlide = 0;
    const totalSlides = 2;
    let sliderInterval = null;
    let touchStartX = 0;

    function showSlide(index) {
      currentSlide = (index + totalSlides) % totalSlides;
      document.querySelectorAll('.banner-slide').forEach((slide, idx) => {
        if (idx === currentSlide) {
          slide.classList.add('is-active');
          slide.classList.remove('is-inactive');
        } else {
          slide.classList.remove('is-active');
          slide.classList.add('is-inactive');
        }
      });
      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById('dot-' + i);
        if (!dot) continue;
        dot.className = i === currentSlide
          ? 'w-6 h-2 rounded-full bg-amber-400 transition-all'
          : 'w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
      }
    }

    function nextSlide() { showSlide(currentSlide + 1); }
    function prevSlide() { showSlide(currentSlide - 1); }
    function goToSlide(idx) { showSlide(idx); }

    function startSlider() {
      stopSlider();
      sliderInterval = setInterval(nextSlide, 5500);
    }
    function stopSlider() {
      if (sliderInterval) {
        clearInterval(sliderInterval);
        sliderInterval = null;
      }
    }
    function pauseSlider() { stopSlider(); }
    function resumeSlider() { startSlider(); }

    /* Hỗ trợ vuốt cảm ứng trên điện thoại cho banner */
    const heroSliderEl = document.getElementById('hero-slider');
    if (heroSliderEl) {
      heroSliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      heroSliderEl.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 40) {
          if (diff < 0) nextSlide();
          else prevSlide();
        }
      }, { passive: true });
    }

    /* ================= MENU ĐIỆN THOẠI ================= */
    function toggleMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const iconOpen = document.getElementById('menu-icon-open');
      const iconClose = document.getElementById('menu-icon-close');
      const btn = document.getElementById('mobile-menu-btn');
      const isHidden = menu.classList.contains('hidden');
      menu.classList.toggle('hidden');
      iconOpen.classList.toggle('hidden', isHidden);
      iconClose.classList.toggle('hidden', !isHidden);
      btn.setAttribute('aria-expanded', String(isHidden));
    }

    function closeMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const iconOpen = document.getElementById('menu-icon-open');
      const iconClose = document.getElementById('menu-icon-close');
      menu.classList.add('hidden');
      iconOpen.classList.remove('hidden');
      iconClose.classList.add('hidden');
    }

    function toggleSubmenu(id) {
      const el = document.getElementById(id);
      if (el) el.classList.toggle('hidden');
    }

    /* ================= XỬ LÝ FORM BÁO GIÁ & THÔNG BÁO ================= */
    function selectProductForQuote(productName) {
      const noteEl = document.getElementById('q-note');
      if (noteEl) {
        noteEl.value = 'Tôi cần báo giá sản phẩm: ' + productName;
      }
    }

    function showToast(message) {
      const toast = document.getElementById('toast-box');
      if (!toast) return;
      toast.textContent = message;
      toast.classList.remove('hidden');
      setTimeout(() => {
        toast.classList.add('hidden');
      }, 4500);
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      if (!name || !phone) {
        showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại.');
        return;
      }
      showToast('Cảm ơn ' + name + '! Kiến Tâm Việt đã nhận yêu cầu và sẽ gọi lại số ' + phone + ' trong ít phút.');
      document.getElementById('quote-form').reset();
    }

    /* Khởi chạy giao diện khi tải trang */
    document.addEventListener('DOMContentLoaded', () => {
      renderProducts('all');
      renderProjects();
      renderArticles('all');
      startSlider();
    });
  </script>
</body>
</html>
