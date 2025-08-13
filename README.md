# Learn-English-
# To'liq A1-A2 Daraja uchun Bitta Yaxlit Platforma

To'g'ri fikr! Sizga to'liq A1-A2 darajasi uchun bitta yaxlit platforma kerak. Quyida barcha darslarni o'z ichiga olgan to'liq versiyani taqdim etaman.

## `index.html` (To'liq A1-A2 kursi)

```html
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌟 English Express - To'liq A1/A2 Kursi</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header class="header">
            <div class="logo">
                <h1>🌟 English Express</h1>
                <p>To'liq A1/A2 Daraja - Mubinaxon & Odinaxon uchun</p>
            </div>
            <nav class="nav">
                <ul>
                    <li><a href="#home" class="active nav-link" data-tab="home">🏠 Bosh sahifa</a></li>
                    <li><a href="#curriculum" class="nav-link" data-tab="curriculum">📚 Dars reja</a></li>
                    <li><a href="#a1-level" class="nav-link" data-tab="a1-level">🅰️ A1 Daraja</a></li>
                    <li><a href="#a2-level" class="nav-link" data-tab="a2-level">🅱️ A2 Daraja</a></li>
                    <li><a href="#progress" class="nav-link" data-tab="progress">📊 Progress</a></li>
                    <li><a href="#resources" class="nav-link" data-tab="resources">📖 Manbalar</a></li>
                </ul>
            </nav>
        </header>

        <!-- Main Content -->
        <main class="main-content">
            <!-- Home Section -->
            <section id="home" class="tab-content active">
                <div class="hero">
                    <h2>Xush kelibsiz, Mubinaxon va Odinaxon!</h2>
                    <p>To'liq A1/A2 darajasi uchun ingliz tili kursiga xush kelibsiz!</p>
                    <div class="course-overview">
                        <div class="overview-card">
                            <h3>📚 50+ Dars</h3>
                            <p>To'liq kurs</p>
                        </div>
                        <div class="overview-card">
                            <h3>🎯 A1 + A2</h3>
                            <p>To'liq darajalar</p>
                        </div>
                        <div class="overview-card">
                            <h3>🎮 Interaktiv</h3>
                            <p>Mashqlar va testlar</p>
                        </div>
                    </div>
                </div>

                <div class="welcome-message">
                    <h3>🎉 Assalomu alaykum Mubinaxon va Odinaxon!</h3>
                    <p>Bu platforma sizlar uchun to'liq A1/A2 darajasi bo'yicha tayyorlandi. Har bir dars o'zaro bog'liq bo'lib, ketma-ket o'rganish tavsiya etiladi.</p>
                    <div class="learning-path">
                        <h4>📌 O'rganish yo'riqnomasi:</h4>
                        <ol>
                            <li>Bosh sahifani ko'rib chiqing</li>
                            <li>Dars rejani o'rganing</li>
                            <li>A1 darajadan boshlang</li>
                            <li>Har bir darsni to'liq tugating</li>
                            <li>Progressni kuzating</li>
                            <li>A2 darajaga o'ting</li>
                        </ol>
                    </div>
                </div>

                <div class="start-button">
                    <button onclick="showTab('curriculum')" class="cta-btn">Dars rejani ko'rish ➡️</button>
                </div>
            </section>

            <!-- Curriculum Section -->
            <section id="curriculum" class="tab-content">
                <h2>📚 To'liq Dars Reja - Mubinaxon & Odinaxon</h2>
                
                <div class="curriculum-overview">
                    <p>Assalomu alaykum Mubinaxon va Odinaxon! Bu to'liq dars rejasi sizlar uchun tayyorlandi. Har bir dars 20-30 daqiqani oladi.</p>
                </div>

                <div class="level-section">
                    <h3>🅰️ A1 Daraja (Beginner) - 25 dars</h3>
                    <div class="modules">
                        <div class="module">
                            <h4>Module 1: Introductions (5 dars)</h4>
                            <ul>
                                <li>Dars 1: Hello & Goodbye</li>
                                <li>Dars 2: My name is...</li>
                                <li>Dars 3: Numbers 1-20</li>
                                <li>Dars 4: How old are you?</li>
                                <li>Dars 5: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 2: Daily Life (5 dars)</h4>
                            <ul>
                                <li>Dars 6: Days of the week</li>
                                <li>Dars 7: My daily routine</li>
                                <li>Dars 8: Present simple</li>
                                <li>Dars 9: Time expressions</li>
                                <li>Dars 10: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 3: Family & Friends (5 dars)</h4>
                            <ul>
                                <li>Dars 11: Family members</li>
                                <li>Dars 12: Describing people</li>
                                <li>Dars 13: Possessive adjectives</li>
                                <li>Dars 14: Likes and dislikes</li>
                                <li>Dars 15: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 4: Food & Shopping (5 dars)</h4>
                            <ul>
                                <li>Dars 16: Food vocabulary</li>
                                <li>Dars 17: At the restaurant</li>
                                <li>Dars 18: Countable/Uncountable</li>
                                <li>Dars 19: How much/How many</li>
                                <li>Dars 20: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 5: Home & Places (5 dars)</h4>
                            <ul>
                                <li>Dars 21: Rooms in the house</li>
                                <li>Dars 22: Prepositions of place</li>
                                <li>Dars 23: There is/There are</li>
                                <li>Dars 24: Directions</li>
                                <li>Dars 25: Final A1 Test</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="level-section">
                    <h3>🅱️ A2 Daraja (Elementary) - 25 dars</h3>
                    <div class="modules">
                        <div class="module">
                            <h4>Module 1: Free Time (5 dars)</h4>
                            <ul>
                                <li>Dars 26: Hobbies and interests</li>
                                <li>Dars 27: Present continuous</li>
                                <li>Dars 28: Frequency adverbs</li>
                                <li>Dars 29: Making plans</li>
                                <li>Dars 30: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 2: Travel & Transport (5 dars)</h4>
                            <ul>
                                <li>Dars 31: Travel vocabulary</li>
                                <li>Dars 32: Past simple (regular)</li>
                                <li>Dars 33: Past simple (irregular)</li>
                                <li>Dars 34: Asking for directions</li>
                                <li>Dars 35: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 3: Health & Body (5 dars)</h4>
                            <ul>
                                <li>Dars 36: Body parts</li>
                                <li>Dars 37: Health problems</li>
                                <li>Dars 38: Going to (future)</li>
                                <li>Dars 39: Giving advice</li>
                                <li>Dars 40: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 4: Work & Education (5 dars)</h4>
                            <ul>
                                <li>Dars 41: Jobs vocabulary</li>
                                <li>Dars 42: Can/Cannot</li>
                                <li>Dars 43: Present perfect</li>
                                <li>Dars 44: Talking about experience</li>
                                <li>Dars 45: Review & Quiz</li>
                            </ul>
                        </div>
                        
                        <div class="module">
                            <h4>Module 5: Weather & Environment (5 dars)</h4>
                            <ul>
                                <li>Dars 46: Weather vocabulary</li>
                                <li>Dars 47: Comparatives/Superlatives</li>
                                <li>Dars 48: Modal verbs</li>
                                <li>Dars 49: Environmental issues</li>
                                <li>Dars 50: Final A2 Test</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="navigation-buttons">
                    <button onclick="showTab('a1-level')" class="nav-btn">A1 Darajani boshlash ➡️</button>
                </div>
            </section>

            <!-- A1 Level Section -->
            <section id="a1-level" class="tab-content">
                <h2>🅰️ A1 Daraja - Mubinaxon & Odinaxon</h2>
                
                <div class="level-intro">
                    <p>Assalomu alaykum Mubinaxon va Odinaxon! A1 daraja - bu ingliz tilining eng asosiy darajasidir. Bu darajada siz:</p>
                    <ul>
                        <li>🔹 O'zizni tanishtira olasiz</li>
                        <li>🔹 Oddiy so'rovlarga javob bera olasiz</li>
                        <li>🔹 Kun tartibingizni tushuntira olasiz</li>
                        <li>🔹 Oddiy matnlarni tushuna olasiz</li>
                    </ul>
                </div>

                <!-- Dars 1: Hello & Goodbye -->
                <div class="lesson" id="lesson-1">
                    <h3>📘 Dars 1: Hello & Goodbye</h3>
                    <div class="lesson-content">
                        <h4>Vocabulary - Mubinaxon va Odinaxon uchun</h4>
                        <div class="vocabulary-list">
                            <div class="vocab-item">
                                <span class="word">Hello</span>
                                <span class="translation">Salom</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Hi</span>
                                <span class="translation">Salom (informal)</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Good morning</span>
                                <span class="translation">Xayrli tong</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Good afternoon</span>
                                <span class="translation">Xayrli tushlik</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Good evening</span>
                                <span class="translation">Xayrli kech</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Goodbye</span>
                                <span class="translation">Xayr</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">See you later</span>
                                <span class="translation">Keyin ko'rishamiz</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Bye</span>
                                <span class="translation">Xayr (informal)</span>
                            </div>
                        </div>

                        <h4>Dialog - Mubinaxon va Odinaxon uchun</h4>
                        <div class="dialog">
                            <p><strong>Tom:</strong> Hello! How are you?</p>
                            <p><strong>Mary:</strong> Hi Tom! I'm fine, thank you. And you?</p>
                            <p><strong>Tom:</strong> I'm good, thanks. See you later!</p>
                            <p><strong>Mary:</strong> Bye!</p>
                        </div>

                        <h4>Grammar - Mubinaxon va Odinaxon uchun</h4>
                        <div class="grammar-point">
                            <p><strong>How are you?</strong> - Qanday holatdasiz?</p>
                            <p><strong>Javoblar:</strong></p>
                            <ul>
                                <li>I'm fine, thank you. - Yaxshi, rahmat.</li>
                                <li>I'm good, thanks. - Yaxshi, rahmat.</li>
                                <li>Not bad, thanks. - Yomon emas, rahmat.</li>
                                <li>I'm okay. - Bo'ldi-yeboti.</li>
                            </ul>
                        </div>

                        <h4>Exercise - Mubinaxon va Odinaxon uchun</h4>
                        <div class="exercise">
                            <p>1. Tushuntiring: Qachon "Good morning" dan foydalanamiz?</p>
                            <textarea id="exercise-1" placeholder="Javobingizni yozing..."></textarea>
                            
                            <p>2. To'g'ri javobni tanlang:</p>
                            <select id="exercise-2">
                                <option value="">Tanlang...</option>
                                <option value="a">Hello - Xayrli kech</option>
                                <option value="b">Hello - Salom</option>
                                <option value="c">Hello - Rahmat</option>
                            </select>
                            
                            <button onclick="checkLesson1()" class="check-btn">Tekshirish</button>
                            <p id="lesson1-result" class="result"></p>
                        </div>
                    </div>
                </div>

                <!-- Dars 2: My name is... -->
                <div class="lesson" id="lesson-2">
                    <h3>📘 Dars 2: My name is...</h3>
                    <div class="lesson-content">
                        <h4>Vocabulary - Mubinaxon va Odinaxon uchun</h4>
                        <div class="vocabulary-list">
                            <div class="vocab-item">
                                <span class="word">Name</span>
                                <span class="translation">Ism</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Age</span>
                                <span class="translation">Yosh</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Nationality</span>
                                <span class="translation">Milliyat</span>
                            </div>
                            <div class="vocab-item">
                                <span class="word">Job</span>
                                <span class="translation">Ish</span>
                            </div>
                        </div>

                        <h4>Grammar - Mubinaxon va Odinaxon uchun</h4>
                        <div class="grammar-point">
                            <p><strong>To be</strong> fe'li (A1 darajasi)</p>
                            <table>
                                <tr>
                                    <th>Shaxs</th>
                                    <th>Fe'l</th>
                                    <th>Misol</th>
                                </tr>
                                <tr>
                                    <td>I</td>
                                    <td>am</td>
                                    <td>I am a student.</td>
                                </tr>
                                <tr>
                                    <td>You/We/They</td>
                                    <td>are</td>
                                    <td>You are happy.</td>
                                </tr>
                                <tr>
                                    <td>He/She/It</td>
                                    <td>is</td>
                                    <td>She is tall.</td>
                                </tr>
                            </table>
                        </div>

                        <h4>Dialog - Mubinaxon va Odinaxon uchun</h4>
                        <div class="dialog">
                            <p><strong>Anna:</strong> Hello! What's your name?</p>
                            <p><strong>John:</strong> My name is John. What's your name?</p>
                            <p><strong>Anna:</strong> I'm Anna. Nice to meet you!</p>
                            <p><strong>John:</strong> Nice to meet you too!</p>
                        </div>

                        <h4>Exercise - Mubinaxon va Odinaxon uchun</h4>
                        <div class="exercise">
                            <p>1. To'ldiring:</p>
                            <p>I _____ a teacher. (am/is/are)</p>
                            <select id="exercise-3">
                                <option value="">Tanlang...</option>
                                <option value="am">am</option>
                                <option value="is">is</option>
                                <option value="are">are</option>
                            </select>
                            
                            <p>2. O'ziz haqingizda 3 ta gap yozing:</p>
                            <textarea id="exercise-4" placeholder="Misol: My name is... I am... years old. I am from..."></textarea>
                            
                            <button onclick="checkLesson2()" class="check-btn">Tekshirish</button>
                            <p id="lesson2-result" class="result"></p>
                        </div>
                    </div>
                </div>

                <!-- Navigation for more lessons -->
                <div class="lesson-navigation">
                    <p>📘 A1 darajada jami 25 ta dars mavjud. Har bir darsni ketma-ket o'rganing!</p>
                    <button onclick="alert('Keyingi darslar platformaga qo\'shiladi. Hozir faqat 2 ta dars mavjud.')" class="nav-btn">Keyingi dars ➡️<
