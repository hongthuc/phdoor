<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>PH DOOR - Công Ty TNHH Sản Xuất Và Thương Mại PH DOOR | Chuyên Nhôm Kính Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR (phdoor.vn) chuyên sản xuất, thi công Cửa nhôm Xingfa, Cửa nhôm Slim, Cửa kính cường lực, Cầu thang kính, Tủ bếp nhôm kính uy tín tại 629 Lê Văn Hiến, Đà Nẵng. Hotline: 077.9533.457">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://phdoor.vn/">
    <meta property="og:site_name" content="PH DOOR - Chuyên Nhôm Kính Đà Nẵng">
    <meta property="og:title" content="CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR - Nhôm Kính Cao Cấp Đà Nẵng">
    <meta property="og:description" content="Chuyên sản xuất & thi công cửa nhôm Xingfa, cửa nhôm Slim, cửa trượt quay, kính cường lực, vách kính, tủ bếp nhôm kính tại Đà Nẵng. Đ/c: 629 Lê Văn Hiến, Ngũ Hành Sơn, Đà Nẵng. SĐT: 077.9533.457">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Sản Xuất Và Thương Mại PH DOOR">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Roboto / Inter chuẩn Flatsome) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

    <style>
        /* Reset chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Roboto', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chuẩn khung Container Flatsome (1200px) */
        .fs-container {
            width: 100%;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Normal / Center) */
        .fs-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 20px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .fs-section-title-main {
            background-color: #0f4c81;
            color: #ffffff;
            font-weight: 700;
            font-size: 16px;
            padding: 9px 18px;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            border-top-left-radius: 6px;
            border-top-right-radius: 6px;
            margin-bottom: -2px;
        }
        @media (min-width: 768px) {
            .fs-section-title-main {
                font-size: 18px;
                padding: 10px 24px;
            }
        }

        /* Banner Slider 2 ảnh bằng kích thước tuyệt đối */
        .banner-slider-wrap {
            position: relative;
            width: 100%;
            height: 250px;
            overflow: hidden;
            background-color: #0f172a;
        }
        @media (min-width: 640px) {
            .banner-slider-wrap {
                height: 340px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slider-wrap {
                height: 440px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: opacity 0.7s ease-in-out;
            pointer-events: none;
        }
        .banner-slide.active {
            opacity: 1;
            pointer-events: auto;
        }

        /* Tên sản phẩm & dự án hiển thị đầy đủ, tự xuống dòng, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            word-break: break-word;
            line-height: 1.4;
            display: block;
        }

        /* Nút liên hệ nổi bật cố định */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         1. TOP BAR CHUẨN FLATSOME
         ========================================== -->
    <div class="bg-[#0b3b66] text-white text-xs sm:text-sm py-2 border-b border-white/10">
        <div class="fs-container flex flex-col sm:flex-row items-center justify-between gap-1 sm:gap-4 text-center sm:text-left">
            <div class="font-medium break-words max-w-full">
                <i class="fa-solid fa-building mr-1.5 text-amber-400"></i>
                <span>CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR - Website: <strong>phdoor.vn</strong></span>
            </div>
            <div class="flex flex-wrap items-center justify-center gap-3 text-xs">
                <span><i class="fa-solid fa-location-dot mr-1 text-amber-400"></i>629 Lê Văn Hiến, P. Ngũ Hành Sơn, Đà Nẵng</span>
                <span class="hidden md:inline">|</span>
                <span><i class="fa-regular fa-clock mr-1 text-amber-400"></i>07:30 - 18:00 (T2 - CN)</span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2. HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="fs-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo + Tên công ty -->
            <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 max-w-[82%] sm:max-w-none">
                <img src="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA&sz=w400';"
                     alt="Logo PH DOOR"
                     class="h-11 w-11 sm:h-14 sm:w-14 object-contain rounded border border-slate-100 bg-white shrink-0">
                <div class="min-w-0">
                    <div class="text-[#0f4c81] font-black text-base sm:text-xl leading-tight tracking-tight break-words">
                        PH DOOR ĐÀ NẴNG
                    </div>
                    <div class="text-slate-600 text-[11px] sm:text-xs font-medium leading-snug break-words">
                        CÔNG TY TNHH SX & TM PH DOOR
                    </div>
                </div>
            </a>

            <!-- Ô tìm kiếm trên máy tính (Flatsome Header Search) -->
            <div class="hidden lg:flex items-center flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input id="desktopSearchInput" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa Slim, cầu thang kính..."
                           oninput="handleSearchProduct(this.value)"
                           class="w-full pl-3.5 pr-10 py-2 text-sm border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]">
                    <button type="button" onclick="scrollToSection('san-pham-thuc-te')" class="absolute right-0 top-0 h-full px-3 text-slate-500 hover:text-[#0f4c81]">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Menu ngang trên máy tính -->
            <nav class="hidden xl:flex items-center gap-5 text-sm font-bold text-slate-700 shrink-0">
                <a href="#trang-chu" class="text-[#0f4c81] hover:text-amber-600 transition">TRANG CHỦ</a>
                <a href="#gioi-thieu" class="hover:text-[#0f4c81] transition">GIỚI THIỆU</a>
                <a href="#danh-muc-he-thong" class="hover:text-[#0f4c81] transition">DANH MỤC</a>
                <a href="#san-pham-thuc-te" class="hover:text-[#0f4c81] transition">SẢN PHẨM</a>
                <a href="#du-an-da-nang" class="hover:text-[#0f4c81] transition">DỰ ÁN ĐÀ NẴNG</a>
                <a href="#tin-tuc" class="hover:text-[#0f4c81] transition">BÀI VIẾT</a>
                <a href="#bao-gia-lien-he" class="hover:text-[#0f4c81] transition">LIÊN HỆ</a>
            </nav>

            <!-- Nút mở Menu trên Điện Thoại / Tablet -->
            <button type="button" onclick="toggleMobileMenu()" aria-label="Mở menu"
                    class="xl:hidden p-2.5 rounded border border-slate-200 text-slate-700 hover:bg-slate-100 shrink-0">
                <i id="mobileMenuIcon" class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Thanh danh mục ngang trên máy tính (Flatsome Header Bottom Nav) -->
        <div class="hidden md:block bg-[#0f4c81] text-white border-t border-white/10">
            <div class="fs-container flex items-center justify-between text-xs lg:text-[13px] font-semibold py-2 overflow-x-auto">
                <a href="#cat-xingfa" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-door-open mr-1"></i>CỬA NHÔM XINGFA</a>
                <a href="#cat-slim" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-table-columns mr-1"></i>CỬA NHÔM SLIM</a>
                <a href="#cat-cuakinh" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-border-all mr-1"></i>CỬA KÍNH CƯỜNG LỰC</a>
                <a href="#cat-truotquay" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-arrows-left-right mr-1"></i>CỬA TRƯỢT QUAY</a>
                <a href="#cat-vachkinh" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-layer-group mr-1"></i>VÁCH NGĂN & CẦU THANG KÍNH</a>
                <a href="#cat-tubep" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-kitchen-set mr-1"></i>TỦ BẾP & KÍNH ỐP BẾP</a>
                <a href="#cat-suachua" class="px-2.5 py-1 hover:text-amber-300 whitespace-nowrap transition"><i class="fa-solid fa-screwdriver-wrench mr-1"></i>MÁI KÍNH & SỬA CHỮA</a>
            </div>
        </div>

        <!-- Menu xổ xuống trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden xl:hidden bg-white border-t border-slate-200">
            <div class="fs-container py-3 space-y-2">
                <div class="relative mb-2">
                    <input type="text" placeholder="Tìm nhanh sản phẩm..."
                           oninput="handleSearchProduct(this.value)"
                           class="w-full pl-3 pr-9 py-2 text-sm border border-slate-300 rounded">
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-2.5 text-slate-400"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-bold text-slate-700">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">TRANG CHỦ</a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">GIỚI THIỆU</a>
                    <a href="#danh-muc-he-thong" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">DANH MỤC SẢN PHẨM</a>
                    <a href="#san-pham-thuc-te" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">SẢN PHẨM THỰC TẾ</a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">DỰ ÁN TẠI ĐÀ NẴNG</a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100">BÀI VIẾT - TIN TỨC</a>
                    <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="p-2 bg-slate-50 rounded hover:bg-slate-100 col-span-2 text-center text-[#0f4c81]">BÁO GIÁ & BẢN ĐỒ LIÊN HỆ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         3. SLIDER 2 ẢNH BANNER TỰ TRƯỢT BẰNG KÍCH THƯỚC
         (Tối ưu chữ trên điện thoại không tràn viền, không dán nhãn phụ)
         ========================================== -->
    <section id="trang-chu" class="w-full bg-slate-900">
        <div class="banner-slider-wrap" id="heroSlider">
            <!-- Slide 1 -->
            <div class="banner-slide active" data-slide="0">
                <img src="https://lh3.googleusercontent.com/d/1lm6sQ8y_DPf25C41IfKHaw6m2hcCeXfO"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lm6sQ8y_DPf25C41IfKHaw6m2hcCeXfO&sz=w1200';"
                     alt="Banner 1 PH DOOR"
                     class="w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/70 to-slate-900/40 flex items-center">
                    <div class="fs-container">
                        <div class="max-w-2xl text-white px-2 sm:px-4">
                            <p class="text-amber-400 font-bold text-xs sm:text-sm md:text-base uppercase tracking-wider mb-1 break-words">
                                CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR
                            </p>
                            <h1 class="text-lg sm:text-2xl md:text-4xl font-black leading-snug mb-2 break-words">
                                CHUYÊN SẢN XUẤT & THI CÔNG NHÔM KÍNH CAO CẤP TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 mb-3 sm:mb-5 leading-relaxed break-words">
                                Cửa Nhôm Xingfa Nhập Khẩu – Cửa Nhôm Slim – Cửa Trượt Quay – Kính Cường Lực – Tủ Bếp Nhôm Kính. Gia công chuẩn xác, bền đẹp vượt thời gian.
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="#bao-gia-lien-he" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded transition">
                                    NHẬN BÁO GIÁ TẠI XƯỞNG
                                </a>
                                <a href="#san-pham-thuc-te" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded transition">
                                    XEM SẢN PHẨM
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2 (Cùng kích thước 100% với Slide 1) -->
            <div class="banner-slide" data-slide="1">
                <img src="https://lh3.googleusercontent.com/d/1LV26DvdILrrExb1aRkajRojU-tIeshFC"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1LV26DvdILrrExb1aRkajRojU-tIeshFC&sz=w1200';"
                     alt="Banner 2 PH DOOR"
                     class="w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/70 to-slate-900/40 flex items-center">
                    <div class="fs-container">
                        <div class="max-w-2xl text-white px-2 sm:px-4">
                            <p class="text-amber-400 font-bold text-xs sm:text-sm md:text-base uppercase tracking-wider mb-1 break-words">
                                XƯỞNG SẢN XUẤT TRỰC TIẾP - PHDOOR.VN
                            </p>
                            <h2 class="text-lg sm:text-2xl md:text-4xl font-black leading-snug mb-2 break-words">
                                GIẢI PHÁP CỬA ĐẸP & NỘI THẤT NHÔM KÍNH BỀN VỮNG CHO MỌI CÔNG TRÌNH
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 mb-3 sm:mb-5 leading-relaxed break-words">
                                Địa chỉ: 629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng. Khảo sát tận nơi miễn phí – Báo giá minh bạch – Bảo hành uy tín dài hạn.
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="tel:0779533457" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded transition">
                                    HOTLINE: 077.9533.457
                                </a>
                                <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded transition">
                                    DỰ ÁN ĐÃ THI CÔNG
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút chuyển slide trái/phải -->
            <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước"
                    class=" hidden sm:flex absolute left-3 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/40 hover:bg-black/70 text-white items-center justify-center z-10">
                <i class="fa-solid fa-chevron-left text-sm"></i>
            </button>
            <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp"
                    class="hidden sm:flex absolute right-3 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/40 hover:bg-black/70 text-white items-center justify-center z-10">
                <i class="fa-solid fa-chevron-right text-sm"></i>
            </button>

            <!-- Dấu chấm điều hướng -->
            <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                <button type="button" onclick="goToSlide(0)" id="sliderDot0" class="w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Banner 1"></button>
                <button type="button" onclick="goToSlide(1)" id="sliderDot1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         4. DANH MỤC SẢN PHẨM (TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI)
         Lấy đúng hệ danh mục từ chuyennhomkinhdanang.com
         ========================================== -->
    <section id="danh-muc-he-thong" class="py-7 sm:py-10 bg-white border-b border-slate-200">
        <div class="fs-container">
            <div class="text-center mb-6">
                <h2 class="text-lg sm:text-2xl font-black text-[#0f4c81] uppercase">
                    DANH MỤC SẢN PHẨM & DỊCH VỤ PH DOOR
                </h2>
                <div class="w-16 h-1 bg-amber-500 mx-auto mt-2"></div>
                <p class="text-xs sm:text-sm text-slate-600 mt-2">
                    Chọn danh mục để xem nhanh các dòng sản phẩm nhôm kính cao cấp tại Đà Nẵng
                </p>
            </div>

            <!-- Grid Danh Mục: 2 cột trên điện thoại, 5 cột trên máy tính cân đối tuyệt đẹp -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4">
                <!-- 1. Cửa nhôm Xingfa -->
                <a href="#cat-xingfa" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-door-open text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CỬA NHÔM XINGFA</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Mở quay, mở lùa, xếp trượt</span>
                </a>

                <!-- 2. Cửa nhôm Slim -->
                <a href="#cat-slim" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-table-columns text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CỬA NHÔM SLIM</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Hệ trượt không ray dưới, mở quay</span>
                </a>

                <!-- 3. Cửa kính cường lực -->
                <a href="#cat-cuakinh" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-border-all text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CỬA KÍNH CƯỜNG LỰC</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Cửa thủy lực, bản lề sàn, cửa lùa</span>
                </a>

                <!-- 4. Cửa trượt quay -->
                <a href="#cat-truotquay" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-arrows-left-right text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CỬA TRƯỢT QUAY</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">2 cánh, 4 cánh vân gỗ, ghi, cà phê</span>
                </a>

                <!-- 5. Cửa nhựa lõi thép -->
                <a href="#cat-truotquay" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-window-maximize text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CỬA NHỰA LÕI THÉP</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Cách âm, cách nhiệt, giá tận xưởng</span>
                </a>

                <!-- 6. Vách ngăn nhôm kính -->
                <a href="#cat-vachkinh" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-layer-group text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">VÁCH NGĂN NHÔM KÍNH</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Vách mặt dựng, vách tắm kính</span>
                </a>

                <!-- 7. Cầu thang kính -->
                <a href="#cat-vachkinh" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-stairs text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">CẦU THANG & LAN CAN KÍNH</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Tay vịn gỗ, inox, ban công kính</span>
                </a>

                <!-- 8. Tủ bếp nhôm kính -->
                <a href="#cat-tubep" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-kitchen-set text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">TỦ BẾP NHÔM KÍNH</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Tủ bếp cánh kính, hợp kim, tủ rượu</span>
                </a>

                <!-- 9. Kính ốp bếp -->
                <a href="#cat-tubep" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-palette text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">KÍNH ỐP BẾP MÀU</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Đủ màu phong thủy, dễ lau chùi</span>
                </a>

                <!-- 10. Mái kính & Sửa chữa -->
                <a href="#cat-suachua" class="group bg-slate-50 hover:bg-[#0f4c81] border border-slate-200 rounded-lg p-3 sm:p-4 flex flex-col items-center text-center transition">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-100 group-hover:bg-white/20 text-[#0f4c81] group-hover:text-white flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-screwdriver-wrench text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800 group-hover:text-white product-title-full">MÁI KÍNH & SỬA CHỮA</h3>
                    <span class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5">Mái hiên kính, thay phụ kiện cửa</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         5. GIỚI THIỆU NGẮN VỀ PH DOOR ĐÀ NẴNG
         ========================================== -->
    <section id="gioi-thieu" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="fs-container">
            <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-6 md:p-8 grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-bold text-amber-600 uppercase tracking-wider">VỀ CHÚNG TÔI - PHDOOR.VN</div>
                    <h2 class="text-lg sm:text-2xl font-black text-[#0f4c81] leading-snug">
                        CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR
                    </h2>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        <strong>PH DOOR</strong> mang đến giải pháp nhôm kính bền vững cho mọi công trình nhà phố, biệt thự, khách sạn và văn phòng tại Đà Nẵng & Miền Trung. Mỗi sản phẩm được gia công chuẩn xác tại xưởng <strong>629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng</strong>, lắp đặt tinh gọn, tạo nên không gian sang trọng và chắc chắn.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                        <div class="bg-slate-50 p-3 rounded border border-slate-200 text-center">
                            <div class="text-[#0f4c81] font-black text-base sm:text-lg">100%</div>
                            <div class="text-xs text-slate-600">Phụ kiện chính hãng</div>
                        </div>
                        <div class="bg-slate-50 p-3 rounded border border-slate-200 text-center">
                            <div class="text-[#0f4c81] font-black text-base sm:text-lg">Giá Xưởng</div>
                            <div class="text-xs text-slate-600">Không qua trung gian</div>
                        </div>
                        <div class="bg-slate-50 p-3 rounded border border-slate-200 text-center">
                            <div class="text-[#0f4c81] font-black text-base sm:text-lg">Kịp Tiến Độ</div>
                            <div class="text-xs text-slate-600">Khảo sát trong 30p</div>
                        </div>
                        <div class="bg-slate-50 p-3 rounded border border-slate-200 text-center">
                            <div class="text-[#0f4c81] font-black text-base sm:text-lg">Bảo Hành</div>
                            <div class="text-xs text-slate-600">Lâu dài, tận tâm</div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5">
                    <img src="https://lh3.googleusercontent.com/d/1-xXVCwg5cbxqXl4l8-BDWOUSCO_ArBIn"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-xXVCwg5cbxqXl4l8-BDWOUSCO_ArBIn&sz=w800';"
                         alt="Xưởng sản xuất và sản phẩm thực tế PH DOOR"
                         class="w-full h-60 sm:h-72 object-cover rounded-lg border border-slate-200">
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         6. HỆ THỐNG SẢN PHẨM THỰC TẾ (13 ẢNH DRIVE THỰC TẾ)
         - Điện thoại: 2 cột (grid-cols-2)
         - Tên sản phẩm: Hiển thị đầy đủ, không cắt chữ, không tràn viền
         - Không có nhãn dán đè lên ảnh sản phẩm
         ========================================== -->
    <section id="san-pham-thuc-te" class="py-8 sm:py-12">
        <div class="fs-container space-y-10">

            <!-- Thông báo lọc tìm kiếm nếu có -->
            <div id="searchFilterNotice" class="hidden bg-amber-50 border border-amber-300 text-slate-800 px-4 py-2.5 rounded flex items-center justify-between text-sm">
                <span id="searchFilterText">Đang lọc sản phẩm</span>
                <button type="button" onclick="clearProductSearch()" class="text-xs font-bold text-red-600 hover:underline">Xóa bộ lọc</button>
            </div>

            <!-- DANH MỤC 1: CỬA NHÔM XINGFA & CỬA NHÔM SLIM -->
            <div id="cat-xingfa" class="product-category-block">
                <div id="cat-slim" class="fs-section-title">
                    <h2 class="fs-section-title-main">
                        <i class="fa-solid fa-door-open"></i> CỬA NHÔM XINGFA & CỬA NHÔM SLIM THỰC TẾ
                    </h2>
                    <a href="#bao-gia-lien-he" class="text-xs sm:text-sm font-bold text-[#0f4c81] hover:underline py-1">
                        Nhận báo giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-xingfa-slim"></div>
            </div>

            <!-- DANH MỤC 2: CỬA KÍNH CƯỜNG LỰC, CỬA TRƯỢT QUAY & CỬA NHỰA LÕI THÉP -->
            <div id="cat-cuakinh" class="product-category-block">
                <div id="cat-truotquay" class="fs-section-title">
                    <h2 class="fs-section-title-main">
                        <i class="fa-solid fa-border-all"></i> CỬA KÍNH CƯỜNG LỰC, CỬA TRƯỢT QUAY & NHỰA LÕI THÉP
                    </h2>
                    <a href="#bao-gia-lien-he" class="text-xs sm:text-sm font-bold text-[#0f4c81] hover:underline py-1">
                        Nhận báo giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-cuakinh-truotquay"></div>
            </div>

            <!-- DANH MỤC 3: VÁCH NGĂN NHÔM KÍNH, CẦU THANG KÍNH, TỦ BẾP & KÍNH ỐP BẾP -->
            <div id="cat-vachkinh" class="product-category-block">
                <div id="cat-tubep" class="fs-section-title">
                    <h2 class="fs-section-title-main">
                        <i class="fa-solid fa-kitchen-set"></i> VÁCH NGĂN, CẦU THANG KÍNH, TỦ BẾP & MÁI KÍNH
                    </h2>
                    <a href="#bao-gia-lien-he" class="text-xs sm:text-sm font-bold text-[#0f4c81] hover:underline py-1">
                        Nhận báo giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>
                <div id="cat-suachua" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
            </div>

        </div>
    </section>

    <!-- ==========================================
         7. DANH MỤC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (12 ẢNH DRIVE THỰC TẾ)
         - Điện thoại: 2 cột (grid-cols-2)
         - Không gắn nhãn dán, tên đầy đủ không tràn chữ
         ========================================== -->
    <section id="du-an-da-nang" class="py-8 sm:py-12 bg-white border-t border-b border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="fs-section-title-main">
                    <i class="fa-solid fa-helmet-safety"></i> DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG
                </h2>
                <span class="text-xs sm:text-sm text-slate-600 font-medium">
                    Hình ảnh công trình thực tế do đội ngũ kỹ thuật PH DOOR lắp đặt
                </span>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5" id="projectsGrid"></div>
        </div>
    </section>

    <!-- ==========================================
         8. DANH MỤC BÀI VIẾT & KINH NGHIỆM TRANG CHỦ
         ========================================== -->
    <section id="tin-tuc" class="py-8 sm:py-12 bg-slate-50 border-b border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="fs-section-title-main">
                    <i class="fa-regular fa-newspaper"></i> BÀI VIẾT & KINH NGHIỆM NHÔM KÍNH
                </h2>
                <span class="text-xs sm:text-sm text-slate-600 font-medium">
                    Tư vấn kỹ thuật và báo giá nhôm kính Đà Nẵng
                </span>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5" id="blogGrid"></div>
        </div>
    </section>

    <!-- ==========================================
         9. FORM YÊU CẦU BÁO GIÁ + FANPAGE + GOOGLE MAPS NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="bao-gia-lien-he" class="py-8 sm:py-12 bg-white">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="fs-section-title-main">
                    <i class="fa-solid fa-file-signature"></i> YÊU CẦU BÁO GIÁ, FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI
                </h2>
                <span class="text-xs sm:text-sm font-bold text-[#0f4c81]">
                    Hotline/Zalo: 077.9533.457
                </span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                <!-- Cột 1 (5/12): Form Yêu Cầu Tư Vấn & Báo Giá Trang Chủ -->
                <div class="lg:col-span-5 bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-6">
                    <h3 class="text-base sm:text-lg font-black text-[#0f4c81] uppercase mb-1">
                        ĐĂNG KÝ NHẬN BÁO GIÁ NHANH
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 mb-4">
                        Quý khách để lại thông tin hoặc kích thước sơ bộ, kỹ thuật viên PH DOOR sẽ liên hệ tư vấn và báo giá tận xưởng trong 5 phút.
                    </p>

                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                            <input type="text" id="custName" required placeholder="Nhập họ và tên của bạn"
                                   class="w-full px-3 py-2 text-sm bg-white border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                            <input type="tel" id="custPhone" required placeholder="Ví dụ: 0905xxxxxx"
                                   class="w-full px-3 py-2 text-sm bg-white border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần tư vấn & báo giá *</label>
                            <select id="custCategory" class="w-full px-3 py-2 text-sm bg-white border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]">
                                <option value="Cửa nhôm Xingfa nhập khẩu">Cửa nhôm Xingfa nhập khẩu</option>
                                <option value="Cửa nhôm hệ Slim cao cấp">Cửa nhôm hệ Slim cao cấp</option>
                                <option value="Cửa kính cường lực / Thủy lực">Cửa kính cường lực / Thủy lực</option>
                                <option value="Cửa trượt quay / Cửa nhựa lõi thép">Cửa trượt quay / Cửa nhựa lõi thép</option>
                                <option value="Vách ngăn nhôm kính / Phòng tắm kính">Vách ngăn nhôm kính / Phòng tắm kính</option>
                                <option value="Cầu thang kính / Lan can kính">Cầu thang kính / Lan can kính</option>
                                <option value="Tủ bếp nhôm cánh kính / Kính ốp bếp">Tủ bếp nhôm cánh kính / Kính ốp bếp</option>
                                <option value="Mái kính cường lực / Sửa chữa cửa">Mái kính cường lực / Sửa chữa cửa</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình tại Đà Nẵng</label>
                            <input type="text" id="custAddress" placeholder="Ví dụ: Ngũ Hành Sơn, Cẩm Lệ, Sơn Trà, Hải Châu..."
                                   class="w-full px-3 py-2 text-sm bg-white border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú yêu cầu / Kích thước sơ bộ</label>
                            <textarea id="custNote" rows="3" placeholder="Nhập số lượng cửa, kích thước ước lượng hoặc yêu cầu khảo sát tận nơi..."
                                      class="w-full px-3 py-2 text-sm bg-white border border-slate-300 rounded focus:outline-none focus:border-[#0f4c81]"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-[#0f4c81] hover:bg-[#0b3b66] text-white font-bold text-sm py-3 rounded transition uppercase tracking-wide">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận gửi Form thành công -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3.5 bg-emerald-50 border border-emerald-300 rounded text-xs sm:text-sm text-emerald-900">
                        <div class="font-bold mb-1"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Đã ghi nhận yêu cầu báo giá!</div>
                        <p id="quoteSuccessDetail" class="mb-2"></p>
                        <div class="flex flex-wrap gap-2">
                            <a href="https://zalo.me/0779533457" target="_blank" rel="noopener noreferrer"
                               class="inline-flex items-center gap-1.5 bg-blue-600 text-white font-bold px-3 py-1.5 rounded text-xs">
                                <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo 077.9533.457
                            </a>
                            <a href="tel:0779533457"
                               class="inline-flex items-center gap-1.5 bg-red-600 text-white font-bold px-3 py-1.5 rounded text-xs">
                                <i class="fa-solid fa-phone"></i> Gọi 077.9533.457
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Cột 2 (7/12): Fanpage Facebook & Google Maps Ngoài Trang Chủ -->
                <div class="lg:col-span-7 space-y-6">
                    <!-- Khối Fanpage chính thức ngoài trang chủ -->
                    <div class="bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-5">
                        <h3 class="text-sm sm:text-base font-black text-[#0f4c81] uppercase mb-3 flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-blue-600 text-lg"></i> KẾT NỐI FANPAGE FACEBOOK PH DOOR
                        </h3>
                        
                        <div class="grid grid-cols-1 md:grid-cols-12 gap-4 items-center">
                            <!-- Thẻ thông tin trực tiếp Fanpage -->
                            <div class="md:col-span-6 bg-white p-3.5 rounded border border-slate-200 flex flex-col justify-between h-full">
                                <div class="flex items-center gap-3 mb-3">
                                    <img src="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA&sz=w300';"
                                         alt="Avatar Fanpage PH DOOR"
                                         class="w-14 h-14 rounded-full object-contain border border-slate-200 shrink-0">
                                    <div class="min-w-0">
                                        <a href="https://www.facebook.com/profile.php?id=61552975239323&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                                           class="font-bold text-sm text-blue-700 hover:underline block product-title-full">
                                            CÔNG TY TNHH SX & TM PH DOOR
                                        </a>
                                        <span class="text-xs text-slate-500 block">Chuyên Nhôm Kính Cao Cấp Đà Nẵng</span>
                                        <span class="text-xs text-emerald-600 font-medium"><i class="fa-solid fa-circle-check mr-1"></i>Đang hoạt động tại Đà Nẵng</span>
                                    </div>
                                </div>
                                <p class="text-xs text-slate-600 mb-3 leading-relaxed">
                                    Cập nhật hình ảnh thi công thực tế hằng ngày tại Fanpage chính thức của PH DOOR. Nhấn theo dõi và nhắn tin để được tư vấn mẫu mới nhất!
                                </p>
                                <div class="flex flex-wrap gap-2">
                                    <a href="https://www.facebook.com/profile.php?id=61552975239323&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                                       class="flex-1 text-center bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs py-2 px-3 rounded transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i> Xem Trang Fanpage
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61552975239323&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                                       class="flex-1 text-center bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold text-xs py-2 px-3 rounded border border-slate-300 transition">
                                        <i class="fa-brands fa-facebook-messenger mr-1 text-blue-600"></i> Gửi Tin Nhắn
                                    </a>
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chuẩn -->
                            <div class="md:col-span-6 w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                                <iframe
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61552975239323&tabs=timeline&width=320&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    width="320" height="210" style="border:none;overflow:hidden;max-width:100%;" scrolling="no" frameborder="0"
                                    allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                    title="Fanpage PH DOOR">
                                </iframe>
                            </div>
                        </div>
                    </div>

                    <!-- Khối Google Maps ngoài trang chủ: 629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng -->
                    <div class="bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-5">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <h3 class="text-sm sm:text-base font-black text-[#0f4c81] uppercase flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-red-600 text-lg"></i> BẢN ĐỒ GOOGLE MAPS PH DOOR
                                </h3>
                                <p class="text-xs text-slate-600 mt-0.5">
                                    Địa chỉ: <strong>629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng</strong>
                                </p>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=629+L%C3%AA+V%C4%83n+Hi%E1%BA%BFn,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener noreferrer"
                               class="inline-flex items-center justify-center gap-1.5 bg-white hover:bg-slate-100 text-[#0f4c81] border border-slate-300 font-bold text-xs px-3 py-1.5 rounded shrink-0">
                                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps lớn
                            </a>
                        </div>

                        <div class="w-full h-60 sm:h-72 rounded overflow-hidden border border-slate-300 bg-slate-200">
                            <iframe
                                src="https://maps.google.com/maps?q=629%20L%C3%AA%20V%C4%83n%20Hi%E1%BA%BFn,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                allowfullscreen=""
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                title="Bản đồ 629 Lê Văn Hiến, Ngũ Hành Sơn, Đà Nẵng">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         10. FOOTER 4 CỘT CHUẨN FLATSOME
         ========================================== -->
    <footer class="bg-[#0b2545] text-slate-200 pt-10 pb-20 md:pb-10 border-t-4 border-amber-500">
        <div class="fs-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="flex items-center gap-3">
                        <img src="https://lh3.googleusercontent.com/d/1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1U8jJAwWl1LPXFKHBOSPq1VHIt6jGTFWA&sz=w300';"
                             alt="Logo PH DOOR"
                             class="w-12 h-12 rounded bg-white p-1 object-contain shrink-0">
                        <div>
                            <div class="font-black text-white text-base">PH DOOR</div>
                            <div class="text-xs text-amber-400 font-semibold">Website: phdoor.vn</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        <strong>CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR</strong> chuyên tư vấn, thiết kế, sản xuất và thi công trọn gói các hạng mục Cửa nhôm Xingfa, Cửa nhôm Slim, Cửa kính cường lực, Tủ bếp nhôm kính, Cầu thang kính tại Đà Nẵng và Miền Trung.
                    </p>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 border-l-4 border-amber-400 pl-2.5">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#cat-xingfa" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm Xingfa nhập khẩu</a></li>
                        <li><a href="#cat-slim" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm Slim cao cấp</a></li>
                        <li><a href="#cat-cuakinh" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa kính cường lực - Thủy lực</a></li>
                        <li><a href="#cat-truotquay" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa trượt quay & Nhựa lõi thép</a></li>
                        <li><a href="#cat-vachkinh" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Vách ngăn nhôm kính & Cầu thang kính</a></li>
                        <li><a href="#cat-tubep" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tủ bếp nhôm kính & Kính ốp bếp</a></li>
                        <li><a href="#cat-suachua" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Mái kính & Dịch vụ sửa chữa cửa</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Cam kết -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 border-l-4 border-amber-400 pl-2.5">
                        DỊCH VỤ KHÁCH HÀNG
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Khảo sát & đo đạc tận nơi miễn phí</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Báo giá gốc trực tiếp từ xưởng sản xuất</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Cam kết thanh nhôm và phụ kiện chính hãng</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Thi công đúng tiến độ, vệ sinh sạch sẽ</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Bảo hành kỹ thuật và phụ kiện dài hạn</li>
                    </ul>
                </div>

                <!-- Cột 4: Thông tin liên hệ -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase mb-3 border-l-4 border-amber-400 pl-2.5">
                        THÔNG TIN LIÊN HỆ
                    </h4>
                    <ul class="space-y-2.5 text-xs text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-0.5 shrink-0"></i>
                            <span>Địa chỉ: 629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-amber-400 shrink-0"></i>
                            <span>Hotline / Zalo: <a href="tel:0779533457" class="text-amber-400 font-bold hover:underline">077.9533.457</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400 shrink-0"></i>
                            <span>Website: <a href="https://phdoor.vn" class="hover:underline">phdoor.vn</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-amber-400 shrink-0"></i>
                            <a href="https://www.facebook.com/profile.php?id=61552975239323&locale=vi_VN" target="_blank" rel="noopener noreferrer" class="hover:underline">
                                Fanpage: PH DOOR Đà Nẵng
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                © Bản quyền thuộc về <strong>CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR (phdoor.vn)</strong> - Đ/c: 629 Lê Văn Hiến, Phường Ngũ Hành Sơn, TP Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ==========================================
         11. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Không tràn viền, hiển thị rõ ràng trên cả máy tính và điện thoại
         ========================================== -->
    <div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61552975239323&locale=vi_VN" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0779533457" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-black text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1">Zalo: 077.9533.457</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a href="tel:0779533457"
           class="floating-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1">077.9533.457</span>
        </a>
    </div>

    <!-- ==========================================
         12. MODAL XEM CHI TIẾT ẢNH SẢN PHẨM / DỰ ÁN / BÀI VIẾT
         ========================================== -->
    <div id="detailModal" class="fixed inset-0 bg-black/75 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-lg max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="font-bold text-sm sm:text-base text-[#0f4c81] pr-3 product-title-full">Chi tiết</h3>
                <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 space-y-4">
                <img id="modalImage" src="" alt="Chi tiết PH DOOR" class="w-full max-h-[380px] object-contain bg-slate-900 rounded">
                <div id="modalContent" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2"></div>
                <div class="pt-3 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2">
                    <div class="text-xs text-slate-600">
                        <strong>CÔNG TY TNHH SX & TM PH DOOR</strong> - 629 Lê Văn Hiến, Đà Nẵng
                    </div>
                    <div class="flex gap-2">
                        <a href="tel:0779533457" class="bg-red-600 text-white text-xs font-bold px-3.5 py-2 rounded">
                            <i class="fa-solid fa-phone mr-1"></i>077.9533.457
                        </a>
                        <a href="https://zalo.me/0779533457" target="_blank" rel="noopener noreferrer" class="bg-[#0068ff] text-white text-xs font-bold px-3.5 py-2 rounded">
                            Báo giá qua Zalo
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC
         ========================================== -->
    <script>
        // Hàm tạo URL ảnh từ Google Drive ID
        function driveImg(id) {
            return `https://lh3.googleusercontent.com/d/${id}`;
        }
        function driveFallback(id) {
            return `https://drive.google.com/thumbnail?id=${id}&sz=w800`;
        }

        // 13 Ảnh Sản Phẩm Thực Tế Từ Google Drive Của Khách Hàng
        // Phân bổ vào các danh mục chuẩn của chuyennhomkinhdanang.com
        const productsData = [
            // Nhóm 1: Cửa nhôm Xingfa & Cửa nhôm Slim (5 sản phẩm thực tế)
            {
                id: 'sp1',
                group: 'xingfa-slim',
                driveId: '1-xXVCwg5cbxqXl4l8-BDWOUSCO_ArBIn',
                name: 'Cửa đi 4 cánh mở quay nhôm Xingfa nhập khẩu chính hãng tại Đà Nẵng',
                desc: 'Gia công từ thanh nhôm Xingfa Quảng Đông dày 2.0mm, kính cường lực an toàn, phụ kiện Kinlong đồng bộ kín khít, cách âm cách nhiệt vượt trội.'
            },
            {
                id: 'sp2',
                group: 'xingfa-slim',
                driveId: '1bOCJ-8jbH4fYu63vhbOEfaGiPHXVGFfp',
                name: 'Cửa đi 2 cánh mở quay nhôm Xingfa mẫu đẹp lắp đặt thực tế',
                desc: 'Thiết kế sang trọng cho cửa mặt tiền hoặc cửa ban công nhà phố, biệt thự tại Đà Nẵng. Bề mặt sơn tĩnh điện bền màu 10 năm.'
            },
            {
                id: 'sp3',
                group: 'xingfa-slim',
                driveId: '1yZFAf_M4Dgnux4S83P5e7pYcu646_5vx',
                name: 'Cửa nhôm trượt Slim 4 cánh không ray dưới siêu êm cao cấp',
                desc: 'Hệ nhôm Slim khung cánh siêu mảnh hiện đại, tích hợp giảm chấn hai chiều đóng mở nhẹ nhàng, không vướng ray sàn.'
            },
            {
                id: 'sp4',
                group: 'xingfa-slim',
                driveId: '1Xxs3wf38QRgs4EAM2zq0AQZg8uxLRiOS',
                name: 'Cửa lùa nhôm Xingfa & hệ cửa sổ mở quay nhôm Xingfa thực tế',
                desc: 'Tối ưu diện tích đóng mở, lấy sáng tối đa, chống thấm nước mưa tuyệt đối cho các công trình ven biển Đà Nẵng.'
            },
            {
                id: 'sp5',
                group: 'xingfa-slim',
                driveId: '18UoP023yc9HdFKsFfMYsonp4iY3p6rsk',
                name: 'Vách ngăn phòng hệ nhôm Slim kết hợp cửa mở quay sang trọng',
                desc: 'Giải pháp ngăn phòng khách và phòng bếp tinh tế, mở rộng tầm nhìn cho căn hộ và nhà phố hiện đại.'
            },

            // Nhóm 2: Cửa kính cường lực, Cửa trượt quay & Cửa nhựa lõi thép (4 sản phẩm thực tế)
            {
                id: 'sp6',
                group: 'cuakinh-truotquay',
                driveId: '1pkU4aBJhkZ90hxg614Mw-9DjQGicrOXc',
                name: 'Cửa kính cường lực bản lề sàn 2 cánh mở quay chính hãng',
                desc: 'Kính cường lực 10ly - 12ly kết hợp bản lề thủy lực VVP/Hafele chịu lực cao, phù hợp cho showroom, văn phòng, cửa hàng kinh doanh.'
            },
            {
                id: 'sp7',
                group: 'cuakinh-truotquay',
                driveId: '1O1GS1JEVyH9VYI1wOqhKv1-AVfcb-j4E',
                name: 'Cửa trượt quay 4 cánh nhôm cao cấp vừa trượt vừa mở quay tiện lợi',
                desc: 'Sự kết hợp hoàn hảo giữa cửa lùa và cửa mở quay, giúp mở rộng 100% không gian mặt tiền nhà phố.'
            },
            {
                id: 'sp8',
                group: 'cuakinh-truotquay',
                driveId: '1lqF715R6y-FqEMskfHZeSFfWQrkqQKIq',
                name: 'Cửa kính mở lùa treo ray Inox & Cửa kính thủy lực thực tế',
                desc: 'Vận hành nhẹ nhàng, tiết kiệm không gian, phụ kiện kẹp kính chống gỉ sét bền bỉ theo thời gian.'
            },
            {
                id: 'sp9',
                group: 'cuakinh-truotquay',
                driveId: '1ByKE0VI4aZcnQSZ0L5-MVz4IV_wXkAxH',
                name: 'Cửa nhựa lõi thép & Cửa nhôm kính hoàn thiện tận xưởng PH DOOR',
                desc: 'Sản xuất trực tiếp tại 629 Lê Văn Hiến, Đà Nẵng với quy trình kiểm định chất lượng nghiêm ngặt.'
            },

            // Nhóm 3: Vách ngăn nhôm kính, Cầu thang kính, Tủ bếp nhôm kính & Kính ốp bếp (4 sản phẩm thực tế)
            {
                id: 'sp10',
                group: 'vachkinh-tubep',
                driveId: '1D_saZmX3giXEr2w2a4MGw0Tlg6Yy4inx',
                name: 'Tủ bếp nhôm cánh kính cường lực & Tủ rượu cánh kính cao cấp',
                desc: 'Chống nước, chống mối mọt tuyệt đối, khung nhôm hợp kim аноdized kết hợp cánh kính tràn viền sang trọng.'
            },
            {
                id: 'sp11',
                group: 'vachkinh-tubep',
                driveId: '1ND080CzfVN7hk4LLnWQ73NYhw7KSYu9O',
                name: 'Cầu thang kính cường lực tay vịn gỗ & Lan can kính ban công',
                desc: 'Kính cường lực an toàn 10mm - 12mm, trụ inox 304 chuẩn chất lượng, tạo điểm nhấn hiện đại cho ngôi nhà.'
            },
            {
                id: 'sp12',
                group: 'vachkinh-tubep',
                driveId: '1m_VtxRE86bsHk7lDKzFnFKfOLYUJskow',
                name: 'Vách kính cường lực mặt tiền & Vách kính phòng tắm hiện đại',
                desc: 'Thi công vách kính thông tầng, vách ngăn văn phòng và cabin tắm kính phụ kiện inox 304 chống nước.'
            },
            {
                id: 'sp13',
                group: 'vachkinh-tubep',
                driveId: '1Th1Ais2jL3nHoUS28sGOqNeLyJ3p_0H5',
                name: 'Kính ốp bếp màu cường lực & Mái kính cường lực lấy sáng Đà Nẵng',
                desc: 'Kính sơn màu chịu nhiệt độ cao, bề mặt bóng sáng dễ vệ sinh và hệ mái kính cường lực an toàn.'
            }
        ];

        // 12 Ảnh Dự Án Thực Tế Tại Đà Nẵng Từ Google Drive Của Khách Hàng
        const projectsData = [
            {
                driveId: '1lm6sQ8y_DPf25C41IfKHaw6m2hcCeXfO',
                title: 'Thi công trọn gói cửa nhôm Xingfa nhà phố tại Phường Ngũ Hành Sơn, Đà Nẵng'
            },
            {
                driveId: '1LV26DvdILrrExb1aRkajRojU-tIeshFC',
                title: 'Lắp đặt hệ cửa đi mở quay và mặt dựng nhôm kính tại Quận Hải Châu, Đà Nẵng'
            },
            {
                driveId: '13gn22O1_nnztWG4lHDy4WkfLl6-eQqpx',
                title: 'Hoàn thiện hạng mục cửa nhôm kính biệt thự khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng'
            },
            {
                driveId: '1pDdX8IhSa8TgoTE8T8iIuNeelVmFSZwF',
                title: 'Dự án lắp đặt cửa nhôm Slim và vách ngăn kính cao cấp tại Quận Sơn Trà, Đà Nẵng'
            },
            {
                driveId: '14U-isawNkKcF2pXL8pgSXjfg3Yyi4Ddz',
                title: 'Thi công cửa kính cường lực mặt tiền kinh doanh tại Lê Văn Hiến, Đà Nẵng'
            },
            {
                driveId: '1HXz_-2lTkxkRjRkLKz7OEsNSnVvXLgw5',
                title: 'Lắp đặt cửa trượt quay và hệ cửa sổ nhôm Xingfa tại Quận Thanh Khê, Đà Nẵng'
            },
            {
                driveId: '1twaN3mvBxrA1J7s3FSFRX01QG6r2y8wc',
                title: 'Hoàn thiện cầu thang kính cường lực và lan can ban công tại Quận Liên Chiểu, Đà Nẵng'
            },
            {
                driveId: '1A2pWLMdaq2TeeIevNvv4SCeS4UAORBSG',
                title: 'Thi công tủ bếp nhôm cánh kính và kính ốp bếp tại Khu đô thị Nam Việt Á, Đà Nẵng'
            },
            {
                driveId: '1qOg6q4CJaQewzYiyMP64fwC7N_BciqB-',
                title: 'Dự án lắp đặt vách kính cường lực văn phòng và cửa bản lề sàn tại Đà Nẵng'
            },
            {
                driveId: '1Ln0cz5A9rghfsm8IxNT5FwMQk-fwa7sl',
                title: 'Hoàn thiện hệ thống cửa nhôm Xingfa Quảng Đông cho căn hộ & khách sạn ven biển Đà Nẵng'
            },
            {
                driveId: '1kl0w4Rj7-CpSWfmb3vAYGFyRdXWlgh0p',
                title: 'Thi công cabin vách kính phòng tắm và cửa nhôm nội thất tại Hòa Quý, Ngũ Hành Sơn'
            },
            {
                driveId: '15-2y7VF0WQQPOg-WZh5AOEETgWDro32Y',
                title: 'Bàn giao công trình cửa nhôm kính cao cấp cho khách hàng tại TP Đà Nẵng'
            }
        ];

        // Danh mục bài viết trang chủ (Lấy cảm hứng từ trang mẫu chuyennhomkinhdanang.com)
        const blogPosts = [
            {
                driveId: '1-xXVCwg5cbxqXl4l8-BDWOUSCO_ArBIn',
                title: 'Kính 5mm 8mm 10mm 12mm 15mm – Nên dùng kính cường lực bao nhiêu mm cho từng hạng mục?',
                excerpt: 'Hướng dẫn chi tiết cách chọn độ dày kính cường lực chuẩn an toàn và tiết kiệm chi phí cho cửa đi, vách ngăn, cầu thang và kính ốp bếp.',
                content: 'Khi thi công nhôm kính tại Đà Nẵng, việc chọn đúng độ dày kính rất quan trọng: Kính 8mm thường dùng cho cửa sổ, kính ốp bếp; Kính 10mm - 12mm phù hợp cho cửa thủy lực bản lề sàn, vách ngăn mặt tiền, cầu thang kính và cabin phòng tắm. Liên hệ PH DOOR 077.9533.457 để được khảo sát và tư vấn trực tiếp.'
            },
            {
                driveId: '1yZFAf_M4Dgnux4S83P5e7pYcu646_5vx',
                title: 'So sánh cửa kính cường lực và cửa nhôm Xingfa tại Đà Nẵng: Nên chọn loại nào?',
                excerpt: 'Phân tích ưu nhược điểm của cửa nhôm Xingfa nhập khẩu và cửa kính cường lực bản lề sàn để gia chủ lựa chọn phù hợp nhất.',
                content: 'Cửa nhôm Xingfa có ưu thế tuyệt đối về độ kín khít, cách âm, chống nước mưa bão rất tốt cho nhà phố và biệt thự. Trong khi đó, cửa kính cường lực bản lề sàn mang lại tầm nhìn thoáng đãng tối đa cho cửa hàng, showroom và văn phòng.'
            },
            {
                driveId: '1D_saZmX3giXEr2w2a4MGw0Tlg6Yy4inx',
                title: 'Xu hướng lắp đặt cửa nhôm Slim và tủ bếp nhôm cánh kính hiện đại năm nay',
                excerpt: 'Vì sao cửa trượt hệ Slim không ray dưới và tủ bếp cánh kính cường lực đang được các gia đình tại Đà Nẵng ưa chuộng?',
                content: 'Hệ nhôm Slim sở hữu khung viền siêu mảnh nhưng cực kỳ cứng cáp, kết hợp cơ chế trượt giảm chấn êm ái không cần ray dưới. Cùng với đó, tủ bếp nhôm cánh kính chống mối mọt, chống ẩm mốc tuyệt đối trong khí hậu miền Trung.'
            },
            {
                driveId: '1ND080CzfVN7hk4LLnWQ73NYhw7KSYu9O',
                title: 'Quy trình khảo sát, sản xuất và lắp đặt nhôm kính chuẩn kỹ thuật tại PH DOOR',
                excerpt: 'Cam kết chất lượng từ khâu đo đạc thực tế, gia công tại xưởng 629 Lê Văn Hiến đến nghiệm thu bàn giao và bảo hành.',
                content: 'Tại CÔNG TY TNHH SX & TM PH DOOR, mọi bộ cửa đều được kiểm tra góc ép, đường keo, độ vuông góc và vận hành thực tế trước khi xuất xưởng. Đội ngũ thợ lành nghề lắp đặt nhanh gọn, chuẩn tiến độ.'
            }
        ];

        // Render thẻ sản phẩm chuẩn Flatsome (Không dán nhãn phụ, tên đầy đủ không bị cắt)
        function createProductCardHTML(item) {
            return `
                <div class="bg-white border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer"
                             onclick="openDetailModal('${item.name.replace(/'/g, "\\'")}', '${item.driveId}', '${item.desc.replace(/'/g, "\\'")}')">
                            <img src="${driveImg(item.driveId)}"
                                 onerror="this.onerror=null;this.src='${driveFallback(item.driveId)}';"
                                 alt="${item.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-[#0f4c81] cursor-pointer product-title-full"
                                onclick="openDetailModal('${item.name.replace(/'/g, "\\'")}', '${item.driveId}', '${item.desc.replace(/'/g, "\\'")}')">
                                ${item.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between gap-2 border-t border-slate-100">
                        <span class="text-xs sm:text-sm font-black text-red-600">Giá: Liên hệ</span>
                        <a href="#bao-gia-lien-he" onclick="prefillCategory('${item.name.replace(/'/g, "\\'")}')"
                           class="bg-[#0f4c81] hover:bg-[#0b3b66] text-white text-[11px] sm:text-xs font-bold px-2.5 py-1.5 rounded transition shrink-0">
                            Báo giá
                        </a>
                    </div>
                </div>
            `;
        }

        // Render danh sách sản phẩm theo nhóm hoặc từ khóa tìm kiếm
        function renderProducts(filterKeyword = '') {
            const kw = filterKeyword.trim().toLowerCase();
            const filtered = productsData.filter(p => !kw || p.name.toLowerCase().includes(kw) || p.desc.toLowerCase().includes(kw));

            const noticeEl = document.getElementById('searchFilterNotice');
            const noticeText = document.getElementById('searchFilterText');
            if (kw) {
                noticeEl.classList.remove('hidden');
                noticeText.textContent = `Kết quả tìm kiếm cho "${filterKeyword}": ${filtered.length} sản phẩm`;
            } else {
                noticeEl.classList.add('hidden');
            }

            const g1 = filtered.filter(p => p.group === 'xingfa-slim');
            const g2 = filtered.filter(p => p.group === 'cuakinh-truotquay');
            const g3 = filtered.filter(p => p.group === 'vachkinh-tubep');

            document.getElementById('grid-xingfa-slim').innerHTML = g1.length
                ? g1.map(createProductCardHTML).join('')
                : '<p class="text-xs text-slate-500 col-span-full">Không tìm thấy sản phẩm phù hợp trong nhóm này.</p>';

            document.getElementById('grid-cuakinh-truotquay').innerHTML = g2.length
                ? g2.map(createProductCardHTML).join('')
                : '<p class="text-xs text-slate-500 col-span-full">Không tìm thấy sản phẩm phù hợp trong nhóm này.</p>';

            document.getElementById('cat-suachua').innerHTML = g3.length
                ? g3.map(createProductCardHTML).join('')
                : '<p class="text-xs text-slate-500 col-span-full">Không tìm thấy sản phẩm phù hợp trong nhóm này.</p>';
        }

        // Render 12 dự án tại Đà Nẵng
        function renderProjects() {
            const container = document.getElementById('projectsGrid');
            container.innerHTML = projectsData.map((proj) => `
                <div class="bg-slate-50 border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between hover:shadow-md transition cursor-pointer"
                     onclick="openDetailModal('${proj.title.replace(/'/g, "\\'")}', '${proj.driveId}', 'Công trình thực tế tại Đà Nẵng do đội ngũ kỹ thuật CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI PH DOOR trực tiếp sản xuất và thi công hoàn thiện.')">
                    <div class="w-full aspect-[4/3] bg-slate-200 overflow-hidden">
                        <img src="${driveImg(proj.driveId)}"
                             onerror="this.onerror=null;this.src='${driveFallback(proj.driveId)}';"
                             alt="${proj.title}"
                             loading="lazy"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-[#0f4c81] product-title-full">
                            ${proj.title}
                        </h3>
                    </div>
                </div>
            `).join('');
        }

        // Render Bài viết trang chủ
        function renderBlogs() {
            const container = document.getElementById('blogGrid');
            container.innerHTML = blogPosts.map((post) => `
                <article class="bg-white border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between hover:shadow-md transition cursor-pointer"
                         onclick="openDetailModal('${post.title.replace(/'/g, "\\'")}', '${post.driveId}', '${post.content.replace(/'/g, "\\'")}')">
                    <div>
                        <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="${driveImg(post.driveId)}"
                                 onerror="this.onerror=null;this.src='${driveFallback(post.driveId)}';"
                                 alt="${post.title}"
                                 loading="lazy"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3 sm:p-4">
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-[#0f4c81] mb-1.5 product-title-full">
                                ${post.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1">
                        <span class="text-xs font-bold text-[#0f4c81] hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        // Tìm kiếm sản phẩm
        function handleSearchProduct(val) {
            renderProducts(val);
        }
        function clearProductSearch() {
            const input = document.getElementById('desktopSearchInput');
            if (input) input.value = '';
            renderProducts('');
        }
        function scrollToSection(id) {
            const el = document.getElementById(id);
            if (el) el.scrollIntoView({ behavior: 'smooth' });
        }

        // Đóng/mở menu điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const icon = document.getElementById('mobileMenuIcon');
            drawer.classList.toggle('hidden');
            if (drawer.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars text-lg';
            } else {
                icon.className = 'fa-solid fa-xmark text-lg';
            }
        }

        // Logic tự trượt 2 ảnh Banner
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function updateSlidesUI() {
            const slides = document.querySelectorAll('.banner-slide');
            slides.forEach((s, idx) => {
                if (idx === currentSlide) {
                    s.classList.add('active');
                } else {
                    s.classList.remove('active');
                }
            });
            const dot0 = document.getElementById('sliderDot0');
            const dot1 = document.getElementById('sliderDot1');
            if (currentSlide === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            } else {
                dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
            }
        }

        function changeSlide(step) {
            currentSlide = (currentSlide + step + totalSlides) % totalSlides;
            updateSlidesUI();
            resetAutoSlide();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateSlidesUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlidesUI();
            }, 4500);
        }

        // Modal xem chi tiết sản phẩm / dự án / bài viết
        function openDetailModal(title, driveId, desc) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = title;
            img.src = driveImg(driveId);
            img.onerror = function() {
                this.onerror = null;
                this.src = driveFallback(driveId);
            };
            document.getElementById('modalContent').textContent = desc;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Điền sẵn sản phẩm vào form báo giá
        function prefillCategory(productName) {
            const noteEl = document.getElementById('custNote');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn & báo giá mẫu: ${productName}`;
            }
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const category = document.getElementById('custCategory').value;
            const address = document.getElementById('custAddress').value.trim();

            const box = document.getElementById('quoteSuccessBox');
            const detail = document.getElementById('quoteSuccessDetail');
            detail.textContent = `Cảm ơn anh/chị ${name} (${phone}). Yêu cầu báo giá hạng mục "${category}" ${address ? 'tại ' + address : ''} đã được ghi nhận. Bộ phận kỹ thuật PH DOOR (077.9533.457) sẽ liên hệ ngay!`;
            box.classList.remove('hidden');
            e.target.reset();
        }

        // Khởi chạy khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderProducts('');
            renderProjects();
            renderBlogs();
            resetAutoSlide();
        });
    </script>
</body>
</html>
