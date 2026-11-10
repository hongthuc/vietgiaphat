<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT - Thế Giới Sàn & Nội Thất</title>
    <meta name="description" content="CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT (vietgiaphat.com) - Chuyên phân phối và thi công Sàn gỗ công nghiệp, Sàn gỗ tự nhiên, Sàn nhựa hèm khóa, Lam nhựa giả gỗ, Tấm nhựa giả đá, Giấy dán tường uy tín.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://vietgiaphat.com/">
    <meta property="og:title" content="CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT - vietgiaphat.com">
    <meta property="og:description" content="Chuyên phân phối & thi công Sàn gỗ, Sàn nhựa, Lam sóng, Tấm ốp PVC vân đá, Giấy dán tường Hàn Quốc, Thảm trải sàn uy tín, giá gốc tại kho.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Flatsome style) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#7c4a1e',   /* Màu nâu gỗ chủ đạo theo Logo */
                            dark: '#4a2b0f',      /* Nâu gỗ trầm đậm */
                            light: '#b87333',     /* Vàng đồng / gỗ sáng */
                            accent: '#d97706',    /* Điểm nhấn cam vàng ấm */
                            bg: '#fdfbf9'         /* Nền kem sáng sang trọng */
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: #f8f9fa;
            color: #222222;
            -webkit-text-size-adjust: 100%;
        }

        /* Chuẩn khung giao diện 1500px của Flatsome trên máy tính */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng trong tên danh mục */
        .nav-cat-link {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.2;
            padding: 9px 10px;
            color: #ffffff;
            transition: all 0.2s ease;
            border-radius: 4px;
        }
        .nav-cat-link:hover, .nav-cat-link.active {
            background-color: rgba(255, 255, 255, 0.16);
            color: #fde68a;
        }

        /* Chữ danh mục ở trang chủ nhỏ gọn, viết liền không gãy chữ */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12px;
            line-height: 1.3;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) và không tràn ra ngoài */
        .product-title-full {
            white-space: normal !important;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
            display: block;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #7c4a1e;
            margin-bottom: 16px;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
        }
        .section-title-main {
            background-color: #7c4a1e;
            color: #ffffff;
            padding: 9px 16px;
            font-size: 14px;
            font-weight: 700;
            text-transform: uppercase;
            border-radius: 6px 6px 0 0;
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 15px;
                padding: 10px 20px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }
        .contact-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Dropdown menu Flatsome trên máy tính */
        .has-dropdown {
            position: relative;
        }
        .has-dropdown .sub-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            border-top: 3px solid #7c4a1e;
            border-radius: 0 0 6px 6px;
            z-index: 100;
            padding: 6px 0;
        }
        .has-dropdown:hover .sub-menu {
            display: block;
        }
        .sub-menu a {
            display: block;
            padding: 7px 14px;
            font-size: 12.5px;
            color: #333333;
            white-space: nowrap;
            border-bottom: 1px solid #f3f4f6;
            transition: background 0.15s;
        }
        .sub-menu a:last-child {
            border-bottom: none;
        }
        .sub-menu a:hover {
            background: #fef3c7;
            color: #7c4a1e;
            font-weight: 600;
        }
    </style>
</head>
<body class="bg-[#f5f5f5] text-gray-800 antialiased selection:bg-brand selection:text-white">

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (KHÔNG CÓ THANH ADMIN UXBUILDER)
         ========================================== -->
    <div class="bg-brand-dark text-amber-50 text-xs py-1.5 border-b border-amber-900/40">
        <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <i class="fa-solid fa-building-shield text-amber-400 shrink-0"></i>
                <span class="font-semibold tracking-wide truncate">CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT - MST: 0402315352</span>
            </div>
            <div class="hidden md:flex items-center gap-5 text-[12px]">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng</span>
                <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i> vietgiaphat.com</span>
                <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" class="hover:text-amber-300 transition">
                    <i class="fa-brands fa-facebook text-amber-400 mr-1"></i> Thế Giới Sàn Việt Gia Phát
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (LOGO GỌN NHỎ - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40">
        <div class="container-1500 py-2.5">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu Danh mục trên Điện Thoại -->
                <button onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md border border-gray-200 text-brand-dark hover:bg-amber-50 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0">
                    <img src="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3&sz=w400';"
                         alt="Logo Sàn Gỗ Việt Gia Phát" 
                         class="h-10 sm:h-11 md:h-12 w-auto object-contain rounded shrink-0 border border-amber-100 p-0.5 bg-white">
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm md:text-base font-extrabold text-brand-dark leading-tight truncate">
                            SÀN GỖ VIỆT GIA PHÁT
                        </div>
                        <div class="text-[10px] sm:text-xs text-gray-500 truncate">
                            Phân phối & Thi công Sàn Gỗ - Nhựa Ốp Tường - Nội Thất
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (hiển thị gọn trên máy tính) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input type="text" id="searchInput" oninput="filterProductsBySearch(this.value)"
                               placeholder="Tìm sàn gỗ, sàn nhựa, tấm ốp PVC, giấy dán tường..." 
                               class="w-full pl-3.5 pr-9 py-2 text-xs border border-gray-300 rounded-md focus:outline-none focus:border-brand bg-gray-50">
                        <button type="button" aria-label="Tìm kiếm" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-brand">
                            <i class="fa-solid fa-magnifying-glass text-sm"></i>
                        </button>
                    </div>
                </div>

                <!-- Thông tin địa chỉ & SĐT dạng văn bản gọn gàng (Không dùng nút Gọi Ngay để chống tràn viền) -->
                <div class="hidden xl:flex items-center gap-5 text-xs text-gray-700 shrink-0">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-brand text-base"></i>
                        <div>
                            <div class="font-bold text-gray-800">486 Điện Biên Phủ</div>
                            <div class="text-[11px] text-gray-500">P. Thanh Khê, TP Đà Nẵng</div>
                        </div>
                    </div>
                    <div class="h-7 w-px bg-gray-200"></div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-headset text-brand text-base"></i>
                        <div>
                            <div class="font-bold text-brand-dark">0936.029.897 - 0789.878.387</div>
                            <div class="text-[11px] text-gray-500">Tư vấn & Báo giá tại kho</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="mt-2 md:hidden">
                <div class="relative w-full">
                    <input type="text" oninput="filterProductsBySearch(this.value)"
                           placeholder="Tìm kiếm sản phẩm: Sàn gỗ, sàn nhựa, lam sóng, PVC..." 
                           class="w-full pl-3 pr-8 py-1.5 text-xs border border-gray-300 rounded-md focus:outline-none focus:border-brand bg-gray-50">
                    <i class="fa-solid fa-magnifying-glass text-xs text-brand absolute right-3 top-1/2 -translate-y-1/2"></i>
                </div>
            </div>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH (VIẾT LIỀN TRÊN 1 HÀNG CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC)
             ========================================== -->
        <nav class="hidden lg:block bg-brand border-t border-brand-dark">
            <div class="container-1500">
                <ul class="flex flex-wrap items-center justify-between gap-x-1 gap-y-0.5 py-0.5">
                    <li>
                        <a href="#top" class="nav-cat-link active">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang Chủ
                        </a>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-san-go-cn" class="nav-cat-link">
                            Sàn Gỗ Công Nghiệp <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-san-go-cn">Sàn Gỗ Povar Cao Cấp 12mm</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Egger Aqua Đức</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Cốt Xanh Chống Ẩm</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Xương Cá Cao Cấp</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Malaysia (Janmi, Inovar)</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Kosmos & Camsan</a>
                            <a href="#sec-san-go-cn">Sàn Gỗ Thái Lan & NeoFloor</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-san-go-tn" class="nav-cat-link">
                            Sàn Gỗ Tự Nhiên <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-san-go-tn">Sàn Gỗ Căm Xe Tự Nhiên</a>
                            <a href="#sec-san-go-tn">Sàn Gỗ Gõ Đỏ Nam Phi</a>
                            <a href="#sec-san-go-tn">Sàn Gỗ Chiu Liu Cao Cấp</a>
                            <a href="#sec-san-go-tn">Sàn Gỗ Teak Ngoài Trời</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-san-nhua" class="nav-cat-link">
                            Sàn Nhựa Giả Gỗ <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-san-nhua">Sàn Nhựa Hèm Khóa SPC</a>
                            <a href="#sec-san-nhua">Sàn Nhựa Dán Keo Vân Gỗ</a>
                            <a href="#sec-san-nhua">Sàn Nhựa Giả Đá & Bê Tông</a>
                            <a href="#sec-san-nhua">Sàn Nhựa Vân Thảm</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-lam-nhua" class="nav-cat-link">
                            Lam Nhựa Giả Gỗ <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-lam-nhua">Lam Nhựa 3 Sóng - 4 Sóng - 5 Sóng</a>
                            <a href="#sec-lam-nhua">Tấm Ốp Tường Nano Phẳng</a>
                            <a href="#sec-lam-nhua">Gỗ Nhựa Ngoài Trời Composite</a>
                            <a href="#sec-lam-nhua">Phào Chỉ Nhựa Trang Trí</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-tam-pvc" class="nav-cat-link">
                            Tấm Nhựa Giả Đá <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-tam-pvc">Tấm PVC Vân Đá Cẩm Thạch</a>
                            <a href="#sec-tam-pvc">Tấm PVC Giả Bê Tông</a>
                            <a href="#sec-tam-pvc">Tấm Ốp Tường 3D & Da 3D</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-giay-dan-tuong" class="nav-cat-link">
                            Giấy Dán Tường Hàn Quốc <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-giay-dan-tuong">Giấy Dán Tường Headline & Kara</a>
                            <a href="#sec-giay-dan-tuong">Giấy Dán Tường Besti & Mood</a>
                            <a href="#sec-giay-dan-tuong">Xốp Dán Tường 3D Cách Âm</a>
                            <a href="#sec-giay-dan-tuong">Tranh Dán Tường 3D In Lụa</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#sec-tham-co" class="nav-cat-link">
                            Thảm Trải Sàn & Cỏ Nhân Tạo <i class="fa-solid fa-angle-down ml-1 text-[10px] opacity-80"></i>
                        </a>
                        <div class="sub-menu">
                            <a href="#sec-tham-co">Thảm Trải Sàn Văn Phòng & Khách Sạn</a>
                            <a href="#sec-tham-co">Thảm Sự Kiện & Thảm Sofa</a>
                            <a href="#sec-tham-co">Thảm Cỏ Nhân Tạo Sân Vườn 1cm - 3cm</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-du-an" class="nav-cat-link">Dự Án Thi Công</a>
                    </li>
                    <li>
                        <a href="#sec-tin-tuc" class="nav-cat-link">Bài Viết</a>
                    </li>
                    <li>
                        <a href="#sec-bao-gia" class="nav-cat-link">Báo Giá & Liên Hệ</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (OFF-CANVAS FLATSOME)
         ========================================== -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileDrawer()" class="fixed inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-brand text-white flex items-center justify-between">
                <span class="font-bold text-sm uppercase tracking-wide">Danh Mục Sản Phẩm</span>
                <button onclick="toggleMobileDrawer()" class="w-7 h-7 flex items-center justify-center rounded bg-white/10 text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="divide-y divide-gray-100 text-xs font-semibold text-gray-700">
                <a href="#top" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50 text-brand-dark"><i class="fa-solid fa-house w-5 text-brand"></i> Trang Chủ</a>
                <a href="#sec-gioi-thieu" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-building w-5 text-brand"></i> Giới Thiệu Việt Gia Phát</a>
                <a href="#sec-san-go-cn" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-layer-group w-5 text-brand"></i> Sàn Gỗ Công Nghiệp</a>
                <a href="#sec-san-go-tn" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-tree w-5 text-brand"></i> Sàn Gỗ Tự Nhiên</a>
                <a href="#sec-san-nhua" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-border-all w-5 text-brand"></i> Sàn Nhựa Giả Gỗ Hèm Khóa</a>
                <a href="#sec-lam-nhua" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-bars-staggered w-5 text-brand"></i> Lam Nhựa Giả Gỗ & Tấm Nano</a>
                <a href="#sec-tam-pvc" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-gem w-5 text-brand"></i> Tấm Nhựa Giả Đá & Ốp 3D</a>
                <a href="#sec-giay-dan-tuong" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-scroll w-5 text-brand"></i> Giấy Dán Tường & Tranh 3D</a>
                <a href="#sec-tham-co" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-rug w-5 text-brand"></i> Thảm Trải Sàn & Cỏ Nhân Tạo</a>
                <a href="#sec-du-an" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-helmet-safety w-5 text-brand"></i> Dự Án Thực Tế Đà Nẵng</a>
                <a href="#sec-doi-tac" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-handshake w-5 text-brand"></i> Đối Tác Thương Hiệu</a>
                <a href="#sec-tin-tuc" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-newspaper w-5 text-brand"></i> Danh Mục Bài Viết</a>
                <a href="#sec-bao-gia" onclick="toggleMobileDrawer()" class="block px-4 py-3 hover:bg-amber-50"><i class="fa-solid fa-file-signature w-5 text-brand"></i> Yêu Cầu Báo Giá & Bản Đồ</a>
            </div>
            <div class="mt-auto p-4 bg-amber-50/70 border-t border-amber-100 text-xs space-y-1.5">
                <div class="font-bold text-brand-dark">CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT</div>
                <p class="text-gray-600"><i class="fa-solid fa-location-dot text-brand mr-1"></i> 486 Điện Biên Phủ, P. Thanh Khê, TP Đà Nẵng</p>
                <p class="text-gray-600"><i class="fa-solid fa-phone text-brand mr-1"></i> 0936.029.897 - 0789.878.387</p>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         THIẾT KẾ RIÊNG BANNER MÁY TÍNH VÀ BANNER ĐIỆN THOẠI ĐỂ CHỮ NẰM GỌN TRONG ẢNH, KHÔNG TRÀN VIỀN
         ========================================== -->
    <section id="top" class="pt-3 pb-2">
        <div class="container-1500">
            <div class="relative w-full overflow-hidden rounded-lg shadow-md bg-brand-dark">

                <!-- SLIDE 1 -->
                <div class="banner-slide block transition-opacity duration-700" data-slide="0">
                    
                    <!-- Bản thiết kế Banner 1 dành riêng cho MÁY TÍNH (Kích thước chuẩn đồng nhất h-[390px]) -->
                    <div class="hidden md:grid md:grid-cols-12 w-full h-[390px] relative overflow-hidden bg-gradient-to-r from-[#2c1808] via-[#4a2b0f] to-[#6e4119]">
                        <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 z-10 text-white">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold px-3 py-1 rounded-full w-fit mb-3">
                                <i class="fa-solid fa-award"></i> TỔNG KHO PHÂN PHỐI & THI CÔNG TRỌN GÓI
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug mb-2">
                                CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT
                            </h1>
                            <p class="text-amber-200 text-xs lg:text-sm font-medium mb-4 leading-relaxed max-w-xl">
                                Chuyên Sàn Gỗ Công Nghiệp, Sàn Gỗ Tự Nhiên, Sàn Nhựa Hèm Khóa SPC, Lam Sóng Giả Gỗ, Tấm PVC Vân Đá & Giấy Dán Tường Hàn Quốc.
                            </p>
                            <div class="grid grid-cols-2 gap-2.5 text-xs text-amber-50 mb-4 max-w-lg">
                                <div class="flex items-center gap-2 bg-black/25 px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-circle-check text-amber-400"></i> Giá gốc tổng kho - Bảo hành dài hạn
                                </div>
                                <div class="flex items-center gap-2 bg-black/25 px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-circle-check text-amber-400"></i> Khảo sát & mang mẫu tận nhà miễn phí
                                </div>
                            </div>
                            <div class="flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-amber-500 text-brand-dark font-bold px-3.5 py-2 rounded">
                                    <i class="fa-solid fa-phone-volume mr-1"></i> Hotline: 0936.029.897 - 0789.878.387
                                </span>
                                <span class="bg-white/10 text-white px-3.5 py-2 rounded border border-white/20">
                                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 486 Điện Biên Phủ, Thanh Khê, Đà Nẵng
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 relative h-full overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U&sz=w1000';"
                                 alt="Showroom Công ty Sàn Gỗ Việt Gia Phát" 
                                 class="w-full h-full object-cover object-center">
                            <div class="absolute inset-0 bg-gradient-to-r from-[#4a2b0f] via-transparent to-transparent"></div>
                        </div>
                    </div>

                    <!-- Bản thiết kế Banner 1 MỚI dành riêng cho ĐIỆN THOẠI (Kích thước đồng nhất h-[220px], chữ nhỏ gọn nằm hết trong ảnh, không tràn viền) -->
                    <div class="block md:hidden relative w-full h-[220px] overflow-hidden bg-[#3a200b]">
                        <img src="https://lh3.googleusercontent.com/d/1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U&sz=w800';"
                             alt="Banner Mobile 1 Sàn Gỗ Việt Gia Phát" 
                             class="w-full h-full object-cover opacity-35">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/65 to-black/40 p-3.5 flex flex-col justify-center">
                            <span class="text-[10px] font-bold uppercase tracking-wider text-amber-300 bg-amber-900/60 border border-amber-400/30 px-2 py-0.5 rounded w-fit mb-1">
                                vietgiaphat.com • Tổng Kho Đà Nẵng
                            </span>
                            <h2 class="text-[13px] font-extrabold text-white leading-snug mb-1">
                                CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT
                            </h2>
                            <p class="text-[11px] text-amber-100 leading-tight mb-2">
                                Phân phối & Thi công Sàn Gỗ, Sàn Nhựa SPC, Lam Sóng, Tấm Ốp PVC Vân Đá, Giấy Dán Tường.
                            </p>
                            <div class="text-[10.5px] text-white bg-brand/90 border border-amber-400/40 rounded px-2.5 py-1 w-fit max-w-full truncate">
                                <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>486 Điện Biên Phủ, Thanh Khê, Đà Nẵng
                            </div>
                            <div class="text-[10.5px] font-bold text-amber-300 mt-1">
                                <i class="fa-solid fa-phone mr-1"></i>SĐT: 0936.029.897 - 0789.878.387
                            </div>
                        </div>
                    </div>

                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
                <div class="banner-slide hidden transition-opacity duration-700" data-slide="1">
                    
                    <!-- Bản thiết kế Banner 2 dành riêng cho MÁY TÍNH (Kích thước chuẩn đồng nhất h-[390px]) -->
                    <div class="hidden md:grid md:grid-cols-12 w-full h-[390px] relative overflow-hidden bg-gradient-to-r from-[#1f2937] via-[#374151] to-[#4b5563]">
                        <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 z-10 text-white">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold px-3 py-1 rounded-full w-fit mb-3">
                                <i class="fa-solid fa-star"></i> GIẢI PHÁP NỘI THẤT HIỆN ĐẠI - BỀN ĐẸP VƯỢT THỜI GIAN
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug mb-2">
                                THIẾT KẾ & THI CÔNG SÀN GỖ - TẤM ỐP TƯỜNG CHUYÊN NGHIỆP
                            </h2>
                            <p class="text-gray-200 text-xs lg:text-sm font-medium mb-4 leading-relaxed max-w-xl">
                                Đa dạng mẫu mã Sàn Gỗ Xương Cá, Sàn Cốt Xanh Chống Ẩm, Lam Nhựa Giả Gỗ, Tấm Ốp Nano, Thảm Trải Sàn & Cỏ Nhân Tạo cho nhà phố, biệt thự, khách sạn.
                            </p>
                            <div class="grid grid-cols-2 gap-2.5 text-xs text-amber-50 mb-4 max-w-lg">
                                <div class="flex items-center gap-2 bg-black/30 px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-shield-halved text-amber-400"></i> Chống nước, chống mối mọt, bền màu
                                </div>
                                <div class="flex items-center gap-2 bg-black/30 px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-user-check text-amber-400"></i> Đội ngũ thợ lành nghề, hoàn thiện tỉ mỉ
                                </div>
                            </div>
                            <div class="flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-amber-500 text-gray-900 font-bold px-3.5 py-2 rounded">
                                    <i class="fa-solid fa-phone-volume mr-1"></i> Tư vấn miễn phí: 0936.029.897 - 0789.878.387
                                </span>
                                <span class="bg-white/10 text-white px-3.5 py-2 rounded border border-white/20">
                                    <i class="fa-solid fa-globe text-amber-400 mr-1"></i> Website: vietgiaphat.com
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 relative h-full overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr&sz=w1000';"
                                 alt="Thi công thực tế Sàn Gỗ Việt Gia Phát" 
                                 class="w-full h-full object-cover object-center">
                            <div class="absolute inset-0 bg-gradient-to-r from-[#374151] via-transparent to-transparent"></div>
                        </div>
                    </div>

                    <!-- Bản thiết kế Banner 2 MỚI dành riêng cho ĐIỆN THOẠI (Kích thước đồng nhất h-[220px], chữ nhỏ gọn nằm hết trong ảnh) -->
                    <div class="block md:hidden relative w-full h-[220px] overflow-hidden bg-[#1f2937]">
                        <img src="https://lh3.googleusercontent.com/d/1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr&sz=w800';"
                             alt="Banner Mobile 2 Thi Công Thực Tế" 
                             class="w-full h-full object-cover opacity-35">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/65 to-black/40 p-3.5 flex flex-col justify-center">
                            <span class="text-[10px] font-bold uppercase tracking-wider text-amber-300 bg-gray-800/80 border border-amber-400/30 px-2 py-0.5 rounded w-fit mb-1">
                                Thi Công Trọn Gói • Uy Tín Hàng Đầu
                            </span>
                            <h2 class="text-[13px] font-extrabold text-white leading-snug mb-1">
                                THẾ GIỚI SÀN GỖ & TẤM ỐP TƯỜNG CAO CẤP
                            </h2>
                            <p class="text-[11px] text-gray-200 leading-tight mb-2">
                                Sàn gỗ cốt xanh, sàn xương cá, tấm ốp Nano, PVC vân đá chống thấm, bền đẹp trên 15 năm.
                            </p>
                            <div class="text-[10.5px] text-white bg-brand/90 border border-amber-400/40 rounded px-2.5 py-1 w-fit max-w-full truncate">
                                <i class="fa-solid fa-check-double text-amber-300 mr-1"></i>Cam kết giá gốc tại kho - Bảo hành uy tín
                            </div>
                            <div class="text-[10.5px] font-bold text-amber-300 mt-1">
                                <i class="fa-solid fa-phone mr-1"></i>Hotline: 0936.029.897 - 0789.878.387
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Banner Slider -->
                <button onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Banner tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button onclick="goToSlide(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         3 Ô CAM KẾT DỊCH VỤ (THEO MẪU NOITHATBINHMINH.COM.VN)
         ========================================== -->
    <section class="py-2">
        <div class="container-1500">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
                <div class="bg-white p-3.5 rounded-lg shadow-xs border border-gray-100 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-100 text-brand flex items-center justify-center shrink-0 mt-0.5">
                        <i class="fa-solid fa-medal text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-dark uppercase">Cam Kết Chất Lượng</h3>
                        <p class="text-xs text-gray-600 mt-0.5 leading-relaxed">Sản phẩm chính hãng nguồn gốc rõ ràng, chống ẩm, chống mối mọt, thi công thẩm mỹ cao.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 rounded-lg shadow-xs border border-gray-100 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-100 text-brand flex items-center justify-center shrink-0 mt-0.5">
                        <i class="fa-solid fa-tags text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-dark uppercase">Đảm Bảo Giá Tốt</h3>
                        <p class="text-xs text-gray-600 mt-0.5 leading-relaxed">Lợi thế Tổng kho & Đại lý phân phối cấp 1 tại Đà Nẵng, luôn cung cấp mức giá cạnh tranh nhất.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 rounded-lg shadow-xs border border-gray-100 flex items-start gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-100 text-brand flex items-center justify-center shrink-0 mt-0.5">
                        <i class="fa-solid fa-screwdriver-wrench text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-dark uppercase">Dịch Vụ Số 1</h3>
                        <p class="text-xs text-gray-600 mt-0.5 leading-relaxed">Đội ngũ thợ tay nghề cao, tận tâm, khảo sát mang mẫu tận nơi và bảo hành uy tín dài hạn.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ (TỐI ƯU TRÊN MÁY TÍNH & ĐIỆN THOẠI, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC)
         ========================================== -->
    <section class="py-3">
        <div class="container-1500">
            <div class="bg-white p-3 sm:p-4 rounded-lg shadow-xs border border-gray-100">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-gray-100">
                    <h2 class="text-xs sm:text-sm font-extrabold uppercase text-brand-dark flex items-center gap-2">
                        <i class="fa-solid fa-table-cells-large text-brand"></i> Danh Mục Sản Phẩm Chủ Lực
                    </h2>
                    <span class="text-[11px] text-gray-500 hidden sm:inline">Chọn danh mục để xem nhanh sản phẩm</span>
                </div>

                <!-- Grid danh mục: 2 cột trên điện thoại, 5 cột trên máy tính (2 hàng gọn đẹp, chữ viết liền trên 1 hàng không gãy chữ) -->
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2">
                    <a href="#sec-san-go-cn" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr&sz=w200';" alt="Sàn Gỗ Công Nghiệp" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Sàn Gỗ Công Nghiệp</span>
                    </a>
                    <a href="#sec-san-go-cn" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t&sz=w200';" alt="Sàn Gỗ Xương Cá" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Sàn Gỗ Xương Cá</span>
                    </a>
                    <a href="#sec-san-go-tn" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D&sz=w200';" alt="Sàn Gỗ Tự Nhiên" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Sàn Gỗ Tự Nhiên</span>
                    </a>
                    <a href="#sec-san-nhua" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-&sz=w200';" alt="Sàn Nhựa Hèm Khóa" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Sàn Nhựa Giả Gỗ</span>
                    </a>
                    <a href="#sec-lam-nhua" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj&sz=w200';" alt="Lam Nhựa Giả Gỗ" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Lam Nhựa Giả Gỗ</span>
                    </a>
                    <a href="#sec-tam-pvc" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc&sz=w200';" alt="Tấm Nhựa Giả Đá" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Tấm Nhựa Giả Đá</span>
                    </a>
                    <a href="#sec-tam-pvc" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1&sz=w200';" alt="Tấm Ốp Tường Nano" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Tấm Ốp Tường 3D</span>
                    </a>
                    <a href="#sec-giay-dan-tuong" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm&sz=w200';" alt="Giấy Dán Tường Hàn Quốc" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Giấy Dán Tường</span>
                    </a>
                    <a href="#sec-giay-dan-tuong" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq&sz=w200';" alt="Xốp Dán Tường 3D" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Tranh & Xốp 3D</span>
                    </a>
                    <a href="#sec-tham-co" class="flex items-center gap-2 p-2 rounded border border-gray-200 hover:border-brand hover:bg-amber-50/60 transition group">
                        <img src="https://lh3.googleusercontent.com/d/1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT&sz=w200';" alt="Thảm Trải Sàn & Cỏ Nhân Tạo" class="w-8 h-8 rounded object-cover shrink-0">
                        <span class="home-cat-pill font-semibold text-gray-800 group-hover:text-brand-dark truncate">Thảm & Cỏ Nhân Tạo</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU THỰC TẾ CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT (KÈM ẢNH THỰC TẾ CÔNG TY)
         ========================================== -->
    <section id="sec-gioi-thieu" class="py-3">
        <div class="container-1500">
            <div class="bg-white rounded-lg shadow-xs border border-gray-100 p-4 sm:p-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-5">
                        <div class="rounded-lg overflow-hidden border border-gray-200 bg-gray-100">
                            <img src="https://lh3.googleusercontent.com/d/1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U&sz=w1000';"
                                 alt="Hình ảnh thực tế Công Ty TNHH MTV Sàn Gỗ Việt Gia Phát tại 486 Điện Biên Phủ" 
                                 class="w-full h-64 sm:h-80 object-cover">
                        </div>
                        <p class="text-[11px] text-center text-gray-500 mt-1.5">
                            Showroom & Kho hàng thực tế: 486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng
                        </p>
                    </div>
                    <div class="lg:col-span-7 space-y-3">
                        <div class="text-xs font-bold text-brand uppercase tracking-wider">Về Chúng Tôi • vietgiaphat.com</div>
                        <h2 class="text-base sm:text-xl font-extrabold text-brand-dark">
                            CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT - THẾ GIỚI SÀN & VẬT LIỆU NỘI THẤT
                        </h2>
                        <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">
                            <strong>CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT</strong> (Fanpage: <em>Thế Giới Sàn Việt Gia Phát</em>) tọa lạc tại <strong>486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng</strong> là đơn vị uy tín hàng đầu chuyên nhập khẩu, phân phối và thi công trọn gói các dòng vật liệu lót sàn, ốp tường, ốp trần nội ngoại thất.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs text-gray-700 pt-1">
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-brand"></i> Đại lý phân phối Sàn gỗ công nghiệp & tự nhiên</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-brand"></i> Sàn nhựa hèm khóa SPC, sàn nhựa dán keo</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-brand"></i> Tấm ốp tường Nano, Lam sóng giả gỗ, PVC vân đá</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-brand"></i> Giấy dán tường Hàn Quốc, Tranh 3D, Thảm, Cỏ nhân tạo</div>
                        </div>
                        <div class="pt-2 flex flex-wrap items-center gap-3 text-xs">
                            <a href="#sec-bao-gia" class="bg-brand hover:bg-brand-dark text-white font-semibold px-4 py-2 rounded transition">
                                <i class="fa-solid fa-calculator mr-1.5"></i> Nhận Báo Giá Tại Kho
                            </a>
                            <a href="https://share.google/CwJ6SoUpKwSPZOtyU" target="_blank" rel="noopener" class="bg-amber-50 hover:bg-amber-100 text-brand-dark border border-amber-200 font-semibold px-4 py-2 rounded transition">
                                <i class="fa-solid fa-map-pin mr-1.5 text-brand"></i> Xem Vị Trí Google Map
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 1: SÀN GỖ CÔNG NGHIỆP ĐÀ NẴNG
         (KHÔNG ĐỂ NHÃN DÁN Ở TRANG CHỦ, CHIA 2 CỘT TRÊN ĐIỆN THOẠI, TÊN SẢN PHẨM ĐẦY ĐỦ KHÔNG TRÀN)
         ========================================== -->
    <section id="sec-san-go-cn" class="py-3 product-section">
        <div class="container-1500">
            <div class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-layer-group"></i> Sàn Gỗ Công Nghiệp Đà Nẵng
                </h2>
                <a href="#sec-bao-gia" class="text-xs font-semibold text-brand hover:underline pr-3 white-space-nowrap">
                    Xem thêm sản phẩm &raquo;
                </a>
            </div>

            <!-- Grid 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3">
                
                <!-- SP 1 (Ảnh thực tế 1) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr&sz=w600';"
                             alt="Sàn gỗ Povar cao cấp cốt xanh PV6608 12mm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Công Nghiệp</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ Povar cao cấp cốt xanh chống ẩm PV6608 dày 12 ly
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ Povar cao cấp cốt xanh chống ẩm PV6608 dày 12 ly')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 2 (Ảnh thực tế 2) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t&sz=w600';"
                             alt="Sàn gỗ xương cá cao cấp vân sồi tự nhiên 12mm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Xương Cá</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ xương cá cao cấp vân gỗ Sồi Bắc Âu dày 12 ly AC4
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ xương cá cao cấp vân gỗ Sồi Bắc Âu dày 12 ly AC4')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 3 (Ảnh thực tế 3) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D&sz=w600';"
                             alt="Sàn gỗ EGGER AQUA EPL 047 8 ly" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Nhập Khẩu Đức</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ EGGER AQUA chịu nước EPL 047 nhập khẩu Đức 8 ly
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ EGGER AQUA chịu nước EPL 047 nhập khẩu Đức 8 ly')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 4 (Ảnh thực tế 4) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-&sz=w600';"
                             alt="Sàn gỗ Malaysia Janmi cốt đen chống nước 12mm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Malaysia</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ nhập khẩu Malaysia Janmi & Inovar chống mối mọt 12 ly
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ nhập khẩu Malaysia Janmi & Inovar chống mối mọt 12 ly')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 5 (Ảnh thực tế 5) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj&sz=w600';"
                             alt="Sàn gỗ Camsan Thổ Nhĩ Kỳ 12mm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Thổ Nhĩ Kỳ</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ Camsan nhập khẩu Thổ Nhĩ Kỳ vân gỗ Óc Chó sang trọng
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ Camsan nhập khẩu Thổ Nhĩ Kỳ vân gỗ Óc Chó sang trọng')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 6 (Ảnh thực tế 6) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc&sz=w600';"
                             alt="Sàn gỗ Kosmos KB1205 12mm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Kosmos</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ công nghiệp Kosmos & Galamax vân gỗ sồi sáng hiện đại
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ công nghiệp Kosmos & Galamax vân gỗ sồi sáng hiện đại')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 7 (Ảnh thực tế 7) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1&sz=w600';"
                             alt="Sàn gỗ Thái Lan Leowood chống ẩm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Thái Lan</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ Thái Lan Leowood cốt HDF chống ẩm chịu lực cao
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ Thái Lan Leowood cốt HDF chống ẩm chịu lực cao')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 8 (Ảnh thực tế 8) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm&sz=w600';"
                             alt="Sàn gỗ Thụy Sỹ Kronoswiss" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Châu Âu</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ Kronoswiss Thụy Sỹ & NeoFloor cao cấp chống xước AC5
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ Kronoswiss Thụy Sỹ & NeoFloor cao cấp chống xước AC5')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 2: SÀN GỖ TỰ NHIÊN & SÀN NHỰA GIẢ GỖ HÈM KHÓA
         ========================================== -->
    <section id="sec-san-nhua" class="py-3 product-section">
        <div class="container-1500">
            <div id="sec-san-go-tn" class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-border-all"></i> Sàn Nhựa Giả Gỗ & Sàn Gỗ Tự Nhiên
                </h2>
                <a href="#sec-bao-gia" class="text-xs font-semibold text-brand hover:underline pr-3 white-space-nowrap">
                    Xem thêm sản phẩm &raquo;
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3">
                
                <!-- SP 9 (Ảnh thực tế 9) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq&sz=w600';"
                             alt="Sàn nhựa hèm khóa SPC M8003" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Nhựa Hèm Khóa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn nhựa hèm khóa SPC M8003 vân gỗ chống nước 100% có lớp xốp IXPE
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn nhựa hèm khóa SPC M8003 vân gỗ chống nước 100%')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 10 (Ảnh thực tế 10) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT&sz=w600';"
                             alt="Sàn nhựa giả gỗ dán keo SW 720" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Nhựa Dán Keo</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn nhựa giả gỗ dán keo SW 720 và sàn nhựa tự dán chống trầy xước
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn nhựa giả gỗ dán keo SW 720')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 11 (Ảnh thực tế 11) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c1gizjI3Cn9R-3V3C4DNcm_fxy_2Icq1" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c1gizjI3Cn9R-3V3C4DNcm_fxy_2Icq1&sz=w600';"
                             alt="Sàn gỗ tự nhiên Căm Xe và Gõ Đỏ" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Sàn Gỗ Tự Nhiên</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ tự nhiên Căm Xe, Gõ Đỏ, Chiu Liu, Gỗ Teak nguyên thanh cao cấp
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ tự nhiên Căm Xe, Gõ Đỏ, Chiu Liu')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 12 (Ảnh thực tế 12) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1nvyP4doy28OB2_be9TQYxU4cS5vyVWJl" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nvyP4doy28OB2_be9TQYxU4cS5vyVWJl&sz=w600';"
                             alt="Ốp bậc cầu thang gỗ và nhựa giả gỗ" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Mặt Bậc Cầu Thang</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Mặt bậc cầu thang nhựa giả gỗ & cầu thang sàn gỗ công nghiệp đồng màu
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Mặt bậc cầu thang nhựa giả gỗ & sàn gỗ')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 3: LAM NHỰA GIẢ GỖ, TẤM ỐP NANO & TẤM NHỰA GIẢ ĐÁ PVC
         ========================================== -->
    <section id="sec-lam-nhua" class="py-3 product-section">
        <div class="container-1500">
            <div id="sec-tam-pvc" class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-bars-staggered"></i> Lam Nhựa Giả Gỗ - Tấm Ốp Nano - Tấm Nhựa Giả Đá
                </h2>
                <a href="#sec-bao-gia" class="text-xs font-semibold text-brand hover:underline pr-3 white-space-nowrap">
                    Xem thêm sản phẩm &raquo;
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3">
                
                <!-- SP 13 (Ảnh thực tế 13) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI&sz=w600';"
                             alt="Lam nhựa giả gỗ 3 sóng 4 sóng 5 sóng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Lam Nhựa Giả Gỗ</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Lam nhựa giả gỗ 3 sóng, 4 sóng cao, 5 sóng ốp tường và trần nội thất
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Lam nhựa giả gỗ 3 sóng, 4 sóng, 5 sóng')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 14 (Ảnh thực tế 14) -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1fo37sU_nzsdV3yPn8iwHIQ6_sgqdYS1h" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1fo37sU_nzsdV3yPn8iwHIQ6_sgqdYS1h&sz=w600';"
                             alt="Tấm ốp tường Nano và PVC vân đá" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Tấm Nhựa Giả Đá & Nano</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Tấm nhựa PVC vân đá cẩm thạch kết hợp lam sóng ốp vách tivi phòng khách
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Tấm nhựa PVC vân đá cẩm thạch kết hợp lam sóng')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 15 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Dj_fIMQ4N1pHI1WZNHXL4KtR0sXAuEkj&sz=w600';"
                             alt="Tấm ốp tường Nano BM18" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Tấm Ốp Tường Nano</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Tấm ốp tường nhựa Nano phẳng BM18 chống thấm ẩm, cách nhiệt
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Tấm ốp tường nhựa Nano phẳng BM18')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 16 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rD4zZWbpDQ9CcmpvMIduz5eNn6AbX9oc&sz=w600';"
                             alt="Gỗ nhựa ngoài trời Composite" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Gỗ Nhựa Ngoài Trời</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Sàn gỗ nhựa ngoài trời Composite lót hồ bơi, ban công, sân vườn
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Sàn gỗ nhựa ngoài trời Composite')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 4: GIẤY DÁN TƯỜNG HÀN QUỐC - XỐP 3D - THẢM TRẢI SÀN - CỎ NHÂN TẠO (THEO WEB MẪU)
         ========================================== -->
    <section id="sec-giay-dan-tuong" class="py-3 product-section">
        <div class="container-1500">
            <div id="sec-tham-co" class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-scroll"></i> Giấy Dán Tường Hàn Quốc - Xốp 3D - Thảm & Cỏ Nhân Tạo
                </h2>
                <a href="#sec-bao-gia" class="text-xs font-semibold text-brand hover:underline pr-3 white-space-nowrap">
                    Xem thêm sản phẩm &raquo;
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3">
                
                <!-- SP 17 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1&sz=w600';"
                             alt="Giấy dán tường Hàn Quốc Headline 9694" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Giấy Dán Tường Hàn Quốc</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Giấy dán tường Hàn Quốc Headline, Kara, Besti, Silk Garden phòng khách
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Giấy dán tường Hàn Quốc Headline, Kara, Besti')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 18 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wQUxUtWBd-JZ9ar7K7SbS47qTYfHk7cm&sz=w600';"
                             alt="Xốp dán tường 3D giả gạch và vân sóng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Xốp Dán Tường & Tranh 3D</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Xốp dán tường 3D giả gạch, giả da & Tranh dán tường 3D in lụa khổ lớn
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Xốp dán tường 3D & Tranh dán tường 3D')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 19 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=10dHj4SpkS-6HZwbuO3aP7CFugDulmgyq&sz=w600';"
                             alt="Thảm trải sàn văn phòng và khách sạn" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Thảm Trải Sàn</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Thảm trải sàn văn phòng, thảm khách sạn, thảm sự kiện & thảm tấm đế cao su
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Thảm trải sàn văn phòng, khách sạn')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

                <!-- SP 20 -->
                <div class="product-card bg-white rounded-md border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8LVAUoG_A4_TFVWnaQ6g1LYuitFMXT&sz=w600';"
                             alt="Thảm cỏ nhân tạo sân vườn 2cm 3cm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-0.5">Cỏ Nhân Tạo</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand">
                                Thảm cỏ nhân tạo sân vườn 1cm, 2cm, 3cm và cỏ nhân tạo trang trí
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-gray-100 flex items-center justify-between text-xs">
                            <span class="font-bold text-brand">Liên hệ báo giá</span>
                            <a href="#sec-bao-gia" onclick="prefillQuote('Thảm cỏ nhân tạo sân vườn 1cm, 2cm, 3cm')" class="text-brand-dark hover:underline font-medium">Đặt mẫu</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ (SỬ DỤNG ẢNH THỰC TẾ GOOGLE DRIVE)
         ========================================== -->
    <section id="sec-du-an" class="py-3">
        <div class="container-1500">
            <div class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-helmet-safety"></i> Dự Án Thi Công Thực Tế Tại Đà Nẵng
                </h2>
                <span class="text-xs text-gray-500 pr-3 hidden sm:inline">Hình ảnh công trình thực tế do Việt Gia Phát thi công</span>
            </div>

            <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3">
                
                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c5QLBuZDoP9GdO_YXmgGA78f7eeKePLr&sz=w700';"
                             alt="Dự án thi công sàn gỗ tại Thanh Khê Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Thi công Sàn gỗ cốt xanh chống ẩm 12mm nhà phố tại Thanh Khê, Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Sàn gỗ công nghiệp 12mm + Phào nẹp đồng bộ</p>
                    </div>
                </div>

                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c8xKnbwvrb7puIApvk8iegMgRgyeDf0t&sz=w700';"
                             alt="Dự án sàn gỗ xương cá biệt thự Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Hoàn thiện Sàn gỗ xương cá cao cấp căn hộ & biệt thự tại Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Sàn gỗ xương cá 12mm cốt HDF chống ẩm</p>
                    </div>
                </div>

                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI&sz=w700';"
                             alt="Dự án ốp tường lam sóng và tấm Nano Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Thi công Lam nhựa giả gỗ & Tấm ốp Nano phòng khách tại Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Lam sóng giả gỗ + Tấm ốp tường Nano</p>
                    </div>
                </div>

                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1fo37sU_nzsdV3yPn8iwHIQ6_sgqdYS1h" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1fo37sU_nzsdV3yPn8iwHIQ6_sgqdYS1h&sz=w700';"
                             alt="Dự án vách tivi PVC vân đá tại Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Lắp đặt vách Tivi Tấm nhựa giả đá PVC kết hợp lam sóng tại Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Tấm PVC vân đá + Phào chỉ trang trí</p>
                    </div>
                </div>

                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1c1gizjI3Cn9R-3V3C4DNcm_fxy_2Icq1" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1c1gizjI3Cn9R-3V3C4DNcm_fxy_2Icq1&sz=w700';"
                             alt="Dự án sàn nhựa hèm khóa SPC văn phòng Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Lót Sàn nhựa hèm khóa SPC chống nước cho showroom & văn phòng Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Sàn nhựa hèm khóa SPC dày 4mm - 6mm</p>
                    </div>
                </div>

                <div class="bg-white rounded-md border border-gray-200 overflow-hidden">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1nvyP4doy28OB2_be9TQYxU4cS5vyVWJl" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nvyP4doy28OB2_be9TQYxU4cS5vyVWJl&sz=w700';"
                             alt="Dự án ốp mặt bậc cầu thang giả gỗ Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">
                            Thi công Ốp mặt bậc cầu thang gỗ & nhựa giả gỗ cao cấp tại Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1">Hạng mục: Mặt bậc cầu thang + Nẹp mũi bậc chống trượt</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)
         ========================================== -->
    <section id="sec-tin-tuc" class="py-3">
        <div class="container-1500">
            <div class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-newspaper"></i> Danh Mục Bài Viết & Tư Vấn Nội Thất
                </h2>
                <span class="text-xs text-gray-500 pr-3 hidden sm:inline">Cập nhật bảng giá & xu hướng nội thất mới nhất</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3">
                
                <article class="bg-white rounded-md border border-gray-200 overflow-hidden flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1AI33XCeCpHvU0E-O7PjlbDgkbMIDIz6D&sz=w600';"
                         alt="Bảng báo giá sàn gỗ công nghiệp Đà Nẵng" class="w-full h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Báo giá sàn gỗ</span>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 mt-1">
                                Bảng báo giá thi công sàn gỗ công nghiệp tại Đà Nẵng mới nhất 2026
                            </h3>
                            <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                                Tổng hợp chi tiết giá vật tư và nhân công hoàn thiện các dòng sàn gỗ 8mm, 12mm cốt xanh chống ẩm, sàn gỗ xương cá và nhập khẩu Malaysia.
                            </p>
                        </div>
                        <a href="#sec-bao-gia" class="text-xs font-bold text-brand mt-2 inline-block hover:underline">Nhận bảng giá chi tiết &rarr;</a>
                    </div>
                </article>

                <article class="bg-white rounded-md border border-gray-200 overflow-hidden flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1eNUHbDQ1W4Pet5zw4cEqZlK19UEMGv9-&sz=w600';"
                         alt="So sánh sàn nhựa hèm khóa SPC và sàn gỗ" class="w-full h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Tư vấn chọn sàn</span>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 mt-1">
                                Kinh nghiệm chọn sàn nhựa giả gỗ hèm khóa SPC bền đẹp, chống nước 100%
                            </h3>
                            <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                                Sàn nhựa hèm khóa SPC có độ bền cao, chống thấm nước và mối mọt tuyệt đối, rất phù hợp với khí hậu miền Trung.
                            </p>
                        </div>
                        <a href="#sec-bao-gia" class="text-xs font-bold text-brand mt-2 inline-block hover:underline">Tư vấn miễn phí &rarr;</a>
                    </div>
                </article>

                <article class="bg-white rounded-md border border-gray-200 overflow-hidden flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Ai2mh-qgA3DsroYqIbW3O33Rh64ruhXI&sz=w600';"
                         alt="Mẫu tấm nhựa ốp tường Nano và lam sóng" class="w-full h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Tấm ốp tường</span>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 mt-1">
                                Xu hướng trang trí phòng khách bằng Lam nhựa giả gỗ & Tấm PVC vân đá
                            </h3>
                            <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                                Giải pháp cải tạo tường ẩm mốc, bong tróc nhanh chóng, mang lại không gian phòng khách sang trọng và hiện đại.
                            </p>
                        </div>
                        <a href="#sec-bao-gia" class="text-xs font-bold text-brand mt-2 inline-block hover:underline">Xem mẫu thực tế &rarr;</a>
                    </div>
                </article>

                <article class="bg-white rounded-md border border-gray-200 overflow-hidden flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sHJ8dNryNfPsGzANqBrSgWnYhOhnYvh1&sz=w600';"
                         alt="Giấy dán tường Hàn Quốc tại Đà Nẵng" class="w-full h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Giấy dán tường</span>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 mt-1">
                                Cách phối màu Giấy dán tường Hàn Quốc với Sàn gỗ tạo không gian ấm cúng
                            </h3>
                            <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                                Bí quyết lựa chọn tông màu giấy dán tường Headline, Kara hài hòa với màu vân gỗ sồi và gỗ óc chó cho phòng ngủ, căn hộ.
                            </p>
                        </div>
                        <a href="#sec-bao-gia" class="text-xs font-bold text-brand mt-2 inline-block hover:underline">Nhận tư vấn &rarr;</a>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU
         ========================================== -->
    <section id="sec-doi-tac" class="py-3">
        <div class="container-1500">
            <div class="section-title-container">
                <h2 class="section-title-main">
                    <i class="fa-solid fa-handshake"></i> Đối Tác & Thương Hiệu Phân Phối Chính Hãng
                </h2>
                <span class="text-xs text-gray-500 pr-3 hidden sm:inline">Cam kết 100% sản phẩm chính hãng</span>
            </div>

            <div class="bg-white p-4 rounded-md border border-gray-200">
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 text-center">
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">NEOFLOOR</span>
                        <span class="text-[10px] text-gray-500">Đại lý chính thức</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">POVAR</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ cốt xanh</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">EGGER</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ CHLB Đức</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">KOSMOS</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ & Gỗ nhựa</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">CAMSAN</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ Thổ Nhĩ Kỳ</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">JANMI</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ Malaysia</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">INOVAR</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ chịu nước</span>
                    </div>
                    <div class="p-2.5 rounded border border-gray-200 bg-amber-50/40 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-brand-dark text-xs sm:text-sm tracking-wide">KRONOSWISS</span>
                        <span class="text-[10px] text-gray-500">Sàn gỗ Thụy Sỹ</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ + FANPAGE FACEBOOK + GOOGLE MAP RA NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="sec-bao-gia" class="py-4">
        <div class="container-1500">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- CỘT 1 (5/12): FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-lg border border-gray-200 p-4 sm:p-5 shadow-xs">
                    <div class="border-b border-gray-100 pb-2.5 mb-3">
                        <h2 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase flex items-center gap-2">
                            <i class="fa-solid fa-file-invoice-dollar text-brand"></i> Form Yêu Cầu Tư Vấn & Báo Giá
                        </h2>
                        <p class="text-xs text-gray-500 mt-0.5">Quý khách để lại thông tin, Việt Gia Phát sẽ gửi báo giá ưu đãi tại kho ngay!</p>
                    </div>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs">
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Họ và tên Quý khách *</label>
                            <input type="text" id="qName" required placeholder="Nhập họ và tên..." 
                                   class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0936029897" 
                                       class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
                            </div>
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Diện tích dự kiến (m²)</label>
                                <input type="text" id="qArea" placeholder="Ví dụ: 55m²" 
                                       class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand">
                            </div>
                        </div>
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Danh mục sản phẩm quan tâm *</label>
                            <select id="qCategory" class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand bg-white">
                                <option value="Sàn Gỗ Công Nghiệp">Sàn Gỗ Công Nghiệp (8mm / 12mm / Cốt xanh / Xương cá)</option>
                                <option value="Sàn Gỗ Tự Nhiên">Sàn Gỗ Tự Nhiên (Căm Xe, Gõ Đỏ, Chiu Liu, Teak)</option>
                                <option value="Sàn Nhựa Giả Gỗ">Sàn Nhựa Giả Gỗ (Hèm khóa SPC / Dán keo)</option>
                                <option value="Lam Nhựa Giả Gỗ & Tấm Nano">Lam Nhựa Giả Gỗ & Tấm Ốp Tường Nano</option>
                                <option value="Tấm Nhựa Giả Đá PVC & Ốp 3D">Tấm Nhựa Giả Đá PVC & Tấm Ốp 3D</option>
                                <option value="Giấy Dán Tường Hàn Quốc & Tranh 3D">Giấy Dán Tường Hàn Quốc & Tranh 3D</option>
                                <option value="Thảm Trải Sàn & Cỏ Nhân Tạo">Thảm Trải Sàn & Cỏ Nhân Tạo</option>
                            </select>
                        </div>
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Địa chỉ công trình & Yêu cầu chi tiết</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập địa chỉ công trình hoặc mã sản phẩm cần mang mẫu tận nơi..." 
                                      class="w-full px-3 py-2 border border-gray-300 rounded focus:outline-none focus:border-brand"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-brand hover:bg-brand-dark text-white font-bold py-2.5 px-4 rounded transition uppercase tracking-wide">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Nhận Báo Giá
                        </button>
                    </form>

                    <!-- Hộp thông báo gửi thành công (Thay cho alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-green-50 border border-green-300 text-green-800 text-xs">
                        <div class="font-bold flex items-center gap-1.5">
                            <i class="fa-solid fa-circle-check text-green-600"></i> Đã ghi nhận yêu cầu báo giá thành công!
                        </div>
                        <p id="quoteSuccessText" class="mt-1"></p>
                    </div>
                </div>

                <!-- CỘT 2 (3/12): ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-3 bg-white rounded-lg border border-gray-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="border-b border-gray-100 pb-2.5 mb-3">
                            <h2 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-[#1877F2]"></i> Fanpage Chính Thức
                            </h2>
                            <p class="text-xs text-gray-500 mt-0.5">Theo dõi công trình mới mỗi ngày trên Fanpage</p>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan + Iframe Facebook Page Plugin -->
                        <div class="rounded-lg border border-gray-200 overflow-hidden mb-3 bg-gray-50">
                            <div class="relative h-28 bg-brand-dark overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n4R-ePafarR-Peg7W-6WzIpgizDCk2_U&sz=w600';"
                                     alt="Bìa Fanpage Thế Giới Sàn Việt Gia Phát" class="w-full h-full object-cover opacity-65">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent p-3 flex items-end gap-2.5">
                                    <img src="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3" 
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3&sz=w200';"
                                         alt="Avatar Fanpage" class="w-12 h-12 rounded border-2 border-white bg-white object-contain shrink-0">
                                    <div class="text-white min-w-0">
                                        <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" class="font-bold text-xs sm:text-sm hover:underline block truncate">
                                            Thế Giới Sàn Việt Gia Phát
                                        </a>
                                        <span class="text-[11px] text-amber-200 block truncate">@thegioisanvietgiaphat</span>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 text-xs space-y-2">
                                <p class="text-gray-700 leading-relaxed">
                                    Chuyên phân phối & thi công Sàn gỗ, Sàn nhựa SPC, Tấm ốp tường Nano, Lam sóng, PVC vân đá tại 486 Điện Biên Phủ, Thanh Khê, Đà Nẵng.
                                </p>
                                <div class="w-full overflow-hidden rounded border border-gray-200 bg-white">
                                    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fthegioisanvietgiaphat&tabs&width=300&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                            width="100%" height="130" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" title="Fanpage Thế Giới Sàn Việt Gia Phát"></iframe>
                                </div>
                            </div>
                        </div>
                    </div>

                    <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" 
                       class="w-full bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-4 rounded text-center transition block">
                        <i class="fa-brands fa-facebook-messenger mr-1.5"></i> Truy Cập Fanpage & Nhắn Tin
                    </a>
                </div>

                <!-- CỘT 3 (4/12): ĐƯA GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-4 bg-white rounded-lg border border-gray-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="border-b border-gray-100 pb-2.5 mb-3">
                            <h2 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-red-600"></i> Bản Đồ Đường Đi Google Map
                            </h2>
                            <p class="text-xs text-gray-600 mt-0.5">486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng</p>
                        </div>

                        <!-- Google Map hiển thị trực tiếp ngoài trang chủ -->
                        <div class="w-full h-64 rounded-lg overflow-hidden border border-gray-300 bg-gray-100 mb-3">
                            <iframe src="https://maps.google.com/maps?q=486%20%C4%90i%E1%BB%87n%20Bi%C3%AAn%20Ph%E1%BB%A7,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                    width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="Bản đồ 486 Điện Biên Phủ Đà Nẵng"></iframe>
                        </div>
                    </div>

                    <a href="https://share.google/CwJ6SoUpKwSPZOtyU" target="_blank" rel="noopener" 
                       class="w-full bg-brand-dark hover:bg-brand text-white text-xs font-bold py-2.5 px-4 rounded text-center transition block">
                        <i class="fa-solid fa-diamond-turn-right mr-1.5 text-amber-300"></i> Mở Google Map Chỉ Đường Đến Showroom
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (ĐẦY ĐỦ THÔNG TIN CÔNG TY, DANH MỤC, LIÊN HỆ)
         ========================================== -->
    <footer class="bg-[#23170d] text-amber-50/90 pt-8 pb-20 md:pb-8 mt-4 border-t-4 border-brand">
        <div class="container-1500">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10 text-xs">
                
                <!-- Thông tin công ty + Logo -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-3">
                        <img src="https://lh3.googleusercontent.com/d/1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1HMVMAPnm9oEn_G56hxs2nQv5Mv_PPTV3&sz=w300';"
                             alt="Logo Việt Gia Phát" class="h-11 w-auto bg-white p-1 rounded object-contain">
                        <div>
                            <h3 class="text-sm font-extrabold text-amber-300 uppercase">CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT</h3>
                            <p class="text-[11px] text-amber-100/80">Website chính thức: vietgiaphat.com</p>
                        </div>
                    </div>
                    <p class="text-gray-300 leading-relaxed">
                        Chuyên phân phối và thi công Sàn gỗ công nghiệp, Sàn gỗ tự nhiên, Sàn nhựa giả gỗ hèm khóa, Lam nhựa giả gỗ, Tấm ốp tường Nano, Tấm nhựa giả đá PVC, Giấy dán tường Hàn Quốc, Thảm trải sàn & Cỏ nhân tạo.
                    </p>
                    <ul class="space-y-1.5 text-amber-100">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> <strong>Địa chỉ:</strong> 486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i> <strong>Điện thoại / Zalo:</strong> 0936.029.897 - 0789.878.387</li>
                        <li><i class="fa-solid fa-id-card text-amber-400 w-5"></i> <strong>Mã số thuế:</strong> 0402315352</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" class="underline hover:text-amber-300">facebook.com/thegioisanvietgiaphat</a></li>
                        <li><i class="fa-solid fa-map-pin text-amber-400 w-5"></i> <strong>Google Map:</strong> <a href="https://share.google/CwJ6SoUpKwSPZOtyU" target="_blank" rel="noopener" class="underline hover:text-amber-300">Xem bản đồ chỉ đường</a></li>
                    </ul>
                </div>

                <!-- Danh mục sản phẩm -->
                <div class="lg:col-span-4">
                    <h4 class="text-xs font-bold uppercase text-amber-300 mb-3 border-b border-white/10 pb-1.5">Danh Mục Sản Phẩm</h4>
                    <div class="grid grid-cols-2 gap-2 text-gray-300">
                        <a href="#sec-san-go-cn" class="hover:text-amber-300 transition">&rsaquo; Sàn gỗ công nghiệp</a>
                        <a href="#sec-san-go-cn" class="hover:text-amber-300 transition">&rsaquo; Sàn gỗ xương cá</a>
                        <a href="#sec-san-go-tn" class="hover:text-amber-300 transition">&rsaquo; Sàn gỗ tự nhiên</a>
                        <a href="#sec-san-nhua" class="hover:text-amber-300 transition">&rsaquo; Sàn nhựa giả gỗ</a>
                        <a href="#sec-lam-nhua" class="hover:text-amber-300 transition">&rsaquo; Lam nhựa giả gỗ</a>
                        <a href="#sec-tam-pvc" class="hover:text-amber-300 transition">&rsaquo; Tấm nhựa giả đá</a>
                        <a href="#sec-tam-pvc" class="hover:text-amber-300 transition">&rsaquo; Tấm ốp tường 3D</a>
                        <a href="#sec-giay-dan-tuong" class="hover:text-amber-300 transition">&rsaquo; Giấy dán tường</a>
                        <a href="#sec-giay-dan-tuong" class="hover:text-amber-300 transition">&rsaquo; Xốp dán tường 3D</a>
                        <a href="#sec-tham-co" class="hover:text-amber-300 transition">&rsaquo; Cỏ nhân tạo & Thảm</a>
                    </div>
                </div>

                <!-- Hỗ trợ khách hàng -->
                <div class="lg:col-span-3">
                    <h4 class="text-xs font-bold uppercase text-amber-300 mb-3 border-b border-white/10 pb-1.5">Hỗ Trợ Khách Hàng</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li><a href="#sec-bao-gia" class="hover:text-amber-300 transition">&rsaquo; Khảo sát & mang mẫu tận nhà</a></li>
                        <li><a href="#sec-bao-gia" class="hover:text-amber-300 transition">&rsaquo; Chính sách bảo hành thi công</a></li>
                        <li><a href="#sec-bao-gia" class="hover:text-amber-300 transition">&rsaquo; Chính sách đại lý & đối tác</a></li>
                        <li><a href="#sec-du-an" class="hover:text-amber-300 transition">&rsaquo; Hình ảnh công trình thực tế</a></li>
                        <li><a href="#sec-tin-tuc" class="hover:text-amber-300 transition">&rsaquo; Bảng báo giá vật tư mới nhất</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-gray-400 gap-2 text-center">
                <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH MTV SÀN GỖ VIỆT GIA PHÁT</strong> (vietgiaphat.com).</div>
                <div>Địa chỉ: 486 Điện Biên Phủ, Phường Thanh Khê, TP Đà Nẵng | SĐT: 0936.029.897 - 0789.878.387</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         ========================================== -->
    <!-- Cụm nút nổi bên trái/phải trên máy tính và thanh liên hệ nhanh trên điện thoại -->
    <div class="fixed right-3 bottom-16 md:bottom-6 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0936029897" target="_blank" rel="noopener" 
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-extrabold text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo: 0936.029.897</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" 
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage Việt Gia Phát</span>
        </a>

        <!-- Nút Hotline 1 nổi bật -->
        <a href="tel:0936029897" 
           class="contact-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1">0936.029.897</span>
        </a>

        <!-- Nút Hotline 2 nổi bật -->
        <a href="tel:0789878387" 
           class="flex items-center gap-2 bg-amber-600 hover:bg-amber-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-amber-700 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1">0789.878.387</span>
        </a>
    </div>

    <!-- Thanh liên hệ cố định dưới đáy màn hình điện thoại (không tràn viền) -->
    <div class="fixed bottom-0 left-0 right-0 z-40 grid grid-cols-4 bg-white border-t border-gray-200 shadow-lg md:hidden text-[11px] font-bold">
        <a href="tel:0936029897" class="flex flex-col items-center justify-center py-2 text-red-600 active:bg-gray-100">
            <i class="fa-solid fa-phone-volume text-sm mb-0.5"></i>
            <span>0936.029.897</span>
        </a>
        <a href="tel:0789878387" class="flex flex-col items-center justify-center py-2 text-brand-dark active:bg-gray-100 border-l border-gray-100">
            <i class="fa-solid fa-phone text-sm mb-0.5"></i>
            <span>0789.878.387</span>
        </a>
        <a href="https://zalo.me/0936029897" target="_blank" rel="noopener" class="flex flex-col items-center justify-center py-2 text-[#0068ff] active:bg-gray-100 border-l border-gray-100">
            <i class="fa-solid fa-comment-dots text-sm mb-0.5"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/thegioisanvietgiaphat" target="_blank" rel="noopener" class="flex flex-col items-center justify-center py-2 text-[#1877F2] active:bg-gray-100 border-l border-gray-100">
            <i class="fa-brands fa-facebook text-sm mb-0.5"></i>
            <span>Fanpage</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, TÌM KIẾM & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // 1. Điều khiển 2 Banner tự trượt chuyên nghiệp
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const totalSlides = slides.length;
        let slideInterval;

        function showSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            // Cập nhật dot
            const dot0 = document.getElementById('dot-0');
            const dot1 = document.getElementById('dot-1');
            if (dot0 && dot1) {
                if (currentSlide === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2 h-2 rounded-full bg-white/60 transition-all';
                } else {
                    dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    dot0.className = 'w-2 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5000);
        }

        window.addEventListener('load', () => {
            resetSlideTimer();
        });

        // 2. Đóng/mở menu danh mục trên điện thoại
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        // 3. Điền sẵn tên sản phẩm vào Form Báo Giá khi bấm "Đặt mẫu"
        function prefillQuote(productName) {
            const noteField = document.getElementById('qNote');
            if (noteField) {
                noteField.value = 'Tôi cần tư vấn & báo giá sản phẩm: ' + productName;
                noteField.focus();
            }
        }

        // 4. Xử lý gửi Form Yêu Cầu Báo Giá trên trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const area = document.getElementById('qArea').value.trim();
            const category = document.getElementById('qCategory').value;
            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');

            if (box && text) {
                text.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá hạng mục "${category}"${area ? ' - Diện tích: ' + area : ''} đã được gửi tới bộ phận kinh doanh Sàn Gỗ Việt Gia Phát. Chúng tôi sẽ liên hệ lại ngay qua SĐT/Zalo 0936.029.897 - 0789.878.387.`;
                box.classList.remove('hidden');
                document.getElementById('quoteForm').reset();
            }
        }

        // 5. Tìm kiếm nhanh sản phẩm ngay trên trang chủ
        function filterProductsBySearch(keyword) {
            const query = keyword.toLowerCase().trim();
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const title = card.innerText.toLowerCase();
                if (!query || title.includes(query)) {
                    card.style.display = '';
                } else {
                    card.style.display = 'none';
                }
            });
        }
    </script>
</body>
</html>
