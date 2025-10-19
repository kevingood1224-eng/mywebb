
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Spade - 가상 베팅 사이트 (발표 자료)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Noto+Sans+KR:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        /* --- CSS 스타일 --- */
        :root {
            --accent-color: #A855F7; /* Violet-500: 강조색 */
            --bg-dark: #121212; /* 배경 */
            --card-bg: #1F1F1F; /* 카드 배경 */
        }
        body {
            font-family: 'Inter', 'Noto Sans KR', sans-serif;
            background-color: var(--bg-dark);
            color: #E0E0E0;
            display: flex;
            justify-content: center;
            align-items: flex-start; /* 콘텐츠를 상단에 배치 */
            min-height: 100vh;
            padding: 20px; /* PC/태블릿 환경에서 적절한 여백 */
            box-sizing: border-box;
        }
        
        /* 앱 컨테이너: 모든 기기에서 최대 너비를 400px로 제한하여 모바일 앱 느낌 유지 */
        .app-container {
            max-width: 400px;
            width: 100%;
            background: var(--bg-dark);
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
            padding: 24px;
            margin-top: 40px; /* 상단 여백 추가 */
            margin-bottom: 40px; /* 하단 여백 추가 */
        }

        /* 미디어 쿼리: 작은 화면 (모바일)에서 상/하단 여백 줄이기 */
        @media (max-width: 480px) {
            body {
                padding: 10px;
            }
            .app-container {
                margin-top: 20px;
                margin-bottom: 20px;
            }
        }
        
        /* UI 애니메이션: 모든 UI에 적용되는 페이드 인 효과 */
        .fade-in-out {
            opacity: 0;
            transform: translateY(10px);
            animation: fadeIn 0.5s forwards;
        }
        @keyframes fadeIn {
            to { opacity: 1; transform: translateY(0); }
        }

        /* 버튼 클릭 시 '딸깍' 효과 (scale down) */
        .click-effect {
            transition: transform 0.1s ease;
        }
        .click-effect:active {
            transform: scale(0.98);
        }

        /* 긴장감 고조 텍스트 애니메이션 스타일 */
        .hype-text {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--accent-color);
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            opacity: 0;
            white-space: nowrap;
        }

        /* --- 커스텀 로고/아이콘 스타일 --- */
        .spade-icon::before {
            content: '\2660'; 
            line-height: 1;
        }
        .choice-icon {
            font-family: 'Inter', sans-serif;
            font-weight: 900;
            color: var(--accent-color);
            display: block;
        }

        /* 가위바위보 카드 스타일 */
        .choice-card {
            background-color: var(--card-bg);
            border: 2px solid #333;
            padding: 20px;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.2s ease-in-out;
            text-align: center;
        }
        .choice-card:hover {
            border-color: var(--accent-color);
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(168, 85, 247, 0.3);
        }
        .choice-card.selected {
            border-color: #4ADE80; /* Green */
            box-shadow: 0 0 20px rgba(74, 222, 128, 0.5);
            transform: scale(1.05);
        }

        /* 송금 모달 페이드 아웃 시 애니메이션 */
        .fade-out {
            opacity: 0 !important;
            transform: translateY(10px) !important;
            transition: opacity 0.3s, transform 0.3s;
        }

        /* 로그인 화면 컨테이너 */
        #loginScreen .app-container {
            animation: none; 
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.7);
            margin: 0 20px; /* 화면 좌우 패딩 */
        }
        #loginScreen {
            padding: 0 20px;
        }
    </style>
</head>
<body>

<div id="loginScreen" class="fixed inset-0 bg-black z-50 flex items-center justify-center fade-in-out">
    <div class="app-container p-8 bg-zinc-900 shadow-2xl">
        <div class="logo-with-icon mb-10 text-center">
            <span class="spade-icon text-5xl text-violet-500 mr-2"></span>
            <h1 class="text-4xl font-black text-white inline-block align-middle">TEAM SPADE</h1>
        </div>

        <h2 class="text-xl font-bold mb-6 text-gray-300 text-center">계정 접속</h2>
        
        <input type="text" id="userId" placeholder="아이디" class="w-full p-4 bg-zinc-800 rounded-lg mb-4 text-white focus:outline-none focus:ring-2 focus:ring-violet-500 border border-transparent hover:border-violet-500 transition">
        <input type="password" id="userPin" placeholder="PIN 번호 (4자리 이상)" maxlength="4" class="w-full p-4 bg-zinc-800 rounded-lg mb-6 text-white focus:outline-none focus:ring-2 focus:ring-violet-500 border border-transparent hover:border-violet-500 transition">

        <button id="loginButton" class="w-full py-4 bg-violet-600 hover:bg-violet-700 text-white font-extrabold rounded-xl transition-all click-effect shadow-violet-500/50 shadow-lg">
            접속하기
        </button>
        <p class="text-xs text-center mt-4 text-gray-500">발표 자료용 가상 로그인 (PIN: 1234)</p>
    </div>
</div>

<div id="app" class="app-container fade-in-out hidden">
    <header class="flex justify-between items-center mb-6">
        <div class="logo-with-icon flex-shrink-0">
            <span class="spade-icon text-2xl text-violet-500 mr-1"></span>
            <h1 class="text-2xl font-black text-white inline-block align-middle">TEAM SPADE</h1>
        </div>
        <div class="text-right flex-shrink-0 ml-4">
            <p class="text-xl font-extrabold text-white whitespace-nowrap" id="currentBalance">50,000 RBX</p>
            <p class="text-xs text-gray-400">잔액 (가상)</p>
        </div>
    </header>

    <main id="mainGame" class="fade-in-out" style="animation-delay: 0.1s;">
        <h2 class="text-3xl font-extrabold mb-8 text-center">가위바위보 베팅 💰</h2>

        <div class="p-5 bg-zinc-800 rounded-xl mb-6 shadow-lg">
            <label for="betAmount" class="block text-sm font-semibold mb-2 text-gray-300">베팅 금액 (RBX)</label>
            <div class="flex items-center">
                <input type="number" id="betAmount" value="1000" min="1000" step="1000" class="w-full text-2xl p-2 bg-transparent border-b-2 border-violet-500 focus:outline-none focus:border-violet-300 transition-colors click-effect text-white">
                <span class="text-xl ml-2 text-violet-400">RBX</span>
            </div>
            <p class="text-xs text-red-400 mt-2 hidden" id="balanceError">잔액이 부족합니다.</p>
        </div>

        <div id="choiceSelection" class="grid grid-cols-3 gap-4 mb-8">
            <div class="choice-card click-effect fade-in-out" data-choice="rock" style="animation-delay: 0.2s;">
                <span class="text-5xl choice-icon">R</span>
                <p class="font-bold mt-2">바위</p>
            </div>
            <div class="choice-card click-effect fade-in-out" data-choice="scissors" style="animation-delay: 0.3s;">
                <span class="text-5xl choice-icon">S</span>
                <p class="font-bold mt-2">가위</p>
            </div>
            <div class="choice-card click-effect fade-in-out" data-choice="paper" style="animation-delay: 0.4s;">
                <span class="text-5xl choice-icon">P</span>
                <p class="font-bold mt-2">보</p>
            </div>
        </div>

        <div class="text-center">
            <button id="betButton" class="w-full py-4 bg-violet-600 hover:bg-violet-700 text-white font-extrabold rounded-xl transition-all click-effect shadow-violet-500/50 shadow-lg" disabled>
                베팅할 선택지를 고르세요
            </button>
            <p id="resultMessage" class="mt-4 text-lg font-semibold text-center hidden"></p>
        </div>

    </main>
</div>

<div id="hypeOverlay" class="fixed inset-0 pointer-events-none z-50 flex items-center justify-center hidden">
    <div id="hypeText" class="hype-text"></div>
</div>

<div id="transferModal" class="fixed inset-0 bg-black bg-opacity-70 z-40 hidden items-center justify-center">
    <div id="modalContent" class="bg-zinc-800 p-6 rounded-xl w-11/12 max-w-sm fade-in-out">
        <h3 class="text-2xl font-bold mb-4">RBX 송금/잔액 확인 (가상)</h3>
        <p class="text-sm text-gray-400 mb-4">현재 잔액: <span class="font-bold text-violet-400" id="modalBalance">50,000 RBX</span></p>
        
        <label for="transferId" class="block text-sm font-semibold mb-1 text-gray-300">받는 사람 ID</label>
        <input type="text" id="transferId" placeholder="ID를 입력하세요" class="w-full p-3 bg-zinc-700 rounded-lg mb-4 text-white focus:outline-none focus:ring-2 focus:ring-violet-500">
        
        <label for="transferAmount" class="block text-sm font-semibold mb-1 text-gray-300">송금 금액 (RBX)</label>
        <input type="number" id="transferAmount" value="0" min="1" class="w-full p-3 bg-zinc-700 rounded-lg mb-6 text-white focus:outline-none focus:ring-2 focus:ring-violet-500">
        
        <div class="flex justify-end space-x-3">
            <button class="py-2 px-4 bg-gray-600 hover:bg-gray-700 rounded-lg text-white font-semibold click-effect" onclick="closeTransferModal()">취소</button>
            <button class="py-2 px-4 bg-violet-600 hover:bg-violet-700 rounded-lg text-white font-semibold click-effect" onclick="handleTransfer()">송금 실행</button>
        </div>
    </div>
</div>

<button class="fixed bottom-4 left-4 py-2 px-4 bg-gray-700 hover:bg-gray-600 rounded-lg text-white font-semibold click-effect fade-in-out hidden" id="transferButton" style="z-index: 30;">
    ⚙️ 더보기/설정
</button>

<script>
    /* --- JavaScript 코드 --- */

    // --- 오디오 설정 (파일이 같은 폴더에 있어야 작동합니다!) ---
    let clickSound, winSound, loseSound;

    // 브라우저의 자동 재생 정책 때문에 사용자 상호작용 후 로드
    function initializeAudio() {
        // 이미 로드되었으면 건너뜀
        if (clickSound) return; 
        
        clickSound = new Audio('click.mp3');
        winSound = new Audio('win.mp3');
        loseSound = new Audio('lose.mp3');
        
        // 오디오 파일을 미리 로드하여 딜레이 최소화
        clickSound.load();
        winSound.load();
        loseSound.load();

        console.log("Audio initialized.");
    }

    // --- 잔액 관리 ---
    const BALANCE_KEY = 'spade_rbs_balance';
    let balance = loadBalance();

    function loadBalance() {
        let initialBalance = 100000; 
        const storedBalance = localStorage.getItem(BALANCE_KEY);
        if (storedBalance) {
            return parseInt(storedBalance);
        }
        localStorage.setItem(BALANCE_KEY, initialBalance);
        return initialBalance;
    }

    function updateBalance(amount) {
        balance += amount;
        localStorage.setItem(BALANCE_KEY, balance);
        const formattedBalance = formatBalance(balance) + ' RBX';
        
        const currentBalanceEl = document.getElementById('currentBalance');
        if (currentBalanceEl) {
            currentBalanceEl.textContent = formattedBalance;
        }
        const modalBalanceEl = document.getElementById('modalBalance');
        if (modalBalanceEl) {
            modalBalanceEl.textContent = formattedBalance;
        }

        if (balance <= 0) {
            if (currentBalanceEl) currentBalanceEl.classList.add('text-red-500');
            if (currentBalanceEl) currentBalanceEl.classList.remove('text-white');
        } else {
            if (currentBalanceEl) currentBalanceEl.classList.remove('text-red-500');
            if (currentBalanceEl) currentBalanceEl.classList.add('text-white');
        }
    }

    function formatBalance(num) {
        return Math.round(num).toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",");
    }

    // 초기 잔액 표시 업데이트
    updateBalance(0); 

    // --- 로그인 시스템 로직 ---
    const loginScreen = document.getElementById('loginScreen');
    const loginButton = document.getElementById('loginButton');
    const mainApp = document.getElementById('app');
    const transferButton = document.getElementById('transferButton');
    const userPinInput = document.getElementById('userPin');

    loginButton.addEventListener('click', () => {
        // 오디오 초기화 시도 (첫 사용자 상호작용)
        initializeAudio(); 

        if (userPinInput.value === '1234') {
            loginScreen.style.opacity = 0;
            loginScreen.style.transition = 'opacity 0.5s ease-out';
            
            setTimeout(() => {
                loginScreen.classList.add('hidden');
                mainApp.classList.remove('hidden');
                transferButton.classList.remove('hidden');
                updateBalance(0); 
            }, 500);
        } else {
            alert("가상 PIN 번호 (1234)가 올바르지 않습니다.");
        }
    });

    // --- UI/UX 기능 (클릭 효과음) ---
    document.querySelectorAll('.click-effect').forEach(element => {
        element.addEventListener('click', () => {
            if (clickSound) {
                 clickSound.currentTime = 0; // 여러 번 빠르게 클릭 시 재생 가능하게 초기화
                 clickSound.play().catch(e => console.log("Click sound blocked by browser policy."));
            }
        });
    });

    // --- 베팅 게임 로직 ---
    const choiceCards = document.querySelectorAll('.choice-card');
    const betButton = document.getElementById('betButton');
    const betAmountInput = document.getElementById('betAmount');
    const resultMessage = document.getElementById('resultMessage');
    let selectedChoice = null;

    // 가위바위보 선택 처리
    choiceCards.forEach(card => {
        card.addEventListener('click', () => {
            if (betButton.disabled === false && betButton.textContent.includes('베팅하기')) return;

            choiceCards.forEach(c => c.classList.remove('selected'));
            card.classList.add('selected');
            selectedChoice = card.getAttribute('data-choice');
            
            checkBetValidity();
        });
    });

    // 베팅 금액 유효성 검사 및 버튼 텍스트 업데이트
    function checkBetValidity() {
        const bet = parseInt(betAmountInput.value);
        const errorElement = document.getElementById('balanceError');

        if (isNaN(bet) || bet < 100) {
            betAmountInput.value = 100;
        }

        if (bet > balance) {
            errorElement.classList.remove('hidden');
            betButton.disabled = true;
            betButton.textContent = "잔액 부족";
            return;
        } else {
            errorElement.classList.add('hidden');
        }
        
        if (selectedChoice) {
            betButton.disabled = false;
            betButton.textContent = `${formatBalance(parseInt(betAmountInput.value))} RBX 베팅하기`;
        } else {
            betButton.disabled = true;
            betButton.textContent = "가위바위보를 선택하세요";
        }
    }

    // 베팅 금액 변경 시 처리
    betAmountInput.addEventListener('input', checkBetValidity);
    betAmountInput.addEventListener('change', checkBetValidity);

    // 최종 베팅 실행
    betButton.addEventListener('click', () => {
        if (!selectedChoice) return;
        
        const betAmount = parseInt(betAmountInput.value);
        if (betAmount > balance) return;
        
        betButton.disabled = true;
        betButton.textContent = "결과 대기 중...";
        resultMessage.classList.add('hidden');
        
        startHypeAnimation(selectedChoice, betAmount);
    });

    // --- 게임 핵심 로직 (애니메이션, 결과 처리) ---
    function startHypeAnimation(userChoice, betAmount) {
        const hypeText = document.getElementById('hypeText');
        const hypeOverlay = document.getElementById('hypeOverlay');
        const choices = ['rock', 'scissors', 'paper'];
        const textSequence = ['락!...', '시져!...', '페이퍼!...']; 

        hypeOverlay.classList.remove('hidden');
        
        let sequenceIndex = 0;

        function nextHype() {
            if (sequenceIndex < textSequence.length) {
                hypeText.textContent = textSequence[sequenceIndex];
                hypeText.style.animation = 'none'; 
                
                setTimeout(() => {
                    hypeText.style.animation = 'fadeIn 0.5s forwards';
                }, 10);
                
                setTimeout(() => {
                    hypeText.style.opacity = 0; 
                    sequenceIndex++;
                    nextHype(); 
                }, 700);
            } else {
                hypeOverlay.classList.add('hidden');
                processGameResult(userChoice, betAmount, choices);
            }
        }
        
        nextHype(); 
    }

    function processGameResult(userChoice, betAmount, choices) {
        const computerChoice = choices[Math.floor(Math.random() * 3)];
        let result = ''; 

        if (userChoice === computerChoice) {
            result = 'draw';
        } else if (
            (userChoice === 'rock' && computerChoice === 'scissors') ||
            (userChoice === 'scissors' && computerChoice === 'paper') ||
            (userChoice === 'paper' && computerChoice === 'rock')
        ) {
            result = 'win';
        } else {
            result = 'lose';
        }

        displayResult(result, betAmount, computerChoice);
    }

    function displayResult(result, betAmount, computerChoice) {
        let message = '';
        let sound = null;

        const choiceMap = { 'rock': '바위', 'scissors': '가위', 'paper': '보' };
        
        if (result === 'win') {
            updateBalance(betAmount);
            message = `**[승리]** 컴퓨터: ${choiceMap[computerChoice]}. **+${formatBalance(betAmount)} RBX** 획득!`;
            resultMessage.className = 'mt-4 text-xl font-extrabold text-green-400 text-center fade-in-out';
            sound = winSound;
        } else if (result === 'lose') {
            updateBalance(-betAmount);
            message = `**[패배]** 컴퓨터: ${choiceMap[computerChoice]}. **-${formatBalance(betAmount)} RBX** 차감.`;
            resultMessage.className = 'mt-4 text-xl font-extrabold text-red-500 text-center fade-in-out';
            sound = loseSound;
            if (balance <= 0) {
                 message += "<br>💸 **모든 잔액 소진!**";
            }
        } else {
            message = `**[무승부]** 컴퓨터: ${choiceMap[computerChoice]}. 베팅금 유지.`;
            resultMessage.className = 'mt-4 text-xl font-extrabold text-yellow-400 text-center fade-in-out';
            sound = clickSound;
        }

        resultMessage.innerHTML = message;
        resultMessage.classList.remove('hidden');
        betButton.disabled = false;
        betButton.textContent = "다시 베팅하기";
        selectedChoice = null; 
        choiceCards.forEach(c => c.classList.remove('selected'));

        if (sound) {
            sound.currentTime = 0; 
            sound.play().catch(e => console.log("Result sound blocked by browser policy."));
        }
    }

    // --- 가상의 송금 모달 기능 (더보기/설정) ---
    const transferModal = document.getElementById('transferModal');
    const modalContent = document.getElementById('modalContent');

    transferButton.addEventListener('click', openTransferModal);

    function openTransferModal() {
        updateBalance(0); 
        transferModal.classList.remove('hidden');
        transferModal.style.display = 'flex';
        modalContent.classList.remove('fade-out'); 
        modalContent.classList.add('fade-in-out');
    }

    function closeTransferModal() {
        modalContent.classList.add('fade-out');
        modalContent.classList.remove('fade-in-out');
        setTimeout(() => {
            transferModal.classList.add('hidden');
            transferModal.style.display = 'none';
        }, 300);
    }

    function handleTransfer() {
        const amount = parseInt(document.getElementById('transferAmount').value);
        const id = document.getElementById('transferId').value;

        if (amount > 0 && id.length > 0) {
            if (amount > balance) {
                alert("송금 잔액이 부족합니다!");
                return;
            }
            updateBalance(-amount);
            alert(`[가상 송금 완료] ${id}님에게 ${formatBalance(amount)} RBX 송금 완료되었습니다!`);
            closeTransferModal();
            checkBetValidity();
        } else {
            alert("받는 사람 ID와 송금 금액을 정확히 입력해주세요.");
        }
    }
</script>
</body>
</html>

