<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Truyền Thông Công Nghệ - Phòng Chống Bạo Lực Học Đường</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap');
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 50%, #311042 100%);
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .glass-card-light {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(226, 232, 240, 0.8);
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col">

    <!-- Header Navigation -->
    <header class="sticky top-0 z-50 glass-card border-b border-slate-800 bg-slate-950/80 backdrop-blur-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-indigo-500 to-rose-500 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-indigo-500/30">
                    <i class="fa-solid font-bold fa-shield-halved"></i>
                </div>
                <div>
                    <h1 class="text-lg font-bold bg-gradient-to-r from-indigo-400 via-purple-300 to-rose-400 bg-clip-text text-transparent">
                        EduShield Tech
                    </h1>
                    <p class="text-xs text-slate-400">Công nghệ truyền thông phòng chống Bạo lực học đường</p>
                </div>
            </div>

            <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
                <a href="#about" class="hover:text-indigo-400 transition-colors">Tổng Quan</a>
                <a href="#solutions" class="hover:text-indigo-400 transition-colors">Sản Phẩm Số</a>
                <a href="#simulator" class="hover:text-indigo-400 transition-colors">Mô Phỏng Tình Huống</a>
                <a href="#pledge" class="hover:text-indigo-400 transition-colors">Thông Điệp</a>
            </nav>

            <a href="#emergency" class="px-5 py-2.5 rounded-full bg-gradient-to-r from-rose-500 to-red-600 text-white font-semibold text-sm shadow-lg shadow-rose-500/25 hover:shadow-rose-500/40 hover:scale-105 transition-all flex items-center gap-2">
                <i class="fa-solid fa-phone-volume animate-pulse"></i>
                <span>Trợ Giúp Khẩn Cấp (111)</span>
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden pt-12 pb-20 md:py-28 gradient-bg">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_30%,rgba(99,102,241,0.15),transparent_50%)]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-indigo-500/10 border border-indigo-500/30 text-indigo-300 text-xs font-semibold uppercase tracking-wider mb-6">
                    <i class="fa-solid fa-microchip"></i> Đổi mới phương thức truyền thông giáo dục
                </span>
                <h1 class="text-3xl sm:text-5xl font-extrabold text-white tracking-tight leading-tight mb-6">
                    Sản Phẩm Số & Ứng Dụng Công Nghệ
                    <span class="block text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 via-purple-300 to-rose-400 mt-2">
                        Truyền Thông Phòng Chống Bạo Lực Học Đường
                    </span>
                </h1>
                <p class="text-slate-300 text-base sm:text-lg leading-relaxed mb-8">
                    Tận dụng sức mạnh của trí tuệ nhân tạo, nền tảng tương tác và truyền thông đa phương tiện để lan tỏa thông điệp yêu thương, tạo dựng môi trường học đường an toàn, lành mạnh cho học sinh.
                </p>
                <div class="flex flex-wrap justify-center gap-4">
                    <a href="#solutions" class="px-7 py-3.5 rounded-xl bg-indigo-600 hover:bg-indigo-500 text-white font-semibold text-sm shadow-xl shadow-indigo-600/30 hover:shadow-indigo-500/50 transition-all flex items-center gap-2">
                        <i class="fa-solid fa-rocket"></i> Khám Phá Giải Pháp Số
                    </a>
                    <a href="#simulator" class="px-7 py-3.5 rounded-xl glass-card hover:bg-white/10 text-white font-semibold text-sm transition-all flex items-center gap-2 border border-slate-700">
                        <i class="fa-solid fa-gamepad"></i> Trải Nghiệm Tình Huống
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Key Digital Products Section -->
    <section id="solutions" class="py-20 bg-slate-900/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-2xl sm:text-3xl font-bold text-white mb-4">Các Mô Hình Truyền Thông Số Nổi Bật</h2>
                <p class="text-slate-400 text-sm sm:text-base">Các sản phẩm công nghệ được ứng dụng trực tiếp trong công tác tuyên truyền và phòng ngừa bạo lực học đường.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-indigo-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-indigo-500/10 border border-indigo-500/20 text-indigo-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-robot"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Chatbot Trợ Lý Tâm Lý AI</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Tích hợp AI để tư vấn 24/7, lắng nghe và tâm sự ẩn danh với học sinh gặp áp lực hoặc nguy cơ bị bắt nạt.
                    </p>
                    <span class="inline-block text-xs font-semibold text-indigo-400 bg-indigo-500/10 px-3 py-1 rounded-full">Trí Tuệ Nhân Tạo</span>
                </div>

                <!-- Card 2 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-purple-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-purple-500/10 border border-purple-500/20 text-purple-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-bullhorn"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Cổng Báo Cáo Ẩn Danh SOS</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Nền tảng web/app cho phép học sinh gửi thông báo khẩn cấp hoặc phản ánh hành vi bắt nạt mà không sợ lộ danh tính.
                    </p>
                    <span class="inline-block text-xs font-semibold text-purple-400 bg-purple-500/10 px-3 py-1 rounded-full">Ứng Dụng Web/App</span>
                </div>

                <!-- Card 3 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-rose-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-rose-500/10 border border-rose-500/20 text-rose-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-vr-cardboard"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Phim Tương Tác & Phim VR</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Sử dụng công nghệ thực tế ảo giúp học sinh nhập vai, trải nghiệm góc nhìn của nạn nhân để xây dựng lòng thấu cảm.
                    </p>
                    <span class="inline-block text-xs font-semibold text-rose-400 bg-rose-500/10 px-3 py-1 rounded-full">Truyền Thông Đa Phương Tiện</span>
                </div>

                <!-- Card 4 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-podcast"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Chuỗi Podcast & Video Ngắn</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Sản xuất nội dung số lan truyền trên TikTok/Facebook/YouTube nâng cao nhận thức về bắt nạt trên mạng (Cyberbullying).
                    </p>
                    <span class="inline-block text-xs font-semibold text-emerald-400 bg-emerald-500/10 px-3 py-1 rounded-full">Mạng Xã Hội</span>
                </div>

                <!-- Card 5 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/10 border border-amber-500/20 text-amber-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-gamepad"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Gamification - Trò Chơi Tuyên Truyền</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Thiết kế game trắc nghiệm và giải đố tình huống giúp việc học kỹ năng ứng xử trở nên sinh động, hấp dẫn.
                    </p>
                    <span class="inline-block text-xs font-semibold text-amber-400 bg-amber-500/10 px-3 py-1 rounded-full">Game Giáo Dục</span>
                </div>

                <!-- Card 6 -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 hover:border-cyan-500/50 transition-all duration-300 group">
                    <div class="w-12 h-12 rounded-xl bg-cyan-500/10 border border-cyan-500/20 text-cyan-400 flex items-center justify-center text-xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-shield-cat"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Bộ Lọc & Cảnh Báo Từ Bắt Nạt</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Công cụ AI phát hiện từ ngữ độc hại, xúc phạm trên môi trường mạng học đường và đưa ra cảnh báo kịp thời.
                    </p>
                    <span class="inline-block text-xs font-semibold text-cyan-400 bg-cyan-500/10 px-3 py-1 rounded-full">An Ninh Mạng</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Simulator Section -->
    <section id="simulator" class="py-20 bg-slate-950">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-indigo-400 text-xs font-bold uppercase tracking-wider">Trải nghiệm tương tác</span>
                <h2 class="text-2xl sm:text-3xl font-bold text-white mt-2">Góc Xử Lý Tình Huống Học Đường</h2>
                <p class="text-slate-400 text-sm mt-2">Thử tài ứng xử của bạn khi gặp các tình huống liên quan đến bạo lực học đường.</p>
            </div>

            <div class="glass-card p-6 sm:p-8 rounded-2xl border border-slate-800 relative">
                <div id="quiz-container">
                    <div class="flex items-center justify-between text-xs text-indigo-400 font-semibold mb-4">
                        <span>Tình huống <span id="current-step">1</span>/3</span>
                        <span id="quiz-category" class="bg-indigo-500/10 px-2.5 py-1 rounded-md">Bắt nạt trên mạng</span>
                    </div>

                    <h3 id="quiz-question" class="text-lg sm:text-xl font-bold text-white mb-6">
                        Bạn thấy một nhóm bạn đăng ảnh chế xúc phạm một bạn cùng lớp lên mạng xã hội. Bạn sẽ làm gì?
                    </h3>

                    <div id="quiz-options" class="space-y-3">
                        <!-- Options generated by JS -->
                    </div>

                    <div id="quiz-feedback" class="hidden mt-6 p-4 rounded-xl text-sm leading-relaxed"></div>

                    <div class="mt-6 flex justify-end">
                        <button id="next-btn" onclick="nextQuestion()" class="hidden px-6 py-2.5 bg-indigo-600 hover:bg-indigo-500 text-white rounded-xl text-sm font-semibold transition-all">
                            Tình huống tiếp theo <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Digital Pledge Board -->
    <section id="pledge" class="py-20 bg-slate-900/40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12">
                <h2 class="text-2xl sm:text-3xl font-bold text-white mb-4">Bức Tường Thông Điệp Yêu Thương</h2>
                <p class="text-slate-400 text-sm">Gửi lời chúc, cam kết chống bạo lực học đường để cùng xây dựng môi trường an toàn.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Form Input -->
                <div class="glass-card p-6 rounded-2xl border border-slate-800 h-fit">
                    <h3 class="text-base font-bold text-white mb-4 flex items-center gap-2">
                        <i class="fa-solid fa-pen-to-square text-indigo-400"></i> Gửi thông điệp của bạn
                    </h3>
                    <form id="pledge-form" onsubmit="addPledge(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-medium text-slate-400 mb-1">Họ và tên / Biệt danh</label>
                            <input type="text" id="pledge-name" required placeholder="Ví dụ: Minh Anh - Lớp 10A1" class="w-full px-4 py-2.5 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-indigo-500">
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-slate-400 mb-1">Thông điệp của bạn</label>
                            <textarea id="pledge-msg" required rows="3" placeholder="Hãy tôn trọng và giúp đỡ bạn bè xung quanh..." class="w-full px-4 py-2.5 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-indigo-500"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 bg-gradient-to-r from-indigo-500 to-purple-600 hover:from-indigo-600 hover:to-purple-700 text-white rounded-xl font-semibold text-sm transition-all shadow-lg shadow-indigo-500/20">
                            Đăng Thông Điệp
                        </button>
                    </form>
                </div>

                <!-- Messages Board -->
                <div class="lg:col-span-2 grid grid-cols-1 sm:grid-cols-2 gap-4" id="pledge-list">
                    <!-- Message Cards -->
                    <div class="glass-card p-5 rounded-xl border border-slate-800">
                        <div class="flex items-center justify-between mb-2">
                            <span class="font-semibold text-indigo-300 text-sm">Nguyễn Hoàng Nam</span>
                            <span class="text-xs text-slate-500">Vừa xong</span>
                        </div>
                        <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">"Nói KHÔNG với bạo lực học đường! Hãy biến trường học thành ngôi nhà thứ hai ngập tràn niềm vui."</p>
                    </div>

                    <div class="glass-card p-5 rounded-xl border border-slate-800">
                        <div class="flex items-center justify-between mb-2">
                            <span class="font-semibold text-purple-300 text-sm">Trần Lê Khánh Linh</span>
                            <span class="text-xs text-slate-500">10 phút trước</span>
                        </div>
                        <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">"Sự im lặng trước hành vi xấu đôi khi là tiếp tay. Hãy dũng cảm lên tiếng bảo vệ bạn mình!"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Emergency Contacts Section -->
    <section id="emergency" class="py-16 bg-gradient-to-b from-slate-900 to-slate-950 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-card p-8 sm:p-12 rounded-3xl border border-rose-500/30 bg-rose-950/10 flex flex-col md:flex-row items-center justify-between gap-8">
                <div class="space-y-3 text-center md:text-left">
                    <span class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-rose-500/20 text-rose-300 text-xs font-bold uppercase">
                        <i class="fa-solid fa-circle-exclamation"></i> Kênh Hỗ Trợ Khẩn Cấp
                    </span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-white">Bạn Cần Sự Trợ Giúp Kịp Thời?</h2>
                    <p class="text-slate-300 text-sm max-w-xl">
                        Nếu bạn hoặc người thân đang là nạn nhân của bạo lực học đường, đừng ngần ngại liên hệ ngay với các đường dây nóng tư vấn miễn phí 24/7.
                    </p>
                </div>
                <div class="flex flex-col sm:flex-row gap-4 w-full md:w-auto">
                    <a href="tel:111" class="px-6 py-4 bg-rose-600 hover:bg-rose-500 text-white rounded-2xl font-bold text-center flex items-center justify-center gap-3 shadow-xl shadow-rose-600/30 transition-all">
                        <i class="fa-solid fa-phone text-xl"></i>
                        <div>
                            <div class="text-xs font-normal">Tổng đài Quốc gia</div>
                            <div class="text-lg">111 (Bảo vệ Trẻ em)</div>
                        </div>
                    </a>
                    <a href="tel:113" class="px-6 py-4 glass-card hover:bg-white/10 text-white rounded-2xl font-bold text-center flex items-center justify-center gap-3 border border-slate-700 transition-all">
                        <i class="fa-solid fa-shield text-xl text-indigo-400"></i>
                        <div>
                            <div class="text-xs font-normal">Cảnh sát Khẩn cấp</div>
                            <div class="text-lg">113</div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="mt-auto py-8 border-t border-slate-900 bg-slate-950 text-center text-xs text-slate-500">
        <div class="max-w-7xl mx-auto px-4">
            <p>© 2026 EduShield Tech - Dự án Truyền thông Sản phẩm số Phòng chống Bạo lực Học đường.</p>
        </div>
    </footer>

    <!-- Interactive Script -->
    <script>
        // Quiz Data
        const quizData = [
            {
                category: "Bắt nạt trên mạng (Cyberbullying)",
                question: "Bạn thấy một nhóm bạn đăng ảnh chế xúc phạm một bạn cùng lớp lên mạng xã hội. Bạn nên xử lý thế nào?",
                options: [
                    { text: "Bình luận tham gia hưởng ứng để không bị cô lập.", correct: false, feedback: "Không nên! Tham gia hưởng ứng làm tổn thương nạn nhân và tiếp tay cho hành vi xấu." },
                    { text: "Chụp ảnh màn hình làm bằng chứng, báo cáo (report) bài viết và gửi tới thầy cô/phụ huynh.", correct: true, feedback: "Chính xác! Lưu bằng chứng và báo cho người có thẩm quyền là cách xử lý văn minh và an toàn nhất." },
                    { text: "Lờ đi coi như không phải việc của mình.", correct: false, feedback: "Thờ ơ có thể khiến tình trạng bắt nạt tiếp diễn nghiêm trọng hơn đối với nạn nhân." }
                ]
            },
            {
                category: "Bạo lực tinh thần",
                question: "Một bạn trong lớp thường xuyên bị các bạn khác tẩy chay, nói xấu và cô lập trong các hoạt động nhóm. Bạn sẽ làm gì?",
                options: [
                    { text: "Chủ động tiếp cận, trò chuyện và rủ bạn tham gia nhóm học tập cùng mình.", correct: true, feedback: "Tuyệt vời! Sự đồng cảm và chủ động của bạn sẽ giúp nạn nhân vượt qua sự cô lập." },
                    { text: "Hùa theo số đông để tránh trở thành mục tiêu tiếp theo.", correct: false, feedback: "Hành động này làm gia tăng tổn thương tâm lý cho bạn học." },
                    { text: "Tới tranh cãi nảy lửa với nhóm bạn tẩy chay.", correct: false, feedback: "Tranh cãi gay gắt có thể làm căng thẳng leo thang. Hãy chọn cách hỗ trợ bạn và báo cáo giáo viên." }
                ]
            },
            {
                category: "Bạo lực thể xác",
                question: "Khi chứng kiến một nhóm học sinh đang đe dọa hoặc có hành vi bạo lực thể xác với bạn khác ngoài cổng trường, hành động đúng là:",
                options: [
                    { text: "Lao vào can ngăn trực tiếp một mình.", correct: false, feedback: "Cảnh báo! Lao vào can ngăn trực tiếp có thể khiến bạn gặp nguy hiểm thể xác." },
                    { text: "Dùng điện thoại quay video rồi đăng ngay lên mạng.", correct: false, feedback: "Quay video đăng mạng không giải quyết được nguy cơ khẩn cấp và có thể vi phạm quyền riêng tư." },
                    { text: "Tìm sự giúp đỡ ngay lập tức từ bảo vệ, giáo viên hoặc người lớn gần nhất.", correct: true, feedback: "Chính xác! Đảm bảo an toàn cho bản thân và hô hoán người lớn hỗ trợ là giải pháp tối ưu." }
                ]
            }
        ];

        let currentStep = 0;

        function loadQuestion() {
            const currentQuiz = quizData[currentStep];
            document.getElementById('current-step').innerText = currentStep + 1;
            document.getElementById('quiz-category').innerText = currentQuiz.category;
            document.getElementById('quiz-question').innerText = currentQuiz.question;
            
            const optionsContainer = document.getElementById('quiz-options');
            optionsContainer.innerHTML = '';

            const feedbackEl = document.getElementById('quiz-feedback');
            feedbackEl.classList.add('hidden');

            document.getElementById('next-btn').classList.add('hidden');

            currentQuiz.options.forEach((opt, idx) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-4 rounded-xl glass-card hover:bg-slate-800/80 border border-slate-800 text-sm text-slate-200 transition-all flex items-center justify-between";
                btn.innerHTML = `<span>${opt.text}</span> <i class="fa-regular fa-circle text-slate-500"></i>`;
                btn.onclick = () => selectOption(idx, opt.correct, opt.feedback, btn);
                optionsContainer.appendChild(btn);
            });
        }

        function selectOption(index, isCorrect, feedback, btnElement) {
            const allBtns = document.getElementById('quiz-options').children;
            for (let b of allBtns) {
                b.disabled = true;
                b.classList.add('opacity-60');
            }
            btnElement.classList.remove('opacity-60');

            const feedbackEl = document.getElementById('quiz-feedback');
            feedbackEl.classList.remove('hidden');

            if (isCorrect) {
                btnElement.classList.add('border-emerald-500', 'bg-emerald-950/30');
                feedbackEl.className = "mt-6 p-4 rounded-xl text-sm leading-relaxed bg-emerald-500/10 border border-emerald-500/30 text-emerald-300";
                feedbackEl.innerHTML = `<i class="fa-solid fa-circle-check mr-2"></i> <strong>Đúng rồi!</strong> ${feedback}`;
            } else {
                btnElement.classList.add('border-rose-500', 'bg-rose-950/30');
                feedbackEl.className = "mt-6 p-4 rounded-xl text-sm leading-relaxed bg-rose-500/10 border border-rose-500/30 text-rose-300";
                feedbackEl.innerHTML = `<i class="fa-solid fa-circle-xmark mr-2"></i> <strong>Chưa chính xác!</strong> ${feedback}`;
            }

            document.getElementById('next-btn').classList.remove('hidden');
        }

        function nextQuestion() {
            currentStep++;
            if (currentStep < quizData.length) {
                loadQuestion();
            } else {
                document.getElementById('quiz-container').innerHTML = `
                    <div class="text-center py-8">
                        <div class="w-16 h-16 bg-emerald-500/20 text-emerald-400 rounded-full flex items-center justify-center text-3xl mx-auto mb-4">
                            <i class="fa-solid fa-award"></i>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Hoàn Thành Trải Nghiệm!</h3>
                        <p class="text-slate-300 text-sm mb-6">Cảm ơn bạn đã tham gia xử lý tình huống. Mỗi hành động nhỏ của bạn đều đóng góp xây dựng môi trường học đường an toàn.</p>
                        <button onclick="resetQuiz()" class="px-6 py-2.5 bg-indigo-600 hover:bg-indigo-500 text-white rounded-xl text-sm font-semibold transition-all">
                            Thực hiện lại
                        </button>
                    </div>
                `;
            }
        }

        function resetQuiz() {
            location.reload();
        }

        // Add Pledge Function
        function addPledge(e) {
            e.preventDefault();
            const name = document.getElementById('pledge-name').value;
            const msg = document.getElementById('pledge-msg').value;

            const pledgeList = document.getElementById('pledge-list');
            const card = document.createElement('div');
            card.className = "glass-card p-5 rounded-xl border border-indigo-500/40 bg-indigo-950/10 transition-all animate-fade-in";
            card.innerHTML = `
                <div class="flex items-center justify-between mb-2">
                    <span class="font-semibold text-indigo-300 text-sm">${name}</span>
                    <span class="text-xs text-slate-500">Vừa xong</span>
                </div>
                <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">"${msg}"</p>
            `;

            pledgeList.prepend(card);
            document.getElementById('pledge-form').reset();
        }

        // Initialize Quiz
        loadQuestion();
    </script>
</body>
</html>
