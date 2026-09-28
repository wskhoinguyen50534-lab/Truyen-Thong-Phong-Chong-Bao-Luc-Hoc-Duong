<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sản phẩm số & Công nghệ Truyền thông phòng chống Bạo lực Học đường</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eef2ff',
                            100: '#e0e7ff',
                            500: '#6366f1',
                            600: '#4f46e5',
                            700: '#4338ca',
                            900: '#312e81',
                        },
                        accent: {
                            500: '#06b6d4',
                            600: '#0891b2',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
        .dark .glass-card {
            background: rgba(30, 41, 59, 0.85);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .gradient-text {
            background: linear-gradient(135deg, #4f46e5 0%, #06b6d4 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #4f46e5 0%, #0891b2 100%);
        }
        @keyframes pulse-subtle {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.92; transform: scale(1.02); }
        }
        .animate-pulse-subtle {
            animation: pulse-subtle 4s infinite ease-in-out;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 dark:bg-slate-900 dark:text-slate-100 font-sans transition-colors duration-300 min-h-screen flex flex-col">

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-50 glass-card border-b border-slate-200 dark:border-slate-800 shadow-sm transition-all">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Logo & Title -->
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-xl gradient-bg flex items-center justify-center text-white font-bold text-xl shadow-md">
                        <i class="fa-solid font-shield-halved"></i>
                    </div>
                    <div>
                        <span class="text-xs font-semibold uppercase tracking-wider text-indigo-600 dark:text-indigo-400 block">Sản Phẩm Số & Công Nghệ</span>
                        <h1 class="text-sm sm:text-base font-bold leading-tight">Phòng Chống Bạo Lực Học Đường</h1>
                    </div>
                </div>

                <!-- Desktop Navigation -->
                <nav class="hidden md:flex items-center space-x-6 text-sm font-medium">
                    <a href="#overview" class="hover:text-indigo-600 dark:hover:text-indigo-400 transition">Tổng Quan</a>
                    <a href="#tech-hub" class="hover:text-indigo-600 dark:hover:text-indigo-400 transition">Giải Pháp Số</a>
                    <a href="#simulator" class="hover:text-indigo-600 dark:hover:text-indigo-400 transition">Tình Huống AI</a>
                    <a href="#wall" class="hover:text-indigo-600 dark:hover:text-indigo-400 transition">Mạng Lưới Cam Kết</a>
                    <a href="#helpline" class="px-3 py-1.5 rounded-lg bg-red-500 hover:bg-red-600 text-white font-semibold shadow-sm transition flex items-center space-x-2">
                        <i class="fa-solid fa-phone-volume animate-bounce"></i>
                        <span>Cứu Hợ 111</span>
                    </a>
                </nav>

                <!-- Mobile menu button & Theme toggle -->
                <div class="flex items-center space-x-2 md:hidden">
                    <a href="#helpline" class="px-2.5 py-1 rounded-md bg-red-500 text-white text-xs font-bold flex items-center gap-1">
                        <i class="fa-solid fa-phone-volume"></i> 111
                    </a>
                    <button id="mobile-menu-btn" class="p-2 rounded-lg text-slate-600 dark:text-slate-300 hover:bg-slate-100 dark:hover:bg-slate-800">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-4 pt-2 pb-4 space-y-2 border-t border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900 shadow-lg">
            <a href="#overview" class="block px-3 py-2 rounded-md hover:bg-slate-100 dark:hover:bg-slate-800 text-base font-medium">Tổng Quan</a>
            <a href="#tech-hub" class="block px-3 py-2 rounded-md hover:bg-slate-100 dark:hover:bg-slate-800 text-base font-medium">Giải Pháp Số</a>
            <a href="#simulator" class="block px-3 py-2 rounded-md hover:bg-slate-100 dark:hover:bg-slate-800 text-base font-medium">Tình Huống AI</a>
            <a href="#wall" class="block px-3 py-2 rounded-md hover:bg-slate-100 dark:hover:bg-slate-800 text-base font-medium">Mạng Lưới Cam Kết</a>
            <a href="#helpline" class="block px-3 py-2 rounded-md bg-red-100 text-red-600 font-bold dark:bg-red-950 dark:text-red-300">Tổng Đài Cứu Hợ 111</a>
        </div>
    </header>

    <main class="flex-grow">
        <!-- HERO SECTION -->
        <section id="overview" class="relative overflow-hidden py-16 sm:py-24 bg-gradient-to-b from-indigo-50/50 via-white to-slate-50 dark:from-slate-900 dark:via-slate-900 dark:to-slate-950">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
                <div class="grid lg:grid-cols-12 gap-12 items-center">
                    <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                        <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-indigo-100 dark:bg-indigo-950/80 text-indigo-700 dark:text-indigo-300 text-xs font-semibold">
                            <span class="w-2 h-2 rounded-full bg-indigo-500 animate-ping"></span>
                            <span>Truyền Thông Số & Công Nghệ Hiện Đại</span>
                        </div>
                        <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">
                            Ứng Dụng Công Nghệ Số Trong <br class="hidden sm:inline">
                            <span class="gradient-text">Truyền Thông Phòng Chống Bạo Lực Học Đường</span>
                        </h1>
                        <p class="text-base sm:text-lg text-slate-600 dark:text-slate-300 max-w-2xl mx-auto lg:mx-0">
                            Chuyển đổi phương thức truyền thông truyền thống sang các <strong>sản phẩm số tương tác</strong>, hệ thống AI nhận diện, thực tế ảo VR và nền tảng tố giác bảo mật — giúp xây dựng môi trường học đường an toàn, lành mạnh cho học sinh.
                        </p>

                        <div class="pt-2 flex flex-wrap gap-4 justify-center lg:justify-start">
                            <a href="#tech-hub" class="px-6 py-3 rounded-xl gradient-bg text-white font-medium hover:shadow-lg hover:shadow-indigo-500/25 transition flex items-center gap-2">
                                <i class="fa-solid fa-laptop-code"></i> Khám Phá Sản Phẩm Số
                            </a>
                            <a href="#simulator" class="px-6 py-3 rounded-xl border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800 font-medium transition flex items-center gap-2">
                                <i class="fa-solid fa-gamepad"></i> Trải Nghiệm Tình Huống
                            </a>
                        </div>

                        <!-- Stats Quick View -->
                        <div class="grid grid-cols-3 gap-4 pt-6 border-t border-slate-200 dark:border-slate-800">
                            <div>
                                <p class="text-2xl sm:text-3xl font-extrabold text-indigo-600 dark:text-indigo-400">100%</p>
                                <p class="text-xs text-slate-500 dark:text-slate-400 font-medium">Bảo mật thông tin tố giác</p>
                            </div>
                            <div>
                                <p class="text-2xl sm:text-3xl font-extrabold text-cyan-600 dark:text-cyan-400">24/7</p>
                                <p class="text-xs text-slate-500 dark:text-slate-400 font-medium">Hỗ trợ tâm lý qua AI Chatbot</p>
                            </div>
                            <div>
                                <p class="text-2xl sm:text-3xl font-extrabold text-emerald-600 dark:text-emerald-400">VR/AR</p>
                                <p class="text-xs text-slate-500 dark:text-slate-400 font-medium">Mô phỏng thấu cảm thực tế</p>
                            </div>
                        </div>
                    </div>

                    <!-- Interactive Tech Card Visual -->
                    <div class="lg:col-span-5">
                        <div class="relative mx-auto max-w-md lg:max-w-none">
                            <div class="absolute -inset-1 bg-gradient-to-r from-indigo-500 to-cyan-500 rounded-2xl blur opacity-30 animate-pulse-subtle"></div>
                            <div class="relative glass-card p-6 rounded-2xl shadow-xl space-y-4">
                                <div class="flex items-center justify-between border-b border-slate-200 dark:border-slate-700/50 pb-4">
                                    <div class="flex items-center space-x-3">
                                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                                    </div>
                                    <span class="text-xs font-mono text-slate-400">digital_protection_hub.v2</span>
                                </div>

                                <div class="space-y-3">
                                    <div class="bg-indigo-50 dark:bg-slate-800/80 p-3 rounded-xl flex items-start gap-3">
                                        <div class="p-2 rounded-lg bg-indigo-500 text-white shrink-0"><i class="fa-solid fa-robot"></i></div>
                                        <div>
                                            <h4 class="text-xs font-bold uppercase text-indigo-600 dark:text-indigo-400">AI Cyberbully Detector</h4>
                                            <p class="text-xs text-slate-600 dark:text-slate-300">Phân tích ngôn từ kích động & bắt nạt trực tuyến theo thời gian thực.</p>
                                        </div>
                                    </div>

                                    <div class="bg-cyan-50 dark:bg-slate-800/80 p-3 rounded-xl flex items-start gap-3">
                                        <div class="p-2 rounded-lg bg-cyan-500 text-white shrink-0"><i class="fa-solid fa-vr-cardboard"></i></div>
                                        <div>
                                            <h4 class="text-xs font-bold uppercase text-cyan-600 dark:text-cyan-400">VR Empathy Simulation</h4>
                                            <p class="text-xs text-slate-600 dark:text-slate-300">Trải nghiệm góc nhìn của nạn nhân giúp xây dựng lòng thấu cảm.</p>
                                        </div>
                                    </div>

                                    <div class="bg-emerald-50 dark:bg-slate-800/80 p-3 rounded-xl flex items-start gap-3">
                                        <div class="p-2 rounded-lg bg-emerald-500 text-white shrink-0"><i class="fa-solid fa-user-secret"></i></div>
                                        <div>
                                            <h4 class="text-xs font-bold uppercase text-emerald-600 dark:text-emerald-400">Anonymous Report Portal</h4>
                                            <p class="text-xs text-slate-600 dark:text-slate-300">Gửi thông báo khẩn cấp ẩn danh tới BGH và chuyên gia tư vấn.</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- DIGITAL PRODUCTS SHOWCASE -->
        <section id="tech-hub" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-2xl sm:text-4xl font-extrabold tracking-tight">Hệ Thống Sản Phẩm Số & Công Nghệ</h2>
                <p class="mt-3 text-slate-600 dark:text-slate-300">Các công cụ số sáng tạo được ứng dụng để đổi mới công tác truyền thông, phòng ngừa và xử lý bạo lực học đường.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Card 1: Chatbot AI -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-indigo-100 dark:bg-indigo-950 text-indigo-600 dark:text-indigo-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-comments"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">1. AI Chatbot Tư Vấn Tâm Lý Ẩn Danh</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Sử dụng AI lắng nghe 24/7, tự động lắng nghe tâm sự, tư vấn giải tỏa áp lực tâm lý và hướng dẫn giải quyết các nguy cơ bị đe dọa hoặc bắt nạt.
                        </p>
                    </div>
                    <button onclick="openDemoModal('chatbot')" class="mt-2 w-full py-2 px-4 rounded-lg bg-indigo-50 dark:bg-slate-800 hover:bg-indigo-100 text-indigo-600 dark:text-indigo-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-circle-play"></i> Xem Mô Phỏng Chatbot
                    </button>
                </div>

                <!-- Card 2: Reporting Portal -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-cyan-100 dark:bg-cyan-950 text-cyan-600 dark:text-cyan-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-shield-cat"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">2. Cổng Tố Giác Bảo Mật Mã Hóa</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Website/App cho phép chứng nhân hoặc nạn nhân gửi bằng ảnh, video, ghi âm hành vi bạo lực hoàn toàn ẩn danh, đảm bảo không lộ danh tính.
                        </p>
                    </div>
                    <button onclick="openDemoModal('report')" class="mt-2 w-full py-2 px-4 rounded-lg bg-cyan-50 dark:bg-slate-800 hover:bg-cyan-100 text-cyan-600 dark:text-cyan-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-paper-plane"></i> Thử Gửi Báo Cáo Mẫu
                    </button>
                </div>

                <!-- Card 3: VR Empathy -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-purple-100 dark:bg-purple-950 text-purple-600 dark:text-purple-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-vr-cardboard"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">3. Thực Tế Ảo VR "Thấu Cảm"</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Ứng dụng VR đặt học sinh vào vị trí người bị bắt nạt để cảm nhận nỗi đau tâm lý, từ đó nâng cao nhận thức và thay đổi hành vi cư xử.
                        </p>
                    </div>
                    <button onclick="openDemoModal('vr')" class="mt-2 w-full py-2 px-4 rounded-lg bg-purple-50 dark:bg-slate-800 hover:bg-purple-100 text-purple-600 dark:text-purple-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-glasses"></i> Khám Phá Mô Hình VR
                    </button>
                </div>

                <!-- Card 4: Media Podcast & Interactive Posters -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-amber-100 dark:bg-amber-950 text-amber-600 dark:text-amber-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-podcast"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">4. Poster Động & Podcast Học Đường</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Chuỗi Podcast truyền thông "Chuyện Học Đường" kết hợp Infographic tương tác và mã QR đặt tại các hành lang lớp học.
                        </p>
                    </div>
                    <button onclick="openDemoModal('podcast')" class="mt-2 w-full py-2 px-4 rounded-lg bg-amber-50 dark:bg-slate-800 hover:bg-amber-100 text-amber-600 dark:text-amber-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-headphones"></i> Bật Đoạn Audio Mẫu
                    </button>
                </div>

                <!-- Card 5: Cyberbullying Detector -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-rose-100 dark:bg-rose-950 text-rose-600 dark:text-rose-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-filter"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">5. Bộ Lọc Từ Tệ Bắt Nạt Mạng</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Công cụ tích hợp vào hội nhóm mạng xã hội học sinh để cảnh báo văn hóa bộc phát, miệt thị ngoại hình (body shaming) hoặc đe dọa.
                        </p>
                    </div>
                    <button onclick="openDemoModal('detector')" class="mt-2 w-full py-2 px-4 rounded-lg bg-rose-50 dark:bg-slate-800 hover:bg-rose-100 text-rose-600 dark:text-rose-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-magnifying-glass-chart"></i> Kích Hoạt Bộ Lọc Thử
                    </button>
                </div>

                <!-- Card 6: Online Gamification -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition border border-slate-200 dark:border-slate-800 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-100 dark:bg-emerald-950 text-emerald-600 dark:text-emerald-400 flex items-center justify-center text-xl mb-4 font-bold">
                            <i class="fa-solid fa-gamepad"></i>
                        </div>
                        <h3 class="text-lg font-bold mb-2">6. Gamification Học Tập Kỹ Năng Sống</h3>
                        <p class="text-sm text-slate-600 dark:text-slate-300 mb-4">
                            Game hóa các bài học ứng xử, quy tắc ứng xử trên mạng và cách tự bảo vệ bản thân qua các phần thưởng huy hiệu tích cực.
                        </p>
                    </div>
                    <a href="#simulator" class="mt-2 w-full py-2 px-4 rounded-lg bg-emerald-50 dark:bg-slate-800 hover:bg-emerald-100 text-emerald-600 dark:text-emerald-300 font-medium text-sm transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-play"></i> Chơi Game Mô Phỏng
                    </a>
                </div>
            </div>
        </section>

        <!-- SCENARIO SIMULATOR / QUIZ -->
        <section id="simulator" class="py-16 bg-slate-100/80 dark:bg-slate-850/50">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-8">
                    <span class="text-xs font-bold uppercase tracking-widest text-indigo-600 dark:text-indigo-400">Trải Nghiệm Tương Tác</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold mt-1">Mô Phỏng Xử Lý Tình Huống Bạo Lực Học Đường</h2>
                    <p class="text-slate-600 dark:text-slate-300 text-sm mt-2">Thử thách khả năng nhận diện và lựa chọn cách ứng xử thông minh nhất khi gặp các kịch bản bắt nạt thực tế.</p>
                </div>

                <div class="glass-card rounded-2xl p-6 sm:p-8 shadow-xl border border-slate-200 dark:border-slate-700">
                    <div id="quiz-container">
                        <!-- Progress Bar -->
                        <div class="flex items-center justify-between mb-4 text-xs font-semibold text-slate-500">
                            <span id="quiz-progress-text">Câu hỏi 1 / 3</span>
                            <span id="quiz-score-text">Điểm: 0</span>
                        </div>
                        <div class="w-full bg-slate-200 dark:bg-slate-700 h-2 rounded-full mb-6 overflow-hidden">
                            <div id="quiz-bar" class="gradient-bg h-full w-1/3 transition-all duration-300"></div>
                        </div>

                        <!-- Question Box -->
                        <div class="mb-6">
                            <span id="quiz-category" class="inline-block px-2.5 py-1 rounded text-xs font-bold bg-amber-100 text-amber-800 dark:bg-amber-950 dark:text-amber-300 mb-2">Bắt nạt trên mạng</span>
                            <h3 id="quiz-question" class="text-lg sm:text-xl font-bold leading-snug">Bạn phát hiện một nhóm chat riêng của lớp đang lan truyền ảnh chế cắt ghép xúc phạm một bạn học cùng lớp. Bạn sẽ làm gì?</h3>
                        </div>

                        <!-- Options Container -->
                        <div id="quiz-options" class="space-y-3 mb-6">
                            <!-- Injected dynamically via JS -->
                        </div>

                        <!-- Feedback area -->
                        <div id="quiz-feedback" class="hidden p-4 rounded-xl mb-4 text-sm font-medium"></div>

                        <!-- Next Action Button -->
                        <div class="flex justify-end">
                            <button id="quiz-next-btn" onclick="nextQuestion()" class="hidden px-5 py-2.5 rounded-xl gradient-bg text-white font-semibold text-sm hover:shadow-md transition">
                                Câu Tiếp Theo <i class="fa-solid fa-arrow-right ml-1"></i>
                            </button>
                        </div>
                    </div>

                    <!-- Final Score Screen (Hidden by default) -->
                    <div id="quiz-result" class="hidden text-center py-8 space-y-4">
                        <div class="w-16 h-16 mx-auto rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center text-3xl font-bold">
                            <i class="fa-solid fa-award"></i>
                        </div>
                        <h3 class="text-2xl font-bold">Hoàn Thành Bài Mô Phỏng!</h3>
                        <p id="result-message" class="text-slate-600 dark:text-slate-300">Bạn đã đạt <span id="final-score" class="font-bold text-indigo-600 dark:text-indigo-400">0</span>/30 điểm.</p>
                        <p class="text-xs text-slate-500 max-w-md mx-auto">Hãy nhớ rằng: Sự chủ động, thấu cảm và sử dụng các kênh báo cáo an toàn là chìa khóa để chấm dứt bạo lực học đường.</p>
                        <button onclick="restartQuiz()" class="px-6 py-2.5 rounded-xl border border-indigo-600 text-indigo-600 dark:text-indigo-400 font-semibold text-sm hover:bg-indigo-50 dark:hover:bg-slate-800 transition">
                            <i class="fa-solid fa-rotate-right mr-1"></i> Thử Lại Kịch Bản
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- DIGITAL PLEDGE / MESSAGE WALL -->
        <section id="wall" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-10">
                <span class="text-xs font-bold uppercase tracking-wider text-indigo-600 dark:text-indigo-400">Thông Điệp Yêu Thương</span>
                <h2 class="text-2xl sm:text-4xl font-extrabold tracking-tight mt-1">Bức Tường Cam Kết Số</h2>
                <p class="text-slate-600 dark:text-slate-300 text-sm mt-2">Cùng gửi lời động viên, cam kết nói "KHÔNG" với bạo lực học đường và lan tỏa năng lượng tích cực.</p>
            </div>

            <!-- Message Form Input -->
            <div class="max-w-2xl mx-auto mb-10 glass-card p-5 rounded-2xl border border-slate-200 dark:border-slate-800 shadow-sm">
                <form id="pledge-form" onsubmit="handlePledgeSubmit(event)" class="space-y-4">
                    <div class="grid sm:grid-cols-2 gap-4">
                        <input type="text" id="pledge-name" placeholder="Tên hoặc Biệt danh (Ví dụ: Minh Anh 11A2)" required class="w-full px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-700 bg-white dark:bg-slate-800 text-sm focus:ring-2 focus:ring-indigo-500 outline-none">
                        <select id="pledge-tag" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-700 bg-white dark:bg-slate-800 text-sm focus:ring-2 focus:ring-indigo-500 outline-none">
                            <option value="Cam Kết">🤝 Cam Kết Không Bắt Nạt</option>
                            <option value="Động Viên">❤️ Lời Động Viên Nạn Nhân</option>
                            <option value="Góp Ý">💡 Giải Pháp Học Đường</option>
                        </select>
                    </div>
                    <textarea id="pledge-text" rows="3" placeholder="Viết lời nhắn tích cực của bạn tại đây..." required class="w-full px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-700 bg-white dark:bg-slate-800 text-sm focus:ring-2 focus:ring-indigo-500 outline-none"></textarea>
                    <div class="flex justify-between items-center">
                        <span class="text-xs text-slate-400">Tin nhắn sẽ được đăng lên bảng công khai</span>
                        <button type="submit" class="px-5 py-2 rounded-xl gradient-bg text-white font-medium text-sm hover:shadow-md transition flex items-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i> Gửi Cam Kết
                        </button>
                    </div>
                </form>
            </div>

            <!-- Wall Messages Grid -->
            <div id="pledge-grid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <!-- Preset Messages -->
                <div class="glass-card p-5 rounded-xl border-l-4 border-l-indigo-500 border border-slate-200 dark:border-slate-800 shadow-sm">
                    <div class="flex items-center justify-between mb-2">
                        <span class="font-bold text-sm">Trần Hoàng Nam (Lớp 10B1)</span>
                        <span class="px-2 py-0.5 rounded text-[10px] font-bold bg-indigo-100 text-indigo-700 dark:bg-indigo-950 dark:text-indigo-300">Cam Kết</span>
                    </div>
                    <p class="text-sm text-slate-600 dark:text-slate-300">"Tớ hứa sẽ luôn lên tiếng bảo vệ bạn bè khi thấy hành vi bắt nạt, không bao giờ làm ngơ hay cổ vũ!"</p>
                    <div class="mt-3 text-xs text-slate-400 flex items-center justify-between">
                        <span>Vừa xong</span>
                        <button onclick="likeCard(this)" class="hover:text-red-500 transition flex items-center gap-1"><i class="fa-regular fa-heart"></i> <span>12</span></button>
                    </div>
                </div>

                <div class="glass-card p-5 rounded-xl border-l-4 border-l-rose-500 border border-slate-200 dark:border-slate-800 shadow-sm">
                    <div class="flex items-center justify-between mb-2">
                        <span class="font-bold text-sm">Hà Phương - Cựu Học Sinh</span>
                        <span class="px-2 py-0.5 rounded text-[10px] font-bold bg-rose-100 text-rose-700 dark:bg-rose-950 dark:text-rose-300">Động Viên</span>
                    </div>
                    <p class="text-sm text-slate-600 dark:text-slate-300">"Gửi các em: Hãy tự tin và chia sẻ ngay với thầy cô hoặc tổng đài 111 khi cảm thấy bất an. Các em không cô độc đâu!"</p>
                    <div class="mt-3 text-xs text-slate-400 flex items-center justify-between">
                        <span>10 phút trước</span>
                        <button onclick="likeCard(this)" class="hover:text-red-500 transition flex items-center gap-1"><i class="fa-regular fa-heart"></i> <span>28</span></button>
                    </div>
                </div>

                <div class="glass-card p-5 rounded-xl border-l-4 border-l-cyan-500 border border-slate-200 dark:border-slate-800 shadow-sm">
                    <div class="flex items-center justify-between mb-2">
                        <span class="font-bold text-sm">CLB Truyền Thông Trẻ</span>
                        <span class="px-2 py-0.5 rounded text-[10px] font-bold bg-cyan-100 text-cyan-700 dark:bg-cyan-950 dark:text-cyan-300">Góp Ý</span>
                    </div>
                    <p class="text-sm text-slate-600 dark:text-slate-300">"Hãy quét mã QR ở bảng tin trường để gửi phản hồi ẩn danh. Công nghệ sinh ra để bảo vệ chúng ta!"</p>
                    <div class="mt-3 text-xs text-slate-400 flex items-center justify-between">
                        <span>25 phút trước</span>
                        <button onclick="likeCard(this)" class="hover:text-red-500 transition flex items-center gap-1"><i class="fa-regular fa-heart"></i> <span>19</span></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- EMERGENCY CONTACTS & HELPLINES -->
        <section id="helpline" class="py-16 bg-red-50/60 dark:bg-red-950/20 border-t border-b border-red-100 dark:border-red-900/30">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-2xl mx-auto mb-10">
                    <span class="px-3 py-1 rounded-full bg-red-100 text-red-600 text-xs font-bold uppercase tracking-wider">Trợ Giúp Khẩn Cấp 24/7</span>
                    <h2 class="text-2xl sm:text-4xl font-extrabold tracking-tight mt-2 text-red-600 dark:text-red-400">Các Kênh Đường Dây Nóng Hỗ Trợ</h2>
                    <p class="text-slate-600 dark:text-slate-300 text-sm mt-2">Nếu bạn hoặc bạn bè đang gặp nguy hiểm hoặc cần tư vấn tâm lý khẩn cấp, hãy liên hệ ngay lập tức.</p>
                </div>

                <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- National Hotline 111 -->
                    <div class="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-md border-2 border-red-500 flex flex-col justify-between items-center text-center">
                        <div>
                            <div class="w-16 h-16 rounded-full bg-red-100 text-red-600 flex items-center justify-center text-2xl font-bold mx-auto mb-3 animate-pulse">
                                <i class="fa-solid fa-phone-volume"></i>
                            </div>
                            <h3 class="text-xl font-extrabold text-slate-800 dark:text-slate-100">Tổng Đài Quốc Gia 111</h3>
                            <p class="text-xs text-slate-500 dark:text-slate-400 mt-1 mb-4">Tổng đài quốc gia bảo vệ trẻ em (Miễn phí cước gọi 24/7)</p>
                        </div>
                        <a href="tel:111" class="w-full py-3 rounded-xl bg-red-600 hover:bg-red-700 text-white font-bold text-base transition shadow-md flex items-center justify-center gap-2">
                            <i class="fa-solid fa-phone"></i> Gọi 111 Ngay
                        </a>
                    </div>

                    <!-- School Counseling Hotline -->
                    <div class="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-md border border-slate-200 dark:border-slate-700 flex flex-col justify-between items-center text-center">
                        <div>
                            <div class="w-16 h-16 rounded-full bg-indigo-100 text-indigo-600 flex items-center justify-center text-2xl font-bold mx-auto mb-3">
                                <i class="fa-solid fa-user-doctor"></i>
                            </div>
                            <h3 class="text-xl font-extrabold text-slate-800 dark:text-slate-100">Phòng Tư Vấn Tâm Lý</h3>
                            <p class="text-xs text-slate-500 dark:text-slate-400 mt-1 mb-4">Tư vấn viên chuyên trách tâm lý học đường tại nhà trường</p>
                        </div>
                        <button onclick="alert('Đã kết nối trực tiếp với chuyên viên tư vấn trực ca.')" class="w-full py-3 rounded-xl bg-indigo-600 hover:bg-indigo-700 text-white font-bold text-base transition shadow-md flex items-center justify-center gap-2">
                            <i class="fa-solid fa-headset"></i> Kết Nối Tư Vấn Viên
                        </button>
                    </div>

                    <!-- Cyber Police / Online Protection -->
                    <div class="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-md border border-slate-200 dark:border-slate-700 flex flex-col justify-between items-center text-center sm:col-span-2 lg:col-span-1">
                        <div>
                            <div class="w-16 h-16 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center text-2xl font-bold mx-auto mb-3">
                                <i class="fa-solid fa-shield-virus"></i>
                            </div>
                            <h3 class="text-xl font-extrabold text-slate-800 dark:text-slate-100">Cổng An Ninh Mạng</h3>
                            <p class="text-xs text-slate-500 dark:text-slate-400 mt-1 mb-4">Xử lý các vụ việc bắt nạt, tống tiền, bôi nhọ trên không gian mạng</p>
                        </div>
                        <button onclick="openDemoModal('report')" class="w-full py-3 rounded-xl bg-cyan-600 hover:bg-cyan-700 text-white font-bold text-base transition shadow-md flex items-center justify-center gap-2">
                            <i class="fa-solid fa-file-shield"></i> Gửi Báo Cáo Khẩn
                        </button>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-900 text-slate-400 text-xs py-8 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center space-x-3">
                <div class="w-8 h-8 rounded-lg gradient-bg flex items-center justify-center text-white font-bold">
                    <i class="fa-solid fa-shield-halved"></i>
                </div>
                <span class="text-sm font-semibold text-slate-200">Truyền Thông Số Phòng Chống Bạo Lực Học Đường</span>
            </div>
            <p>© 2026 Dự án Chuyển đổi số Truyền thông Giáo dục Kỹ năng sống & An toàn Học đường.</p>
        </div>
    </footer>

    <!-- DEMO INTERACTIVE MODAL CONTAINER -->
    <div id="demo-modal" class="fixed inset-0 z-50 hidden bg-slate-900/60 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white dark:bg-slate-800 rounded-2xl max-w-lg w-full p-6 shadow-2xl border border-slate-200 dark:border-slate-700 relative animate-pulse-subtle">
            <button onclick="closeDemoModal()" class="absolute top-4 right-4 text-slate-400 hover:text-slate-600 dark:hover:text-slate-200 text-xl font-bold">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-content">
                <!-- Dynamic Content injected by JS -->
            </div>
        </div>
    </div>

    <script>
        // Quiz Data & State
        const quizData = [
            {
                category: "Bắt nạt trên mạng (Cyberbullying)",
                question: "Bạn phát hiện một nhóm chat riêng của lớp đang lan truyền ảnh chế cắt ghép xúc phạm một bạn học cùng lớp. Bạn nên xử lý thế nào?",
                options: [
                    { text: "A. Im lặng thoát nhóm để không bị liên lụy.", score: 0, feedback: "Chưa tối ưu! Sự im lặng của chứng nhân đôi khi vô tình tiếp tay cho hành vi bắt nạt." },
                    { text: "B. Chụp màn hình bằng chứng, nhắn riêng khuyên các bạn dừng lại và báo cáo cho giáo viên chủ nhiệm.", score: 10, feedback: "Chính xác! Lưu giữ bằng chứng và báo cáo cho người có trách nhiệm là cách làm đúng đắn và an toàn." },
                    { text: "C. Nhắn tin chửi lại các bạn trong nhóm để bảo vệ nạn nhân.", score: 2, feedback: "Không nên! Dùng bạo lực ngôn từ phản công sẽ chỉ làm mâu thuẫn leo thang phức tạp hơn." }
                ]
            },
            {
                category: "Bắt nạt tâm lý / Cô lập",
                question: "Một bạn học trong lớp liên tục bị cả nhóm tẩy chay, không cho tham gia bài tập nhóm và giấu đồ dùng học tập. Hành vi này là gì?",
                options: [
                    { text: "A. Chỉ là trò đùa vui tinh nghịch của học sinh.", score: 0, feedback: "Sai! Đây là hành vi bạo lực tinh thần/tâm lý gây tổn thương nghiêm trọng cho nạn nhân." },
                    { text: "B. Bạo lực tinh thần/tâm lý. Cần chủ động bắt chuyện, rủ bạn vào nhóm và báo giáo viên.", score: 10, feedback: "Rất chuẩn! Bắt nạt tinh thần để lại hậu quả tâm lý lâu dài. Thấu cảm và chủ động hỗ trợ là giải pháp xuất sắc." },
                    { text: "C. Mặc kệ vì đó là việc riêng giữa các bạn.", score: 0, feedback: "Chưa đúng. Xây dựng môi trường học đường lành mạnh cần sự đoàn kết của tập thể." }
                ]
            },
            {
                category: "Bắt nạt thể xác / Đe dọa",
                question: "Bạn vô tình chứng kiến một nhóm học sinh khóa trên đang trấn lột tiền và đe dọa đánh một học sinh lớp dưới ở khu vực vắng. Bạn nên làm gì?",
                options: [
                    { text: "A. Lao vào can ngăn trực tiếp ngay lập tức.", score: 3, feedback: "Cẩn thận! Lao vào trực tiếp khi không có bảo hộ có thể khiến bạn gặp nguy hiểm thể xác." },
                    { text: "B. Tìm kiếm sự trợ giúp ngay từ bảo vệ, thầy cô gần nhất hoặc gọi hotline 111 khẩn cấp.", score: 10, feedback: "Xuất sắc! Đảm bảo an toàn cho bản thân đồng thời tìm kiếm sự can thiệp từ người lớn là quy trình chuẩn." },
                    { text: "C. Quay video lại đăng lên mạng xã hội để câu view.", score: 0, feedback: "Rất nguy hiểm và vi phạm đạo đức/quy định bảo mật hình ảnh cá nhân!" }
                ]
            }
        ];

        let currentQuestion = 0;
        let totalScore = 0;

        function loadQuestion() {
            const q = quizData[currentQuestion];
            document.getElementById('quiz-progress-text').innerText = `Câu hỏi ${currentQuestion + 1} / ${quizData.length}`;
            document.getElementById('quiz-score-text').innerText = `Điểm: ${totalScore}`;
            document.getElementById('quiz-bar').style.width = `${((currentQuestion + 1) / quizData.length) * 100}%`;
            
            document.getElementById('quiz-category').innerText = q.category;
            document.getElementById('quiz-question').innerText = q.question;

            const optionsContainer = document.getElementById('quiz-options');
            optionsContainer.innerHTML = '';

            q.options.forEach((opt, idx) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-3.5 rounded-xl border border-slate-200 dark:border-slate-700 bg-white/50 dark:bg-slate-800/50 hover:bg-indigo-50 dark:hover:bg-slate-700 transition text-sm font-medium flex items-center justify-between";
                btn.innerHTML = `<span>${opt.text}</span> <i class="fa-regular fa-circle text-slate-300"></i>`;
                btn.onclick = () => selectOption(idx, btn);
                optionsContainer.appendChild(btn);
            });

            document.getElementById('quiz-feedback').classList.add('hidden');
            document.getElementById('quiz-next-btn').classList.add('hidden');
        }

        function selectOption(index, element) {
            const q = quizData[currentQuestion];
            const selected = q.options[index];

            // Disable all option buttons
            const buttons = document.getElementById('quiz-options').querySelectorAll('button');
            buttons.forEach(b => {
                b.disabled = true;
                b.classList.add('opacity-60', 'cursor-not-allowed');
            });

            element.classList.remove('opacity-60');
            element.classList.add('border-indigo-600', 'bg-indigo-50', 'dark:bg-slate-700');

            totalScore += selected.score;
            document.getElementById('quiz-score-text').innerText = `Điểm: ${totalScore}`;

            const feedback = document.getElementById('quiz-feedback');
            feedback.innerText = selected.feedback;
            feedback.className = `p-4 rounded-xl mb-4 text-sm font-medium ${selected.score === 10 ? 'bg-emerald-100 text-emerald-800 dark:bg-emerald-950 dark:text-emerald-200' : 'bg-amber-100 text-amber-800 dark:bg-amber-950 dark:text-amber-200'}`;
            feedback.classList.remove('hidden');

            document.getElementById('quiz-next-btn').classList.remove('hidden');
        }

        function nextQuestion() {
            currentQuestion++;
            if (currentQuestion < quizData.length) {
                loadQuestion();
            } else {
                showQuizResult();
            }
        }

        function showQuizResult() {
            document.getElementById('quiz-container').classList.add('hidden');
            document.getElementById('quiz-result').classList.remove('hidden');
            document.getElementById('final-score').innerText = totalScore;
        }

        function restartQuiz() {
            currentQuestion = 0;
            totalScore = 0;
            document.getElementById('quiz-result').classList.add('hidden');
            document.getElementById('quiz-container').classList.remove('hidden');
            loadQuestion();
        }

        // Handle Pledge Wall Input
        function handlePledgeSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('pledge-name').value;
            const tag = document.getElementById('pledge-tag').value;
            const text = document.getElementById('pledge-text').value;

            const colorMap = {
                'Cam Kết': 'border-l-indigo-500 bg-indigo-100 text-indigo-700 dark:bg-indigo-950 dark:text-indigo-300',
                'Động Viên': 'border-l-rose-500 bg-rose-100 text-rose-700 dark:bg-rose-950 dark:text-rose-300',
                'Góp Ý': 'border-l-cyan-500 bg-cyan-100 text-cyan-700 dark:bg-cyan-950 dark:text-cyan-300'
            };

            const grid = document.getElementById('pledge-grid');
            const card = document.createElement('div');
            card.className = `glass-card p-5 rounded-xl border-l-4 border ${colorMap[tag].split(' ')[0]} border-slate-200 dark:border-slate-800 shadow-sm animate-fade-in`;
            card.innerHTML = `
                <div class="flex items-center justify-between mb-2">
                    <span class="font-bold text-sm">${escapeHtml(name)}</span>
                    <span class="px-2 py-0.5 rounded text-[10px] font-bold ${colorMap[tag].split(' ').slice(1).join(' ')}">${tag}</span>
                </div>
                <p class="text-sm text-slate-600 dark:text-slate-300">"${escapeHtml(text)}"</p>
                <div class="mt-3 text-xs text-slate-400 flex items-center justify-between">
                    <span>Vừa xong</span>
                    <button onclick="likeCard(this)" class="hover:text-red-500 transition flex items-center gap-1"><i class="fa-regular fa-heart"></i> <span>0</span></button>
                </div>
            `;

            grid.prepend(card);
            document.getElementById('pledge-form').reset();
        }

        function escapeHtml(str) {
            return str.replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;").replace(/"/g, "&quot;");
        }

        function likeCard(btn) {
            const countSpan = btn.querySelector('span');
            let count = parseInt(countSpan.innerText);
            const icon = btn.querySelector('i');
            if (icon.classList.contains('fa-regular')) {
                icon.classList.remove('fa-regular');
                icon.classList.add('fa-solid', 'text-red-500');
                countSpan.innerText = count + 1;
            } else {
                icon.classList.remove('fa-solid', 'text-red-500');
                icon.classList.add('fa-regular');
                countSpan.innerText = count - 1;
            }
        }

        // Demo Interactive Modals
        function openDemoModal(type) {
            const modal = document.getElementById('demo-modal');
            const content = document.getElementById('modal-content');

            if (type === 'chatbot') {
                content.innerHTML = `
                    <h3 class="text-lg font-bold mb-3 flex items-center gap-2 text-indigo-600"><i class="fa-solid fa-robot"></i> Mô Phỏng AI Chatbot Tư Vấn</h3>
                    <div class="bg-slate-100 dark:bg-slate-900 p-3 rounded-xl h-48 overflow-y-auto space-y-2 text-xs mb-3">
                        <div class="bg-indigo-600 text-white p-2 rounded-lg max-w-[80%]">Xin chào! Tớ là AI Trợ Lý Học Đường. Bạn đang gặp phải áp lực hoặc lo lắng gì ở trường? Tớ luôn ở đây lắng nghe và giữ bí mật.</div>
                        <div class="bg-slate-200 dark:bg-slate-800 text-slate-700 dark:text-slate-200 p-2 rounded-lg max-w-[80%] ml-auto">Mình bị một nhóm bạn lập nhóm mạng xã hội để chế giễu...</div>
                        <div class="bg-indigo-600 text-white p-2 rounded-lg max-w-[80%]">Tớ rất tiếc khi nghe điều này. Lỗi hoàn toàn không phải ở bạn. Bạn hãy lưu lại hình ảnh bằng chứng và báo với giáo viên hoặc gửi thông tin ẩn danh qua Cổng Tố Giác của trường nhé!</div>
                    </div>
                    <p class="text-xs text-slate-500">Mô hình AI giúp giải tỏa căng thẳng tâm lý ban đầu cho học sinh 24/7.</p>
                `;
            } else if (type === 'report') {
                content.innerHTML = `
                    <h3 class="text-lg font-bold mb-3 flex items-center gap-2 text-cyan-600"><i class="fa-solid fa-shield-cat"></i> Mô Phỏng Cổng Báo Cáo Ẩn Danh</h3>
                    <form onsubmit="event.preventDefault(); alert('Báo cáo thử nghiệm đã được gửi bảo mật!'); closeDemoModal();" class="space-y-3 text-xs">
                        <div>
                            <label class="block font-semibold mb-1">Loại sự việc:</label>
                            <select class="w-full p-2 rounded border border-slate-300 dark:border-slate-700 dark:bg-slate-800"><option>Bắt nạt trên mạng xã hội</option><option>Đe dọa/Trấn lột thể xác</option><option>Cô lập/Tẩy chay</option></select>
                        </div>
                        <div>
                            <label class="block font-semibold mb-1">Mô tả tóm tắt sự việc:</label>
                            <textarea class="w-full p-2 rounded border border-slate-300 dark:border-slate-700 dark:bg-slate-800" rows="3" placeholder="Ghi rõ thời gian, địa điểm nếu có..."></textarea>
                        </div>
                        <div class="p-2 bg-emerald-50 text-emerald-700 rounded flex items-center gap-2"><i class="fa-solid fa-lock"></i> Hệ thống mã hóa thông tin. Không lưu địa chỉ IP cá nhân.</div>
                        <button type="submit" class="w-full py-2 bg-cyan-600 text-white font-bold rounded">Gửi Báo Cáo Bảo Mật</button>
                    </form>
                `;
            } else if (type === 'vr') {
                content.innerHTML = `
                    <h3 class="text-lg font-bold mb-2 flex items-center gap-2 text-purple-600"><i class="fa-solid fa-vr-cardboard"></i> Trải Nghiệm VR Thấu Cảm</h3>
                    <div class="aspect-video bg-slate-900 rounded-xl flex flex-col items-center justify-center text-white p-4 text-center">
                        <i class="fa-solid fa-glasses text-4xl mb-2 text-purple-400 animate-bounce"></i>
                        <p class="text-xs font-semibold">Đang kết nối kính VR / Thiết bị 360°...</p>
                        <p class="text-[10px] text-slate-400 mt-1">Học sinh trải nghiệm tình huống giả định dưới góc nhìn của nạn nhân bị bắt nạt để gia tăng sự thấu cảm.</p>
                    </div>
                `;
            } else if (type === 'podcast') {
                content.innerHTML = `
                    <h3 class="text-lg font-bold mb-3 flex items-center gap-2 text-amber-600"><i class="fa-solid fa-podcast"></i> Radio / Podcast Học Đường</h3>
                    <div class="bg-amber-50 dark:bg-slate-900 p-4 rounded-xl border border-amber-200 dark:border-slate-700 flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-amber-500 text-white flex items-center justify-center text-xl shrink-0"><i class="fa-solid fa-play"></i></div>
                        <div>
                            <h4 class="text-sm font-bold">Tập 05: "Sức Mạnh Của Lời Nói Tích Cực"</h4>
                            <p class="text-xs text-slate-500">Chủ đề truyền thông Tháng 10 - Phát thanh học đường</p>
                        </div>
                    </div>
                `;
            } else if (type === 'detector') {
                content.innerHTML = `
                    <h3 class="text-lg font-bold mb-3 flex items-center gap-2 text-rose-600"><i class="fa-solid fa-filter"></i> Bộ Lọc Ngôn Từ Xúc Phạm AI</h3>
                    <div class="space-y-2 text-xs">
                        <p class="font-medium">Thử nhập tin nhắn có chứa từ ngữ công kích:</p>
                        <input type="text" value="Bạn mập như con lợn vậy!" class="w-full p-2 rounded border border-red-300 dark:border-red-900 dark:bg-slate-800 text-red-600" readonly>
                        <div class="p-2 bg-red-100 dark:bg-red-950/60 text-red-700 dark:text-red-300 rounded flex items-center gap-2">
                            <i class="fa-solid fa-triangle-exclamation text-lg"></i>
                            <span>Cảnh báo: Phát hiện hành vi "Body Shaming" (Miệt thị ngoại hình). Tin nhắn đã bị chặn tự động!</span>
                        </div>
                    </div>
                `;
            }

            modal.classList.remove('hidden');
        }

        function closeDemoModal() {
            document.getElementById('demo-modal').classList.add('hidden');
        }

        // Mobile Menu Toggle Logic
        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Initialize App
        window.onload = function() {
            loadQuestion();
        }
    </script>
</body>
</html>
