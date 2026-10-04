<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nhà thông thái CNKHXH - Phiên Bản Việt Nam (Admin & Auth)</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            background: radial-gradient(circle at center, #1a2a56 0%, #091026 70%, #030611 100%);
            color: #ffffff;
            user-select: none;
            min-height: 100vh;
        }

        /* Viền kim loại vàng & Glow */
        .gold-border {
            border: 2px solid #F1C40F;
            box-shadow: 0 0 10px rgba(241, 196, 15, 0.4), inset 0 0 10px rgba(241, 196, 15, 0.2);
        }
        
        .gold-text {
            color: #F1C40F;
            text-shadow: 0 0 8px rgba(241, 196, 15, 0.6);
        }

        /* Khung câu hỏi dạng lục giác cách điệu */
        .hex-box {
            position: relative;
            background: linear-gradient(180deg, #101c3d 0%, #080f24 100%);
            border: 2px solid #3b82f6;
            clip-path: polygon(20px 0%, calc(100% - 20px) 0%, 100% 50%, calc(100% - 20px) 100%, 20px 100%, 0% 50%);
            transition: all 0.25s ease;
        }

        .hex-btn {
            position: relative;
            background: linear-gradient(180deg, #132247 0%, #0a1329 100%);
            border: 2px solid #2563eb;
            clip-path: polygon(15px 0%, calc(100% - 15px) 0%, 100% 50%, calc(100% - 15px) 100%, 15px 100%, 0% 50%);
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .hex-btn:hover:not(:disabled) {
            background: linear-gradient(180deg, #1d356e 0%, #112247 100%);
            border-color: #f59e0b;
            box-shadow: 0 0 15px rgba(245, 158, 11, 0.5);
            transform: scale(1.02);
        }

        /* Trạng thái chọn đáp án */
        .hex-btn.selected {
            background: linear-gradient(180deg, #b45309 0%, #78350f 100%) !important;
            border-color: #f59e0b !important;
            animation: pulse-orange 0.8s infinite alternate;
        }

        .hex-btn.correct {
            background: linear-gradient(180deg, #15803d 0%, #166534 100%) !important;
            border-color: #22c55e !important;
            animation: pulse-green 0.5s infinite alternate;
        }

        .hex-btn.wrong {
            background: linear-gradient(180deg, #b91c1c 0%, #991b1b 100%) !important;
            border-color: #ef4444 !important;
            animation: pulse-red 0.5s infinite alternate;
        }

        @keyframes pulse-orange {
            from { box-shadow: 0 0 5px #f59e0b; }
            to { box-shadow: 0 0 20px #f59e0b; }
        }
        @keyframes pulse-green {
            from { box-shadow: 0 0 5px #22c55e; }
            to { box-shadow: 0 0 25px #22c55e; }
        }
        @keyframes pulse-red {
            from { box-shadow: 0 0 5px #ef4444; }
            to { box-shadow: 0 0 20px #ef4444; }
        }

        /* Money Tree highlight */
        .money-active {
            background: #f59e0b;
            color: #000;
            font-weight: bold;
            box-shadow: 0 0 12px #f59e0b;
            animation: neon-glow 1s infinite alternate;
        }

        @keyframes neon-glow {
            0% { box-shadow: 0 0 5px #f59e0b; }
            100% { box-shadow: 0 0 18px #f59e0b; }
        }

        /* Confetti Canvas */
        #confetti-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            pointer-events: none;
            z-index: 100;
        }
        :root {
            --millionaire-blue: #050b28;
            --millionaire-indigo: #0d1f67;
            --millionaire-cyan: #33d6ff;
            --millionaire-gold: #ffd166;
            --millionaire-panel: rgba(5, 13, 45, 0.84);
        }

        * {
            scrollbar-color: rgba(255, 209, 102, 0.85) rgba(5, 13, 45, 0.75);
        }

        body {
            background:
                radial-gradient(circle at 50% -10%, rgba(51, 214, 255, 0.26) 0 10%, transparent 32%),
                radial-gradient(circle at 50% 46%, rgba(255, 209, 102, 0.14) 0 7%, rgba(36, 16, 95, 0.46) 23%, transparent 48%),
                conic-gradient(from 0deg at 50% 50%, rgba(51, 214, 255, 0.18), transparent 12%, rgba(255, 209, 102, 0.2) 18%, transparent 27%, rgba(89, 56, 255, 0.22) 37%, transparent 52%, rgba(51, 214, 255, 0.16) 66%, transparent 82%, rgba(255, 209, 102, 0.18)),
                linear-gradient(145deg, #020518 0%, var(--millionaire-blue) 38%, #140729 68%, #02030d 100%);
            overflow-x: hidden;
        }

        body::before,
        body::after {
            content: "";
            position: fixed;
            inset: -18vmax;
            pointer-events: none;
            z-index: 0;
        }

        body::before {
            background:
                repeating-conic-gradient(from 0deg at 50% 50%, transparent 0deg 8deg, rgba(71, 185, 255, 0.08) 9deg 10deg, transparent 11deg 20deg),
                radial-gradient(circle, transparent 0 28%, rgba(255, 209, 102, 0.08) 29%, transparent 31% 100%);
            animation: rotate-stage 42s linear infinite;
        }

        body::after {
            inset: 0;
            background:
                linear-gradient(90deg, transparent 0 48%, rgba(255, 209, 102, 0.16) 50%, transparent 52%),
                radial-gradient(circle at 50% 50%, transparent 0 34%, rgba(0, 0, 0, 0.28) 72%, rgba(0, 0, 0, 0.58) 100%);
            mix-blend-mode: screen;
            opacity: 0.6;
        }

        @keyframes rotate-stage {
            to { transform: rotate(360deg); }
        }

        #particle-canvas,
        #confetti-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            pointer-events: none;
        }

        #particle-canvas {
            z-index: 1;
            opacity: 0.95;
        }

        #confetti-canvas {
            z-index: 100;
        }

        header,
        .container {
            position: relative;
            z-index: 10;
        }

        header {
            background: linear-gradient(90deg, rgba(2, 5, 24, 0.94), rgba(12, 26, 82, 0.9), rgba(2, 5, 24, 0.94)) !important;
            border-bottom: 1px solid rgba(255, 209, 102, 0.42) !important;
            box-shadow: 0 12px 38px rgba(0, 0, 0, 0.32), inset 0 -1px 0 rgba(51, 214, 255, 0.28);
        }

        header::before {
            content: "";
            position: absolute;
            left: 50%;
            top: 100%;
            width: min(780px, 86vw);
            height: 1px;
            transform: translateX(-50%);
            background: linear-gradient(90deg, transparent, rgba(255, 209, 102, 0.88), transparent);
            box-shadow: 0 0 20px rgba(255, 209, 102, 0.8);
        }

        .gold-border {
            border: 1px solid rgba(255, 209, 102, 0.82);
            box-shadow:
                0 0 0 1px rgba(51, 214, 255, 0.22),
                0 0 26px rgba(51, 214, 255, 0.24),
                0 0 48px rgba(255, 209, 102, 0.16),
                inset 0 0 24px rgba(255, 209, 102, 0.08);
        }

        .gold-text {
            color: var(--millionaire-gold);
            text-shadow: 0 0 7px rgba(255, 209, 102, 0.8), 0 0 20px rgba(51, 214, 255, 0.34);
        }

        #start-screen,
        #end-screen,
        #modal-confirm > div,
        #modal-phone > div,
        #modal-audience > div,
        #modal-expert > div,
        #modal-auth > div,
        #modal-admin > div {
            position: relative;
            overflow: hidden;
            background:
                linear-gradient(180deg, rgba(18, 34, 103, 0.9), rgba(5, 12, 40, 0.94)) !important;
            border-radius: 8px !important;
            backdrop-filter: blur(18px);
        }

        #start-screen::before,
        #end-screen::before,
        #modal-confirm > div::before,
        #modal-phone > div::before,
        #modal-audience > div::before,
        #modal-expert > div::before,
        #modal-auth > div::before,
        #modal-admin > div::before {
            content: "";
            position: absolute;
            inset: 0;
            border-radius: inherit;
            padding: 1px;
            background: linear-gradient(135deg, rgba(255, 209, 102, 0.95), rgba(51, 214, 255, 0.3), rgba(255, 209, 102, 0.75));
            mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
            mask-composite: exclude;
            pointer-events: none;
        }

        #start-screen::after,
        #end-screen::after {
            content: "";
            position: absolute;
            inset: 12px;
            border: 1px solid rgba(51, 214, 255, 0.18);
            clip-path: polygon(3% 0, 97% 0, 100% 12%, 100% 88%, 97% 100%, 3% 100%, 0 88%, 0 12%);
            pointer-events: none;
        }

        #game-screen > div:first-child,
        #game-screen > div:last-child {
            position: relative;
            background: linear-gradient(180deg, rgba(7, 17, 58, 0.78), rgba(3, 8, 30, 0.86));
            border: 1px solid rgba(51, 214, 255, 0.2);
            box-shadow: inset 0 0 24px rgba(51, 214, 255, 0.07), 0 20px 55px rgba(0, 0, 0, 0.25);
            padding: 16px;
            border-radius: 8px;
        }

        .hex-box {
            position: relative;
            background:
                radial-gradient(circle at 50% 0%, rgba(51, 214, 255, 0.22), transparent 58%),
                linear-gradient(180deg, rgba(13, 31, 103, 0.98) 0%, rgba(4, 10, 36, 0.98) 100%);
            border: 2px solid rgba(77, 203, 255, 0.92);
            clip-path: polygon(32px 0%, calc(100% - 32px) 0%, 100% 50%, calc(100% - 32px) 100%, 32px 100%, 0% 50%);
            box-shadow:
                0 0 0 2px rgba(255, 209, 102, 0.24),
                0 0 26px rgba(51, 214, 255, 0.38),
                inset 0 0 35px rgba(6, 214, 255, 0.09);
        }

        .hex-box::before,
        .hex-btn::before {
            content: "";
            position: absolute;
            inset: 6px 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.18);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
            pointer-events: none;
        }

        .hex-btn {
            position: relative;
            min-height: 68px;
            background:
                linear-gradient(90deg, rgba(255, 209, 102, 0.14), transparent 16% 84%, rgba(255, 209, 102, 0.14)),
                linear-gradient(180deg, rgba(14, 35, 119, 0.98) 0%, rgba(6, 13, 48, 0.98) 100%);
            border: 2px solid rgba(58, 173, 255, 0.86);
            clip-path: polygon(22px 0%, calc(100% - 22px) 0%, 100% 50%, calc(100% - 22px) 100%, 22px 100%, 0% 50%);
            transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
            box-shadow: inset 0 0 18px rgba(51, 214, 255, 0.08), 0 8px 22px rgba(0, 0, 0, 0.24);
        }

        .hex-btn:hover:not(:disabled) {
            background:
                linear-gradient(90deg, rgba(255, 209, 102, 0.24), transparent 18% 82%, rgba(255, 209, 102, 0.24)),
                linear-gradient(180deg, rgba(22, 58, 169, 0.98) 0%, rgba(8, 20, 74, 0.98) 100%);
            border-color: var(--millionaire-gold);
            box-shadow: 0 0 24px rgba(255, 209, 102, 0.52), 0 0 38px rgba(51, 214, 255, 0.26);
            transform: translateY(-2px) scale(1.01);
        }

        .hex-btn:disabled {
            cursor: not-allowed;
            opacity: 0.42;
            filter: grayscale(0.35);
        }

        .hex-btn.selected {
            background: linear-gradient(180deg, #d97706 0%, #7c2d12 100%) !important;
            border-color: var(--millionaire-gold) !important;
            animation: pulse-orange 0.8s infinite alternate;
        }

        .hex-btn.correct {
            background: linear-gradient(180deg, #00a36c 0%, #06603f 100%) !important;
            border-color: #4ade80 !important;
            animation: pulse-green 0.5s infinite alternate;
        }

        .hex-btn.wrong {
            background: linear-gradient(180deg, #d92525 0%, #8f1212 100%) !important;
            border-color: #fb7185 !important;
            animation: pulse-red 0.5s infinite alternate;
        }

        @keyframes pulse-orange {
            from { box-shadow: 0 0 8px rgba(255, 159, 28, 0.72); }
            to { box-shadow: 0 0 30px rgba(255, 209, 102, 0.95); }
        }

        @keyframes pulse-green {
            from { box-shadow: 0 0 8px #22c55e; }
            to { box-shadow: 0 0 28px #4ade80; }
        }

        @keyframes pulse-red {
            from { box-shadow: 0 0 8px #ef4444; }
            to { box-shadow: 0 0 28px #fb7185; }
        }

        .money-active {
            background: linear-gradient(90deg, #ffe08a, #ffb703) !important;
            color: #071133 !important;
            box-shadow: 0 0 22px rgba(255, 209, 102, 0.84), inset 0 0 10px rgba(255, 255, 255, 0.28);
            animation: neon-glow 1s infinite alternate;
        }

        @keyframes neon-glow {
            0% { box-shadow: 0 0 8px rgba(255, 209, 102, 0.6); }
            100% { box-shadow: 0 0 26px rgba(255, 209, 102, 0.98), 0 0 38px rgba(51, 214, 255, 0.26); }
        }

        input,
        select,
        textarea {
            background-color: rgba(3, 8, 30, 0.86) !important;
            border-color: rgba(51, 214, 255, 0.32) !important;
            box-shadow: inset 0 0 14px rgba(51, 214, 255, 0.06);
        }

        input:focus,
        select:focus,
        textarea:focus {
            border-color: var(--millionaire-gold) !important;
            box-shadow: 0 0 0 2px rgba(255, 209, 102, 0.18), inset 0 0 14px rgba(51, 214, 255, 0.12);
        }

        button {
            letter-spacing: 0;
        }

        #timer-display {
            box-shadow: 0 0 18px rgba(255, 209, 102, 0.68), inset 0 0 18px rgba(51, 214, 255, 0.15);
        }

        @media (max-width: 768px) {
            .hex-box {
                clip-path: polygon(18px 0%, calc(100% - 18px) 0%, 100% 50%, calc(100% - 18px) 100%, 18px 100%, 0% 50%);
            }

            .hex-btn {
                min-height: 60px;
                clip-path: polygon(16px 0%, calc(100% - 16px) 0%, 100% 50%, calc(100% - 16px) 100%, 16px 100%, 0% 50%);
            }
        }
    </style>
</head>
<body class="flex flex-col min-h-screen overflow-x-hidden">
    <canvas id="particle-canvas" aria-hidden="true"></canvas>
    <canvas id="confetti-canvas"></canvas>

    <!-- THANH HEADER THANH CÔNG CỤ TÀI KHOẢN -->
    <header class="w-full bg-slate-900/80 backdrop-blur border-b border-slate-700 px-4 py-2 flex justify-between items-center z-40">
        <div class="flex items-center space-x-3">
            <span class="text-xl font-extrabold gold-text tracking-wider flex items-center gap-2">
                <i class="fa-solid fa-trophy"></i> NHÀ THÔNG THÁI CNKHXH
            </span>
        </div>
        <div id="user-nav-status" class="flex items-center gap-3 text-sm">
            <!-- Đánh dấu trạng thái Đăng nhập sẽ tự tạo động ở đây -->
        </div>
        <div id="public-tunnel-banner" class="hidden ml-4 text-sm text-amber-300 flex items-center gap-2">
            <span class="text-slate-400">Public:</span>
            <a id="public-tunnel-link" href="#" target="_blank" class="underline text-amber-200 hover:text-white">(no tunnel)</a>
            <button id="copy-tunnel-btn" class="ml-2 px-2 py-1 bg-slate-800/60 border border-slate-700 rounded text-xs">Copy</button>
        </div>
    </header>

    <div class="container mx-auto px-2 py-4 flex-grow flex flex-col justify-center items-center relative z-10">

        <!-- ==================== MÀN HÌNH BẮT ĐẦU (START MENU) ==================== -->
        <div id="start-screen" class="w-full max-w-4xl bg-slate-900/90 rounded-2xl p-6 md:p-8 gold-border backdrop-blur text-center shadow-2xl">
            <div class="mb-6 relative">
                <div class="w-32 h-32 md:w-40 md:h-40 mx-auto rounded-full bg-gradient-to-tr from-amber-500 to-blue-700 p-1 shadow-lg animate-pulse">
                    <div class="w-full h-full bg-slate-950 rounded-full flex justify-center items-center">
                        <i class="fa-solid fa-graduation-cap text-5xl md:text-6xl gold-text"></i>
                    </div>
                </div>
                <h1 class="text-3xl md:text-5xl font-black gold-text mt-4 tracking-wider uppercase">NHÀ THÔNG THÁI CNKHXH</h1>
                <p class="text-slate-400 text-sm md:text-base mt-1">Trò chơi truyền hình trí tuệ đỉnh cao Việt Nam</p>
            </div>

                <div class="max-w-md mx-auto space-y-4">
                <div>
                    <label class="block text-left text-slate-300 text-sm font-bold mb-1">Tên người chơi:</label>
                    <input type="text" id="player-name-input" placeholder="Nhập tên của bạn..." 
                        class="w-full px-4 py-3 bg-slate-800 border border-slate-600 rounded-lg text-white focus:outline-none focus:border-amber-400 text-center text-lg font-bold">
                </div>
                <div>
                    <label class="block text-left text-slate-300 text-sm font-bold mb-1">Chọn bộ câu hỏi:</label>
                    <select id="select-question-set" class="w-full px-4 py-3 bg-slate-800 border border-slate-600 rounded-lg text-white focus:outline-none text-center text-lg font-bold">
                        <option value="">-- Chưa có bộ câu hỏi --</option>
                    </select>
                </div>

                <button onclick="startGame()" class="w-full py-4 bg-gradient-to-r from-amber-500 to-yellow-600 hover:from-amber-400 hover:to-yellow-500 text-slate-950 font-black text-xl rounded-xl shadow-lg transition duration-200 transform hover:scale-105 uppercase tracking-wider">
                    <i class="fa-solid fa-play mr-2"></i> Bắt Đầu Chơi
                </button>
            </div>

            <!-- BẢNG XẾP HẠNG HIGH SCORES -->
            <div class="mt-8 pt-6 border-t border-slate-700 text-left">
                <h3 class="text-lg font-bold gold-text mb-3 flex items-center gap-2">
                    <i class="fa-solid fa-medal"></i> Bảng Xếp Hạng Kỷ Lục
                </h3>
                <div class="bg-slate-950/60 rounded-xl p-3 border border-slate-800 max-h-48 overflow-y-auto">
                    <table class="w-full text-sm text-slate-300">
                        <thead>
                            <tr class="text-slate-500 border-b border-slate-800">
                                <th class="pb-2 text-left">#</th>
                                <th class="pb-2 text-left">Người chơi</th>
                                <th class="pb-2 text-center">Câu đã đạt</th>
                                <th class="pb-2 text-right">Tiền thưởng</th>
                            </tr>
                        </thead>
                        <tbody id="leaderboard-body">
                            <!-- JS tự nạp dữ liệu -->
                        </tbody>
                    </table>
                </div>
            </div>
        </div>

        <!-- ==================== MÀN HÌNH CHƠI GAME (GAMEPLAY) ==================== -->
        <div id="game-screen" class="w-full max-w-6xl hidden flex flex-col lg:flex-row gap-6 items-stretch">
            
            <!-- KHU VỰC CÂU HỎI VÀ ĐÁP ÁN (BÊN TRÁI) -->
            <div class="lg:w-3/4 flex flex-col justify-between space-y-4">
                
                <!-- Thanh công cụ hỗ trợ & Đồng hồ -->
                <div class="bg-slate-900/80 p-3 rounded-xl border border-slate-700 flex flex-wrap justify-between items-center gap-2">
                    <!-- Trợ giúp Lifelines -->
                    <div class="flex items-center gap-2">
                        <button id="btn-life-5050" onclick="useLifeline('5050')" class="w-11 h-11 rounded-full bg-slate-800 hover:bg-amber-500 hover:text-slate-950 border border-amber-400 font-bold gold-text transition flex justify-center items-center text-xs shadow" title="50:50">50:50</button>
                        <button id="btn-life-phone" onclick="useLifeline('phone')" class="w-11 h-11 rounded-full bg-slate-800 hover:bg-amber-500 hover:text-slate-950 border border-amber-400 font-bold gold-text transition flex justify-center items-center text-base shadow" title="Gọi điện cho người thân"><i class="fa-solid fa-phone"></i></button>
                        <button id="btn-life-audience" onclick="useLifeline('audience')" class="w-11 h-11 rounded-full bg-slate-800 hover:bg-amber-500 hover:text-slate-950 border border-amber-400 font-bold gold-text transition flex justify-center items-center text-base shadow" title="Hỏi ý kiến khán giả"><i class="fa-solid fa-users"></i></button>
                        <button id="btn-life-expert" onclick="useLifeline('expert')" class="w-11 h-11 rounded-full bg-slate-800 hover:bg-amber-500 hover:text-slate-950 border border-amber-400 font-bold gold-text transition flex justify-center items-center text-base shadow" title="Trợ giúp chuyên gia"><i class="fa-solid fa-chalkboard-teacher"></i></button>
                    </div>

                    <!-- Thông tin người chơi & Dừng cuộc chơi -->
                    <div class="flex items-center gap-3">
                        <button onclick="walkAway()" class="px-3 py-1.5 bg-red-600/80 hover:bg-red-600 text-white font-bold rounded-lg text-xs transition border border-red-400 flex items-center gap-1">
                            <i class="fa-solid fa-hand"></i> Dừng cuộc chơi
                        </button>
                        <button onclick="toggleSound()" id="sound-toggle-btn" class="w-9 h-9 rounded-lg bg-slate-800 border border-slate-600 text-slate-300 hover:text-white flex justify-center items-center">
                            <i class="fa-solid fa-volume-high"></i>
                        </button>
                    </div>
                </div>

                <!-- Đồng hồ đếm ngược + Vị trí câu hỏi -->
                <div class="flex justify-between items-center px-4 py-2 bg-slate-950/60 rounded-lg border border-slate-800">
                    <div>
                        <span class="text-xs text-slate-400 block">NGƯỜI CHƠI:</span>
                        <span id="display-player-name" class="font-bold gold-text text-base">---</span>
                    </div>
                    <!-- Timer -->
                    <div class="relative w-14 h-14 flex justify-center items-center">
                        <div id="timer-display" class="w-12 h-12 rounded-full border-4 border-amber-400 flex justify-center items-center text-xl font-black text-white bg-slate-900 shadow">30</div>
                    </div>
                    <div class="text-right">
                        <span class="text-xs text-slate-400 block">CÂU HỎI HIỆN TẠI:</span>
                        <span id="current-question-num" class="font-black text-amber-400 text-lg">Câu 1 / 10</span>
                    </div>
                </div>

                <!-- Khung hiển thị nội dung câu hỏi -->
                <div class="hex-box p-6 md:p-8 my-4 min-h-[140px] flex justify-center items-center text-center">
                    <p id="question-text" class="text-lg md:text-2xl font-bold text-slate-100 leading-relaxed">
                        Đang tải nội dung câu hỏi...
                    </p>
                </div>

                <!-- Khung 4 đáp án A, B, C, D -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 pt-2">
                    <button id="ans-btn-0" onclick="selectAnswer(0)" class="hex-btn py-4 px-6 text-left flex items-center text-base md:text-lg">
                        <span class="font-black gold-text mr-3">A:</span> <span id="ans-text-0" class="ans-label">...</span>
                    </button>
                    <button id="ans-btn-1" onclick="selectAnswer(1)" class="hex-btn py-4 px-6 text-left flex items-center text-base md:text-lg">
                        <span class="font-black gold-text mr-3">B:</span> <span id="ans-text-1" class="ans-label">...</span>
                    </button>
                    <button id="ans-btn-2" onclick="selectAnswer(2)" class="hex-btn py-4 px-6 text-left flex items-center text-base md:text-lg">
                        <span class="font-black gold-text mr-3">C:</span> <span id="ans-text-2" class="ans-label">...</span>
                    </button>
                    <button id="ans-btn-3" onclick="selectAnswer(3)" class="hex-btn py-4 px-6 text-left flex items-center text-base md:text-lg">
                        <span class="font-black gold-text mr-3">D:</span> <span id="ans-text-3" class="ans-label">...</span>
                    </button>
                </div>

            </div>

            <!-- THANG TIỀN THƯỞNG (MONEY TREE - BÊN PHẢI) -->
            <div class="lg:w-1/4 bg-slate-900/90 rounded-xl p-4 border border-slate-700 flex flex-col justify-between">
                <h4 class="text-center font-bold gold-text text-sm uppercase tracking-wider mb-2 border-b border-slate-800 pb-2">Thang Tiền Thưởng</h4>
                <div id="money-tree-list" class="flex flex-col gap-1 my-auto">
                    <!-- JS sẽ tự render 10 mốc tiền thưởng -->
                </div>
            </div>

        </div>

        <!-- ==================== MÀN HÌNH KẾT THÚC (GAME OVER / VICTORY) ==================== -->
        <div id="end-screen" class="w-full max-w-2xl hidden bg-slate-900/90 rounded-2xl p-6 md:p-8 gold-border text-center backdrop-blur shadow-2xl">
            <div id="end-icon-box" class="w-24 h-24 mx-auto rounded-full bg-amber-500/20 border-2 border-amber-400 flex justify-center items-center text-5xl gold-text mb-4">
                <i class="fa-solid fa-trophy"></i>
            </div>
            <h2 id="end-title" class="text-3xl font-black gold-text mb-2 uppercase">KẾT THÚC CUỘC CHƠI</h2>
            <p id="end-subtitle" class="text-slate-300 text-base mb-6">Bạn đã thể hiện rất xuất sắc!</p>

            <div class="bg-slate-950/80 rounded-xl p-5 border border-slate-800 mb-6 space-y-3">
                <div class="flex justify-between items-center text-slate-400 text-sm">
                    <span>Người chơi:</span>
                    <span id="end-player-name" class="font-bold text-white text-base">---</span>
                </div>
                <div class="flex justify-between items-center text-slate-400 text-sm">
                    <span>Số câu trả lời đúng:</span>
                    <span id="end-questions-passed" class="font-bold text-amber-400 text-base">0 / 10</span>
                </div>
                <div class="flex justify-between items-center border-t border-slate-800 pt-3">
                    <span class="text-slate-300 font-bold">Tổng tiền thưởng nhận được:</span>
                    <span id="end-final-money" class="text-2xl font-black gold-text">0 VNĐ</span>
                </div>
            </div>

            <div class="flex gap-4">
                <button onclick="restartGame()" class="flex-1 py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl transition shadow">
                    <i class="fa-solid fa-rotate-right mr-1"></i> Chơi Lại
                </button>
                <button onclick="showStartScreen()" class="flex-1 py-3 bg-slate-800 hover:bg-slate-700 text-white font-bold rounded-xl border border-slate-600 transition">
                    <i class="fa-solid fa-house mr-1"></i> Màn Hình Chính
                </button>
            </div>
        </div>

    </div>

    <!-- ==================== MODALS TRỢ GIÚP & CHỐT ĐÁP ÁN ==================== -->

    <!-- Modal Xác nhận đáp án -->
    <div id="modal-confirm" class="fixed inset-0 bg-black/80 backdrop-blur-sm hidden flex justify-center items-center z-50 p-4">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl p-6 max-w-md w-full text-center shadow-2xl">
            <i class="fa-solid fa-circle-question text-5xl gold-text mb-3"></i>
            <h3 class="text-xl font-bold text-white mb-2">Xác nhận câu trả lời</h3>
            <p class="text-slate-300 mb-6">"Bạn có chắc chắn muốn chọn đáp án này là câu trả lời cuối cùng không?"</p>
            <div class="flex gap-4">
                <button onclick="confirmAnswer(true)" class="flex-1 py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-black rounded-xl uppercase">Có, Chốt!</button>
                <button onclick="confirmAnswer(false)" class="flex-1 py-3 bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold rounded-xl">Hủy</button>
            </div>
        </div>
    </div>

    <script>
        // Public tunnel URL injected by the helper; update when tunnel is created.
        const PUBLIC_TUNNEL_URL = 'https://squishier-footbath-variety.ngrok-free.dev';

        function showPublicTunnel() {
            try {
                const banner = document.getElementById('public-tunnel-banner');
                const link = document.getElementById('public-tunnel-link');
                const copyBtn = document.getElementById('copy-tunnel-btn');
                if (!banner || !link || !copyBtn) return;
                if (PUBLIC_TUNNEL_URL && PUBLIC_TUNNEL_URL.startsWith('http')) {
                    link.href = PUBLIC_TUNNEL_URL;
                    link.textContent = PUBLIC_TUNNEL_URL;
                    banner.classList.remove('hidden');
                    copyBtn.addEventListener('click', () => {
                        navigator.clipboard?.writeText(PUBLIC_TUNNEL_URL).then(()=>{
                            copyBtn.textContent = 'Copied';
                            setTimeout(()=> copyBtn.textContent = 'Copy', 1500);
                        }).catch(()=>{
                            // fallback: select link
                            const temp = document.createElement('input');
                            document.body.appendChild(temp);
                            temp.value = PUBLIC_TUNNEL_URL;
                            temp.select();
                            document.execCommand('copy');
                            document.body.removeChild(temp);
                            copyBtn.textContent = 'Copied';
                            setTimeout(()=> copyBtn.textContent = 'Copy', 1500);
                        });
                    });
                }
            } catch (e) {
                console.warn('showPublicTunnel error', e);
            }
        }

        // Run on load
        document.addEventListener('DOMContentLoaded', showPublicTunnel);
    </script>
    <!-- Modal Gọi điện thoại cho người thân -->
    <div id="modal-phone" class="fixed inset-0 bg-black/80 backdrop-blur-sm hidden flex justify-center items-center z-50 p-4">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl p-6 max-w-md w-full text-center shadow-2xl">
            <div class="w-16 h-16 bg-amber-500/20 rounded-full flex justify-center items-center text-3xl gold-text mx-auto mb-3">
                <i class="fa-solid fa-phone-volume"></i>
            </div>
            <h3 class="text-xl font-bold text-white mb-1">Trợ giúp Gọi điện thoại</h3>
            <p class="text-xs text-slate-400 mb-4">Đang kết nối tới Giáo sư tư vấn...</p>
            <div class="bg-slate-950 p-4 rounded-xl text-left border border-slate-800 text-slate-200 text-sm leading-relaxed mb-6 italic" id="phone-dialog-text">
                "Theo tôi suy đoán, đáp án chính xác nhất ở câu hỏi này nhiều khả năng là..."
            </div>
            <button onclick="closeModal('modal-phone')" class="w-full py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl">Đóng Modal</button>
        </div>
    </div>

    <!-- Modal Hỏi ý kiến khán giả -->
    <div id="modal-audience" class="fixed inset-0 bg-black/80 backdrop-blur-sm hidden flex justify-center items-center z-50 p-4">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl p-6 max-w-md w-full text-center shadow-2xl">
            <i class="fa-solid fa-chart-column text-4xl gold-text mb-2"></i>
            <h3 class="text-xl font-bold text-white mb-4">Ý Kiến Khán Giả Trường Quay</h3>
            
            <div class="flex justify-around items-end h-44 bg-slate-950 p-4 rounded-xl border border-slate-800 mb-6">
                <!-- Cột A -->
                <div class="flex flex-col items-center flex-1">
                    <span id="aud-percent-0" class="text-xs font-bold text-amber-400 mb-1">0%</span>
                    <div id="aud-bar-0" class="w-8 bg-amber-500 rounded-t transition-all duration-1000 h-0"></div>
                    <span class="text-xs font-bold text-white mt-2">A</span>
                </div>
                <!-- Cột B -->
                <div class="flex flex-col items-center flex-1">
                    <span id="aud-percent-1" class="text-xs font-bold text-amber-400 mb-1">0%</span>
                    <div id="aud-bar-1" class="w-8 bg-amber-500 rounded-t transition-all duration-1000 h-0"></div>
                    <span class="text-xs font-bold text-white mt-2">B</span>
                </div>
                <!-- Cột C -->
                <div class="flex flex-col items-center flex-1">
                    <span id="aud-percent-2" class="text-xs font-bold text-amber-400 mb-1">0%</span>
                    <div id="aud-bar-2" class="w-8 bg-amber-500 rounded-t transition-all duration-1000 h-0"></div>
                    <span class="text-xs font-bold text-white mt-2">C</span>
                </div>
                <!-- Cột D -->
                <div class="flex flex-col items-center flex-1">
                    <span id="aud-percent-3" class="text-xs font-bold text-amber-400 mb-1">0%</span>
                    <div id="aud-bar-3" class="w-8 bg-amber-500 rounded-t transition-all duration-1000 h-0"></div>
                    <span class="text-xs font-bold text-white mt-2">D</span>
                </div>
            </div>

            <button onclick="closeModal('modal-audience')" class="w-full py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl">Cảm ơn khán giả</button>
        </div>
    </div>

    <!-- Modal Trợ giúp chuyên gia (tượng trưng) -->
    <div id="modal-expert" class="fixed inset-0 bg-black/80 backdrop-blur-sm hidden flex justify-center items-center z-50 p-4">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl p-6 max-w-md w-full text-center shadow-2xl">
            <div class="w-16 h-16 bg-amber-500/20 rounded-full flex justify-center items-center text-3xl gold-text mx-auto mb-3">
                <i class="fa-solid fa-user-tie"></i>
            </div>
            <h3 class="text-xl font-bold text-white mb-1">Trợ giúp chuyên gia</h3>
            <p class="text-xs text-slate-400 mb-4">Lưu ý: trợ giúp mang tính tượng trưng cho lớp học — dùng sẽ mất.</p>
            <div id="expert-text" class="bg-slate-950 p-4 rounded-xl text-left border border-slate-800 text-slate-200 text-sm leading-relaxed mb-6 italic">
                "Chuyên gia gợi ý..."
            </div>
            <button onclick="closeModal('modal-expert')" class="w-full py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl">Đóng</button>
        </div>
    </div>

    

    <!-- Modal Đăng nhập / Đăng ký -->
    <div id="modal-auth" class="fixed inset-0 bg-black/80 backdrop-blur-sm hidden flex justify-center items-center z-50 p-4">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl p-6 max-w-md w-full shadow-2xl relative">
            <button onclick="closeModal('modal-auth')" class="absolute top-4 right-4 text-slate-400 hover:text-white text-xl"><i class="fa-solid fa-xmark"></i></button>

            <!-- Tabs -->
            <div class="flex border-b border-slate-700 mb-6">
                <button id="auth-tab-login" onclick="switchAuthTab('login')" class="flex-1 py-2 font-bold text-center border-b-2 border-amber-400 text-amber-400">Đăng Nhập</button>
                <button id="auth-tab-register" onclick="switchAuthTab('register')" class="flex-1 py-2 font-bold text-center border-b-2 border-transparent text-slate-400 hover:text-slate-200">Đăng Ký</button>
            </div>

            <!-- Form Đăng Nhập -->
            <form id="form-login" onsubmit="handleLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-xs text-slate-400 mb-1">Tên đăng nhập:</label>
                    <input type="text" id="login-username" required class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-lg text-white focus:outline-none focus:border-amber-400">
                </div>
                <div>
                    <label class="block text-xs text-slate-400 mb-1">Mật khẩu:</label>
                    <input type="password" id="login-password" required class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-lg text-white focus:outline-none focus:border-amber-400">
                </div>
                <div class="p-2 bg-amber-500/10 border border-amber-500/30 rounded text-xs text-amber-300">
                    <i class="fa-solid fa-circle-info mr-1"></i> Tài khoản Admin mặc định: <b>admin</b> / MK: <b>admin123</b>
                </div>
                <button type="submit" class="w-full py-3 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl">Đăng Nhập</button>
            </form>

            <!-- Form Đăng Ký -->
            <form id="form-register" onsubmit="handleRegister(event)" class="space-y-4 hidden">
                <div>
                    <label class="block text-xs text-slate-400 mb-1">Họ và Tên (Hiển thị):</label>
                    <input type="text" id="reg-fullname" required class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-lg text-white focus:outline-none focus:border-amber-400">
                </div>
                <div>
                    <label class="block text-xs text-slate-400 mb-1">Tên đăng nhập:</label>
                    <input type="text" id="reg-username" required class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-lg text-white focus:outline-none focus:border-amber-400">
                </div>
                <div>
                    <label class="block text-xs text-slate-400 mb-1">Mật khẩu:</label>
                    <input type="password" id="reg-password" required class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-lg text-white focus:outline-none focus:border-amber-400">
                </div>
                <button type="submit" class="w-full py-3 bg-blue-600 hover:bg-blue-500 text-white font-bold rounded-xl">Tạo Tài Khoản</button>
            </form>
        </div>
    </div>

    <!-- Modal Trang Admin Quản Lý Câu Hỏi -->
    <div id="modal-admin" class="fixed inset-0 bg-black/90 backdrop-blur-md hidden flex justify-center items-center z-50 p-2 md:p-6">
        <div class="bg-slate-900 border-2 border-amber-400 rounded-2xl w-full max-w-5xl h-[90vh] flex flex-col shadow-2xl overflow-hidden relative">
            
            <!-- Admin Header -->
            <div class="bg-slate-950 p-4 border-b border-slate-800 flex justify-between items-center">
                <h3 class="text-xl font-bold gold-text flex items-center gap-2">
                    <i class="fa-solid fa-user-gear"></i> Trang Quản Trị Admin - Quản Lý Câu Hỏi
                </h3>
                <div class="flex items-center gap-2">
                    <button onclick="resetDefaultQuestions()" class="px-3 py-1.5 bg-red-600/80 hover:bg-red-600 text-white text-xs font-bold rounded-lg">
                        <i class="fa-solid fa-rotate-left"></i> Khôi phục mặc định
                    </button>
                    <button onclick="adminCreateSet()" class="px-3 py-1.5 bg-green-600/80 hover:bg-green-600 text-white text-xs font-bold rounded-lg">
                        <i class="fa-solid fa-layer-plus"></i> Tạo Bộ Câu Hỏi
                    </button>
                    <button onclick="adminPublishSet()" class="px-3 py-1.5 bg-amber-600/80 hover:bg-amber-600 text-white text-xs font-bold rounded-lg">
                        <i class="fa-solid fa-upload"></i> Xuất bản Bộ
                    </button>
                    <button onclick="closeModal('modal-admin')" class="text-slate-400 hover:text-white text-2xl ml-2"><i class="fa-solid fa-xmark"></i></button>
                </div>
            </div>

            <div class="flex-grow flex flex-col md:flex-row overflow-hidden">
                
                <!-- Bảng Danh Sách Câu Hỏi -->
                <div class="md:w-3/5 p-4 overflow-y-auto border-r border-slate-800">
                    <div class="flex justify-between items-center mb-3">
                        <span class="text-sm text-slate-300 font-bold">Danh sách câu hỏi trong ngân hàng:</span>
                        <div class="flex gap-2">
                            <select id="admin-filter-set" onchange="renderAdminQuestionList()" class="bg-slate-800 text-xs text-slate-200 border border-slate-700 rounded px-2 py-1">
                                <option value="all">Tất cả bộ câu hỏi</option>
                            </select>
                            <select id="admin-filter-level" onchange="renderAdminQuestionList()" class="bg-slate-800 text-xs text-slate-200 border border-slate-700 rounded px-2 py-1">
                                <option value="all">Tất cả các mốc (1-10)</option>
                                <!-- 1-10 options -->
                            </select>
                        </div>
                    </div>

                    <div class="space-y-3" id="admin-question-list">
                        <!-- Render danh sách câu hỏi -->
                    </div>
                </div>

                <!-- Form Thêm/Sửa Câu Hỏi -->
                <div class="md:w-2/5 p-4 bg-slate-950/50 overflow-y-auto">
                    <h4 id="admin-form-title" class="font-bold text-amber-400 text-base mb-3 pb-2 border-b border-slate-800">Thêm Câu Hỏi Mới</h4>
                    
                    <form id="form-question" onsubmit="saveAdminQuestion(event)" class="space-y-3 text-xs">
                        <input type="hidden" id="q-edit-id" value="">
                        
                        <div>
                            <label class="block text-slate-400 mb-1">Thuộc bộ câu hỏi:</label>
                            <select id="q-set" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                                <!-- bộ câu hỏi sẽ được nạp động -->
                            </select>
                        </div>
                        <div>
                            <label class="block text-slate-400 mb-1">Mốc độ khó (Câu 1 đến 10):</label>
                            <select id="q-level" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                                <!-- 1 -> 10 -->
                            </select>
                        </div>

                        <div>
                            <label class="block text-slate-400 mb-1">Nội dung câu hỏi:</label>
                            <textarea id="q-text" rows="3" required placeholder="Nhập câu hỏi..." class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white"></textarea>
                        </div>

                        <div class="grid grid-cols-2 gap-2">
                            <div>
                                <label class="block text-slate-400 mb-1">Phương án A:</label>
                                <input type="text" id="q-ans-0" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                            </div>
                            <div>
                                <label class="block text-slate-400 mb-1">Phương án B:</label>
                                <input type="text" id="q-ans-1" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                            </div>
                            <div>
                                <label class="block text-slate-400 mb-1">Phương án C:</label>
                                <input type="text" id="q-ans-2" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                            </div>
                            <div>
                                <label class="block text-slate-400 mb-1">Phương án D:</label>
                                <input type="text" id="q-ans-3" required class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white">
                            </div>
                        </div>

                        <div>
                            <label class="block text-slate-400 mb-1">Đáp án đúng chính xác:</label>
                            <select id="q-correct" class="w-full bg-slate-800 border border-slate-700 rounded p-2 text-white font-bold">
                                <option value="0">Phương án A</option>
                                <option value="1">Phương án B</option>
                                <option value="2">Phương án C</option>
                                <option value="3">Phương án D</option>
                            </select>
                        </div>

                        <div class="pt-2 flex gap-2">
                            <button type="submit" class="flex-1 py-2.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-lg text-sm">Lưu Câu Hỏi</button>
                            <button type="button" onclick="resetAdminForm()" class="px-3 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold rounded-lg text-sm">Hủy</button>
                        </div>
                    </form>
                </div>

            </div>

        </div>
    </div>


    <!-- ==================== JAVASCRIPT LOGIC TRÒ CHƠI & ADMIN ==================== -->
    <script>
        /* ================= 1. NGUỒN CÂU HỎI MẶC ĐỊNH ================= */
        const DEFAULT_QUESTIONS = [
            {
                        "id": "docx-s01-q01",
                        "level": 1,
                        "setId": "docx-set-01",
                        "question": "Theo nội dung bài học, nhân dân thực hiện quyền dân chủ của mình thông qua những hình thức nào?",
                        "options": [
                                    "Dân chủ trực tiếp và dân chủ tập trung",
                                    "Dân chủ trực tiếp và dân chủ đại diện",
                                    "Dân chủ đại diện và dân chủ tham vấn",
                                    "Dân chủ cơ sở và dân chủ đại diện"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s01-q02",
                        "level": 2,
                        "setId": "docx-set-01",
                        "question": "Ở Việt Nam, cơ quan nào thực hiện quyền lập pháp trong bộ máy nhà nước pháp quyền XHCN?",
                        "options": [
                                    "Chính phủ",
                                    "Quốc hội",
                                    "Tòa án nhân dân tối cao",
                                    "Viện kiểm sát nhân dân tối cao"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s01-q03",
                        "level": 3,
                        "setId": "docx-set-01",
                        "question": "Hãy chọn nhận định đúng về nguyên tắc làm việc của cơ quan nhà nước và công dân.",
                        "options": [
                                    "Cơ quan nhà nước và công dân đều chỉ được làm những việc được liệt kê cụ thể trong luật.",
                                    "Cơ quan nhà nước được làm mọi việc nếu cho rằng việc đó có lợi cho xã hội.",
                                    "Công dân chỉ được thực hiện những việc được cơ quan nhà nước cho phép trước.",
                                    "Cơ quan nhà nước chỉ được làm những gì pháp luật cho phép, còn công dân được làm mọi điều pháp luật không cấm."
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s01-q04",
                        "level": 4,
                        "setId": "docx-set-01",
                        "question": "Trong nhà nước pháp quyền, quyền lực nhà nước được tổ chức và thực hiện theo nguyên tắc nào?",
                        "options": [
                                    "Tập trung vào một người hoặc một cơ quan duy nhất để bảo đảm hiệu quả quản lý",
                                    "Phân chia tuyệt đối, các cơ quan hoạt động hoàn toàn độc lập, không kiểm soát lẫn nhau",
                                    "Chủ yếu được phân cấp giữa chính quyền trung ương và chính quyền địa phương",
                                    "Được phân công giữa các cơ quan lập pháp, hành pháp, tư pháp và được kiểm soát chặt chẽ"
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s01-q05",
                        "level": 5,
                        "setId": "docx-set-01",
                        "question": "Trong mối quan hệ giữa Nhà nước và kinh tế, vai trò của Nhà nước pháp quyền được xác định theo hướng nào?",
                        "options": [
                                    "Nhà nước trực tiếp điều hành toàn bộ hoạt động kinh tế thông qua kế hoạch hóa tập trung",
                                    "Nhà nước tôn trọng, phát huy các quy luật khách quan của thị trường, thông qua thị trường để điều tiết các quan hệ kinh tế",
                                    "Nhà nước đứng trên kinh tế và xã hội để quản lý bằng mệnh lệnh hành chính",
                                    "Nhà nước hoàn toàn không can thiệp vào nền kinh tế, để thị trường tự điều tiết"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s01-q06",
                        "level": 6,
                        "setId": "docx-set-01",
                        "question": "Dân chủ có vai trò gì đối với nhà nước pháp quyền? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "A và C",
                                    "A và D",
                                    "B và C",
                                    "B và D"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s01-q07",
                        "level": 7,
                        "setId": "docx-set-01",
                        "question": "Cơ chế bảo vệ Hiến pháp trong nhà nước pháp quyền có đặc điểm gì? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "A và D",
                                    "A và C",
                                    "B và D",
                                    "C và D"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s01-q08",
                        "level": 8,
                        "setId": "docx-set-01",
                        "question": "Cơ chế nào sau đây thể hiện rõ nhất nguyên tắc \"Kiểm soát quyền lực\" giữa nhánh Hành pháp và Lập pháp ở Việt Nam theo Hiến pháp 2013?",
                        "options": [
                                    "Chính phủ có quyền giải tán Quốc hội nếu không thông qua luật.",
                                    "Quốc hội bãi bỏ các văn bản quy phạm pháp luật của Chính phủ, Thủ tướng Chính phủ trái với Hiến pháp, luật, nghị quyết của Quốc hội.",
                                    "Tòa án nhân dân tối cao có quyền tuyên bố một đạo luật do Quốc hội ban hành là vi hiến.",
                                    "Chủ tịch nước có quyền phủ quyết (veto) tuyệt đối các dự thảo luật do Quốc hội thông qua."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s01-q09",
                        "level": 9,
                        "setId": "docx-set-01",
                        "question": "Yếu tố nào quyết định tính chất \"XHCN\" của nền kinh tế thị trường tại Trung Quốc và Việt Nam?",
                        "options": [
                                    "Cấm hoàn toàn sự tồn tại của thành phần kinh tế tư nhân và kinh tế có vốn đầu tư nước ngoài.",
                                    "Sự dẫn dắt của kinh tế nhà nước, vai trò quản lý của Nhà nước XHCN và mục tiêu vì dân giàu, nước mạnh, công bằng, văn minh.",
                                    "Áp dụng mô hình kinh tế kế hoạch hóa tập trung bao cấp như giai đoạn trước năm 1986.",
                                    "Triệt tiêu hoàn toàn các quy luật của kinh tế thị trường (quy luật giá trị, cung cầu)."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s01-q10",
                        "level": 10,
                        "setId": "docx-set-01",
                        "question": "Theo Nghị quyết 27-NQ/TW năm 2022, trọng tâm xây dựng Nhà nước pháp quyền XHCN trong giai đoạn mới gắn với hoàn thiện hệ thống nào và đẩy mạnh nội dung nào?",
                        "options": [
                                    "Hoàn thiện hệ thống pháp luật và đẩy mạnh kiểm soát quyền lực nhà nước.",
                                    "Hoàn thiện hệ thống hành chính và đẩy mạnh tập trung quyền lực.",
                                    "Hoàn thiện hệ thống kinh tế tư nhân và giảm kiểm soát quyền lực.",
                                    "Hoàn thiện hệ thống tư pháp quốc tế và trao quyền phủ quyết cho Tòa án."
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s02-q01",
                        "level": 1,
                        "setId": "docx-set-02",
                        "question": "Tiêu chí cốt lõi để đánh giá tính pháp quyền của chế độ nhà nước là gì?",
                        "options": [
                                    "Sức mạnh quân sự và an ninh",
                                    "Sự phát triển của các mô hình kinh tế",
                                    "Sự tôn trọng và bảo đảm quyền con người",
                                    "Số lượng đạo luật được ban hành hàng năm"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s02-q02",
                        "level": 2,
                        "setId": "docx-set-02",
                        "question": "Theo tài liệu, dân chủ có vai trò như thế nào đối với Nhà nước pháp quyền XHCN Việt Nam?",
                        "options": [
                                    "Dân chủ là bản chất và đồng thời là điều kiện, tiền đề của Nhà nước pháp quyền.",
                                    "Dân chủ chỉ được thực hiện thông qua các cơ quan đại diện của Nhà nước.",
                                    "Dân chủ chỉ là phương thức tổ chức hoạt động của bộ máy hành chính.",
                                    "Dân chủ là mục tiêu phụ thuộc hoàn toàn vào sự phát triển kinh tế."
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s02-q03",
                        "level": 3,
                        "setId": "docx-set-02",
                        "question": "Nhận định nào sau đây ĐÚNG về chức năng của nhà nước XHCN?",
                        "options": [
                                    "Căn cứ vào phạm vi tác động của quyền lực, chức năng được chia thành chức năng giai cấp và chức năng xã hội",
                                    "Chức năng giai cấp (trấn áp) là chức năng chủ yếu, giữ vai trò quyết định",
                                    "Chức năng xã hội (tổ chức, xây dựng) là chức năng chủ yếu",
                                    "Chức năng đối nội được thực hiện chủ yếu bằng mệnh lệnh hành chính thay cho pháp luật"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s02-q04",
                        "level": 4,
                        "setId": "docx-set-02",
                        "question": "Ngược lại với công dân, các cơ quan nhà nước khi thực thi công vụ phải tuân thủ nguyên tắc nào?",
                        "options": [
                                    "Được làm tất cả trừ những điều luật cấm",
                                    "Được phép linh hoạt vượt qua khuôn khổ pháp luật khi cần thiết",
                                    "Có quyền tự quyết định mọi vấn đề phát sinh trong xã hội",
                                    "Chỉ được làm những gì luật cho phép"
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s02-q05",
                        "level": 5,
                        "setId": "docx-set-02",
                        "question": "Hoàn thành nhận định: \"Quyền lực nhà nước trong Nhà nước pháp quyền được tổ chức và thực hiện theo các nguyên tắc dân chủ là phân công quyền lực và ______ quyền lực.\"",
                        "options": [
                                    "Kiểm soát",
                                    "Tập trung hóa",
                                    "Loại bỏ",
                                    "Tư nhân hóa"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s02-q06",
                        "level": 6,
                        "setId": "docx-set-02",
                        "question": "Trong Nhà nước pháp quyền XHCN Việt Nam, tính thống nhất của quyền lực nhà nước xuất phát từ đâu?",
                        "options": [
                                    "Từ việc quyền lực tập trung tuyệt đối vào Chính phủ.",
                                    "Từ việc toàn bộ quyền lực nhà nước đều thuộc về nhân dân.",
                                    "Từ việc Tòa án có quyền phủ quyết mọi quyết định của Quốc hội.",
                                    "Từ việc quyền lực nhà nước được phân lập thành ba nhánh độc lập tuyệt đối."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s02-q07",
                        "level": 7,
                        "setId": "docx-set-02",
                        "question": "Trong nhà nước pháp quyền XHCN Việt Nam, cơ quan nào thuộc cơ chế kiểm soát quyền lực từ bên ngoài bộ máy nhà nước? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "B và D",
                                    "A và D",
                                    "B và C",
                                    "C và D"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s02-q08",
                        "level": 8,
                        "setId": "docx-set-02",
                        "question": "Tại sao trong việc tổ chức quyền lực nhà nước, đòi hỏi phải có sự phân công giữa lập pháp, hành pháp, tư pháp và có cơ chế kiểm soát chặt chẽ?",
                        "options": [
                                    "Để tạo sự cạnh tranh thành tích giữa các cơ quan nhà nước",
                                    "Nhằm làm suy giảm vai trò giám sát của nhân dân đối với nhà nước",
                                    "Để quyền lực không tập trung vào một người, một cơ quan, bảo đảm không lạm quyền",
                                    "Nhằm tối ưu hóa chi phí trả lương cho bộ máy nhà nước"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s02-q09",
                        "level": 9,
                        "setId": "docx-set-02",
                        "question": "Trong thể chế chính trị Trung Quốc, cơ quan nào được xác định là \"cơ quan cố vấn chính trị\", nơi hội tụ các 'đảng phái dân chủ' và nhân sĩ tri thức để thực hiện hiệp thương dân chủ?",
                        "options": [
                                    "Đại hội Đại biểu Nhân dân Toàn quốc (Nhân đại)",
                                    "Ủy ban Thường vụ Nhân đại",
                                    "Hội nghị Hiệp thương Chính trị Nhân dân Trung Quốc (Chính hiệp)",
                                    "Bộ Chính trị Trung ương Đảng Cộng sản Trung Quốc"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s02-q10",
                        "level": 10,
                        "setId": "docx-set-02",
                        "question": "Chức năng nào của Nhà nước XHCN là chủ yếu, mang tính quyết định bản chất tiến bộ và sự tồn tại lâu dài?",
                        "options": [
                                    "Chức năng trấn áp.",
                                    "Chức năng tổ chức và xây dựng.",
                                    "Chức năng cạnh tranh đảng phái.",
                                    "Chức năng hạn chế dân chủ."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s03-q01",
                        "level": 1,
                        "setId": "docx-set-03",
                        "question": "Theo khái niệm, nhà nước XHCN là nhà nước mà ở đó sự thống trị chính trị thuộc về:",
                        "options": [
                                    "Toàn thể nhân dân lao động",
                                    "Giai cấp công nhân",
                                    "Liên minh công nhân - nông dân - trí thức",
                                    "Đảng Cộng sản"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s03-q02",
                        "level": 2,
                        "setId": "docx-set-03",
                        "question": "Cơ quan nào sau đây thực hiện quyền tư pháp trong nhà nước pháp quyền XHCN Việt Nam?",
                        "options": [
                                    "Quốc hội",
                                    "Chính phủ",
                                    "Tòa án nhân dân",
                                    "Viện kiểm sát nhân dân"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s03-q03",
                        "level": 3,
                        "setId": "docx-set-03",
                        "question": "Hãy chọn nhận định đúng về mối quan hệ giữa Nhà nước pháp quyền và Hiến pháp, pháp luật.",
                        "options": [
                                    "Hoạt động của Nhà nước không cần căn cứ vào Hiến pháp nếu đã có quyết định hành chính.",
                                    "Hiến pháp và pháp luật chỉ điều chỉnh hoạt động của công dân, không điều chỉnh Nhà nước.",
                                    "Nhà nước pháp quyền chỉ chịu sự điều chỉnh của các quy tắc đạo đức xã hội.",
                                    "Nhà nước pháp quyền được tổ chức và hoạt động trong khuôn khổ Hiến pháp và pháp luật."
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s03-q04",
                        "level": 4,
                        "setId": "docx-set-03",
                        "question": "Nguyên tắc xác định mối quan hệ giữa Nhà nước và cá nhân trong nhà nước pháp quyền là gì?",
                        "options": [
                                    "Cơ quan nhà nước được làm tất cả những gì luật không cấm; công dân chỉ được làm những gì luật cho phép",
                                    "Cơ quan nhà nước chỉ được làm những gì luật cho phép; công dân được làm tất cả trừ những điều luật cấm",
                                    "Cả cơ quan nhà nước và công dân đều chỉ được làm những gì luật cho phép",
                                    "Cả cơ quan nhà nước và công dân đều được làm tất cả trừ những điều luật cấm"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s03-q05",
                        "level": 5,
                        "setId": "docx-set-03",
                        "question": "Theo đặc điểm của nhà nước pháp quyền, mối quan hệ giữa Nhà nước với kinh tế và xã hội được hiểu như thế nào?",
                        "options": [
                                    "Nhà nước đứng trên kinh tế, xã hội, điều hành mọi quan hệ kinh tế bằng mệnh lệnh hành chính",
                                    "Nhà nước đứng ngoài, để thị trường tự điều tiết hoàn toàn và không can thiệp",
                                    "Nhà nước không đứng trên mà gắn liền, phục vụ kinh tế và xã hội trong phạm vi Hiến pháp và pháp luật",
                                    "Nhà nước quản lý xã hội chủ yếu bằng đạo đức, hạn chế quyền tự quản của các tổ chức xã hội"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s03-q06",
                        "level": 6,
                        "setId": "docx-set-03",
                        "question": "Việc tổ chức quyền lực nhà nước trong nhà nước pháp quyền tuân theo những nguyên tắc dân chủ nào? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "B và C",
                                    "A và C",
                                    "B và D",
                                    "A và D"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s03-q07",
                        "level": 7,
                        "setId": "docx-set-03",
                        "question": "Vai trò của Nhà nước đối với nền kinh tế trong Nhà nước pháp quyền XHCN được xác định như thế nào?",
                        "options": [
                                    "Nhà nước can thiệp trực tiếp bằng mệnh lệnh hành chính vào mọi hoạt động giao thương",
                                    "Nhà nước đứng trên các quy luật kinh tế, áp đặt định hướng bất chấp thị trường",
                                    "Nhà nước hoàn toàn tách biệt, không can thiệp vào bất kỳ hoạt động kinh tế nào",
                                    "Nhà nước tôn trọng quy luật khách quan của thị trường, dùng thị trường để điều tiết và khắc phục tiêu cực"
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s03-q08",
                        "level": 8,
                        "setId": "docx-set-03",
                        "question": "Mối quan hệ giữa \"Dân chủ XHCN\" và \"Nhà nước pháp quyền XHCN\" được lý giải chuẩn xác nhất theo quan điểm Mác-Lênin là:",
                        "options": [
                                    "Dân chủ XHCN là sản phẩm thụ động được tạo ra sau khi Nhà nước pháp quyền đã hoàn thiện.",
                                    "Dân chủ vừa là bản chất, vừa là điều kiện, tiền đề của Nhà nước pháp quyền; ngược lại, Nhà nước pháp quyền là phương thức/công cụ thể chế hóa và bảo đảm dân chủ.",
                                    "Pháp quyền chỉ là công cụ quản lý hành chính, không liên quan đến bản chất dân chủ.",
                                    "Dân chủ và Pháp quyền là hai khái niệm đối lập, triệt tiêu lẫn nhau trong thực tiễn."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s03-q09",
                        "level": 9,
                        "setId": "docx-set-03",
                        "question": "Điểm đặc thù trong cơ quan lập pháp của Cuba (Quốc hội của Chính quyền Nhân dân) về chế độ hoạt động và cơ cấu giữa hai kỳ họp là gì?",
                        "options": [
                                    "Quốc hội họp liên tục quanh năm, không có cơ quan thường trực.",
                                    "Quốc hội chỉ họp 2 phiên/năm; giữa hai kỳ họp, quyền lập pháp do Hội đồng Bộ trưởng (21 thành viên) nắm giữ.",
                                    "Quyền lập pháp giữa hai kỳ họp được chuyển hoàn toàn cho Tòa án tối cao Cuba.",
                                    "Quốc hội chỉ đóng vai trò tư vấn, không có thẩm quyền ban hành luật."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s03-q10",
                        "level": 10,
                        "setId": "docx-set-03",
                        "question": "Nhận định \"Mọi chế độ lập hiến và hệ thống pháp luật đều có thể đưa lại khả năng xây dựng Nhà nước pháp quyền\" là đúng hay sai?",
                        "options": [
                                    "Đúng.",
                                    "Sai.",
                                    "Chỉ đúng khi có Hiến pháp thành văn.",
                                    "Chỉ đúng với nhà nước liên bang."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s04-q01",
                        "level": 1,
                        "setId": "docx-set-04",
                        "question": "Bản chất và cũng là điều kiện, tiền đề của nhà nước pháp quyền XHCN ở Việt Nam là gì?",
                        "options": [
                                    "Sự áp đặt của pháp luật",
                                    "Chế độ dân chủ",
                                    "Quyền lực hành pháp tuyệt đối",
                                    "Cơ chế phân chia giai cấp"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s04-q02",
                        "level": 2,
                        "setId": "docx-set-04",
                        "question": "Mối quan hệ giữa dân chủ XHCN và nhà nước XHCN được thể hiện như thế nào?",
                        "options": [
                                    "Nhà nước XHCN là cơ sở, nền tảng của dân chủ XHCN; dân chủ XHCN là công cụ để nhà nước quản lý xã hội",
                                    "Dân chủ XHCN là cơ sở, nền tảng của nhà nước XHCN; nhà nước XHCN là công cụ thực thi quyền làm chủ của nhân dân",
                                    "Dân chủ XHCN và nhà nước XHCN tồn tại độc lập, không ràng buộc lẫn nhau",
                                    "Nhà nước XHCN càng được củng cố thì phạm vi dân chủ XHCN càng bị thu hẹp"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s04-q03",
                        "level": 3,
                        "setId": "docx-set-04",
                        "question": "Quyền lực nhà nước trong nhà nước pháp quyền XHCN được tổ chức và thực hiện theo nguyên tắc dân chủ nào?",
                        "options": [
                                    "Tập trung toàn bộ quyền lực vào một cơ quan duy nhất",
                                    "Trao toàn quyền quyết định cho cơ quan hành pháp",
                                    "Phân công quyền lực và kiểm soát quyền lực",
                                    "Các cơ quan hoạt động độc lập tuyệt đối, không cần kiểm soát"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s04-q04",
                        "level": 4,
                        "setId": "docx-set-04",
                        "question": "Mô hình quan hệ giữa Nhà nước và cá nhân trong nhà nước pháp quyền được xác định theo nguyên tắc nào?",
                        "options": [
                                    "Cơ quan nhà nước chỉ được làm những gì luật cho phép; công dân được làm tất cả trừ những điều luật cấm",
                                    "Cơ quan nhà nước được làm tất cả trừ những điều luật cấm; công dân chỉ được làm những gì luật cho phép",
                                    "Cả cơ quan nhà nước và công dân đều chỉ được làm những gì luật cho phép",
                                    "Cả cơ quan nhà nước và công dân đều được làm tất cả trừ những điều luật cấm"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s04-q05",
                        "level": 5,
                        "setId": "docx-set-04",
                        "question": "Trong nhà nước pháp quyền XHCN, dân chủ có vị trí như thế nào?",
                        "options": [
                                    "Chỉ là mục tiêu hướng tới trong tương lai, chưa phải là bản chất của nhà nước pháp quyền",
                                    "Là phương tiện để giai cấp cầm quyền củng cố và duy trì quyền lực của mình",
                                    "Vừa là bản chất của nhà nước pháp quyền, vừa là điều kiện, tiền đề của chế độ nhà nước",
                                    "Chỉ được thực hiện qua dân chủ đại diện, không có hình thức dân chủ trực tiếp"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s04-q06",
                        "level": 6,
                        "setId": "docx-set-04",
                        "question": "Để Hiến pháp và hệ thống pháp luật có thể làm cơ sở xây dựng nhà nước pháp quyền, cần đáp ứng yêu cầu nào? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "B và D",
                                    "A và D",
                                    "B và C",
                                    "C và D"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s04-q07",
                        "level": 7,
                        "setId": "docx-set-04",
                        "question": "Cơ quan nào ở Việt Nam giữ chức năng thực hành quyền công tố và kiểm sát hoạt động tư pháp?",
                        "options": [
                                    "Tòa án nhân dân",
                                    "Bộ Tư pháp",
                                    "Viện kiểm sát nhân dân",
                                    "Thanh tra Chính phủ"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s04-q08",
                        "level": 8,
                        "setId": "docx-set-04",
                        "question": "Trong mối quan hệ với xã hội, Nhà nước pháp quyền thực hiện vai trò của mình như thế nào? Chọn tổ hợp đáp án đúng.",
                        "options": [
                                    "A, C và D",
                                    "A, B và D",
                                    "B, C và D",
                                    "A, B và C"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s04-q09",
                        "level": 9,
                        "setId": "docx-set-04",
                        "question": "Nhận định nào đúng về chế độ đa đảng ở Trung Quốc?",
                        "options": [
                                    "Trung Quốc là thể chế đa đảng cạnh tranh quyền lực như phương Tây.",
                                    "Các đảng phái dân chủ ở Trung Quốc hoạt động dưới cơ chế hợp tác đa đảng và hiệp thương chính trị, thừa nhận sự lãnh đạo của Đảng Cộng sản Trung Quốc.",
                                    "Trung Quốc không có tổ chức chính trị nào ngoài Đảng Cộng sản Trung Quốc.",
                                    "Các đảng phái dân chủ ở Trung Quốc có quyền thành lập chính phủ đối lập."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s04-q10",
                        "level": 10,
                        "setId": "docx-set-04",
                        "question": "Nhận định \"Nhà nước pháp quyền đứng trên kinh tế và xã hội để phục vụ lợi ích chung\" là đúng hay sai?",
                        "options": [
                                    "Đúng.",
                                    "Sai.",
                                    "Chỉ đúng khi nền kinh tế khủng hoảng.",
                                    "Chỉ đúng trong quản lý hành chính."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s05-q01",
                        "level": 1,
                        "setId": "docx-set-05",
                        "question": "Nhân dân thực hiện quyền dân chủ của mình bằng những hình thức nào?",
                        "options": [
                                    "Chỉ thông qua hoạt động của các cơ quan hành chính.",
                                    "Thông qua dân chủ trực tiếp và dân chủ đại diện.",
                                    "Thông qua quyền lực tư pháp và hoạt động xét xử.",
                                    "Chỉ thông qua việc tham gia các tổ chức xã hội."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s05-q02",
                        "level": 2,
                        "setId": "docx-set-05",
                        "question": "Điều kiện nào của Hiến pháp và hệ thống pháp luật là cần thiết để làm cơ sở cho Nhà nước pháp quyền?",
                        "options": [
                                    "Hiến pháp và pháp luật phải có tính dân chủ và công bằng.",
                                    "Hiến pháp và pháp luật phải hạn chế tối đa quyền tham gia của nhân dân.",
                                    "Hiến pháp và pháp luật chỉ cần được ban hành bởi cơ quan có thẩm quyền.",
                                    "Hiến pháp và pháp luật phải ưu tiên quyền lực của cơ quan nhà nước."
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s05-q03",
                        "level": 3,
                        "setId": "docx-set-05",
                        "question": "Nhận định nào sau đây phản ánh ĐÚNG bản chất của nhà nước XHCN?",
                        "options": [
                                    "Về chính trị: mang bản chất giai cấp công nhân, thống trị để giải phóng mình và nhân dân lao động",
                                    "Về kinh tế: dựa trên chế độ tư hữu về tư liệu sản xuất chủ yếu, chấp nhận quan hệ bóc lột",
                                    "Về văn hóa: chỉ dựa trên các giá trị truyền thống của dân tộc, không tiếp thu tinh hoa nhân loại",
                                    "Về xã hội: sự phân hóa giữa các giai cấp, tầng lớp ngày càng được mở rộng và khoét sâu"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s05-q04",
                        "level": 4,
                        "setId": "docx-set-05",
                        "question": "Trong mối quan hệ giữa cá nhân và nhà nước, công dân được thực hiện quyền tự do của mình theo nguyên tắc nào?",
                        "options": [
                                    "Chỉ được làm những gì pháp luật cho phép",
                                    "Được làm tất cả trừ những điều luật cấm",
                                    "Tuân thủ tuyệt đối mọi quyết định hành chính bất chấp pháp luật",
                                    "Được làm mọi thứ kể cả những điều luật cấm nếu có lý do chính đáng"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s05-q05",
                        "level": 5,
                        "setId": "docx-set-05",
                        "question": "Vì sao việc tôn trọng và bảo đảm quyền con người là đặc điểm quan trọng của Nhà nước pháp quyền?",
                        "options": [
                                    "Vì mọi hoạt động của Nhà nước phải xuất phát từ sự tôn trọng và bảo đảm quyền con người.",
                                    "Vì quyền con người cho phép Nhà nước hoạt động ngoài khuôn khổ pháp luật.",
                                    "Vì quyền con người thay thế hoàn toàn vai trò điều chỉnh của Hiến pháp.",
                                    "Vì quyền con người chỉ có ý nghĩa trong lĩnh vực hoạt động của cơ quan tư pháp."
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s05-q06",
                        "level": 6,
                        "setId": "docx-set-05",
                        "question": "Nhận định nào sau đây KHÔNG đúng về Nhà nước pháp quyền XHCN?",
                        "options": [
                                    "Quyền con người là thước đo để đánh giá tính pháp quyền của một chế độ nhà nước",
                                    "Nhà nước pháp quyền cần có cơ chế phù hợp để bảo vệ Hiến pháp và pháp luật",
                                    "Hiến pháp, pháp luật điều chỉnh cơ bản toàn bộ hoạt động của Nhà nước và xã hội",
                                    "Bất kỳ chế độ lập hiến, hệ thống pháp luật nào cũng có thể làm nền tảng cho nhà nước pháp quyền"
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s05-q07",
                        "level": 7,
                        "setId": "docx-set-05",
                        "question": "Quy tắc hành xử pháp lý: \"Cơ quan nhà nước chỉ được làm những gì luật cho phép; công dân được làm tất cả trừ những điều luật cấm\" phản ánh bản chất nào của Nhà nước pháp quyền?",
                        "options": [
                                    "Giới hạn quyền lực nhà nước nhằm chống lạm quyền và tối đa hóa không gian tự do hợp pháp của công dân.",
                                    "Sự ưu tiên tuyệt đối quyền lợi của bộ máy nhà nước so với nhân dân.",
                                    "Sự buông lỏng quản lý của Nhà nước đối với các hành vi dân sự.",
                                    "Đặt quyền lực cá nhân của người đứng đầu lên trên hệ thống Hiến pháp."
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s05-q08",
                        "level": 8,
                        "setId": "docx-set-05",
                        "question": "Trong mối quan hệ với xã hội, ngoài việc dùng pháp luật để quản lý, Nhà nước pháp quyền cần có thái độ như thế nào đối với các tổ chức, cộng đồng xã hội?",
                        "options": [
                                    "Tôn trọng, đề cao vị trí, vai trò và quyền tự chủ (tự quản) của các cấu trúc xã hội",
                                    "Sáp nhập tất cả các tổ chức xã hội vào hệ thống cơ quan hành chính nhà nước",
                                    "Trực tiếp điều hành mọi hoạt động nội bộ của các cộng đồng xã hội",
                                    "Xóa bỏ sự tồn tại của các tổ chức xã hội để bảo đảm quyền lực nhà nước tuyệt đối"
                        ],
                        "correct": 0
            },
            {
                        "id": "docx-s05-q09",
                        "level": 9,
                        "setId": "docx-set-05",
                        "question": "Điểm khác biệt CĂN BẢN VỀ MẶT LÝ LUẬN giữa nguyên tắc phân công, phối hợp, kiểm soát quyền lực trong Nhà nước pháp quyền XHCN Việt Nam và học thuyết \"Tam quyền phân lập\" của Montesquieu là gì?",
                        "options": [
                                    "Việt Nam không chia bộ máy thành các nhánh Lập pháp, Hành pháp, Tư pháp.",
                                    "Việt Nam thừa nhận sự phân lập tuyệt đối và đối trọng triệt để giữa các cơ quan.",
                                    "Việt Nam khẳng định quyền lực nhà nước là thống nhất thuộc về nhân dân, không phân chia nguồn gốc quyền lực; các cơ quan chỉ phân công nhiệm vụ.",
                                    "Việt Nam trao toàn bộ quyền kiểm soát tối cao cho Tòa án nhân dân thay vì Quốc hội."
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s05-q10",
                        "level": 10,
                        "setId": "docx-set-05",
                        "question": "Hiến pháp năm 2013 bổ sung nguyên tắc nào bên cạnh phân công, phối hợp trong tổ chức quyền lực nhà nước?",
                        "options": [
                                    "Phân lập quyền lực.",
                                    "Kiểm soát quyền lực.",
                                    "Tập trung quyền lực.",
                                    "Tư nhân hóa quyền lực."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s06-q01",
                        "level": 1,
                        "setId": "docx-set-06",
                        "question": "Hoàn thành nhận định: \"Quyền con người là ______ đánh giá tính pháp quyền của chế độ nhà nước.\"",
                        "options": [
                                    "Công cụ hành chính",
                                    "Hình thức tổ chức",
                                    "Tiêu chí",
                                    "Thủ tục"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s06-q02",
                        "level": 2,
                        "setId": "docx-set-06",
                        "question": "Nhà nước XHCN ra đời là kết quả của:",
                        "options": [
                                    "Quá trình cải cách, dân chủ hóa dần dần bộ máy nhà nước tư sản theo hướng tiến bộ",
                                    "Sự thỏa hiệp, chia sẻ quyền lực giữa giai cấp công nhân và giai cấp tư sản",
                                    "Phong trào đấu tranh tự phát của nhân dân lao động, không cần chính đảng lãnh đạo",
                                    "Cách mạng do giai cấp vô sản và nhân dân lao động tiến hành, dưới sự lãnh đạo của Đảng Cộng sản"
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s06-q03",
                        "level": 3,
                        "setId": "docx-set-06",
                        "question": "Trong nhà nước pháp quyền, quyền lực nhà nước được phân công giữa các cơ quan thực hiện những quyền nào?",
                        "options": [
                                    "Quyền lập pháp, quyền hành pháp và quyền giám sát",
                                    "Quyền lập pháp, quyền tư pháp và quyền giám sát",
                                    "Quyền lập pháp, quyền hành pháp và quyền tư pháp",
                                    "Quyền hành pháp, quyền tư pháp và quyền kiểm sát"
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s06-q04",
                        "level": 4,
                        "setId": "docx-set-06",
                        "question": "Mối quan hệ giữa Nhà nước và cá nhân trong Nhà nước pháp quyền được xác định như thế nào?",
                        "options": [
                                    "Được xác định tùy thuộc vào quyết định riêng của từng cơ quan công quyền.",
                                    "Được xác định chặt chẽ bằng pháp luật và mang tính bình đẳng.",
                                    "Được xác định chủ yếu bằng mệnh lệnh hành chính và sự phục tùng tuyệt đối.",
                                    "Được xác định theo sự ưu tiên pháp lý tuyệt đối của Nhà nước."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s06-q05",
                        "level": 5,
                        "setId": "docx-set-06",
                        "question": "Một hệ thống pháp luật như thế nào mới có thể làm cơ sở vững chắc cho chế độ pháp quyền?",
                        "options": [
                                    "Hệ thống pháp luật có tính trừng phạt cao và nghiêm khắc",
                                    "Hệ thống pháp luật dân chủ, công bằng",
                                    "Hệ thống pháp luật do một cơ quan duy nhất độc quyền soạn thảo",
                                    "Hệ thống pháp luật luôn giữ nguyên, không bao giờ thay đổi"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s06-q06",
                        "level": 6,
                        "setId": "docx-set-06",
                        "question": "Hãy chọn nhận định đúng về cách thức phân công và kiểm soát quyền lực nhà nước.",
                        "options": [
                                    "Phân công quyền lực luôn loại trừ hoàn toàn khả năng kiểm soát quyền lực.",
                                    "Chính thể nhà nước không có liên hệ với cách thức tổ chức quyền lực.",
                                    "Mọi quốc gia phải áp dụng duy nhất một mô hình phân công quyền lực giống nhau.",
                                    "Cách thức phân công và kiểm soát quyền lực có thể khác nhau tùy thuộc vào chính thể của mỗi quốc gia."
                        ],
                        "correct": 3
            },
            {
                        "id": "docx-s06-q07",
                        "level": 7,
                        "setId": "docx-set-06",
                        "question": "Mục đích tối thượng của việc xây dựng cơ chế bảo vệ Hiến pháp và pháp luật trong nhà nước pháp quyền là gì?",
                        "options": [
                                    "Giới hạn quyền tự do dân chủ của nhân dân ở mức tối thiểu",
                                    "Bảo đảm địa vị tối cao, bất khả xâm phạm của Hiến pháp, loại bỏ hành vi trái Hiến pháp",
                                    "Cho phép cơ quan hành pháp tự do thay đổi các quy định pháp luật",
                                    "Thay thế hoàn toàn vai trò của các cơ quan tư pháp bằng cơ quan hành chính"
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s06-q08",
                        "level": 8,
                        "setId": "docx-set-06",
                        "question": "Nhận định nào đúng về quan hệ giữa hệ thống pháp luật và Nhà nước pháp quyền?",
                        "options": [
                                    "Mọi hệ thống pháp luật đều đương nhiên tạo ra Nhà nước pháp quyền.",
                                    "Chỉ cần có văn bản luật là đủ hình thành Nhà nước pháp quyền.",
                                    "Chỉ Hiến pháp và hệ thống pháp luật dân chủ, công bằng mới là cơ sở cho chế độ pháp quyền.",
                                    "Nhà nước pháp quyền không phụ thuộc vào Hiến pháp và pháp luật."
                        ],
                        "correct": 2
            },
            {
                        "id": "docx-s06-q09",
                        "level": 9,
                        "setId": "docx-set-06",
                        "question": "Ở Lào, việc Thủ tướng Chính phủ bắt buộc là thành viên Bộ Chính trị Đảng Nhân dân Cách mạng Lào phản ánh điều gì?",
                        "options": [
                                    "Sự tách biệt hoàn toàn giữa Đảng và Nhà nước.",
                                    "Sự gắn kết chặt chẽ giữa tổ chức Đảng và bộ máy nhà nước.",
                                    "Sự cạnh tranh quyền lực giữa các đảng phái.",
                                    "Việc Chính phủ hoạt động độc lập tuyệt đối với Đảng."
                        ],
                        "correct": 1
            },
            {
                        "id": "docx-s06-q10",
                        "level": 10,
                        "setId": "docx-set-06",
                        "question": "Nhận định \"Quyền con người là tiêu chí đánh giá tính pháp quyền của chế độ nhà nước\" là đúng hay sai?",
                        "options": [
                                    "Đúng.",
                                    "Sai.",
                                    "Chỉ đúng trong lĩnh vực tư pháp.",
                                    "Chỉ đúng với quyền kinh tế."
                        ],
                        "correct": 0
            }
];

        const DEFAULT_SETS = [
            {
                        "id": "docx-set-01",
                        "name": "Bộ câu hỏi 01",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            },
            {
                        "id": "docx-set-02",
                        "name": "Bộ câu hỏi 02",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            },
            {
                        "id": "docx-set-03",
                        "name": "Bộ câu hỏi 03",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            },
            {
                        "id": "docx-set-04",
                        "name": "Bộ câu hỏi 04",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            },
            {
                        "id": "docx-set-05",
                        "name": "Bộ câu hỏi 05",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            },
            {
                        "id": "docx-set-06",
                        "name": "Bộ câu hỏi 06",
                        "published": true,
                        "createdAt": "2026-10-04T00:00:00.000Z"
            }
];

        // 10 Mốc tiền thưởng
        // Reward labels for 10-question game; checkpoints at 1,5,10
        const MONEY_TREE = [
            "1 gói bim bim", "—", "—", "—", "3 gói bim bim",
            "—", "—", "—", "—", "Pad chuột"
        ];

        const CHECKPOINTS = [1,5,10]; // levels

        /* ================= 2. QUẢN LÝ TÀI KHOẢN & PHÂN QUYỀN ================= */
        let currentUser = null; // { username, fullname, role: 'user'|'admin' }

        function initAuth() {
            // Kiểm tra xem đã có admin mặc định chưa
            let users = JSON.parse(localStorage.getItem('altp_users')) || [];
            if (!users.some(u => u.username === 'admin')) {
                users.push({ username: 'admin', password: 'admin123', fullname: 'Quản Trị Viên', role: 'admin' });
                localStorage.setItem('altp_users', JSON.stringify(users));
            }

            // Kiểm tra phiên đăng nhập
            const savedUser = localStorage.getItem('altp_current_user');
            if (savedUser) {
                currentUser = JSON.parse(savedUser);
            }
            updateUserNavUI();
        }

        function updateUserNavUI() {
            const nav = document.getElementById('user-nav-status');
            if (currentUser) {
                let adminBtn = currentUser.role === 'admin' 
                    ? `<button onclick="openAdminModal()" class="px-3 py-1 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-lg text-xs flex items-center gap-1"><i class="fa-solid fa-gear"></i> Trang Admin</button>`
                    : '';
                nav.innerHTML = `
                    <span class="text-slate-300"><i class="fa-solid fa-user text-amber-400"></i> ${currentUser.fullname}</span>
                    ${adminBtn}
                    <button onclick="handleLogout()" class="px-2 py-1 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded text-xs"><i class="fa-solid fa-right-from-bracket"></i> Đăng xuất</button>
                `;
                document.getElementById('player-name-input').value = currentUser.fullname;
            } else {
                nav.innerHTML = `
                    <button onclick="openAuthModal('login')" class="px-3 py-1.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-lg text-xs">
                        <i class="fa-solid fa-right-to-bracket mr-1"></i> Đăng Nhập / Đăng Ký
                    </button>
                `;
            }
        }

        /* ================= 2.5. SETS / BỘ CÂU HỎI ================= */
        function getSets() {
            return JSON.parse(localStorage.getItem('altp_sets')) || [];
        }

        function saveSets(sets) {
            localStorage.setItem('altp_sets', JSON.stringify(sets));
        }

        function initSets() {
            let sets = getSets().filter(s => s.id !== 'default');
            const setById = new Map(sets.map(s => [s.id, s]));

            DEFAULT_SETS.forEach(defaultSet => {
                if (setById.has(defaultSet.id)) {
                    Object.assign(setById.get(defaultSet.id), defaultSet);
                } else {
                    sets.push({ ...defaultSet });
                }
            });
            saveSets(sets);

            let questions = JSON.parse(localStorage.getItem('altp_questions')) || [];
            questions = questions.filter(q => q.setId !== 'default' && !String(q.id).startsWith('docx-s'));
            questions.push(...DEFAULT_QUESTIONS.map(q => ({ ...q, options: [...q.options] })));
            saveQuestionBank(questions);

            renderSetOptions();
        }

        function renderSetOptions() {
            const sets = getSets();
            const sel = document.getElementById('select-question-set');
            const adminSel = document.getElementById('q-set');
            const adminFilterSet = document.getElementById('admin-filter-set');
            if (sel) {
                sel.innerHTML = '';
                sets.forEach(s => {
                    const label = s.published ? `${s.name}` : `${s.name} (chưa xuất bản)`;
                    sel.innerHTML += `<option value="${s.id}">${label}</option>`;
                });
            }
            if (adminSel) {
                adminSel.innerHTML = '';
                sets.forEach(s => adminSel.innerHTML += `<option value="${s.id}">${s.name}</option>`);
            }
            if (adminFilterSet) {
                adminFilterSet.innerHTML = `<option value="all">Tất cả bộ câu hỏi</option>`;
                sets.forEach(s => adminFilterSet.innerHTML += `<option value="${s.id}">${s.name}</option>`);
            }
        }

        function adminCreateSet() {
            const name = prompt('Tên bộ câu hỏi mới:');
            if (!name) return;
            const sets = getSets();
            const id = name.toLowerCase().replace(/[^a-z0-9]+/g, '-') + '-' + Date.now();
            sets.push({ id, name, published: false, createdAt: new Date().toISOString() });
            saveSets(sets);
            renderSetOptions();
            alert('Bộ câu hỏi đã được tạo. Hãy thêm câu hỏi cho bộ và xuất bản (publish) khi sẵn sàng.');
        }

        function adminPublishSet() {
            const sets = getSets();
            if (sets.length === 0) { alert('Chưa có bộ nào để xuất bản.'); return; }
            const choice = prompt('Nhập id bộ muốn xuất bản/thu hồi (xem id trong altp_sets), hoặc tên bộ để tìm:');
            if (!choice) return;
            const found = sets.find(s => s.id === choice || s.name === choice);
            if (!found) { alert('Không tìm thấy bộ phù hợp.'); return; }
            found.published = !found.published;
            saveSets(sets);
            renderSetOptions();
            alert(`Bộ "${found.name}" đã ${found.published ? 'được xuất bản' : 'thu hồi khỏi xuất bản'}.`);
        }


        function openAuthModal(tab = 'login') {
            switchAuthTab(tab);
            document.getElementById('modal-auth').classList.remove('hidden');
        }

        function switchAuthTab(tab) {
            const loginForm = document.getElementById('form-login');
            const regForm = document.getElementById('form-register');
            const tabLogin = document.getElementById('auth-tab-login');
            const tabReg = document.getElementById('auth-tab-register');

            if (tab === 'login') {
                loginForm.classList.remove('hidden');
                regForm.classList.add('hidden');
                tabLogin.className = "flex-1 py-2 font-bold text-center border-b-2 border-amber-400 text-amber-400";
                tabReg.className = "flex-1 py-2 font-bold text-center border-b-2 border-transparent text-slate-400 hover:text-slate-200";
            } else {
                loginForm.classList.add('hidden');
                regForm.classList.remove('hidden');
                tabReg.className = "flex-1 py-2 font-bold text-center border-b-2 border-amber-400 text-amber-400";
                tabLogin.className = "flex-1 py-2 font-bold text-center border-b-2 border-transparent text-slate-400 hover:text-slate-200";
            }
        }

        function handleLogin(e) {
            e.preventDefault();
            const u = document.getElementById('login-username').value.trim();
            const p = document.getElementById('login-password').value;

            const users = JSON.parse(localStorage.getItem('altp_users')) || [];
            const found = users.find(user => user.username === u && user.password === p);

            if (found) {
                currentUser = { username: found.username, fullname: found.fullname, role: found.role };
                localStorage.setItem('altp_current_user', JSON.stringify(currentUser));
                updateUserNavUI();
                closeModal('modal-auth');
                alert(`Đăng nhập thành công! Xin chào ${found.fullname}`);
            } else {
                alert("Tên đăng nhập hoặc mật khẩu không chính xác!");
            }
        }

        function handleRegister(e) {
            e.preventDefault();
            const fullname = document.getElementById('reg-fullname').value.trim();
            const u = document.getElementById('reg-username').value.trim();
            const p = document.getElementById('reg-password').value;

            let users = JSON.parse(localStorage.getItem('altp_users')) || [];
            if (users.some(user => user.username === u)) {
                alert("Tên đăng nhập đã tồn tại! Vui lòng chọn tên khác.");
                return;
            }

            const newUser = { username: u, password: p, fullname: fullname, role: 'user' };
            users.push(newUser);
            localStorage.setItem('altp_users', JSON.stringify(users));

            // Tự động đăng nhập
            currentUser = { username: newUser.username, fullname: newUser.fullname, role: newUser.role };
            localStorage.setItem('altp_current_user', JSON.stringify(currentUser));
            updateUserNavUI();
            closeModal('modal-auth');
            alert("Đăng ký tài khoản thành công!");
        }

        function handleLogout() {
            currentUser = null;
            localStorage.removeItem('altp_current_user');
            updateUserNavUI();
            document.getElementById('player-name-input').value = "";
        }

        /* ================= 3. TRANG QUẢN TRỊ ADMIN (CRUD CÂU HỎI) ================= */
        function getQuestionBank() {
            const localData = localStorage.getItem('altp_questions');
            if (localData) {
                return JSON.parse(localData);
            } else {
                localStorage.setItem('altp_questions', JSON.stringify(DEFAULT_QUESTIONS));
                return DEFAULT_QUESTIONS;
            }
        }

        function saveQuestionBank(questions) {
            localStorage.setItem('altp_questions', JSON.stringify(questions));
        }

        function openAdminModal() {
            if (!currentUser || currentUser.role !== 'admin') {
                alert("Bạn không có quyền truy cập trang quản trị!");
                return;
            }
            initAdminUI();
            document.getElementById('modal-admin').classList.remove('hidden');
        }

        function initAdminUI() {
            // Populate select filter & level options
            const filterSel = document.getElementById('admin-filter-level');
            const levelSel = document.getElementById('q-level');
            
            filterSel.innerHTML = `<option value="all">Tất cả các mốc (1-10)</option>`;
            levelSel.innerHTML = ``;

            for (let i = 1; i <= 10; i++) {
                filterSel.innerHTML += `<option value="${i}">Mốc Câu ${i}</option>`;
                levelSel.innerHTML += `<option value="${i}">Câu ${i} (${MONEY_TREE[i-1] || ''})</option>`;
            }

            renderSetOptions();

            renderAdminQuestionList();
            resetAdminForm();
        }

        function renderAdminQuestionList() {
            const filter = document.getElementById('admin-filter-level').value;
            const questions = getQuestionBank();
            const listEl = document.getElementById('admin-question-list');
            listEl.innerHTML = '';

            const setFilter = document.getElementById('admin-filter-set') ? document.getElementById('admin-filter-set').value : 'all';
            let filtered = questions;
            if (filter !== 'all') filtered = filtered.filter(q => q.level == filter);
            if (setFilter !== 'all') filtered = filtered.filter(q => q.setId == setFilter);

            if (filtered.length === 0) {
                listEl.innerHTML = `<p class="text-xs text-slate-500 italic py-4 text-center">Chưa có câu hỏi nào ở mốc này.</p>`;
                return;
            }

            filtered.forEach(q => {
                const item = document.createElement('div');
                item.className = "bg-slate-800/80 p-3 rounded-lg border border-slate-700 text-xs flex justify-between items-start gap-2";
                item.innerHTML = `
                    <div class="space-y-1">
                        <div class="flex items-center gap-2">
                            <span class="px-2 py-0.5 bg-amber-500/20 text-amber-400 font-bold rounded">Câu ${q.level}</span>
                            <span class="text-slate-200 font-bold">${escapeHtml(q.question)}</span>
                        </div>
                        <div class="text-slate-400 grid grid-cols-2 gap-x-2">
                            <span>A: ${escapeHtml(q.options[0])}</span>
                            <span>B: ${escapeHtml(q.options[1])}</span>
                            <span>C: ${escapeHtml(q.options[2])}</span>
                            <span>D: ${escapeHtml(q.options[3])}</span>
                        </div>
                        <div class="text-green-400 font-bold">-> Đáp án đúng: ${['A', 'B', 'C', 'D'][q.correct]}</div>
                    </div>
                    <div class="flex flex-col gap-1">
                        <button onclick="editQuestion(${q.id})" class="px-2 py-1 bg-blue-600 hover:bg-blue-500 text-white rounded"><i class="fa-solid fa-pen-to-square"></i></button>
                        <button onclick="deleteQuestion(${q.id})" class="px-2 py-1 bg-red-600 hover:bg-red-500 text-white rounded"><i class="fa-solid fa-trash"></i></button>
                    </div>
                `;
                listEl.appendChild(item);
            });
        }

        function saveAdminQuestion(e) {
            e.preventDefault();
            const editId = document.getElementById('q-edit-id').value;
            const level = parseInt(document.getElementById('q-level').value);
            const questionText = document.getElementById('q-text').value.trim();
            const options = [
                document.getElementById('q-ans-0').value.trim(),
                document.getElementById('q-ans-1').value.trim(),
                document.getElementById('q-ans-2').value.trim(),
                document.getElementById('q-ans-3').value.trim()
            ];
            const correct = parseInt(document.getElementById('q-correct').value);

            let questions = getQuestionBank();

            const setId = document.getElementById('q-set') ? document.getElementById('q-set').value : 'default';

            if (editId) {
                // Update
                const index = questions.findIndex(q => q.id == editId);
                if (index !== -1) {
                    questions[index] = { id: parseInt(editId), level, setId, question: questionText, options, correct };
                }
            } else {
                // Create
                const newId = Date.now();
                questions.push({ id: newId, level, setId, question: questionText, options, correct });
            }

            saveQuestionBank(questions);
            renderAdminQuestionList();
            resetAdminForm();
            alert("Lưu câu hỏi thành công!");
        }

        function editQuestion(id) {
            const questions = getQuestionBank();
            const q = questions.find(item => item.id == id);
            if (!q) return;

            document.getElementById('admin-form-title').innerText = "Chỉnh Sửa Câu Hỏi";
            document.getElementById('q-edit-id').value = q.id;
            document.getElementById('q-level').value = q.level;
            if (document.getElementById('q-set')) document.getElementById('q-set').value = q.setId || 'default';
            document.getElementById('q-text').value = q.question;
            document.getElementById('q-ans-0').value = q.options[0];
            document.getElementById('q-ans-1').value = q.options[1];
            document.getElementById('q-ans-2').value = q.options[2];
            document.getElementById('q-ans-3').value = q.options[3];
            document.getElementById('q-correct').value = q.correct;
        }

        function deleteQuestion(id) {
            if (!confirm("Bạn có chắc chắn muốn xóa câu hỏi này?")) return;
            let questions = getQuestionBank();
            questions = questions.filter(q => q.id != id);
            saveQuestionBank(questions);
            renderAdminQuestionList();
        }

        function resetAdminForm() {
            document.getElementById('admin-form-title').innerText = "Thêm Câu Hỏi Mới";
            document.getElementById('q-edit-id').value = "";
            document.getElementById('form-question').reset();
        }

        function resetDefaultQuestions() {
            if (confirm("Khôi phục sẽ ghi đè toàn bộ câu hỏi về danh sách mặc định ban đầu. Bạn chắc chắn chứ?")) {
                localStorage.setItem('altp_questions', JSON.stringify(DEFAULT_QUESTIONS));
                renderAdminQuestionList();
                alert("Đã khôi phục ngân hàng câu hỏi mặc định!");
            }
        }

        function escapeHtml(text) {
            return text.replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;");
        }

        /* ================= 4. SOUND ENGINE (WEB AUDIO API) ================= */
        let audioCtx = null;
        let isSoundOn = true;

        function getAudioContext() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
            return audioCtx;
        }

        function toggleSound() {
            isSoundOn = !isSoundOn;
            const btn = document.getElementById('sound-toggle-btn');
            btn.innerHTML = isSoundOn ? '<i class="fa-solid fa-volume-high"></i>' : '<i class="fa-solid fa-volume-xmark text-red-400"></i>';
        }

        function playSound(type) {
            if (!isSoundOn) return;
            try {
                const ctx = getAudioContext();
                const now = ctx.currentTime;

                if (type === 'tick') {
                    const osc = ctx.createOscillator();
                    const gain = ctx.createGain();
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(600, now);
                    gain.gain.setValueAtTime(0.05, now);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + 0.05);
                    osc.connect(gain);
                    gain.connect(ctx.destination);
                    osc.start(now);
                    osc.stop(now + 0.05);
                } else if (type === 'select') {
                    const osc = ctx.createOscillator();
                    const gain = ctx.createGain();
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(440, now);
                    osc.frequency.exponentialRampToValueAtTime(880, now + 0.15);
                    gain.gain.setValueAtTime(0.1, now);
                    gain.gain.linearRampToValueAtTime(0.01, now + 0.15);
                    osc.connect(gain);
                    gain.connect(ctx.destination);
                    osc.start(now);
                    osc.stop(now + 0.15);
                } else if (type === 'correct') {
                    [523.25, 659.25, 783.99, 1046.50].forEach((freq, idx) => {
                        const osc = ctx.createOscillator();
                        const gain = ctx.createGain();
                        osc.type = 'sine';
                        osc.frequency.setValueAtTime(freq, now + idx * 0.1);
                        gain.gain.setValueAtTime(0.15, now + idx * 0.1);
                        gain.gain.exponentialRampToValueAtTime(0.001, now + idx * 0.1 + 0.3);
                        osc.connect(gain);
                        gain.connect(ctx.destination);
                        osc.start(now + idx * 0.1);
                        osc.stop(now + idx * 0.1 + 0.3);
                    });
                } else if (type === 'wrong') {
                    const osc = ctx.createOscillator();
                    const gain = ctx.createGain();
                    osc.type = 'sawtooth';
                    osc.frequency.setValueAtTime(150, now);
                    osc.frequency.linearRampToValueAtTime(80, now + 0.4);
                    gain.gain.setValueAtTime(0.2, now);
                    gain.gain.exponentialRampToValueAtTime(0.01, now + 0.4);
                    osc.connect(gain);
                    gain.connect(ctx.destination);
                    osc.start(now);
                    osc.stop(now + 0.4);
                }
            } catch(e) { console.log(e); }
        }

        /* ================= 5. CORE GAMEPLAY LOGIC (10 QUESTIONS) ================= */
        const MAX_QUESTIONS = 10;
        let playerName = "";
        let currentQuestionIdx = 0; // 0..9
        let currentQuestionData = null;
        let gameQuestions = [];
        let selectedOptionIdx = null;
        let timerInterval = null;
        let timeLeft = 30;

        let usedLifelines = {
            '5050': false,
            'phone': false,
            'audience': false,
            'expert': false
        };

        function startGame() {
            const input = document.getElementById('player-name-input').value.trim();
            playerName = input || (currentUser ? currentUser.fullname : "Người chơi vô danh");

            const selectedSetId = document.getElementById('select-question-set') ? document.getElementById('select-question-set').value : '';
            if (!selectedSetId) {
                alert('Vui lòng chọn một bộ câu hỏi (admin phải tạo/ xuất bản bộ câu hỏi trước).');
                return;
            }

            const sets = getSets();
            const selSet = sets.find(s => s.id === selectedSetId);
            if (!selSet || !selSet.published) {
                alert('Bộ câu hỏi chưa được xuất bản bởi Admin. Vui lòng chờ admin xuất bản.');
                return;
            }

            const allQuestions = getQuestionBank().filter(q => q.setId === selectedSetId);
            if (allQuestions.length < MAX_QUESTIONS) {
                alert(`Bộ câu hỏi này chưa đủ ${MAX_QUESTIONS} câu. Vui lòng liên hệ Admin.`);
                return;
            }

            // Build gameQuestions: pick one question per level (1..MAX_QUESTIONS) if possible, else pick random remaining
            const pool = allQuestions.slice();
            gameQuestions = [];
            for (let lvl = 1; lvl <= MAX_QUESTIONS; lvl++) {
                let candidates = pool.filter(q => q.level === lvl);
                if (candidates.length === 0) candidates = pool;
                if (candidates.length === 0) {
                    // fallback sample
                    gameQuestions.push({ level: lvl, question: `Câu mẫu ${lvl}`, options: ['A','B','C','D'], correct: 0, id: `sample-${lvl}` });
                } else {
                    const pick = candidates[Math.floor(Math.random() * candidates.length)];
                    gameQuestions.push(pick);
                    // remove chosen from pool
                    const remIdx = pool.findIndex(x => x.id === pick.id);
                    if (remIdx !== -1) pool.splice(remIdx, 1);
                }
            }

            currentQuestionIdx = 0;
            usedLifelines = { '5050': false, 'phone': false, 'audience': false, 'expert': false };
            resetLifelineButtonsUI();

            document.getElementById('start-screen').classList.add('hidden');
            document.getElementById('end-screen').classList.add('hidden');
            document.getElementById('game-screen').classList.remove('hidden');

            document.getElementById('display-player-name').innerText = playerName;

            renderMoneyTree();
            loadQuestion(currentQuestionIdx);
        }

        function renderMoneyTree() {
            const list = document.getElementById('money-tree-list');
            list.innerHTML = '';

            for (let i = MAX_QUESTIONS - 1; i >= 0; i--) {
                const isMilestone = (i === 0 || i === 4 || i === (MAX_QUESTIONS - 1)); // Mốc 1,5,10
                const item = document.createElement('div');
                item.id = `money-item-${i}`;
                item.className = `px-3 py-1 rounded text-xs md:text-sm flex justify-between items-center transition ${
                    isMilestone ? 'font-black gold-text border border-amber-500/30 bg-amber-500/10' : 'text-slate-300'
                }`;
                item.innerHTML = `<span>Câu ${i + 1}</span> <span>${MONEY_TREE[i] || ''}</span>`;
                list.appendChild(item);
            }
        }

        function updateMoneyTreeActive() {
            for (let i = 0; i < MAX_QUESTIONS; i++) {
                const el = document.getElementById(`money-item-${i}`);
                if (el) {
                    if (i === currentQuestionIdx) {
                        el.classList.add('money-active');
                    } else {
                        el.classList.remove('money-active');
                    }
                }
            }
        }

        function loadQuestion(idx) {
            currentQuestionIdx = idx;
            updateMoneyTreeActive();

            currentQuestionData = gameQuestions[idx] || null;
            if (!currentQuestionData) {
                currentQuestionData = { level: idx + 1, question: `Câu mẫu số ${idx + 1}`, options: ['A','B','C','D'], correct: 0 };
            }

            // Render UI
            document.getElementById('current-question-num').innerText = `Câu ${idx + 1} / ${MAX_QUESTIONS}`;
            document.getElementById('question-text').innerText = currentQuestionData.question;

            for (let i = 0; i < 4; i++) {
                const btn = document.getElementById(`ans-btn-${i}`);
                const txt = document.getElementById(`ans-text-${i}`);
                txt.innerText = currentQuestionData.options[i] || '';
                btn.className = "hex-btn py-4 px-6 text-left flex items-center text-base md:text-lg";
                btn.disabled = false;
                btn.style.opacity = "1";
            }

            selectedOptionIdx = null;
            startTimer();
        }

        function startTimer() {
            // No time limit mode: timer disabled (infinite)
            clearInterval(timerInterval);
            timeLeft = null;
            const disp = document.getElementById('timer-display');
            if (disp) disp.innerText = '∞';
        }

        function selectAnswer(optIdx) {
            playSound('select');
            selectedOptionIdx = optIdx;

            // Reset highlight
            for (let i = 0; i < 4; i++) {
                document.getElementById(`ans-btn-${i}`).classList.remove('selected');
            }
            document.getElementById(`ans-btn-${optIdx}`).classList.add('selected');

            // Mở Modal xác nhận
            document.getElementById('modal-confirm').classList.remove('hidden');
        }

        function confirmAnswer(isYes) {
            document.getElementById('modal-confirm').classList.add('hidden');
            if (!isYes) {
                // Hủy chọn
                if (selectedOptionIdx !== null) {
                    document.getElementById(`ans-btn-${selectedOptionIdx}`).classList.remove('selected');
                    selectedOptionIdx = null;
                }
                return;
            }

            // Dừng đồng hồ
            clearInterval(timerInterval);

            const isCorrect = (selectedOptionIdx === currentQuestionData.correct);
            const selectedBtn = document.getElementById(`ans-btn-${selectedOptionIdx}`);
            const correctBtn = document.getElementById(`ans-btn-${currentQuestionData.correct}`);

            selectedBtn.classList.remove('selected');

            if (isCorrect) {
                selectedBtn.classList.add('correct');
                playSound('correct');

                setTimeout(() => {
                    if (currentQuestionIdx === (MAX_QUESTIONS - 1)) {
                        // Thắng tối cao
                        triggerConfetti();
                        gameOver(true);
                    } else {
                        loadQuestion(currentQuestionIdx + 1);
                    }
                }, 2000);
            } else {
                selectedBtn.classList.add('wrong');
                correctBtn.classList.add('correct');
                playSound('wrong');

                setTimeout(() => {
                    gameOver(false);
                }, 2000);
            }
        }

        function walkAway() {
            if (confirm("Bạn có chắc chắn muốn dừng cuộc chơi tại đây để bảo toàn số tiền thưởng?")) {
                clearInterval(timerInterval);
                gameOver(true, true);
            }
        }

        function gameOver(isWinCurrent = false, isWalkAway = false) {
            clearInterval(timerInterval);

            let finalReward = "Không có phần thưởng";
            let passedQuestions = isWinCurrent ? MAX_QUESTIONS : currentQuestionIdx;

            if (isWalkAway) {
                // Dừng cuộc chơi bảo toàn câu đã qua
                const lastCorrect = currentQuestionIdx;
                // reward is highest checkpoint <= lastCorrect
                const resp = CHECKPOINTS.slice().reverse().find(c => c <= lastCorrect);
                finalReward = resp ? (MONEY_TREE[resp - 1] || 'Không có phần thưởng') : 'Không có phần thưởng';
            } else if (isWinCurrent) {
                passedQuestions = MAX_QUESTIONS;
                finalReward = MONEY_TREE[MAX_QUESTIONS - 1] || 'Không có phần thưởng';
            } else {
                // Trả lời sai -> Về mốc an toàn: highest checkpoint <= lastCorrect
                const lastCorrect = currentQuestionIdx;
                const resp = CHECKPOINTS.slice().reverse().find(c => c <= lastCorrect);
                finalReward = resp ? (MONEY_TREE[resp - 1] || 'Không có phần thưởng') : 'Không có phần thưởng';
            }

            // Save High Score
            saveHighScore(playerName, passedQuestions, finalReward);

            // Render End Screen UI
            document.getElementById('game-screen').classList.add('hidden');
            document.getElementById('end-screen').classList.remove('hidden');

            document.getElementById('end-player-name').innerText = playerName;
            document.getElementById('end-questions-passed').innerText = `${passedQuestions} / ${MAX_QUESTIONS}`;
            document.getElementById('end-final-money').innerText = finalReward;

            if (passedQuestions === MAX_QUESTIONS) {
                document.getElementById('end-title').innerText = "XUẤT SẮC! CHIẾN THẮNG!";
                document.getElementById('end-subtitle').innerText = `Bạn đã chinh phục hoàn hảo ${MAX_QUESTIONS} câu hỏi!`;
            } else {
                document.getElementById('end-title').innerText = "KẾT THÚC CUỘC CHƠI";
                document.getElementById('end-subtitle').innerText = "Cảm ơn bạn đã tham gia chương trình!";
            }
        }

        /* ================= 6. LIFELINES LOGIC (4 QUYỀN TRỢ GIÚP) ================= */
        function resetLifelineButtonsUI() {
            ['5050', 'phone', 'audience', 'expert'].forEach(type => {
                const btn = document.getElementById(`btn-life-${type}`);
                if (btn) {
                    btn.disabled = false;
                    btn.style.opacity = "1";
                }
            });
        }

        function useLifeline(type) {
            // Symbolic lifelines for classroom play: using consumes the lifeline and shows expert hint only.
            if (usedLifelines[type]) return;
            usedLifelines[type] = true;
            disableLifelineBtn(`btn-life-${type}`);
            // 50:50 hides two wrong answers; other lifelines only get consumed (no modal/help).
            if (type === '5050') {
                apply5050();
            }
            // For non-5050 lifelines we simply consume the lifeline and disable the button.
            return;
        }

        function apply5050() {
            // Hide two incorrect options (disable + dim). Do not change correct answer.
            if (!currentQuestionData || typeof currentQuestionData.correct !== 'number') return;
            const correct = currentQuestionData.correct;
            const wrongs = [0,1,2,3].filter(i => i !== correct);
            // shuffle wrongs
            for (let i = wrongs.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [wrongs[i], wrongs[j]] = [wrongs[j], wrongs[i]];
            }
            const toHide = wrongs.slice(0, 2);
            toHide.forEach(i => {
                const btn = document.getElementById(`ans-btn-${i}`);
                if (btn) {
                    btn.disabled = true;
                    btn.style.opacity = '0.35';
                    btn.classList.add('line-through');
                }
            });
        }

        function disableLifelineBtn(id) {
            const btn = document.getElementById(id);
            btn.disabled = true;
            btn.style.opacity = "0.3";
            btn.classList.add('line-through');
        }

        function closeModal(id) {
            document.getElementById(id).classList.add('hidden');
        }

        function showExpertHelp(type) {
            const optLabels = ['A', 'B', 'C', 'D'];
            let correctIdx = currentQuestionData && typeof currentQuestionData.correct === 'number' ? currentQuestionData.correct : null;
            const correctLabel = correctIdx !== null ? optLabels[correctIdx] : '?';

            if (type === 'phone') {
                const el = document.getElementById('phone-dialog-text');
                if (el) el.innerText = `Chuyên gia gọi điện: Tôi nghĩ đáp án khả dĩ là ${correctLabel}.`;
                document.getElementById('modal-phone').classList.remove('hidden');
                return;
            }

            if (type === 'audience') {
                // Audience: generate symbolic percentages but do not affect answers
                let percents = [0,0,0,0];
                let correctPerc = Math.floor(Math.random() * 30) + 40; // 40% - 69%
                if (correctIdx === null) correctIdx = 0;
                percents[correctIdx] = correctPerc;
                let remaining = 100 - correctPerc;
                for (let i = 0; i < 4; i++) {
                    if (i !== correctIdx) {
                        let p = Math.floor(Math.random() * remaining);
                        percents[i] = p;
                        remaining -= p;
                    }
                }
                percents[3] += remaining;
                for (let i = 0; i < 4; i++) {
                    const pctEl = document.getElementById(`aud-percent-${i}`);
                    const barEl = document.getElementById(`aud-bar-${i}`);
                    if (pctEl) pctEl.innerText = `${percents[i]}%`;
                    if (barEl) barEl.style.height = `${percents[i]}%`;
                }
                document.getElementById('modal-audience').classList.remove('hidden');
                return;
            }

            // Expert: show expert modal with a gentle hint (symbolic only)
            if (type === 'expert') {
                const note = `Gợi ý chuyên gia: dựa trên câu hỏi, chuyên gia gợi ý phương án ${correctLabel}. (Tượng trưng)`;
                const expertEl = document.getElementById('expert-text');
                if (expertEl) expertEl.innerText = note;
                document.getElementById('modal-expert').classList.remove('hidden');
            }
        }

        /* ================= 7. LEADERBOARD & CONFETTI ================= */
        function saveHighScore(name, questionsPassed, money) {
            let leaderboard = JSON.parse(localStorage.getItem('altp_leaderboard')) || [];
            leaderboard.push({ name, questionsPassed, money, date: new Date().toLocaleDateString('vi-VN') });
            leaderboard.sort((a, b) => b.questionsPassed - a.questionsPassed);
            leaderboard = leaderboard.slice(0, 5); // Top 5
            localStorage.setItem('altp_leaderboard', JSON.stringify(leaderboard));
            renderLeaderboard();
        }

        function renderLeaderboard() {
            const body = document.getElementById('leaderboard-body');
            const leaderboard = JSON.parse(localStorage.getItem('altp_leaderboard')) || [];

            if (leaderboard.length === 0) {
                body.innerHTML = `<tr><td colspan="4" class="text-center py-3 text-slate-500 italic">Chưa có kỷ lục nào. Hãy là người chơi đầu tiên!</td></tr>`;
                return;
            }

            body.innerHTML = leaderboard.map((item, idx) => `
                <tr class="border-b border-slate-800/50 hover:bg-slate-900/40">
                    <td class="py-2 font-bold ${idx === 0 ? 'gold-text' : 'text-slate-400'}">${idx + 1}</td>
                    <td class="py-2 font-bold text-slate-200">${escapeHtml(item.name)}</td>
                    <td class="py-2 text-center text-amber-400">${item.questionsPassed} / 10</td>
                    <td class="py-2 text-right font-bold text-green-400">${item.money}</td>
                </tr>
            `).join('');
        }

        function restartGame() {
            startGame();
        }

        function showStartScreen() {
            document.getElementById('end-screen').classList.add('hidden');
            document.getElementById('game-screen').classList.add('hidden');
            document.getElementById('start-screen').classList.remove('hidden');
            renderLeaderboard();
        }

        // Hiệu ứng Pháo hoa Confetti
        function triggerConfetti() {
            const canvas = document.getElementById('confetti-canvas');
            const ctx = canvas.getContext('2d');
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;

            const particles = [];
            const colors = ['#f59e0b', '#3b82f6', '#10b981', '#ef4444', '#ec4899', '#8b5cf6'];

            for (let i = 0; i < 150; i++) {
                particles.push({
                    x: canvas.width / 2,
                    y: canvas.height / 2,
                    vx: (Math.random() - 0.5) * 12,
                    vy: (Math.random() - 0.5) * 12 - 4,
                    color: colors[Math.floor(Math.random() * colors.length)],
                    radius: Math.random() * 6 + 2,
                    life: 100
                });
            }

            function animate() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                let alive = false;

                particles.forEach(p => {
                    if (p.life > 0) {
                        alive = true;
                        p.x += p.vx;
                        p.y += p.vy;
                        p.vy += 0.1; // gravity
                        p.life--;
                        ctx.beginPath();
                        ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                        ctx.fillStyle = p.color;
                        ctx.fill();
                    }
                });

                if (alive) requestAnimationFrame(animate);
            }
            animate();
        }

        function initParticleSystem() {
            const canvas = document.getElementById('particle-canvas');
            if (!canvas) return;

            const ctx = canvas.getContext('2d');
            const pointer = { x: window.innerWidth / 2, y: window.innerHeight / 2, active: false };
            let particles = [];
            let width = 0;
            let height = 0;

            function resize() {
                const dpr = Math.min(window.devicePixelRatio || 1, 2);
                width = window.innerWidth;
                height = window.innerHeight;
                canvas.width = Math.floor(width * dpr);
                canvas.height = Math.floor(height * dpr);
                canvas.style.width = `${width}px`;
                canvas.style.height = `${height}px`;
                ctx.setTransform(dpr, 0, 0, dpr, 0, 0);

                const count = Math.min(110, Math.max(54, Math.floor((width * height) / 17000)));
                particles = Array.from({ length: count }, (_, index) => {
                    const ring = index % 5;
                    return {
                        x: Math.random() * width,
                        y: Math.random() * height,
                        vx: (Math.random() - 0.5) * 0.34,
                        vy: (Math.random() - 0.5) * 0.34,
                        radius: 1.1 + Math.random() * 2.2 + ring * 0.08,
                        phase: Math.random() * Math.PI * 2,
                        hue: Math.random() > 0.64 ? 43 : 194
                    };
                });
            }

            function drawSpotlight() {
                const centerX = width / 2;
                const centerY = height * 0.48;
                const radius = Math.min(width, height) * 0.42;
                const glow = ctx.createRadialGradient(centerX, centerY, 0, centerX, centerY, radius);
                glow.addColorStop(0, 'rgba(255, 209, 102, 0.09)');
                glow.addColorStop(0.44, 'rgba(51, 214, 255, 0.055)');
                glow.addColorStop(1, 'rgba(0, 0, 0, 0)');
                ctx.fillStyle = glow;
                ctx.fillRect(0, 0, width, height);
            }

            function animate(time) {
                ctx.clearRect(0, 0, width, height);
                drawSpotlight();

                for (let i = 0; i < particles.length; i++) {
                    const p = particles[i];
                    const drift = Math.sin(time * 0.001 + p.phase) * 0.12;
                    p.x += p.vx + drift;
                    p.y += p.vy + Math.cos(time * 0.0012 + p.phase) * 0.08;

                    if (pointer.active) {
                        const dx = p.x - pointer.x;
                        const dy = p.y - pointer.y;
                        const distSq = dx * dx + dy * dy;
                        if (distSq < 16000 && distSq > 1) {
                            const force = (1 - distSq / 16000) * 0.18;
                            p.x += dx * force;
                            p.y += dy * force;
                        }
                    }

                    if (p.x < -20) p.x = width + 20;
                    if (p.x > width + 20) p.x = -20;
                    if (p.y < -20) p.y = height + 20;
                    if (p.y > height + 20) p.y = -20;

                    for (let j = i + 1; j < particles.length; j++) {
                        const other = particles[j];
                        const dx = p.x - other.x;
                        const dy = p.y - other.y;
                        const dist = Math.hypot(dx, dy);
                        if (dist < 118) {
                            const alpha = (1 - dist / 118) * 0.16;
                            ctx.strokeStyle = `rgba(51, 214, 255, ${alpha})`;
                            ctx.lineWidth = 1;
                            ctx.beginPath();
                            ctx.moveTo(p.x, p.y);
                            ctx.lineTo(other.x, other.y);
                            ctx.stroke();
                        }
                    }

                    const isGold = p.hue === 43;
                    const pulse = 0.7 + Math.sin(time * 0.002 + p.phase) * 0.3;
                    ctx.beginPath();
                    ctx.arc(p.x, p.y, p.radius + pulse * 0.6, 0, Math.PI * 2);
                    ctx.fillStyle = isGold
                        ? `rgba(255, 209, 102, ${0.32 + pulse * 0.2})`
                        : `rgba(51, 214, 255, ${0.26 + pulse * 0.18})`;
                    ctx.shadowBlur = isGold ? 14 : 11;
                    ctx.shadowColor = isGold ? 'rgba(255, 209, 102, 0.75)' : 'rgba(51, 214, 255, 0.7)';
                    ctx.fill();
                    ctx.shadowBlur = 0;
                }

                requestAnimationFrame(animate);
            }

            window.addEventListener('resize', resize);
            window.addEventListener('pointermove', (event) => {
                pointer.x = event.clientX;
                pointer.y = event.clientY;
                pointer.active = true;
            }, { passive: true });
            window.addEventListener('pointerleave', () => {
                pointer.active = false;
            });

            resize();
            requestAnimationFrame(animate);
        }

        /* INITIALIZATION ON LOAD */
        window.onload = function() {
            initParticleSystem();
            initAuth();
            getQuestionBank(); // Ensure questions localstorage initialized
            initSets();
            renderSetOptions();
            renderLeaderboard();
        };
    </script>
</body>
</html>
