<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>ĐẠI ĐỒNG PAINT - Chuyên Phân Phối Sơn Dulux & Jotun Chính Hãng Đà Nẵng | daidongpaint.com</title>
  <meta name="description" content="CÔNG TY TNHH MỘT THÀNH VIÊN ĐẠI ĐỒNG PAINT (daidongpaint.com) - Đại lý cấp 1 chuyên phân phối sơn Dulux và Jotun chính hãng tại Đà Nẵng. Hotline: 0905 205 219.">
  
  <!-- Open Graph Thumbnail là Logo trang web khi gửi link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://daidongpaint.com/">
  <meta property="og:title" content="CÔNG TY TNHH MTV ĐẠI ĐỒNG PAINT - Phân Phối Sơn Dulux & Jotun Chính Hãng">
  <meta property="og:description" content="Chuyên phân phối sơn Dulux và Jotun chính hãng tại Đà Nẵng. Địa chỉ: 534 Ngô Quyền & 154 Lê Ấm. Hotline: 0905 205 219.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1jyEXPgKibQJny9kx3RYW4DFLL7pKIVqB&sz=w1200">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="ĐẠI ĐỒNG PAINT - daidongpaint.com">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1jyEXPgKibQJny9kx3RYW4DFLL7pKIVqB&sz=w1200">

  <!-- Favicon SVG Logo Đại Đồng Paint -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='18' fill='%230b3b8c'/%3E%3Cpath d='M22 25h34c14 0 24 10 24 25s-10 25-24 25H22V25zm14 13v24h18c7 0 12-5 12-12s-5-12-12-12H36z' fill='%23ffffff'/%3E%3Cpath d='M36 38h18c7 0 12 5 12 12H36V38z' fill='%23f59e0b'/%3E%3Ccircle cx='74' cy='26' r='9' fill='%23ef4444'/%3E%3C/svg%3E">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              blue: '#0b3b8c',      /* Màu xanh đậm chủ đạo theo logo */
              lightBlue: '#1d5ec7', /* Màu xanh sáng */
              orange: '#f59e0b',    /* Màu vàng cam sơn */
              red: '#e11d48',       /* Màu đỏ giảm giá Flatsome */
              dark: '#1e293b'
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Reset chống tràn viền & chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề Section kiểu Flatsome chuẩn dễ dựng lại trên UX Builder */
    .section-title-container {
      margin-bottom: 1.25rem;
    }
    .section-title-normal {
      border-bottom: 2px solid #e2e8f0;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }
    .section-title-main {
      border-bottom: 3px solid #0b3b8c;
      margin-bottom: -2px;
      padding-bottom: 8px;
      font-weight: 800;
      text-transform: uppercase;
      color: #0b3b8c;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }

    /* Tên danh mục trên máy tính viết liền trên 1 hàng, không được xuống dòng tên danh mục */
    .cat-nav-item {
      white-space: nowrap !important;
      display: inline-flex;
      align-items: center;
      flex-shrink: 0;
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ */
    .product-title-full {
      white-space: normal;
      word-break: break-word;
      overflow-wrap: break-word;
      line-height: 1.38;
      display: block;
    }

    /* Nhãn % giảm giá Flatsome góc trên bên trái */
    .badge-container-flatsome {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      pointer-events: none;
    }
    .onsale-flatsome {
      background-color: #e11d48;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 40px;
      height: 40px;
      border-radius: 9999px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(225, 29, 72, 0.35);
    }
    @media (max-width: 640px) {
      .onsale-flatsome {
        width: 34px;
        height: 34px;
        font-size: 10px;
      }
    }

    /* Hiệu ứng nút liên hệ nổi */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(225, 29, 72, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0); }
    }
    .pulse-hotline {
      animation: pulse-ring 2s infinite;
    }
  </style>
</head>
<body class=" flex flex-col min-h-screen">

  <!-- =====================================================================
       TOP BAR FLATSOME (Đơn giản, không hiển thị thanh UX Builder)
  ====================================================================== -->
  <div class="bg-brand-blue text-white text-xs py-1.5 border-b border-blue-800">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 overflow-hidden">
        <span class="font-semibold tracking-wide truncate">
          <i class="fa-solid fa-building mr-1 text-brand-orange"></i>CÔNG TY TNHH MỘT THÀNH VIÊN ĐẠI ĐỒNG PAINT
        </span>
        <span class="hidden md:inline-block text-blue-200">|</span>
        <span class="hidden md:inline-block text-blue-100">
          <i class="fa-solid fa-globe mr-1 text-brand-orange"></i>daidongpaint.com
        </span>
      </div>
      <div class="flex items-center gap-3 text-[11px] sm:text-xs ml-auto">
        <span class="hidden sm:inline-block text-blue-100">
          <i class="fa-solid fa-location-dot mr-1 text-brand-orange"></i>534 Ngô Quyền & 154 Lê Ấm, TP. Đà Nẵng
        </span>
        <span class="hidden sm:inline-block text-blue-200">|</span>
        <a href="https://www.facebook.com/profile.php?id=61577753637919" target="_blank" rel="noopener" class="hover:text-brand-orange transition flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> Fanpage Đại Đồng Paint
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       HEADER CHÍNH (Logo gọn nhỏ, Không để nút gọi ngay tránh tràn viền)
  ====================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
      
      <!-- Logo Đại Đồng Paint thiết kế mới chuyên nghiệp, chỉnh gọn nhỏ lại -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-brand-blue flex items-center justify-center shadow-sm relative overflow-hidden shrink-0 border border-blue-900">
          <svg viewBox="0 0 100 100" class="w-8 h-8 sm:w-9 sm:h-9">
            <!-- Biểu tượng cọ lăn sơn & chữ ĐĐ cách điệu -->
            <defs>
              <linearGradient id="paintGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                <stop offset="0%" stop-color="#f59e0b" />
                <stop offset="100%" stop-color="#ef4444" />
              </linearGradient>
            </defs>
            <path d="M18 22h34c16 0 28 11 28 28s-12 28-28 28H18V22zm14 13v30h19c9 0 15-6 15-15s-6-15-15-15H32z" fill="#ffffff"/>
            <path d="M32 35h19c9 0 15 6 15 15H32V35z" fill="url(#paintGrad)"/>
            <circle cx="77" cy="24" r="9" fill="#f59e0b"/>
            <path d="M18 72h64v6H18z" fill="#38bdf8"/>
          </svg>
        </div>
        <div class="leading-tight">
          <div class="text-sm sm:text-base font-extrabold text-brand-blue tracking-tight group-hover:text-brand-lightBlue transition">
            ĐẠI ĐỒNG <span class="text-brand-orange">PAINT</span>
          </div>
          <div class="text-[10px] sm:text-[11px] font-medium text-slate-500">
            Phân phối Sơn Dulux & Jotun
          </div>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm (giống mẫu Flatsome) -->
      <div class="hidden md:flex flex-1 max-w-md mx-4">
        <div class="relative w-full">
          <input 
            id="searchInputDesktop" 
            type="text" 
            placeholder="Tìm kiếm sơn Dulux, Jotun, chống thấm, bột trét..." 
            class="w-full pl-3.5 pr-10 py-1.5 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-brand-blue bg-slate-50"
            oninput="filterProductsBySearch(this.value)"
          >
          <button type="button" aria-label="Tìm kiếm" class="absolute right-0 top-0 h-full px-3 text-white bg-brand-blue rounded-r-md hover:bg-brand-lightBlue transition">
            <i class="fa-solid fa-magnifying-glass text-xs"></i>
          </button>
        </div>
      </div>

      <!-- Menu điều hướng chính trên máy tính (Không có nút Gọi ngay để tránh tràn viền) -->
      <nav class="hidden lg:flex items-center gap-4 text-xs font-bold text-slate-700 uppercase">
        <a href="#trang-chu" class="text-brand-blue hover:text-brand-orange transition whitespace-nowrap">Trang chủ</a>
        <a href="#gioi-thieu" class="hover:text-brand-blue transition whitespace-nowrap">Giới thiệu</a>
        <a href="#danh-muc-san-pham" class="hover:text-brand-blue transition whitespace-nowrap">Sản phẩm</a>
        <a href="#cong-trinh-cong-ty" class="hover:text-brand-blue transition whitespace-nowrap">Hình ảnh công ty</a>
        <a href="#bao-gia-form" class="hover:text-brand-blue transition whitespace-nowrap">Báo giá</a>
        <a href="#tin-tuc" class="hover:text-brand-blue transition whitespace-nowrap">Tin tức</a>
        <a href="#he-thong-dia-chi" class="hover:text-brand-blue transition whitespace-nowrap">Liên hệ</a>
      </nav>

      <!-- Nút mở Menu trên Điện thoại -->
      <button 
        type="button" 
        onclick="toggleMobileMenu()" 
        class="lg:hidden inline-flex items-center justify-center p-2 rounded-md text-brand-blue border border-slate-200 hover:bg-slate-100 focus:outline-none"
        aria-label="Mở danh mục"
      >
        <i id="mobileMenuIcon" class="fa-solid fa-bars text-base"></i>
        <span class="ml-1.5 text-xs font-bold uppercase">Danh mục</span>
      </button>
    </div>

    <!-- Thanh Danh Mục Sản Phẩm trên Máy Tính:
         Tên danh mục viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2,
         không được xuống dòng bên trong tên danh mục -->
    <div class="hidden md:block bg-slate-100 border-t border-slate-200">
      <div class="flatsome-container py-1.5">
        <div class="flex flex-wrap items-center justify-center gap-x-2 gap-y-1.5">
          <button onclick="filterCategory('all')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-bold bg-brand-blue text-white hover:bg-brand-lightBlue transition" data-cat-btn="all">
            <i class="fa-solid fa-border-all mr-1.5 text-[11px]"></i>Tất cả sản phẩm
          </button>
          <button onclick="filterCategory('son-phu-noi-that')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-phu-noi-that">
            <i class="fa-solid fa-house-chimney-window mr-1 text-brand-orange text-[11px]"></i>Sơn phủ nội thất
          </button>
          <button onclick="filterCategory('son-phu-ngoai-that')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-phu-ngoai-that">
            <i class="fa-solid fa-sun mr-1 text-brand-orange text-[11px]"></i>Sơn phủ ngoại thất
          </button>
          <button onclick="filterCategory('son-lot')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-lot">
            <i class="fa-solid fa-shield-halved mr-1 text-brand-orange text-[11px]"></i>Sơn lót chống kiềm
          </button>
          <button onclick="filterCategory('son-chong-tham')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-chong-tham">
            <i class="fa-solid fa-droplet-slash mr-1 text-brand-orange text-[11px]"></i>Sơn chống thấm
          </button>
          <button onclick="filterCategory('bot-tret')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="bot-tret">
            <i class="fa-solid fa-trowel mr-1 text-brand-orange text-[11px]"></i>Bột trét tường
          </button>
          <button onclick="filterCategory('son-dulux')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-dulux">
            <i class="fa-solid fa-fill-drip mr-1 text-blue-600 text-[11px]"></i>Sơn Dulux chính hãng
          </button>
          <button onclick="filterCategory('son-jotun')" class="cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition" data-cat-btn="son-jotun">
            <i class="fa-solid fa-paint-roller mr-1 text-amber-500 text-[11px]"></i>Sơn Jotun chính hãng
          </button>
        </div>
      </div>
    </div>

    <!-- Menu & Tìm kiếm trên Điện Thoại -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 space-y-3">
      <div class="relative w-full">
        <input 
          type="text" 
          placeholder="Tìm sản phẩm sơn Dulux, Jotun..." 
          class="w-full pl-3 pr-9 py-1.5 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-brand-blue"
          oninput="filterProductsBySearch(this.value)"
        >
        <i class="fa-solid fa-magnifying-glass absolute right-3 top-2.5 text-xs text-slate-400"></i>
      </div>
      <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
        <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-brand-blue">Trang chủ</a>
        <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-slate-700">Giới thiệu</a>
        <a href="#danh-muc-san-pham" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-slate-700">Sản phẩm</a>
        <a href="#cong-trinh-cong-ty" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-slate-700">Ảnh công ty</a>
        <a href="#bao-gia-form" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-slate-700">Nhận báo giá</a>
        <a href="#he-thong-dia-chi" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-100 text-slate-700">Địa chỉ & Bản đồ</a>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       MAIN CONTENT
  ====================================================================== -->
  <main id="trang-chu" class="flex-1">

    <!-- ===================================================================
         SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế ảnh banner điện thoại KHÁC với ảnh banner trên máy tính
         - Tối ưu chữ nhỏ gọn nằm hết bên trong ảnh, tuyệt đối không tràn viền
    ==================================================================== -->
    <section class="py-3">
      <div class="flatsome-container">
        <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-blue">
          
          <!-- SLIDE 1 -->
          <div class="banner-slide block transition-opacity duration-500" data-slide="0">
            <!-- Banner 1 dành riêng cho Máy Tính (Tỷ lệ cố định 1200x360, chữ gọn bên trong) -->
            <svg viewBox="0 0 1200 360" class="hidden md:block w-full h-[250px] lg:h-[330px] object-cover bg-[#0b3b8c]" preserveAspectRatio="xMidYMid slice">
              <defs>
                <linearGradient id="dtBg1" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#07265e"/>
                  <stop offset="55%" stop-color="#0b3b8c"/>
                  <stop offset="100%" stop-color="#1e40af"/>
                </linearGradient>
                <linearGradient id="goldAcc1" x1="0%" y1="0%" x2="100%" y2="0%">
                  <stop offset="0%" stop-color="#f59e0b"/>
                  <stop offset="100%" stop-color="#fbbf24"/>
                </linearGradient>
              </defs>
              <rect width="1200" height="360" fill="url(#dtBg1)"/>
              <!-- Họa tiết sóng màu sơn mềm mại -->
              <path d="M720 0 C860 120, 790 240, 960 360 L1200 360 L1200 0 Z" fill="#1d4ed8" opacity="0.45"/>
              <circle cx="1020" cy="180" r="135" fill="#f59e0b" opacity="0.15"/>
              <circle cx="940" cy="180" r="110" fill="#38bdf8" opacity="0.12"/>
              
              <!-- Khung nội dung chữ bên trái có lề an toàn rộng (x=70 đến x=760) -->
              <rect x="70" y="48" width="310" height="30" rx="15" fill="url(#goldAcc1)"/>
              <text x="225" y="68" font-family="Inter, sans-serif" font-size="13" font-weight="800" fill="#0f172a" text-anchor="middle">ĐẠI LÝ PHÂN PHỐI CHÍNH HÃNG TẠI ĐÀ NẴNG</text>
              
              <text x="70" y="122" font-family="Inter, sans-serif" font-size="31" font-weight="800" fill="#ffffff">CÔNG TY TNHH MTV ĐẠI ĐỒNG PAINT</text>
              <text x="70" y="162" font-family="Inter, sans-serif" font-size="21" font-weight="700" fill="#fbbf24">CHUYÊN PHÂN PHỐI SƠN DULUX &amp; JOTUN CHÍNH HÃNG 100%</text>
              
              <text x="70" y="202" font-family="Inter, sans-serif" font-size="15" font-weight="500" fill="#e2e8f0">• Pha màu vi tính chuẩn nhà máy - Chiết khấu cao cho nhà thầu &amp; chủ nhà</text>
              <text x="70" y="230" font-family="Inter, sans-serif" font-size="15" font-weight="500" fill="#e2e8f0">• Hệ thống cửa hàng: 534 Ngô Quyền &amp; 154 Lê Ấm, TP. Đà Nẵng</text>
              
              <rect x="70" y="258" width="440" height="44" rx="8" fill="#ffffff" opacity="0.12" stroke="#fbbf24" stroke-width="1.5"/>
              <text x="90" y="286" font-family="Inter, sans-serif" font-size="16" font-weight="700" fill="#ffffff">HOTLINE BÁO GIÁ: 0905 205 219  |  daidongpaint.com</text>

              <!-- Minh họa 2 thùng sơn Dulux & Jotun bên phải -->
              <g transform="translate(830, 58)">
                <!-- Thùng sơn Dulux -->
                <rect x="10" y="30" width="125" height="155" rx="10" fill="#ffffff" stroke="#cbd5e1" stroke-width="3"/>
                <rect x="6" y="20" width="133" height="16" rx="5" fill="#38bdf8"/>
                <rect x="22" y="52" width="101" height="42" rx="6" fill="#0b3b8c"/>
                <text x="72" y="79" font-family="Inter, sans-serif" font-size="20" font-weight="800" fill="#ffffff" text-anchor="middle">DULUX</text>
                <text x="72" y="118" font-family="Inter, sans-serif" font-size="11" font-weight="700" fill="#0f172a" text-anchor="middle">WEATHERSHIELD</text>
                <text x="72" y="136" font-family="Inter, sans-serif" font-size="10" font-weight="600" fill="#0284c7" text-anchor="middle">Bền Đẹp Vượt Trội</text>
                <path d="M22 155 Q72 172 123 155" stroke="#f59e0b" stroke-width="6" fill="none"/>

                <!-- Thùng sơn Jotun -->
                <rect x="148" y="45" width="125" height="155" rx="10" fill="#ffffff" stroke="#cbd5e1" stroke-width="3"/>
                <rect x="144" y="35" width="133" height="16" rx="5" fill="#f59e0b"/>
                <rect x="160" y="67" width="101" height="42" rx="6" fill="#b91c1c"/>
                <text x="210" y="94" font-family="Inter, sans-serif" font-size="20" font-weight="800" fill="#ffffff" text-anchor="middle">JOTUN</text>
                <text x="210" y="133" font-family="Inter, sans-serif" font-size="11" font-weight="700" fill="#0f172a" text-anchor="middle">JOTASHIELD</text>
                <text x="210" y="151" font-family="Inter, sans-serif" font-size="10" font-weight="600" fill="#b91c1c" text-anchor="middle">Bền Màu Toàn Diện</text>
                <path d="M160 170 Q210 187 261 170" stroke="#0b3b8c" stroke-width="6" fill="none"/>
              </g>
            </svg>

            <!-- Banner 1 dành riêng cho Điện Thoại (Bố cục đứng gọn, chữ nhỏ nằm gọn trong khung 600x300) -->
            <svg viewBox="0 0 600 300" class="block md:hidden w-full h-[185px] sm:h-[220px] object-cover bg-[#0b3b8c]" preserveAspectRatio="xMidYMid meet">
              <defs>
                <linearGradient id="mbBg1" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#07265e"/>
                  <stop offset="100%" stop-color="#1e40af"/>
                </linearGradient>
              </defs>
              <rect width="600" height="300" fill="url(#mbBg1)"/>
              <circle cx="520" cy="60" r="90" fill="#f59e0b" opacity="0.14"/>
              <circle cx="80" cy="250" r="80" fill="#38bdf8" opacity="0.12"/>
              
              <!-- Chữ căn giữa có khoảng đệm 40px mỗi bên để không bao giờ tràn viền -->
              <rect x="130" y="28" width="340" height="26" rx="13" fill="#f59e0b"/>
              <text x="300" y="45" font-family="Inter, sans-serif" font-size="12" font-weight="800" fill="#0f172a" text-anchor="middle">ĐẠI LÝ SƠN CHÍNH HÃNG ĐÀ NẴNG</text>

              <text x="300" y="88" font-family="Inter, sans-serif" font-size="22" font-weight="800" fill="#ffffff" text-anchor="middle">CÔNG TY ĐẠI ĐỒNG PAINT</text>
              <text x="300" y="118" font-family="Inter, sans-serif" font-size="15" font-weight="700" fill="#fbbf24" text-anchor="middle">PHÂN PHỐI SƠN DULUX &amp; JOTUN</text>

              <text x="300" y="152" font-family="Inter, sans-serif" font-size="13" font-weight="500" fill="#e2e8f0" text-anchor="middle">Pha màu vi tính • Giao hàng tận công trình</text>
              <text x="300" y="176" font-family="Inter, sans-serif" font-size="12.5" font-weight="500" fill="#cbd5e1" text-anchor="middle">Đ/c: 534 Ngô Quyền &amp; 154 Lê Ấm, Đà Nẵng</text>

              <rect x="95" y="202" width="410" height="38" rx="8" fill="#ffffff" opacity="0.14" stroke="#fbbf24" stroke-width="1.2"/>
              <text x="300" y="226" font-family="Inter, sans-serif" font-size="14" font-weight="700" fill="#ffffff" text-anchor="middle">Hotline: 0905 205 219 • daidongpaint.com</text>
              
              <text x="300" y="268" font-family="Inter, sans-serif" font-size="11.5" font-weight="600" fill="#93c5fd" text-anchor="middle">Sơn Phủ Nội Ngoại Thất • Sơn Lót • Chống Thấm • Bột Trét</text>
            </svg>
          </div>

          <!-- SLIDE 2 (Kích thước bằng đúng Slide 1) -->
          <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
            <!-- Banner 2 dành riêng cho Máy Tính (Kích thước 1200x360 bằng hệt Banner 1) -->
            <svg viewBox="0 0 1200 360" class="hidden md:block w-full h-[250px] lg:h-[330px] object-cover bg-[#0f2942]" preserveAspectRatio="xMidYMid slice">
              <defs>
                <linearGradient id="dtBg2" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#0f172a"/>
                  <stop offset="50%" stop-color="#0b3b8c"/>
                  <stop offset="100%" stop-color="#0369a1"/>
                </linearGradient>
              </defs>
              <rect width="1200" height="360" fill="url(#dtBg2)"/>
              <path d="M750 0 L1200 0 L1200 360 L660 360 Z" fill="#f59e0b" opacity="0.14"/>
              <circle cx="980" cy="180" r="130" fill="#ffffff" opacity="0.06"/>

              <!-- Nội dung chữ gọn trong khung trái -->
              <rect x="70" y="48" width="340" height="30" rx="15" fill="#38bdf8"/>
              <text x="240" y="68" font-family="Inter, sans-serif" font-size="13" font-weight="800" fill="#0f172a" text-anchor="middle">GIẢI PHÁP BẢO VỆ TOÀN DIỆN CÔNG TRÌNH</text>

              <text x="70" y="122" font-family="Inter, sans-serif" font-size="30" font-weight="800" fill="#ffffff">TỔNG KHO SƠN DULUX &amp; JOTUN ĐÀ NẴNG</text>
              <text x="70" y="162" font-family="Inter, sans-serif" font-size="20" font-weight="700" fill="#fbbf24">ƯU ĐÃI CHIẾT KHẤU LÊN ĐẾN 20% - BÁO GIÁ NHANH 24/7</text>

              <text x="70" y="202" font-family="Inter, sans-serif" font-size="15" font-weight="500" fill="#e2e8f0">• Kho 1: 532 Ngô Quyền, P. An Hải  |  Kho 2: 201 Thái Văn Lung, P. An Hải</text>
              <text x="70" y="230" font-family="Inter, sans-serif" font-size="15" font-weight="500" fill="#e2e8f0">• Cam kết hàng chính hãng từ nhà máy - Hỗ trợ phối màu 3D miễn phí</text>

              <rect x="70" y="258" width="460" height="44" rx="8" fill="#f59e0b"/>
              <text x="300" y="286" font-family="Inter, sans-serif" font-size="16" font-weight="800" fill="#0f172a" text-anchor="middle">LIÊN HỆ TƯ VẤN: 0905 205 219 (ĐẠI ĐỒNG PAINT)</text>

              <!-- Minh họa bảng màu & ngôi nhà -->
              <g transform="translate(835, 62)">
                <rect x="15" y="20" width="240" height="190" rx="14" fill="#ffffff" opacity="0.95"/>
                <rect x="35" y="40" width="60" height="45" rx="6" fill="#0b3b8c"/>
                <rect x="105" y="40" width="60" height="45" rx="6" fill="#0284c7"/>
                <rect x="175" y="40" width="60" height="45" rx="6" fill="#38bdf8"/>
                <rect x="35" y="95" width="60" height="45" rx="6" fill="#f59e0b"/>
                <rect x="105" y="95" width="60" height="45" rx="6" fill="#ea580c"/>
                <rect x="175" y="95" width="60" height="45" rx="6" fill="#10b981"/>
                <text x="135" y="168" font-family="Inter, sans-serif" font-size="14" font-weight="800" fill="#0b3b8c" text-anchor="middle">2.000+ MÃ MÀU CHUẨN</text>
                <text x="135" y="190" font-family="Inter, sans-serif" font-size="12" font-weight="600" fill="#475569" text-anchor="middle">DULUX &amp; JOTUN CHÍNH HÃNG</text>
              </g>
            </svg>

            <!-- Banner 2 dành riêng cho Điện Thoại (Kích thước 600x300 bằng hệt Banner 1 Mobile) -->
            <svg viewBox="0 0 600 300" class="block md:hidden w-full h-[185px] sm:h-[220px] object-cover bg-[#0f2942]" preserveAspectRatio="xMidYMid meet">
              <defs>
                <linearGradient id="mbBg2" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#0f172a"/>
                  <stop offset="100%" stop-color="#0b3b8c"/>
                </linearGradient>
              </defs>
              <rect width="600" height="300" fill="url(#mbBg2)"/>
              <circle cx="80" cy="60" r="85" fill="#38bdf8" opacity="0.14"/>
              <circle cx="520" cy="240" r="85" fill="#f59e0b" opacity="0.14"/>

              <rect x="125" y="28" width="350" height="26" rx="13" fill="#38bdf8"/>
              <text x="300" y="45" font-family="Inter, sans-serif" font-size="12" font-weight="800" fill="#0f172a" text-anchor="middle">HỆ THỐNG KHO SƠN CHÍNH HÃNG</text>

              <text x="300" y="88" font-family="Inter, sans-serif" font-size="21" font-weight="800" fill="#ffffff" text-anchor="middle">TỔNG KHO ĐẠI ĐỒNG PAINT</text>
              <text x="300" y="118" font-family="Inter, sans-serif" font-size="15" font-weight="700" fill="#fbbf24" text-anchor="middle">ƯU ĐÃI CHIẾT KHẤU SƠN ĐẾN 20%</text>

              <text x="300" y="152" font-family="Inter, sans-serif" font-size="12.5" font-weight="500" fill="#e2e8f0" text-anchor="middle">Kho 1: 532 Ngô Quyền • Kho 2: 201 Thái Văn Lung</text>
              <text x="300" y="176" font-family="Inter, sans-serif" font-size="12.5" font-weight="500" fill="#cbd5e1" text-anchor="middle">Chuyên Sơn Dulux • Sơn Jotun • Chống Thấm</text>

              <rect x="95" y="202" width="410" height="38" rx="8" fill="#f59e0b"/>
              <text x="300" y="226" font-family="Inter, sans-serif" font-size="14" font-weight="800" fill="#0f172a" text-anchor="middle">Tư Vấn Báo Giá: 0905 205 219</text>

              <text x="300" y="268" font-family="Inter, sans-serif" font-size="11.5" font-weight="600" fill="#93c5fd" text-anchor="middle">Cam Kết Chính Hãng 100% • Giao Nhanh Tại Đà Nẵng</text>
            </svg>
          </div>

          <!-- Nút chuyển trái/phải Banner -->
          <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/35 text-white hover:bg-black/60 flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-left text-xs"></i>
          </button>
          <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/35 text-white hover:bg-black/60 flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-right text-xs"></i>
          </button>

          <!-- Chấm chỉ báo Slide -->
          <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2">
            <button type="button" onclick="goToSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-brand-orange transition" aria-label="Banner 1"></button>
            <button type="button" onclick="goToSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition" aria-label="Banner 2"></button>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ
         - Thiết kế đẹp trên máy tính & điện thoại
         - Chữ danh mục ở trang chủ nhỏ gọn, không xuống dòng tên danh mục
         - Không để nhãn dán rườm rà
    ==================================================================== -->
    <section id="danh-muc-san-pham" class="py-5">
      <div class="flatsome-container">
        <div class="section-title-container">
          <div class="section-title-normal">
            <h2 class="section-title-main text-base sm:text-lg">
              <i class="fa-solid fa-layer-group text-brand-orange"></i>
              <span>DANH MỤC SẢN PHẨM</span>
            </h2>
            <span class="text-xs text-slate-500">Chuyên phân phối sơn Dulux &amp; Jotun chính hãng</span>
          </div>
        </div>

        <!-- Grid 6 danh mục giống trang mẫu sonkienanthinh.com, chữ nhỏ gọn trên 1 hàng -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
          
          <div onclick="filterCategory('son-phu-noi-that')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-blue-50 text-brand-blue group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-couch text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Sơn phủ nội thất</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Dulux &amp; Jotun nội thất</p>
          </div>

          <div onclick="filterCategory('son-phu-ngoai-that')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-amber-50 text-amber-600 group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-building-shield text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Sơn phủ ngoại thất</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Bền màu, chống bám bẩn</p>
          </div>

          <div onclick="filterCategory('son-lot')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-emerald-50 text-emerald-600 group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-shield-virus text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Sơn lót chống kiềm</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Nội thất &amp; ngoại thất</p>
          </div>

          <div onclick="filterCategory('son-chong-tham')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-cyan-50 text-cyan-600 group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-droplet-slash text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Sơn chống thấm</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Aquatech &amp; WaterGuard</p>
          </div>

          <div onclick="filterCategory('bot-tret')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-purple-50 text-purple-600 group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-trowel-bricks text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Bột trét tường</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Bột trét Dulux &amp; Jotun</p>
          </div>

          <div onclick="filterCategory('all')" class="cursor-pointer group bg-white rounded-lg border border-slate-200 hover:border-brand-blue p-3 text-center shadow-sm hover:shadow transition flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-rose-50 text-rose-600 group-hover:bg-brand-blue group-hover:text-white flex items-center justify-center transition mb-2">
              <i class="fa-solid fa-swatchbook text-lg"></i>
            </div>
            <h3 class="text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Tất cả sản phẩm</h3>
            <p class="text-[11px] text-slate-500 mt-0.5 whitespace-nowrap">Xem trọn bộ sản phẩm</p>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 3: SẢN PHẨM NỔI BẬT (8 ẢNH SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE)
         - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Giá giảm giá và % giảm giá giống Flatsome ở góc trên bên trái
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
    ==================================================================== -->
    <section class="py-5">
      <div class="flatsome-container">
        <div class="section-title-container">
          <div class="section-title-normal">
            <h2 class="section-title-main text-base sm:text-lg">
              <i class="fa-solid fa-paint-roller text-brand-orange"></i>
              <span id="activeCategoryHeading">SẢN PHẨM NỔI BẬT DULUX &amp; JOTUN</span>
            </h2>
            <div class="flex items-center gap-1.5 flex-wrap">
              <button onclick="filterCategory('all')" class="text-xs px-2.5 py-1 rounded bg-brand-blue text-white font-semibold whitespace-nowrap">Tất cả (8)</button>
              <button onclick="filterCategory('son-dulux')" class="text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 hover:border-brand-blue font-semibold whitespace-nowrap">Sơn Dulux</button>
              <button onclick="filterCategory('son-jotun')" class="text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 hover:border-brand-blue font-semibold whitespace-nowrap">Sơn Jotun</button>
            </div>
          </div>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div id="productGridContainer" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
          <!-- Được render tự động từ mảng 8 sản phẩm Google Drive bên dưới -->
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 4: GIỚI THIỆU & 6 ẢNH THỰC TẾ CÔNG TY ĐẠI ĐỒNG PAINT
    ==================================================================== -->
    <section id="gioi-thieu" class="py-6 bg-white border-y border-slate-200">
      <div class="flatsome-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
          
          <!-- Cột thông tin giới thiệu công ty (5/12) -->
          <div class="lg:col-span-5 space-y-3">
            <div class="section-title-container">
              <div class="section-title-normal">
                <h2 class="section-title-main text-base sm:text-lg">
                  <i class="fa-solid fa-award text-brand-orange"></i>
                  <span>VỀ ĐẠI ĐỒNG PAINT</span>
                </h2>
              </div>
            </div>

            <h3 class="text-base sm:text-lg font-extrabold text-brand-blue leading-snug">
              CÔNG TY TNHH MỘT THÀNH VIÊN ĐẠI ĐỒNG PAINT
            </h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              <strong>ĐẠI ĐỒNG PAINT (<a href="https://daidongpaint.com" class="text-brand-blue underline">daidongpaint.com</a>)</strong> là đơn vị uy tín hàng đầu tại TP. Đà Nẵng chuyên phân phối chính hãng các dòng <strong>Sơn Dulux</strong> và <strong>Sơn Jotun</strong> phục vụ công trình dân dụng, biệt thự, khách sạn và dự án xây dựng.
            </p>

            <div class="bg-slate-50 p-3.5 rounded-lg border border-slate-200 space-y-2 text-xs text-slate-700">
              <div class="font-bold text-brand-blue uppercase flex items-center gap-1.5">
                <i class="fa-solid fa-map-location-dot text-brand-orange"></i>
                HỆ THỐNG ĐỊA CHỈ ĐẠI ĐỒNG PAINT:
              </div>
              <div>
                <span class="font-bold text-slate-900">• Địa điểm kinh doanh:</span>
                <ul class="pl-4 mt-0.5 space-y-0.5 list-disc">
                  <li>534 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</li>
                  <li>154 Lê Ấm, Phường Hòa Xuân, TP. Đà Nẵng</li>
                </ul>
              </div>
              <div>
                <span class="font-bold text-slate-900">• Hệ thống kho hàng:</span>
                <ul class="pl-4 mt-0.5 space-y-0.5 list-disc">
                  <li>Kho 1: 532 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</li>
                  <li>Kho 2: 201 Thái Văn Lung, Phường An Hải, TP. Đà Nẵng</li>
                </ul>
              </div>
              <div>
                <span class="font-bold text-slate-900">• Văn phòng đại diện:</span> DNC
              </div>
              <div class="pt-1 border-t border-slate-200 flex items-center justify-between">
                <span class="font-bold text-slate-900">Hotline tư vấn &amp; báo giá:</span>
                <a href="tel:0905205219" class="text-sm font-extrabold text-brand-red hover:underline">0905 205 219</a>
              </div>
            </div>

            <div class="grid grid-cols-2 gap-2.5 pt-1">
              <div class="p-2.5 rounded-lg bg-blue-50/70 border border-blue-100 flex items-center gap-2.5">
                <i class="fa-solid fa-certificate text-brand-blue text-lg"></i>
                <div class="text-xs">
                  <div class="font-bold text-slate-800">100% Chính Hãng</div>
                  <div class="text-[11px] text-slate-500">Từ nhà máy Dulux &amp; Jotun</div>
                </div>
              </div>
              <div class="p-2.5 rounded-lg bg-amber-50/70 border border-amber-100 flex items-center gap-2.5">
                <i class="fa-solid fa-truck-fast text-amber-600 text-lg"></i>
                <div class="text-xs">
                  <div class="font-bold text-slate-800">Giao Nhanh Tận Nơi</div>
                  <div class="text-[11px] text-slate-500">Hệ thống 2 showroom &amp; 2 kho</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Cột 6 Ảnh Thực Tế Công Ty từ Google Drive (7/12) -->
          <div id="cong-trinh-cong-ty" class="lg:col-span-7">
            <div class="section-title-container">
              <div class="section-title-normal">
                <h2 class="section-title-main text-base sm:text-lg">
                  <i class="fa-solid fa-images text-brand-orange"></i>
                  <span>HÌNH ẢNH THỰC TẾ CÔNG TY &amp; KHO HÀNG</span>
                </h2>
              </div>
            </div>

            <div id="companyGalleryGrid" class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 sm:gap-3">
              <!-- Được render từ 6 link Google Drive ảnh công ty -->
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 5: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
    ==================================================================== -->
    <section id="bao-gia-form" class="py-6">
      <div class="flatsome-container">
        <div class="bg-gradient-to-r from-brand-blue to-blue-800 rounded-xl p-4 sm:p-6 text-white shadow-md">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
            
            <div class="lg:col-span-5 space-y-2.5">
              <span class="inline-block bg-brand-orange text-slate-900 text-[11px] font-extrabold px-2.5 py-1 rounded uppercase">
                Báo giá chiết khấu đại lý cấp 1
              </span>
              <h2 class="text-lg sm:text-xl font-extrabold leading-snug">
                ĐĂNG KÝ NHẬN BÁO GIÁ SƠN DULUX &amp; JOTUN TỐT NHẤT
              </h2>
              <p class="text-xs sm:text-sm text-blue-100 leading-relaxed">
                Quý khách hàng, chủ nhà, thầu xây dựng cần bảng báo giá chi tiết và mức chiết khấu mới nhất? Hãy để lại thông tin, bộ phận kinh doanh <strong>Đại Đồng Paint</strong> sẽ liên hệ tư vấn ngay trong 5 phút!
              </p>
              <div class="pt-2 space-y-1.5 text-xs text-blue-100">
                <div><i class="fa-solid fa-circle-check text-brand-orange mr-1.5"></i>Hỗ trợ tính toán khối lượng sơn chính xác theo diện tích</div>
                <div><i class="fa-solid fa-circle-check text-brand-orange mr-1.5"></i>Pha màu vi tính chính hãng lấy ngay tại 534 Ngô Quyền &amp; 154 Lê Ấm</div>
                <div><i class="fa-solid fa-phone-volume text-brand-orange mr-1.5"></i>Hotline trực tiếp: <strong class="text-white text-sm">0905 205 219</strong></div>
              </div>
            </div>

            <div class="lg:col-span-7">
              <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-lg p-4 sm:p-5 shadow space-y-3">
                <h3 class="text-sm sm:text-base font-extrabold text-brand-blue uppercase border-b border-slate-200 pb-2">
                  Form Yêu Cầu &amp; Báo Giá Nhanh
                </h3>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                  <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                    <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand-blue">
                  </div>
                  <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                    <input type="tel" id="qPhone" required placeholder="Ví dụ: 0905 205 219" class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand-blue">
                  </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                  <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Thương hiệu sơn quan tâm</label>
                    <select id="qBrand" class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand-blue bg-white">
                      <option value="Sơn Dulux & Jotun">Tư vấn cả Sơn Dulux &amp; Jotun</option>
                      <option value="Sơn Dulux chính hãng">Sơn Dulux chính hãng</option>
                      <option value="Sơn Jotun chính hãng">Sơn Jotun chính hãng</option>
                      <option value="Sơn chống thấm & Bột trét">Sơn chống thấm &amp; Bột trét</option>
                    </select>
                  </div>
                  <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                    <select id="qType" class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand-blue bg-white">
                      <option value="Trọn gói sơn nhà mới">Trọn gói sơn nhà mới / Biệt thự</option>
                      <option value="Sơn phủ nội thất & ngoại thất">Sơn phủ nội thất &amp; ngoại thất</option>
                      <option value="Sơn chống thấm tường / sàn">Sơn chống thấm tường / sàn</option>
                      <option value="Mua sỉ cho thầu / công trình">Báo giá sỉ cho thầu / dự án</option>
                    </select>
                  </div>
                </div>

                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú diện tích hoặc mã sản phẩm cần báo giá</label>
                  <textarea id="qNote" rows="2" placeholder="Nhập diện tích (m2), số tầng hoặc tên loại sơn quý khách cần báo giá..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand-blue"></textarea>
                </div>

                <div class="flex flex-col sm:flex-row items-center justify-between gap-2 pt-1">
                  <span class="text-[11px] text-slate-500">
                    <i class="fa-solid fa-lock text-emerald-600 mr-1"></i>Thông tin được bảo mật &amp; phản hồi ngay.
                  </span>
                  <button type="submit" class="w-full sm:w-auto px-5 py-2.5 bg-brand-orange hover:bg-amber-500 text-slate-900 font-extrabold text-xs uppercase rounded shadow transition">
                    <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá
                  </button>
                </div>

                <div id="quoteSuccessAlert" class="hidden p-3 rounded bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
              </form>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC NỔI BẬT)
    ==================================================================== -->
    <section id="tin-tuc" class="py-5">
      <div class="flatsome-container">
        <div class="section-title-container">
          <div class="section-title-normal">
            <h2 class="section-title-main text-base sm:text-lg">
              <i class="fa-solid fa-newspaper text-brand-orange"></i>
              <span>DANH MỤC BÀI VIẾT &amp; TIN TỨC NỔI BẬT</span>
            </h2>
            <div class="flex items-center gap-1.5 flex-wrap">
              <button onclick="filterPosts('all')" class="post-cat-btn text-xs px-2.5 py-1 rounded bg-brand-blue text-white font-semibold whitespace-nowrap" data-post-cat="all">Tất cả bài viết</button>
              <button onclick="filterPosts('bang-gia')" class="post-cat-btn text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 font-semibold whitespace-nowrap" data-post-cat="bang-gia">Bảng giá sơn</button>
              <button onclick="filterPosts('kinh-nghiem')" class="post-cat-btn text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 font-semibold whitespace-nowrap" data-post-cat="kinh-nghiem">Tư vấn chọn sơn</button>
              <button onclick="filterPosts('ky-thuat')" class="post-cat-btn text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 font-semibold whitespace-nowrap" data-post-cat="ky-thuat">Kỹ thuật thi công</button>
            </div>
          </div>
        </div>

        <div id="blogGridContainer" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
          <!-- Render tự động các bài viết trang chủ -->
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 7: DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
    ==================================================================== -->
    <section class="py-5 bg-white border-t border-slate-200">
      <div class="flatsome-container">
        <div class="section-title-container">
          <div class="section-title-normal">
            <h2 class="section-title-main text-base sm:text-lg">
              <i class="fa-solid fa-handshake text-brand-orange"></i>
              <span>ĐỐI TÁC &amp; THƯƠNG HIỆU PHÂN PHỐI</span>
            </h2>
          </div>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#0b3b8c] tracking-wider">DULUX</div>
            <div class="text-[11px] text-slate-500 mt-0.5">AkzoNobel Hà Lan</div>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#b91c1c] tracking-wider">JOTUN</div>
            <div class="text-[11px] text-slate-500 mt-0.5">Tập đoàn Sơn Na Uy</div>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#0284c7] tracking-wider">MAXILITE</div>
            <div class="text-[11px] text-slate-500 mt-0.5">Từ Dulux AkzoNobel</div>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#059669] tracking-wider">AQUATECH</div>
            <div class="text-[11px] text-slate-500 mt-0.5">Chống thấm cao cấp</div>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#d97706] tracking-wider">JOTASHIELD</div>
            <div class="text-[11px] text-slate-500 mt-0.5">Ngoại thất thượng hạng</div>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
            <div class="text-base font-black text-[#4f46e5] tracking-wider">MAJESTIC</div>
            <div class="text-[11px] text-slate-500 mt-0.5">Nội thất sang trọng</div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 8: ĐƯA GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ
         + HỆ THỐNG ĐỊA CHỈ ĐẠI ĐỒNG PAINT ĐẦY ĐỦ
    ==================================================================== -->
    <section id="he-thong-dia-chi" class="py-6 bg-slate-100 border-t border-slate-200">
      <div class="flatsome-container">
        <div class="section-title-container">
          <div class="section-title-normal">
            <h2 class="section-title-main text-base sm:text-lg">
              <i class="fa-solid fa-map-location-dot text-brand-orange"></i>
              <span>HỆ THỐNG ĐỊA CHỈ, BẢN ĐỒ GOOGLE MAPS &amp; FANPAGE</span>
            </h2>
          </div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
          
          <!-- Cột 1: Hệ thống địa chỉ Đại Đồng Paint (4/12) -->
          <div class="lg:col-span-4 bg-white rounded-xl p-4 border border-slate-200 shadow-sm flex flex-col justify-between space-y-3">
            <div class="space-y-3">
              <div class="flex items-center gap-2.5 border-b border-slate-100 pb-2.5">
                <div class="w-9 h-9 rounded-lg bg-brand-blue text-white flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-building-columns"></i>
                </div>
                <div>
                  <h3 class="text-xs sm:text-sm font-extrabold text-brand-blue">HỆ THỐNG ĐỊA CHỈ ĐẠI ĐỒNG PAINT</h3>
                  <p class="text-[11px] text-slate-500">Website: daidongpaint.com</p>
                </div>
              </div>

              <!-- Địa điểm kinh doanh -->
              <div class="space-y-1.5">
                <div class="text-xs font-extrabold text-slate-800 uppercase flex items-center gap-1.5">
                  <i class="fa-solid fa-store text-brand-orange"></i> Địa điểm kinh doanh:
                </div>
                <button type="button" onclick="switchGoogleMap('534 Ngô Quyền, Phường An Hải, Đà Nẵng', 'Showroom 1: 534 Ngô Quyền, P. An Hải, TP. Đà Nẵng')" class="w-full text-left p-2 rounded bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-brand-blue transition text-xs">
                  <div class="font-bold text-brand-blue">1. 534 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</div>
                  <div class="text-[11px] text-slate-500">Nhấn để xem vị trí trên bản đồ</div>
                </button>
                <button type="button" onclick="switchGoogleMap('154 Lê Ấm, Phường Hòa Xuân, Đà Nẵng', 'Showroom 2: 154 Lê Ấm, P. Hòa Xuân, TP. Đà Nẵng')" class="w-full text-left p-2 rounded bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-brand-blue transition text-xs">
                  <div class="font-bold text-brand-blue">2. 154 Lê Ấm, Phường Hòa Xuân, TP. Đà Nẵng</div>
                  <div class="text-[11px] text-slate-500">Nhấn để xem vị trí trên bản đồ</div>
                </button>
              </div>

              <!-- Hệ thống kho hàng -->
              <div class="space-y-1.5">
                <div class="text-xs font-extrabold text-slate-800 uppercase flex items-center gap-1.5">
                  <i class="fa-solid fa-warehouse text-brand-orange"></i> Hệ thống kho hàng:
                </div>
                <button type="button" onclick="switchGoogleMap('532 Ngô Quyền, Phường An Hải, Đà Nẵng', 'Kho 1: 532 Ngô Quyền, P. An Hải, TP. Đà Nẵng')" class="w-full text-left p-2 rounded bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-brand-blue transition text-xs">
                  <div class="font-bold text-slate-800">• Kho 1: 532 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</div>
                </button>
                <button type="button" onclick="switchGoogleMap('201 Thái Văn Lung, Đà Nẵng', 'Kho 2: 201 Thái Văn Lung, P. An Hải, TP. Đà Nẵng')" class="w-full text-left p-2 rounded bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-brand-blue transition text-xs">
                  <div class="font-bold text-slate-800">• Kho 2: 201 Thái Văn Lung, Phường An Hải, TP. Đà Nẵng</div>
                </button>
              </div>

              <!-- Văn phòng đại diện -->
              <div class="p-2 rounded bg-amber-50/70 border border-amber-200 text-xs font-bold text-slate-800">
                <i class="fa-solid fa-briefcase text-brand-orange mr-1.5"></i>Văn phòng đại diện: <span class="text-brand-blue">DNC</span>
              </div>
            </div>

            <div class="pt-2 border-t border-slate-200 flex items-center justify-between text-xs">
              <span class="font-bold text-slate-700">Hotline 24/7:</span>
              <a href="tel:0905205219" class="font-extrabold text-sm text-brand-red">0905 205 219</a>
            </div>
          </div>

          <!-- Cột 2: Bản đồ Google Maps trực tiếp ngoài trang chủ (5/12) -->
          <div class="lg:col-span-5 bg-white rounded-xl p-3 border border-slate-200 shadow-sm flex flex-col">
            <div class="flex items-center justify-between gap-2 mb-2 px-1">
              <div class="text-xs font-extrabold text-brand-blue truncate" id="currentMapLabel">
                <i class="fa-solid fa-location-dot text-brand-red mr-1"></i>534 Ngô Quyền, Phường An Hải, TP. Đà Nẵng
              </div>
              <a id="externalMapLink" href="https://www.google.com/maps/search/?api=1&query=534+Ng%C3%B4+Quy%E1%BB%81n,+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-[11px] font-bold text-brand-lightBlue hover:underline whitespace-nowrap">
                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-0.5"></i>
              </a>
            </div>
            <div class="w-full h-[290px] sm:h-[330px] rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
              <iframe 
                id="googleMapIframe"
                title="Bản đồ Đại Đồng Paint 534 Ngô Quyền Đà Nẵng"
                src="https://maps.google.com/maps?q=534%20Ng%C3%B4%20Quy%E1%BB%81n,%20An%20H%E1%BA%A3i,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <!-- Cột 3: Fanpage Facebook Đại Đồng Paint ngoài trang chủ (3/12) -->
          <div class="lg:col-span-3 bg-white rounded-xl p-4 border border-slate-200 shadow-sm flex flex-col justify-between">
            <div>
              <div class="flex items-center justify-between border-b border-slate-100 pb-2.5 mb-3">
                <div class="flex items-center gap-2">
                  <i class="fa-brands fa-facebook text-xl text-[#1877F2]"></i>
                  <span class="text-xs font-extrabold text-slate-800 uppercase">Fanpage Chính Thức</span>
                </div>
                <span class="text-[10px] bg-blue-50 text-[#1877F2] px-2 py-0.5 rounded font-semibold">Đã xác thực</span>
              </div>

              <!-- Khung hiển thị trực quan Fanpage Đại Đồng Paint -->
              <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50">
                <div class="h-24 bg-gradient-to-r from-brand-blue to-blue-700 p-3 flex items-end relative">
                  <div class="flex items-center gap-2.5 z-10">
                    <div class="w-12 h-12 rounded-full bg-white p-1 shadow border border-slate-200 flex items-center justify-center shrink-0">
                      <svg viewBox="0 0 100 100" class="w-9 h-9">
                        <rect width="100" height="100" rx="18" fill="#0b3b8c"/>
                        <path d="M22 25h34c14 0 24 10 24 25s-10 25-24 25H22V25zm14 13v24h18c7 0 12-5 12-12s-5-12-12-12H36z" fill="#ffffff"/>
                        <circle cx="74" cy="26" r="9" fill="#f59e0b"/>
                      </svg>
                    </div>
                    <div class="text-white leading-tight">
                      <a href="https://www.facebook.com/profile.php?id=61577753637919" target="_blank" rel="noopener" class="font-extrabold text-xs sm:text-sm hover:underline block">
                        ĐẠI ĐỒNG PAINT
                      </a>
                      <span class="text-[11px] text-blue-100">Phân phối Sơn Dulux &amp; Jotun</span>
                    </div>
                  </div>
                </div>

                <div class="p-3 space-y-2.5 text-xs">
                  <p class="text-slate-600 text-[11.5px] leading-relaxed">
                    Cập nhật bảng màu mới nhất, chương trình khuyến mãi chiết khấu sơn Dulux &amp; Jotun và hình ảnh giao hàng thực tế mỗi ngày.
                  </p>
                  <div class="text-[11px] text-slate-500 space-y-1">
                    <div><i class="fa-solid fa-location-dot text-brand-blue mr-1.5"></i>534 Ngô Quyền &amp; 154 Lê Ấm, Đà Nẵng</div>
                    <div><i class="fa-solid fa-phone text-brand-blue mr-1.5"></i>0905 205 219</div>
                  </div>
                  <div class="pt-1 flex gap-2">
                    <a href="https://www.facebook.com/profile.php?id=61577753637919" target="_blank" rel="noopener" class="flex-1 py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-center text-xs transition flex items-center justify-center gap-1.5">
                      <i class="fa-brands fa-facebook-f"></i> Theo dõi Fanpage
                    </a>
                    <a href="https://www.facebook.com/profile.php?id=61577753637919" target="_blank" rel="noopener" class="py-2 px-3 rounded bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold text-center text-xs transition">
                      Nhắn tin
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 text-center">
              Kết nối trực tiếp qua Facebook &amp; Zalo 0905 205 219
            </div>
          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- =====================================================================
       FOOTER CHUẨN FLATSOME
  ====================================================================== -->
  <footer class="bg-[#082559] text-white pt-8 pb-6 border-t-4 border-brand-orange">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-blue-800/80">
        
        <!-- Cột 1: Thông tin công ty (5/12) -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded-lg bg-white flex items-center justify-center shrink-0">
              <svg viewBox="0 0 100 100" class="w-7 h-7">
                <rect width="100" height="100" rx="16" fill="#0b3b8c"/>
                <path d="M22 25h34c14 0 24 10 24 25s-10 25-24 25H22V25zm14 13v24h18c7 0 12-5 12-12s-5-12-12-12H36z" fill="#ffffff"/>
                <circle cx="74" cy="26" r="9" fill="#f59e0b"/>
              </svg>
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-white uppercase">
                CÔNG TY TNHH MỘT THÀNH VIÊN ĐẠI ĐỒNG PAINT
              </h3>
              <p class="text-[11px] text-brand-orange font-semibold">Chuyên phân phối sơn Dulux và Jotun chính hãng</p>
            </div>
          </div>

          <div class="text-xs text-blue-100 space-y-1.5 pt-1">
            <div><strong class="text-white">Địa điểm kinh doanh 1:</strong> 534 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</div>
            <div><strong class="text-white">Địa điểm kinh doanh 2:</strong> 154 Lê Ấm, Phường Hòa Xuân, TP. Đà Nẵng</div>
            <div><strong class="text-white">Kho 1:</strong> 532 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</div>
            <div><strong class="text-white">Kho 2:</strong> 201 Thái Văn Lung, Phường An Hải, TP. Đà Nẵng</div>
            <div><strong class="text-white">Văn phòng đại diện:</strong> DNC</div>
            <div><strong class="text-white">Hotline:</strong> <a href="tel:0905205219" class="text-brand-orange font-extrabold">0905 205 219</a></div>
            <div><strong class="text-white">Website:</strong> <a href="https://daidongpaint.com" class="hover:underline text-blue-200">daidongpaint.com</a></div>
          </div>
        </div>

        <!-- Cột 2: Danh mục sản phẩm (3/12) -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-brand-orange border-b border-blue-800 pb-1.5">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="space-y-1.5 text-xs text-blue-100">
            <li><a href="#danh-muc-san-pham" onclick="filterCategory('son-phu-noi-that')" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn phủ nội thất Dulux &amp; Jotun</a></li>
            <li><a href="#danh-muc-san-pham" onclick="filterCategory('son-phu-ngoai-that')" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn phủ ngoại thất cao cấp</a></li>
            <li><a href="#danh-muc-san-pham" onclick="filterCategory('son-lot')" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn lót chống kiềm nội ngoại thất</a></li>
            <li><a href="#danh-muc-san-pham" onclick="filterCategory('son-chong-tham')" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn chống thấm chuyên dụng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="filterCategory('bot-tret')" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Bột trét tường nội ngoại thất</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Kết nối (4/12) -->
        <div class="lg:col-span-4 space-y-2.5">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-brand-orange border-b border-blue-800 pb-1.5">
            Cam Kết Khách Hàng
          </h4>
          <ul class="space-y-1.5 text-xs text-blue-100">
            <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Cam kết sơn chính hãng 100% từ nhà máy sản xuất</li>
            <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Pha màu vi tính chuẩn xác theo cây màu Dulux &amp; Jotun</li>
            <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Chiết khấu ưu đãi cao cho nhà thầu &amp; công trình</li>
            <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Giao hàng tận chân công trình nhanh chóng tại Đà Nẵng</li>
          </ul>
          <div class="pt-2 flex items-center gap-2">
            <a href="https://www.facebook.com/profile.php?id=61577753637919" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-[#1877F2] hover:bg-blue-600 text-xs font-bold flex items-center gap-1.5 transition">
              <i class="fa-brands fa-facebook-f"></i> Fanpage
            </a>
            <a href="https://zalo.me/0905205219" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-sky-500 hover:bg-sky-600 text-xs font-bold flex items-center gap-1.5 transition">
              <i class="fa-solid fa-comment-dots"></i> Chat Zalo
            </a>
            <a href="tel:0905205219" class="px-3 py-1.5 rounded bg-brand-red hover:bg-rose-700 text-xs font-bold flex items-center gap-1.5 transition">
              <i class="fa-solid fa-phone"></i> 0905 205 219
            </a>
          </div>
        </div>

      </div>

      <div class="pt-4 text-center text-xs text-blue-200 flex flex-col sm:flex-row items-center justify-between gap-2">
        <div>Copyright 2026 © <strong>CÔNG TY TNHH MỘT THÀNH VIÊN ĐẠI ĐỒNG PAINT</strong> (daidongpaint.com)</div>
        <div>Thiết kế theo chuẩn giao diện Flatsome UX Builder</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền
  ====================================================================== -->
  <div class="fixed bottom-4 right-3 sm:right-4 z-50 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/profile.php?id=61577753637919" 
      target="_blank" 
      rel="noopener" 
      aria-label="Facebook Đại Đồng Paint"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <i class="fa-brands fa-facebook-f text-base w-5 text-center"></i>
      <span class="hidden sm:inline-block text-xs font-bold">Fanpage</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a 
      href="https://zalo.me/0905205219" 
      target="_blank" 
      rel="noopener" 
      aria-label="Zalo 0905 205 219"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <span class="font-black text-[11px] bg-white text-[#0068ff] rounded-full w-5 h-5 flex items-center justify-center shrink-0">Z</span>
      <span class="hidden sm:inline-block text-xs font-bold">Chat Zalo</span>
    </a>

    <!-- Nút Hotline Nổi Bật -->
    <a 
      href="tel:0905205219" 
      aria-label="Gọi ngay 0905 205 219"
      class="pulse-hotline flex items-center gap-2 bg-brand-red hover:bg-rose-700 text-white rounded-full px-3.5 py-2.5 shadow-xl transition"
    >
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span class="text-xs sm:text-sm font-extrabold tracking-wide">0905 205 219</span>
    </a>
  </div>

  <!-- =====================================================================
       MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT (Không dùng alert)
  ====================================================================== -->
  <div id="detailModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-lg w-full p-4 sm:p-5 shadow-2xl relative max-h-[90vh] overflow-y-auto">
      <button type="button" onclick="closeDetailModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detailModalBody"></div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC
  ====================================================================== -->
  <script>
    /* Danh sách 8 sản phẩm thực tế lấy trực tiếp từ 8 file Google Drive được cung cấp */
    const PRODUCTS = [
      {
        id: 1,
        driveId: '1uWWtZo6UIWsXqWBIBCjqKELrzqxEEVwk',
        name: 'Sơn Ngoại Thất Cao Cấp Dulux Weathershield Bề Mặt Bóng - Thùng 15L',
        category: 'son-phu-ngoai-that',
        brand: 'son-dulux',
        categoryLabel: 'Sơn phủ ngoại thất',
        oldPrice: '4.150.000đ',
        newPrice: '3.390.000đ',
        discountPercent: '-18%',
        spec: 'Chống thấm, chống rêu mốc & bền màu vượt trội'
      },
      {
        id: 2,
        driveId: '10SnIbZAvT9a0Z_qM_eh0loMA1wt1Q4X3',
        name: 'Sơn Nội Thất Cao Cấp Dulux Ambiance 5in1 Superflexx Bóng Sang Trọng - 15L',
        category: 'son-phu-noi-that',
        brand: 'son-dulux',
        categoryLabel: 'Sơn phủ nội thất',
        oldPrice: '3.890.000đ',
        newPrice: '3.150.000đ',
        discountPercent: '-19%',
        spec: 'Màng sơn co giãn che lấp khe nứt nhỏ, kháng khuẩn'
      },
      {
        id: 3,
        driveId: '15QoPr6OrcYP1R1Lh901eG0o_rT3clfyv',
        name: 'Sơn Nội Thất Dulux EasyClean Lau Chùi Hiệu Quả Kháng Khuẩn - Thùng 15L',
        category: 'son-phu-noi-that',
        brand: 'son-dulux',
        categoryLabel: 'Sơn phủ nội thất',
        oldPrice: '2.950.000đ',
        newPrice: '2.390.000đ',
        discountPercent: '-19%',
        spec: 'Công nghệ chống bám bẩn chủ động, dễ lau chùi'
      },
      {
        id: 4,
        driveId: '1xamBWb-kE0_NdOMT4A1HdDglKPQIQ0gp',
        name: 'Sơn Ngoại Thất Thượng Hạng Jotun Jotashield Bền Màu Toàn Diện - Thùng 15L',
        category: 'son-phu-ngoai-that',
        brand: 'son-jotun',
        categoryLabel: 'Sơn phủ ngoại thất',
        oldPrice: '4.280.000đ',
        newPrice: '3.450.000đ',
        discountPercent: '-19%',
        spec: 'Bảo vệ 12 năm, chống tia UV & giảm nhiệt hiệu quả'
      },
      {
        id: 5,
        driveId: '1T3d0Ta9TzFhPSBas3UXZXrue5UZmiqj2',
        name: 'Sơn Nội Thất Cao Cấp Jotun Majestic Đẹp Hoàn Hảo Bóng Sang Trọng - 15L',
        category: 'son-phu-noi-that',
        brand: 'son-jotun',
        categoryLabel: 'Sơn phủ nội thất',
        oldPrice: '3.650.000đ',
        newPrice: '2.980.000đ',
        discountPercent: '-18%',
        spec: 'Màu sắc rực rỡ sắc nét, nhẹ mùi, kháng khuẩn'
      },
      {
        id: 6,
        driveId: '1ZwC-e60dUcVRhHGkCusxepcJj1nRqsY6',
        name: 'Sơn Lót Chống Kiềm Ngoại Thất Dulux Weathershield Powersealer - Thùng 18L',
        category: 'son-lot',
        brand: 'son-dulux',
        categoryLabel: 'Sơn lót chống kiềm',
        oldPrice: '3.150.000đ',
        newPrice: '2.580.000đ',
        discountPercent: '-18%',
        spec: 'Tăng cường độ bám dính, kháng kiềm tối ưu cho tường'
      },
      {
        id: 7,
        driveId: '1yWT-Eb6_Y3X7vcSHjOHe2_37_aWRQYhR',
        name: 'Sơn Chống Thấm Cao Cấp Dulux Aquatech Flex Waterproofing - Thùng 20Kg',
        category: 'son-chong-tham',
        brand: 'son-dulux',
        categoryLabel: 'Sơn chống thấm',
        oldPrice: '2.850.000đ',
        newPrice: '2.290.000đ',
        discountPercent: '-20%',
        spec: 'Chống thấm gấp 2 lần, không cần pha xi măng'
      },
      {
        id: 8,
        driveId: '1YOekhOzrIHPxdoX0pwwylnXC44f-j_La',
        name: 'Bột Trét Tường Nội Ngoại Thất Cao Cấp Dulux & Jotun Chính Hãng - Bao 40Kg',
        category: 'bot-tret',
        brand: 'son-jotun',
        categoryLabel: 'Bột trét tường',
        oldPrice: '560.000đ',
        newPrice: '465.000đ',
        discountPercent: '-17%',
        spec: 'Làm phẳng mịn bề mặt tường, tăng độ bền lớp sơn phủ'
      }
    ];

    /* Danh sách 6 ảnh công ty thực tế từ Google Drive */
    const COMPANY_PHOTOS = [
      {
        driveId: '1jyEXPgKibQJny9kx3RYW4DFLL7pKIVqB',
        title: 'Showroom Đại Đồng Paint - 534 Ngô Quyền, Đà Nẵng'
      },
      {
        driveId: '1Kspifo-TxkTMx8cxTs5ECXYGCn-TO9tt',
        title: 'Trung tâm pha màu sơn vi tính Dulux & Jotun chính hãng'
      },
      {
        driveId: '19z4ReKWRb8nwlULGWyb8afihNmGDkw38',
        title: 'Hệ thống trưng bày sản phẩm sơn Dulux & Jotun'
      },
      {
        driveId: '1tyBK_XxBtE30RV118fxt0v-jd2P-HZgf',
        title: 'Cơ sở kinh doanh 154 Lê Ấm, P. Hòa Xuân, Đà Nẵng'
      },
      {
        driveId: '1OsFm_Ui30Bgq7sqQyLSuaaXFLnXY9hoO',
        title: 'Hệ thống kho hàng 532 Ngô Quyền & 201 Thái Văn Lung'
      },
      {
        driveId: '1IcywlKUgi-xR3sNtgBMmK-uK_jrn-Wuq',
        title: 'Hoạt động xuất kho giao sơn tận công trình tại Đà Nẵng'
      }
    ];

    /* Danh sách các bài viết trang chủ */
    const BLOG_POSTS = [
      {
        id: 101,
        cat: 'bang-gia',
        catName: 'Bảng giá sơn',
        date: '14/11/2026',
        title: 'Bảng Báo Giá Sơn Dulux & Jotun Chính Hãng Mới Nhất Tại Đà Nẵng',
        excerpt: 'Cập nhật bảng giá niêm yết và mức chiết khấu ưu đãi lên đến 20% cho các dòng sơn nội thất, ngoại thất, chống thấm tại Đại Đồng Paint.',
        driveId: '1uWWtZo6UIWsXqWBIBCjqKELrzqxEEVwk'
      },
      {
        id: 102,
        cat: 'kinh-nghiem',
        catName: 'Tư vấn chọn sơn',
        date: '10/11/2026',
        title: 'Kinh Nghiệm Chọn Sơn Ngoại Thất Chống Thấm Bền Màu Cho Khí Hậu Đà Nẵng',
        excerpt: 'Với thời tiết nắng mưa miền Trung, việc kết hợp sơn lót kháng kiềm và sơn phủ Dulux Weathershield hoặc Jotun Jotashield giúp bảo vệ ngôi nhà trên 10 năm.',
        driveId: '1xamBWb-kE0_NdOMT4A1HdDglKPQIQ0gp'
      },
      {
        id: 103,
        cat: 'ky-thuat',
        catName: 'Kỹ thuật thi công',
        date: '05/11/2026',
        title: 'Quy Trình Thi Công Sơn Nước Chuẩn Kỹ Thuật Từ Bột Trét Đến Sơn Phủ',
        excerpt: 'Hướng dẫn chi tiết quy trình xử lý độ ẩm tường, bả 2 lớp bột trét, 1 lớp sơn lót chống kiềm và 2 lớp sơn phủ hoàn thiện đẹp nguyên bản.',
        driveId: '1ZwC-e60dUcVRhHGkCusxepcJj1nRqsY6'
      },
      {
        id: 104,
        cat: 'kinh-nghiem',
        catName: 'Tư vấn chọn sơn',
        date: '01/11/2026',
        title: 'Địa Chỉ Đại Lý Phân Phối Sơn Dulux & Jotun Uy Tín Giao Nhanh Tại Đà Nẵng',
        excerpt: 'Hệ thống cửa hàng Đại Đồng Paint tại 534 Ngô Quyền và 154 Lê Ấm cùng 2 kho hàng lớn luôn sẵn sàng phục vụ nhanh mọi công trình.',
        driveId: '1jyEXPgKibQJny9kx3RYW4DFLL7pKIVqB'
      }
    ];

    /* Hàm tạo link ảnh Google Drive có cơ chế tự động chuyển đổi dự phòng nếu bị chặn */
    function handleDriveImgError(imgEl, driveId, fallbackLabel) {
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w800';
      } else if (step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
      } else {
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/600x600/0b3b8c/ffffff?text=' + encodeURIComponent(fallbackLabel || 'DAI DONG PAINT');
      }
    }

    /* Render danh sách 8 sản phẩm ra trang chủ (2 cột trên điện thoại, 4 cột trên máy tính) */
    function renderProducts(list) {
      const container = document.getElementById('productGridContainer');
      if (!list.length) {
        container.innerHTML = `
          <div class="col-span-full bg-white rounded-lg p-6 text-center border border-slate-200 text-xs text-slate-600">
            Không tìm thấy sản phẩm phù hợp. Vui lòng gọi <strong>0905 205 219</strong> để được tư vấn trực tiếp.
          </div>
        `;
        return;
      }

      container.innerHTML = list.map(item => `
        <div class="product-small box bg-white rounded-lg border border-slate-200 hover:border-brand-blue shadow-sm hover:shadow-md transition flex flex-col justify-between relative overflow-hidden group">
          
          <!-- Nhãn % giảm giá giống Flatsome ở góc trên bên trái -->
          <div class="badge-container-flatsome">
            <div class="onsale-flatsome">${item.discountPercent}</div>
          </div>

          <div>
            <!-- Khung ảnh sản phẩm thực tế từ Google Drive -->
            <div onclick="openProductModal(${item.id})" class="cursor-pointer w-full aspect-square bg-slate-50 flex items-center justify-center p-2.5 overflow-hidden border-b border-slate-100">
              <img 
                src="https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800" 
                alt="${item.name}"
                onerror="handleDriveImgError(this, '${item.driveId}', 'Son Chính Hang')"
                class="w-full h-full object-contain group-hover:scale-105 transition duration-300"
                loading="lazy"
              >
            </div>

            <!-- Nội dung thông tin sản phẩm: Tên sản phẩm đầy đủ không bị cắt chữ -->
            <div class="p-2.5 sm:p-3 space-y-1.5">
              <div class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase">
                ${item.categoryLabel}
              </div>

              <h3 onclick="openProductModal(${item.id})" class="product-title-full cursor-pointer text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-blue transition">
                ${item.name}
              </h3>

              <p class="text-[11px] text-slate-500 leading-snug">
                ${item.spec}
              </p>
            </div>
          </div>

          <!-- Giá giảm giá & Hotline báo giá giống Flatsome -->
          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100 space-y-2">
            <div class="flex items-baseline flex-wrap gap-x-2 gap-y-0.5">
              <del class="text-[11px] text-slate-400 font-medium">${item.oldPrice}</del>
              <ins class="text-xs sm:text-sm font-extrabold text-brand-red no-underline">${item.newPrice}</ins>
            </div>

            <div class="text-[11px] text-slate-600 flex items-center justify-between bg-slate-50 px-2 py-1 rounded">
              <span>Giá sỉ liên hệ:</span>
              <a href="tel:0905205219" class="font-extrabold text-brand-blue hover:underline">0905 205 219</a>
            </div>
          </div>

        </div>
      `).join('');
    }

    /* Render 6 ảnh công ty từ Google Drive */
    function renderCompanyGallery() {
      const container = document.getElementById('companyGalleryGrid');
      container.innerHTML = COMPANY_PHOTOS.map((photo, idx) => `
        <div class="bg-slate-50 rounded-lg overflow-hidden border border-slate-200 shadow-sm group flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img 
              src="https://drive.google.com/thumbnail?id=${photo.driveId}&sz=w800" 
              alt="${photo.title}"
              onerror="handleDriveImgError(this, '${photo.driveId}', 'Dai Dong Paint ${idx + 1}')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              loading="lazy"
            >
          </div>
          <div class="p-2 text-[11px] font-semibold text-slate-700 text-center leading-snug">
            ${photo.title}
          </div>
        </div>
      `).join('');
    }

    /* Render danh sách bài viết trang chủ */
    function renderBlogPosts(filterCat = 'all') {
      const container = document.getElementById('blogGridContainer');
      const filtered = filterCat === 'all' ? BLOG_POSTS : BLOG_POSTS.filter(p => p.cat === filterCat);

      container.innerHTML = filtered.map(post => `
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="aspect-[16/10] bg-slate-100 overflow-hidden relative">
              <img 
                src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w600" 
                alt="${post.title}"
                onerror="handleDriveImgError(this, '${post.driveId}', 'Tin Tuc Son')"
                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                loading="lazy"
              >
              <span class="absolute top-2 left-2 bg-brand-blue text-white text-[10px] font-bold px-2 py-0.5 rounded">
                ${post.catName}
              </span>
            </div>
            <div class="p-3 space-y-1.5">
              <div class="text-[11px] text-slate-400">
                <i class="fa-regular fa-calendar mr-1"></i>${post.date}
              </div>
              <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-blue transition">
                ${post.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                ${post.excerpt}
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 pt-1">
            <a href="#bao-gia-form" class="text-xs font-bold text-brand-blue hover:text-brand-orange inline-flex items-center gap-1">
              Nhận tư vấn chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </a>
          </div>
        </article>
      `).join('');
    }

    /* Lọc sản phẩm theo danh mục */
    function filterCategory(catKey) {
      const buttons = document.querySelectorAll('[data-cat-btn]');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-cat-btn') === catKey) {
          btn.className = 'cat-nav-item px-2.5 py-1 rounded text-[12px] font-bold bg-brand-blue text-white transition';
        } else {
          btn.className = 'cat-nav-item px-2.5 py-1 rounded text-[12px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-blue hover:text-brand-blue transition';
        }
      });

      const titleMap = {
        'all': 'SẢN PHẨM NỔI BẬT DULUX & JOTUN',
        'son-phu-noi-that': 'DANH MỤC: SƠN PHỦ NỘI THẤT',
        'son-phu-ngoai-that': 'DANH MỤC: SƠN PHỦ NGOẠI THẤT',
        'son-lot': 'DANH MỤC: SƠN LÓT CHỐNG KIỀM',
        'son-chong-tham': 'DANH MỤC: SƠN CHỐNG THẤM',
        'bot-tret': 'DANH MỤC: BỘT TRÉT TƯỜNG',
        'son-dulux': 'DANH MỤC: SƠN DULUX CHÍNH HÃNG',
        'son-jotun': 'DANH MỤC: SƠN JOTUN CHÍNH HÃNG'
      };
      document.getElementById('activeCategoryHeading').textContent = titleMap[catKey] || 'SẢN PHẨM NỔI BẬT';

      if (catKey === 'all') {
        renderProducts(PRODUCTS);
      } else if (catKey === 'son-dulux' || catKey === 'son-jotun') {
        renderProducts(PRODUCTS.filter(p => p.brand === catKey));
      } else {
        renderProducts(PRODUCTS.filter(p => p.category === catKey));
      }
    }

    /* Tìm kiếm sản phẩm theo từ khóa */
    function filterProductsBySearch(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      if (!q) {
        renderProducts(PRODUCTS);
        return;
      }
      const matched = PRODUCTS.filter(p => 
        p.name.toLowerCase().includes(q) ||
        p.categoryLabel.toLowerCase().includes(q) ||
        p.spec.toLowerCase().includes(q)
      );
      renderProducts(matched);
    }

    /* Lọc danh mục bài viết */
    function filterPosts(catKey) {
      document.querySelectorAll('.post-cat-btn').forEach(btn => {
        if (btn.getAttribute('data-post-cat') === catKey) {
          btn.className = 'post-cat-btn text-xs px-2.5 py-1 rounded bg-brand-blue text-white font-semibold whitespace-nowrap';
        } else {
          btn.className = 'post-cat-btn text-xs px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 font-semibold whitespace-nowrap';
        }
      });
      renderBlogPosts(catKey);
    }

    /* Mở Modal xem chi tiết sản phẩm */
    function openProductModal(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      const modal = document.getElementById('detailModal');
      const body = document.getElementById('detailModalBody');
      body.innerHTML = `
        <div class="space-y-3">
          <div class="w-48 h-48 mx-auto bg-slate-50 rounded-lg p-2 border border-slate-200 flex items-center justify-center">
            <img 
              src="https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800" 
              alt="${product.name}"
              onerror="handleDriveImgError(this, '${product.driveId}', 'Dai Dong Paint')"
              class="w-full h-full object-contain"
            >
          </div>
          <div class="text-xs font-bold text-brand-blue uppercase">${product.categoryLabel}</div>
          <h3 class="text-sm sm:text-base font-extrabold text-slate-900">${product.name}</h3>
          <div class="flex items-center gap-3">
            <span class="px-2 py-0.5 rounded bg-brand-red text-white text-xs font-bold">${product.discountPercent}</span>
            <del class="text-xs text-slate-400">${product.oldPrice}</del>
            <span class="text-base font-extrabold text-brand-red">${product.newPrice}</span>
          </div>
          <p class="text-xs text-slate-600 leading-relaxed">${product.spec}. Phân phối chính hãng bởi <strong>CÔNG TY TNHH MTV ĐẠI ĐỒNG PAINT</strong>.</p>
          <div class="bg-slate-50 p-3 rounded border border-slate-200 text-xs space-y-1">
            <div><strong>Địa chỉ 1:</strong> 534 Ngô Quyền, Phường An Hải, TP. Đà Nẵng</div>
            <div><strong>Địa chỉ 2:</strong> 154 Lê Ấm, Phường Hòa Xuân, TP. Đà Nẵng</div>
            <div><strong>Hotline đặt hàng:</strong> <a href="tel:0905205219" class="text-brand-red font-extrabold">0905 205 219</a></div>
          </div>
          <div class="flex gap-2 pt-1">
            <a href="tel:0905205219" class="flex-1 py-2.5 rounded bg-brand-blue text-white text-center text-xs font-extrabold uppercase">
              <i class="fa-solid fa-phone mr-1"></i>Gọi 0905 205 219
            </a>
            <a href="https://zalo.me/0905205219" target="_blank" rel="noopener" class="flex-1 py-2.5 rounded bg-brand-orange text-slate-900 text-center text-xs font-extrabold uppercase">
              Nhắn Zalo Báo Giá
            </a>
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /* Chuyển đổi địa chỉ trên Google Maps ngoài trang chủ */
    function switchGoogleMap(queryAddress, displayLabel) {
      const iframe = document.getElementById('googleMapIframe');
      const label = document.getElementById('currentMapLabel');
      const extLink = document.getElementById('externalMapLink');

      iframe.src = 'https://maps.google.com/maps?q=' + encodeURIComponent(queryAddress) + '&t=&z=16&ie=UTF8&iwloc=&output=embed';
      label.innerHTML = '<i class="fa-solid fa-location-dot text-brand-red mr-1"></i>' + displayLabel;
      extLink.href = 'https://www.google.com/maps/search/?api=1&query=' + encodeURIComponent(queryAddress);
    }

    /* Xử lý gửi Form Yêu Cầu Báo Giá */
    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const brand = document.getElementById('qBrand').value;
      const type = document.getElementById('qType').value;

      const alertBox = document.getElementById('quoteSuccessAlert');
      alertBox.classList.remove('hidden');
      alertBox.innerHTML = `
        <i class="fa-solid fa-circle-check mr-1"></i>
        Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${brand} - ${type}</strong> đã được ghi nhận. Bộ phận kinh doanh <strong>Đại Đồng Paint (0905 205 219)</strong> sẽ liên hệ tư vấn ngay!
      `;
      document.getElementById('quoteRequestForm').reset();
    }

    /* Xử lý đóng/mở menu trên điện thoại */
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      drawer.classList.toggle('hidden');
    }

    /* Xử lý 2 Banner tự trượt chuyên nghiệp */
    let currentSlideIndex = 0;
    const totalSlides = 2;
    let slideInterval = null;

    function showSlide(index) {
      currentSlideIndex = (index + totalSlides) % totalSlides;
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.banner-dot');

      slides.forEach((slide, idx) => {
        if (idx === currentSlideIndex) {
          slide.classList.remove('hidden');
          slide.classList.add('block');
        } else {
          slide.classList.remove('block');
          slide.classList.add('hidden');
        }
      });

      dots.forEach((dot, idx) => {
        if (idx === currentSlideIndex) {
          dot.className = 'banner-dot w-2.5 h-2.5 rounded-full bg-brand-orange transition';
        } else {
          dot.className = 'banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition';
        }
      });
    }

    function changeSlide(step) {
      showSlide(currentSlideIndex + step);
      resetSlideTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        showSlide(currentSlideIndex + 1);
      }, 5000);
    }

    /* Khởi tạo khi tải trang */
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts(PRODUCTS);
      renderCompanyGallery();
      renderBlogPosts('all');
      resetSlideTimer();
    });
  </script>
</body>
</html>
