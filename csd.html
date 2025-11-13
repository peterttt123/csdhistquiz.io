<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameQuest - Gaming Quiz Platform</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #6a5acd;
            --secondary: #ff6b6b;
            --accent: #4ecdc4;
            --dark: #292f36;
            --light: #f8f9fa;
            --success: #51cf66;
            --warning: #fcc419;
            --danger: #ff6b6b;
        }

        body {
            background: linear-gradient(135deg, #1a1a2e, #16213e);
            color: var(--light);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 900px;
            width: 100%;
            background: rgba(25, 25, 45, 0.85);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        header {
            background: rgba(15, 15, 35, 0.95);
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid var(--accent);
            position: relative;
        }

        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            margin-bottom: 10px;
        }

        .logo i {
            font-size: 2.5rem;
            color: var(--accent);
            text-shadow: 0 0 10px rgba(78, 205, 196, 0.7);
        }

        h1 {
            font-size: 2.2rem;
            background: linear-gradient(to right, var(--accent), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        .subtitle {
            color: #a0a0c0;
            font-size: 1.1rem;
            margin-top: 5px;
        }

        .main-content {
            display: flex;
            min-height: 500px;
        }

        .quiz-container {
            flex: 3;
            padding: 25px;
        }

        .theme-controls {
            flex: 1;
            background: rgba(30, 30, 50, 0.7);
            padding: 20px;
            border-left: 1px solid rgba(255, 255, 255, 0.1);
        }

        .theme-title {
            text-align: center;
            margin-bottom: 20px;
            color: var(--accent);
            font-size: 1.3rem;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .theme-option {
            margin-bottom: 15px;
        }

        .theme-option label {
            display: block;
            margin-bottom: 8px;
            color: #c0c0e0;
        }

        .theme-selector {
            width: 100%;
            padding: 10px;
            border-radius: 8px;
            background: rgba(20, 20, 40, 0.8);
            border: 1px solid var(--primary);
            color: white;
        }

        .question-container {
            background: rgba(40, 40, 60, 0.7);
            border-radius: 12px;
            padding: 25px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(106, 90, 205, 0.3);
            position: relative;
            overflow: hidden;
        }

        .question-container::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, var(--primary), var(--accent));
        }

        .question-number {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-weight: bold;
            margin-bottom: 15px;
            font-size: 0.9rem;
        }

        .question-text {
            font-size: 1.3rem;
            margin-bottom: 20px;
            line-height: 1.5;
        }

        .options-container {
            margin-top: 20px;
        }

        .option {
            background: rgba(50, 50, 70, 0.8);
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 12px;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
        }

        .option:hover {
            background: rgba(70, 70, 100, 0.8);
            transform: translateY(-2px);
            border-color: var(--accent);
        }

        .option.selected {
            background: rgba(106, 90, 205, 0.3);
            border-color: var(--primary);
        }

        .option input {
            margin-right: 12px;
        }

        .progress-container {
            margin: 25px 0;
        }

        .progress-bar {
            height: 12px;
            background: rgba(50, 50, 70, 0.8);
            border-radius: 10px;
            overflow: hidden;
            margin-bottom: 10px;
        }

        .progress {
            height: 100%;
            background: linear-gradient(90deg, var(--primary), var(--accent));
            border-radius: 10px;
            width: 33%;
            transition: width 0.5s ease;
        }

        .progress-text {
            text-align: right;
            color: #a0a0c0;
            font-size: 0.9rem;
        }

        .navigation {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        .btn {
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 1rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background: #5a4ac0;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(106, 90, 205, 0.4);
        }

        .btn-secondary {
            background: rgba(50, 50, 70, 0.8);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .btn-secondary:hover {
            background: rgba(70, 70, 100, 0.8);
            transform: translateY(-2px);
        }

        .btn-success {
            background: var(--success);
            color: white;
        }

        .btn-success:hover {
            background: #40b354;
            transform: translateY(-2px);
        }

        .score-display {
            text-align: center;
            padding: 30px;
            background: rgba(40, 40, 60, 0.7);
            border-radius: 12px;
            margin: 20px 0;
        }

        .score-title {
            font-size: 2rem;
            color: var(--accent);
            margin-bottom: 15px;
        }

        .final-score {
            font-size: 4rem;
            font-weight: bold;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin: 20px 0;
        }

        .achievement {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }

        .trophy {
            font-size: 4rem;
            color: gold;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.7);
            margin-bottom: 15px;
        }

        .results-container {
            display: none;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin-top: 20px;
        }

        .stat-card {
            background: rgba(50, 50, 70, 0.8);
            border-radius: 10px;
            padding: 15px;
            text-align: center;
        }

        .stat-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent);
        }

        .stat-label {
            color: #a0a0c0;
            font-size: 0.9rem;
        }

        .hidden {
            display: none;
        }

        .theme-preview {
            height: 100px;
            border-radius: 10px;
            margin: 15px 0;
            background-size: cover;
            background-position: center;
            border: 2px solid rgba(255, 255, 255, 0.2);
        }

        .fantasy-theme {
            background: url('https://images.unsplash.com/photo-1534423861386-85a16f5d13fd?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80');
        }

        .cyber-theme {
            background: url('https://images.unsplash.com/photo-1550745165-9bc0b252726f?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80');
        }

        .space-theme {
            background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80');
        }

        .retro-theme {
            background: url('https://images.unsplash.com/photo-1550745165-9bc0b252726f?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80');
        }

        .character {
            position: absolute;
            bottom: 10px;
            right: 15px;
            font-size: 3rem;
            opacity: 0.7;
        }

        .character-1 {
            color: #ff6b6b;
        }

        .character-2 {
            color: #4ecdc4;
        }

        .character-3 {
            color: #ffd166;
        }

        @media (max-width: 768px) {
            .main-content {
                flex-direction: column;
            }
            
            .theme-controls {
                border-left: none;
                border-top: 1px solid rgba(255, 255, 255, 0.1);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <i class="fas fa-gamepad"></i>
                <h1>GameQuest</h1>
            </div>
            <p class="subtitle">Customizable Gaming Quiz Platform</p>
        </header>

        <div class="main-content">
            <div class="quiz-container">
                <div class="progress-container">
                    <div class="progress-bar">
                        <div class="progress" id="progress-bar"></div>
                    </div>
                    <div class="progress-text">Question <span id="current-question">1</span> of <span id="total-questions">3</span></div>
                </div>

                <div class="question-container">
                    <div class="question-number">Question 1</div>
                    <div class="question-text">What is the best-selling video game of all time?</div>
                    
                    <div class="options-container">
                        <div class="option">
                            <input type="radio" name="q1" id="q1a" value="a">
                            <label for="q1a">The Legend of Zelda: Breath of the Wild</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q1" id="q1b" value="b">
                            <label for="q1b">Minecraft</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q1" id="q1c" value="c">
                            <label for="q1c">Super Mario Bros.</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q1" id="q1d" value="d">
                            <label for="q1d">Tetris</label>
                        </div>
                    </div>
                    
                    <div class="character character-1">
                        <i class="fas fa-dragon"></i>
                    </div>
                </div>

                <div class="question-container">
                    <div class="question-number">Question 2</div>
                    <div class="question-text">Which company developed the PlayStation?</div>
                    
                    <div class="options-container">
                        <div class="option">
                            <input type="radio" name="q2" id="q2a" value="a">
                            <label for="q2a">Microsoft</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q2" id="q2b" value="b">
                            <label for="q2b">Nintendo</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q2" id="q2c" value="c">
                            <label for="q2c">Sony</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q2" id="q2d" value="d">
                            <label for="q2d">Sega</label>
                        </div>
                    </div>
                    
                    <div class="character character-2">
                        <i class="fas fa-robot"></i>
                    </div>
                </div>

                <div class="question-container">
                    <div class="question-number">Question 3</div>
                    <div class="question-text">In which year was the first Super Mario Bros. game released?</div>
                    
                    <div class="options-container">
                        <div class="option">
                            <input type="radio" name="q3" id="q3a" value="a">
                            <label for="q3a">1983</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q3" id="q3b" value="b">
                            <label for="q3b">1985</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q3" id="q3c" value="c">
                            <label for="q3c">1987</label>
                        </div>
                        <div class="option">
                            <input type="radio" name="q3" id="q3d" value="d">
                            <label for="q3d">1989</label>
                        </div>
                    </div>
                    
                    <div class="character character-3">
                        <i class="fas fa-hat-wizard"></i>
                    </div>
                </div>

                <div class="navigation">
                    <button class="btn btn-secondary" id="prev-btn">
                        <i class="fas fa-arrow-left"></i> Previous
                    </button>
                    <button class="btn btn-primary" id="next-btn">
                        Next <i class="fas fa-arrow-right"></i>
                    </button>
                    <button class="btn btn-success hidden" id="submit-btn">
                        Submit Quiz <i class="fas fa-check"></i>
                    </button>
                </div>

                <div class="results-container" id="results">
                    <div class="score-display">
                        <h2 class="score-title">Quiz Completed!</h2>
                        <div class="final-score">85%</div>
                        <p>You've completed the quiz successfully</p>
                        
                        <div class="achievement">
                            <div class="trophy">
                                <i class="fas fa-trophy"></i>
                            </div>
                            <h3>Master Gamer</h3>
                            <p>You've earned the Master Gamer badge</p>
                        </div>
                        
                        <div class="stats">
                            <div class="stat-card">
                                <div class="stat-value">3</div>
                                <div class="stat-label">Questions</div>
                            </div>
                            <div class="stat-card">
                                <div class="stat-value">2.5</div>
                                <div class="stat-label">Avg. Time</div>
                            </div>
                            <div class="stat-card">
                                <div class="stat-value">85%</div>
                                <div class="stat-label">Accuracy</div>
                            </div>
                            <div class="stat-card">
                                <div class="stat-value">12s</div>
                                <div class="stat-label">Fastest Q</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="theme-controls">
                <h3 class="theme-title">Theme Customization</h3>
                
                <div class="theme-preview fantasy-theme"></div>
                
                <div class="theme-option">
                    <label for="theme-select">Select Theme:</label>
                    <select class="theme-selector" id="theme-select">
                        <option value="default">Default Gaming</option>
                        <option value="fantasy">Fantasy Adventure</option>
                        <option value="cyber">Cyberpunk</option>
                        <option value="space">Space Odyssey</option>
                        <option value="retro">Retro Pixel</option>
                    </select>
                </div>
                
                <div class="theme-option">
                    <label for="character-select">Select Character:</label>
                    <select class="theme-selector" id="character-select">
                        <option value="dragon">Dragon</option>
                        <option value="robot">Robot</option>
                        <option value="wizard">Wizard</option>
                        <option value="ninja">Ninja</option>
                        <option value="knight">Knight</option>
                    </select>
                </div>
                
                <div class="theme-option">
                    <label for="difficulty">Difficulty Level:</label>
                    <select class="theme-selector" id="difficulty">
                        <option value="easy">Easy</option>
                        <option value="medium" selected>Medium</option>
                        <option value="hard">Hard</option>
                    </select>
                </div>
                
                <div class="theme-option">
                    <label for="timer">Timer (seconds per question):</label>
                    <input type="number" class="theme-selector" id="timer" value="30" min="10" max="120">
                </div>
                
                <button class="btn btn-primary" style="width: 100%; margin-top: 20px;">
                    <i class="fas fa-sync-alt"></i> Apply Settings
                </button>
                
                <div class="theme-option" style="margin-top: 25px;">
                    <h3 style="color: var(--accent); margin-bottom: 15px;">Question Editor</h3>
                    <button class="btn btn-secondary" style="width: 100%;">
                        <i class="fas fa-plus-circle"></i> Add New Question
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Quiz state
            const quizState = {
                currentQuestion: 0,
                totalQuestions: 3,
                answers: [null, null, null]
            };
            
            // DOM elements
            const questionContainers = document.querySelectorAll('.question-container');
            const progressBar = document.getElementById('progress-bar');
            const currentQuestionEl = document.getElementById('current-question');
            const totalQuestionsEl = document.getElementById('total-questions');
            const prevBtn = document.getElementById('prev-btn');
            const nextBtn = document.getElementById('next-btn');
            const submitBtn = document.getElementById('submit-btn');
            const resultsContainer = document.getElementById('results');
            
            // Initialize quiz
            totalQuestionsEl.textContent = quizState.totalQuestions;
            updateProgress();
            showQuestion(quizState.currentQuestion);
            
            // Navigation
            prevBtn.addEventListener('click', () => {
                if (quizState.currentQuestion > 0) {
                    quizState.currentQuestion--;
                    showQuestion(quizState.currentQuestion);
                }
            });
            
            nextBtn.addEventListener('click', () => {
                if (quizState.currentQuestion < quizState.totalQuestions - 1) {
                    quizState.currentQuestion++;
                    showQuestion(quizState.currentQuestion);
                } else {
                    // Show submit button on last question
                    nextBtn.classList.add('hidden');
                    submitBtn.classList.remove('hidden');
                }
            });
            
            submitBtn.addEventListener('click', () => {
                // Show results
                document.querySelector('.quiz-container').innerHTML = '';
                document.querySelector('.quiz-container').appendChild(resultsContainer);
                resultsContainer.style.display = 'block';
            });
            
            // Option selection
            document.querySelectorAll('.option').forEach(option => {
                option.addEventListener('click', function() {
                    const radio = this.querySelector('input[type="radio"]');
                    radio.checked = true;
                    
                    // Remove selected class from siblings
                    this.parentElement.querySelectorAll('.option').forEach(opt => {
                        opt.classList.remove('selected');
                    });
                    
                    // Add selected class to clicked option
                    this.classList.add('selected');
                    
                    // Store answer
                    const questionIndex = Array.from(this.closest('.question-container').parentElement.children).indexOf(this.closest('.question-container'));
                    const answerValue = radio.value;
                    quizState.answers[questionIndex] = answerValue;
                });
            });
            
            // Update progress bar
            function updateProgress() {
                const progress = ((quizState.currentQuestion + 1) / quizState.totalQuestions) * 100;
                progressBar.style.width = `${progress}%`;
                currentQuestionEl.textContent = quizState.currentQuestion + 1;
            }
            
            // Show specific question
            function showQuestion(index) {
                questionContainers.forEach((container, i) => {
                    if (i === index) {
                        container.style.display = 'block';
                    } else {
                        container.style.display = 'none';
                    }
                });
                
                updateProgress();
                
                // Update navigation buttons
                prevBtn.disabled = index === 0;
                nextBtn.classList.remove('hidden');
                submitBtn.classList.add('hidden');
                
                // Update next button text
                if (index === quizState.totalQuestions - 1) {
                    nextBtn.innerHTML = 'Submit <i class="fas fa-arrow-right"></i>';
                } else {
                    nextBtn.innerHTML = 'Next <i class="fas fa-arrow-right"></i>';
                }
            }
            
            // Theme customization
            const themeSelect = document.getElementById('theme-select');
            const characterSelect = document.getElementById('character-select');
            const themePreview = document.querySelector('.theme-preview');
            
            themeSelect.addEventListener('change', function() {
                themePreview.className = 'theme-preview';
                themePreview.classList.add(`${this.value}-theme`);
            });
            
            characterSelect.addEventListener('change', function() {
                // In a real app, this would change the character icon
                console.log(`Character changed to: ${this.value}`);
            });
        });
    </script>
</body>
</html>
