
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Зат есім тақырыбы бойынша тест</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: #333;
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
             background-image: url('дала.jpg');
        }

        .container {
            background-color: rgba(255, 255, 255, 0.173);
            border-radius: 50px;
            padding: 30px;
            width: 90%;
            max-width: 2000px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        h1 {
            color: #2575fc;
            margin-bottom: 20px;
            font-size: 2.2rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .instructions {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 25px;
            font-size: 1.1rem;
            line-height: 1.6;
            border-left: 5px solid #2575fc;
        }

        .oylar-container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            margin-bottom: 30px;
        }

        .oyu {
            height: 250px;
            width: 250px; /* Дөңгелек пішін үшін бірдей биіктік пен ені */
            border-radius: 50%; /* Дөңгелек пішін үшін 50% */
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            background: linear-gradient(to right, #bfa86f, #f1ece6);
            color: white;
            font-size: 2.5rem;
            font-weight: bold;
            position: relative;
            overflow: hidden;
            margin: 0 auto; /* Ортаға туралау */
        }

        .oyu img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
            transition: transform 0.3s ease;
            border-radius: 50%; /* Суретті де дөңгелек ету */
        }

        .oyu .number {
            position: relative;
            z-index: 2;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        .oyu:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        .oyu:hover img {
            transform: scale(1.1);
        }

        .question-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
        }

        .question-modal.active {
            opacity: 1;
            visibility: visible;
        }

        .question-container {
            background-color: white;
            border-radius: 15px;
            padding: 30px;
            width: 90%;
            max-width: 600px;
            box-shadow: 0 5px 30px rgba(0, 0, 0, 0.3);
            position: relative;
            transform: translateY(50px);
            transition: transform 0.3s ease;
        }

        .question-modal.active .question-container {
            transform: translateY(0);
        }

        .close-btn {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 1.5rem;
            cursor: pointer;
            color: #999;
            transition: color 0.3s ease;
        }

        .close-btn:hover {
            color: #333;
        }

        .question-text {
            font-size: 1.4rem;
            margin-bottom: 20px;
            color: #2575fc;
            font-weight: bold;
            line-height: 1.4;
        }

        .timer {
            font-size: 1.2rem;
            margin-bottom: 15px;
            color: #e74c3c;
            font-weight: bold;
        }

        .options {
            display: grid;
            grid-template-columns: 1fr;
            gap: 12px;
            margin-bottom: 20px;
        }

        .option {
            padding: 15px;
            background-color: #f8f9fa;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.2s ease;
            text-align: left;
            border: 2px solid #e9ecef;
            font-size: 1.1rem;
        }

        .option:hover {
            background-color: #e9ecef;
            transform: translateX(5px);
        }

        .option.correct {
            background-color: #d4edda;
            color: #155724;
            border-color: #c3e6cb;
        }

        .option.incorrect {
            background-color: #f8d7da;
            color: #721c24;
            border-color: #f5c6cb;
        }

        .score-container {
            margin-top: 20px;
            font-size: 1.3rem;
            font-weight: bold;
            color: #2575fc;
            padding: 10px;
            background-color: #f8f9fa;
            border-radius: 10px;
            display: inline-block;
        }

        .controls {
            margin-top: 25px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        button {
            padding: 12px 25px;
            background: linear-gradient(to right, #2575fc, #6a11cb);
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        button:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .music-control {
            margin-top: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .result {
            margin-top: 20px;
            font-size: 1.2rem;
            font-weight: bold;
            padding: 15px;
            border-radius: 10px;
            display: none;
        }

        .correct-result {
            background-color: #d5d2a9;
            color: #155724;
        }

        .incorrect-result {
            background-color: #f8d7da;
            color: #721c24;
        }

        @media (max-width: 768px) {
            .oylar-container {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .oyu {
                height: 100px;
                width: 100px;
                font-size: 2rem;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .question-text {
                font-size: 1.2rem;
            }
        }

        @media (max-width: 480px) {
            .oylar-container {
                grid-template-columns: 1fr;
            }
            
            .container {
                padding: 15px;
            }
            
            h1 {
                font-size: 1.6rem;
            }
            
            .question-container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div >
        <h1> </h1>
        
        <div>
           
        </div>
        
        <div class="oylar-container">
            <div class="oyu">
                <img src="1.jpg" alt="Сурет 1">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="2.jpg" alt="Сурет 2">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="3.jpg" alt="Сурет 3">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="4.jpg" alt="Сурет 4">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="5.jpg" alt="Сурет 5">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="6.jpg" alt="Сурет 6">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="7.jpg" alt="Сурет 7">
                <div class="number"> </div>
            </div>
            <div class="oyu">
                <img src="8.jpg" alt="Сурет 8">
                <div class="number"> </div>
            </div>
        </div>
        
        <div class="score-container">
            Ұпай: <span id="score">0</span>
        </div>
        
        <div class="controls">
            <button id="restartBtn">Қайта бастау</button>
        </div>
        
        <div class="music-control">
            <span>  </span>
            <button id="playMusic"> </button>
            <button id="pauseMusic"> </button>
        </div>
    </div>

    <div class="question-modal" id="questionModal">
        <div class="question-container">
            <div class="close-btn" id="closeQuestion">×</div>
            <div class="question-text" id="questionText"></div>
            <div class="timer" id="timer">10 секунд қалды</div>
            <div class="options" id="optionsContainer"></div>
            <div class="result" id="result"></div>
        </div>
    </div>

    <audio id="backgroundMusic" loop>
        <source src="Нұрғиса Тілендиев - Аққу.mp3" type="audio/mpeg">
    </audio>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Элементтерді алу
            const oyuElements = document.querySelectorAll('.oyu');
            const questionModal = document.getElementById('questionModal');
            const questionText = document.getElementById('questionText');
            const timerElement = document.getElementById('timer');
            const optionsContainer = document.getElementById('optionsContainer');
            const resultElement = document.getElementById('result');
            const scoreElement = document.getElementById('score');
            const restartBtn = document.getElementById('restartBtn');
            const playMusicBtn = document.getElementById('playMusic');
            const pauseMusicBtn = document.getElementById('pauseMusic');
            const backgroundMusic = document.getElementById('backgroundMusic');
            const closeQuestionBtn = document.getElementById('closeQuestion');
            
            // Айнымалылар
            let score = 0;
            let currentQuestionIndex = -1;
            let timer;
            let timeLeft = 10;
            let usedQuestions = [];
            
            // Сұрақтар мен жауаптар
            const questions = [
                {
                    question: "1. Зат есімнің түрлену түрлерін көрсетіңіз:",
                    options: [
                        "А) Септелу, жіктелу",
                        "Ә) Септелу, көптелу, тәуелдену",
                        "Б) Септелу, көптелу, жіктелу, тәуелдену",
                        "В) Тек септелу"
                    ],
                    correct: 1
                },
                {
                    question: "2. Зат есімнің сөйлемдегі негізгі қызметтері:",
                    options: [
                        "А) Бастауыш пен баяндауыш",
                        "Ә) Бастауыш пен толықтауыш",
                        "Б) Анықтауыш пен пысықтауыш",
                        "В) Толықтауыш пен анықтауыш"
                    ],
                    correct: 1
                },
                {
                    question: "3. Зат есім барлық сөйлем мүшесінің қызметін атқара ала ма?",
                    options: [
                        "А) Иә",
                        "Ә) Жоқ",
                        "Б) Тек бастауыш болады",
                        "В) Тек толықтауыш болады"
                    ],
                    correct: 0
                },
                {
                    question: "4. «Балықшылар теңізге қарай бет алды» сөйлеміндегі бастауыш:",
                    options: [
                        "А) Теңізге",
                        "Ә) Қарай",
                        "Б) Балықшылар",
                        "В) Бет алды"
                    ],
                    correct: 2
                },
                {
                    question: "5. «Тілекке әкесінің сөзі ой салды» сөйлеміндегі толықтауыш:",
                    options: [
                        "А) Тілекке",
                        "Ә) Әкесінің",
                        "Б) Сөзі",
                        "В) Ой"
                    ],
                    correct: 0
                },
                {
                    question: "6. «Тілекке әкесінің сөзі ой салды» сөйлеміндегі анықтауыш:",
                    options: [
                        "А) Тілекке",
                        "Ә) Әкесінің",
                        "Б) Сөзі",
                        "В) Ой салды"
                    ],
                    correct: 1
                },
                {
                    question: "7. «Тілекке әкесінің сөзі ой салды» сөйлеміндегі бастауыш:",
                    options: [
                        "А) Тілекке",
                        "Ә) Әкесінің",
                        "Б) Сөзі",
                        "В) Ой"
                    ],
                    correct: 2
                },
                {
                    question: "8. «Елдос Астанадан Алматыға ұшақпен келді» сөйлеміндегі «Астанадан» қандай мүше?",
                    options: [
                        "А) Бастауыш",
                        "Ә) Толықтауыш",
                        "Б) Пысықтауыш",
                        "В) Анықтауыш"
                    ],
                    correct: 1
                },
                {
                    question: "9. «Алматыға» сөзінің сөйлемдегі қызметі:",
                    options: [
                        "А) Толықтауыш",
                        "Ә) Анықтауыш",
                        "Б) Пысықтауыш",
                        "В) Бастауыш"
                    ],
                    correct: 1
                },
                {
                    question: "10. «Ұшақпен» сөзінің сөйлемдегі қызметі:",
                    options: [
                        "А) Пысықтауыш",
                        "Ә) Толықтауыш",
                        "Б) Бастауыш",
                        "В) Анықтауыш"
                    ],
                    correct: 0
                },
                {
                    question: "11. «Адам бойындағы асыл қасиет – адамгершілік» сөйлемінде «адамгершілік» қай мүше?",
                    options: [
                        "А) Бастауыш",
                        "Ә) Толықтауыш",
                        "Б) Баяндауыш",
                        "В) Анықтауыш"
                    ],
                    correct: 1
                },
                {
                    question: "12. Зат есім баяндауыш бола ала ма?",
                    options: [
                        "А) Иә, жіктеліп келіп",
                        "Ә) Жоқ",
                        "Б) Тек жалқы есім болса ғана",
                        "В) Тек көптелсе ғана"
                    ],
                    correct: 0
                },
                {
                    question: "13. «Бар қазақтың Абайы» сөйлемінде «Абайы» қай қызметте тұр?",
                    options: [
                        "А) Толықтауыш",
                        "Ә) Баяндауыш",
                        "Б) Анықтауыш",
                        "В) Пысықтауыш"
                    ],
                    correct: 0
                },
                {
                    question: "14. Көмекші есімнің басты белгісі:",
                    options: [
                        "А) Толық мағынасы бар",
                        "Ә) Сөйлем мүшесі бола алады",
                        "Б) Толық мағынасы жоқ, көмекшілік қызмет атқарады",
                        "В) Тек бастауыш болады"
                    ],
                    correct: 2
                },
                {
                    question: "15. Көмекші есімдер қай септікте байланысады?",
                    options: [
                        "А) Атау септік",
                        "Ә) Ілік септік",
                        "Б) Жатыс септік",
                        "В) Шығыс септік"
                    ],
                    correct: 1
                },
                {
                    question: "16. Көмекші есім тәуелдік жалғаудың қай тұлғасында келеді?",
                    options: [
                        "А) Жіктік тұлғасында",
                        "Ә) Көптік тұлғасында",
                        "Б) Тәуелдік тұлғасында",
                        "В) Септік тұлғасыnda"
                    ],
                    correct: 2
                },
                {
                    question: "17. «Қаланың сырты» тіркесінде көмекші есім қай сөз?",
                    options: [
                        "А) Қаланың",
                        "Ә) Сырты",
                        "Б) Қала",
                        "В) Ілік"
                    ],
                    correct: 1
                },
                {
                    question: "18. «Жердің асты» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Жердің",
                        "Ә) Жер",
                        "Б) Асты",
                        "В) Түбі"
                    ],
                    correct: 2
                },
                {
                    question: "19. «Үстелдің үсті» тіркесінде көмекші есімнің орны:",
                    options: [
                        "А) Үстелдің",
                        "Ә) Үсті",
                        "Б) Үстел",
                        "В) Алды"
                    ],
                    correct: 1
                },
                {
                    question: "20. «Мектептің алды» тіркесінде көмекші есім қайсы?",
                    options: [
                        "А) Мектептің",
                        "Ә) Алды",
                        "Б) Мектеп",
                        "В) Сырты"
                    ],
                    correct: 1
                },
                {
                    question: "21. «Дүкеннің қасы» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Дүкеннің",
                        "Ә) Қасы",
                        "Б) Дүкен",
                        "В) Жаны"
                    ],
                    correct: 1
                },
                {
                    question: "22. «Үйдің жаны» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Үйдің",
                        "Ә) Жаны",
                        "Б) Үй",
                        "В) Түбі"
                    ],
                    correct: 1
                },
                {
                    question: "23. «Ауылдың маңы» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Ауылдың",
                        "Ә) Маңы",
                        "Б) Ауыл",
                        "В) Қасы"
                    ],
                    correct: 1
                },
                {
                    question: "24. «Ыдыстың түбі» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Ыдыстың",
                        "Ә) Түбі",
                        "Б) Ыдыс",
                        "В) Асты"
                    ],
                    correct: 1
                },
                {
                    question: "25. «Көшенің арасы» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Көшенің",
                        "Ә) Арасы",
                        "Б) Көше",
                        "В) Іші"
                    ],
                    correct: 1
                },
                {
                    question: "26. «Бөлменің іші» тіркесіндегі көмекші есім:",
                    options: [
                        "А) Бөлменің",
                        "Ә) Іші",
                        "Б) Бөлме",
                        "В) Жаны"
                    ],
                    correct: 1
                },
                {
                    question: "27. Көмекші есімдер сөйлемде қандай қызмет атқара алады?",
                    options: [
                        "А) Тек бастауыш болады",
                        "Ә) Зат есім сияқты түрленіп, түрлі сөйлем мүшесі болады",
                        "Б) Тек баяндауыш болады",
                        "В) Тек анықтауыш болады"
                    ],
                    correct: 1
                },
                {
                    question: "28. «Ауылдың жанында бір қора мал жайылып жүр» сөйлемінде «Ауылдың жанында» қай мүше?",
                    options: [
                        "А) Бастауыш",
                        "Ә) Толықтауыш",
                        "Б) Пысықтауыш",
                        "В) Анықтауыш"
                    ],
                    correct: 2
                },
                {
                    question: "29. Көмекші есімдер қандай сөз табымен байланысады?",
                    options: [
                        "А) Етістік",
                        "Ә) Сын есім",
                        "Б) Есім сөздермен",
                        "В) Үстеумен"
                    ],
                    correct: 2
                },
                {
                    question: "30. Зат есімнің сөйлемдегі ең жиі кездесетін қызметі:",
                    options: [
                        "А) Анықтауыш",
                        "Ә) Пысықтауыш",
                        "Б) Бастауыш пен толықтауыш",
                        "В) Баяндауыш"
                    ],
                    correct: 2
                }
            ];
            
            // Музыканы басқару
            playMusicBtn.addEventListener('click', function() {
                backgroundMusic.play();
            });
            
            pauseMusicBtn.addEventListener('click', function() {
                backgroundMusic.pause();
            });
            
            // Оюларға іс-әрекеттерді қосу
            oyuElements.forEach(oyu => {
                oyu.addEventListener('click', function() {
                    showRandomQuestion();
                });
            });
            
            // Сұрақты жабу
            closeQuestionBtn.addEventListener('click', function() {
                closeQuestionModal();
            });
            
            // Қайта бастау түймесі
            restartBtn.addEventListener('click', function() {
                resetGame();
            });
            
            // Кездейсоқ сұрақты көрсету
            function showRandomQuestion() {
                if (usedQuestions.length === questions.length) {
                    usedQuestions = [];
                }
                
                let randomIndex;
                do {
                    randomIndex = Math.floor(Math.random() * questions.length);
                } while (usedQuestions.includes(randomIndex));
                
                usedQuestions.push(randomIndex);
                currentQuestionIndex = randomIndex;
                
                // Сұрақты көрсету
                displayQuestion(currentQuestionIndex);
                
                // Модалды терезесін ашу
                questionModal.classList.add('active');
                
                // Таймерді бастау
                startTimer();
            }
            
            // Сұрақ модалды терезесін жабу
            function closeQuestionModal() {
                clearInterval(timer);
                questionModal.classList.remove('active');
            }
            
            // Сұрақты көрсету
            function displayQuestion(index) {
                const question = questions[index];
                questionText.textContent = question.question;
                
                // Нұсқаларды тазалау
                optionsContainer.innerHTML = '';
                
                // Нұсқаларды қосу
                question.options.forEach((option, i) => {
                    const optionElement = document.createElement('div');
                    optionElement.className = 'option';
                    optionElement.textContent = option;
                    optionElement.dataset.index = i;
                    
                    optionElement.addEventListener('click', function() {
                        checkAnswer(parseInt(this.dataset.index));
                    });
                    
                    optionsContainer.appendChild(optionElement);
                });
                
                // Нәтиже жасырын
                resultElement.style.display = 'none';
            }
            
            // Жауапты тексеру
            function checkAnswer(selectedIndex) {
                clearInterval(timer);
                
                const question = questions[currentQuestionIndex];
                const isCorrect = selectedIndex === question.correct;
                
                // Барлық нұсқаларды өшіріп қою
                const allOptions = optionsContainer.querySelectorAll('.option');
                allOptions.forEach(option => {
                    option.style.pointerEvents = 'none';
                });
                
                // Дұрыс жауапты жасыл етіп белгілеу
                allOptions[question.correct].classList.add('correct');
                
                if (isCorrect) {
                    score += 10;
                    resultElement.textContent = 'Дұрыс! +10 ұпай';
                    resultElement.className = 'result correct-result';
                } else {
                    // Қате жауапты қызыл етіп белгілеу
                    allOptions[selectedIndex].classList.add('incorrect');
                    
                    resultElement.textContent = `Қате! Дұрыс жауап: ${question.options[question.correct]}`;
                    resultElement.className = 'result incorrect-result';
                }
                
                scoreElement.textContent = score;
                resultElement.style.display = 'block';
                
                // Келесі сұраққа өту үшін күту
                setTimeout(() => {
                    closeQuestionModal();
                }, 3000);
            }
            
            // Таймерді бастау
            function startTimer() {
                timeLeft = 10;
                timerElement.textContent = `${timeLeft} секунд қалды`;
                
                clearInterval(timer);
                timer = setInterval(() => {
                    timeLeft--;
                    timerElement.textContent = `${timeLeft} секунд қалды`;
                    
                    if (timeLeft <= 0) {
                        clearInterval(timer);
                        const question = questions[currentQuestionIndex];
                        
                        // Дұрыс жауапты көрсету
                        const allOptions = optionsContainer.querySelectorAll('.option');
                        allOptions.forEach(option => {
                            option.style.pointerEvents = 'none';
                        });
                        allOptions[question.correct].classList.add('correct');
                        
                        resultElement.textContent = `Уақыт бітті! Дұрыс жауап: ${question.options[question.correct]}`;
                        resultElement.className = 'result incorrect-result';
                        resultElement.style.display = 'block';
                        
                        // Келесі сұраққа өту үшін күту
                        setTimeout(() => {
                            closeQuestionModal();
                        }, 3000);
                    }
                }, 1000);
            }
            
            // Ойынды қалпына келтіру
            function resetGame() {
                score = 0;
                usedQuestions = [];
                scoreElement.textContent = score;
                closeQuestionModal();
                clearInterval(timer);
            }
        });
    </script>
</body>
</html>
