<!DOCTYPE html>
<html lang="hy">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Readme.md</title>
    <style>
        /* Հիմնական ոճեր */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f8ff;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            padding: 20px;
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        /* Քարտերի ցանց */
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        /* Քարտի ոճեր */
        .card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
        }
        
        .card-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }
        
        .card-content {
            padding: 20px;
        }
        
        .card-title {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        
        .card-description {
            color: #666;
            margin-bottom: 15px;
            line-height: 1.5;
        }
        
        .card-date {
            color: #888;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
        }
        
        .card-date::before {
            content: "📅";
            margin-right: 8px;
        }
        
        /* Responsive design */
        /* PC/Desktop (1200px և ավելի) */
        @media (min-width: 1200px) {
            .cards-grid {
                grid-template-columns: repeat(4, 1fr);
            }
        }
        
        /* Laptop (992px - 1199px) */
        @media (min-width: 992px) and (max-width: 1199px) {
            .cards-grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }
        
        /* Notebook/Tablet Landscape (768px - 991px) */
        @media (min-width: 768px) and (max-width: 991px) {
            .cards-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            
            h1 {
                font-size: 2.2rem;
            }
        }
        
        /* Tablet Portrait/Mobile Landscape (576px - 767px) */
        @media (min-width: 576px) and (max-width: 767px) {
            .cards-grid {
                grid-template-columns: 1fr;
                max-width: 500px;
                margin: 0 auto;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
        
        /* Mobile (575px և ավելի փոքր) */
        @media (max-width: 575px) {
            .cards-grid {
                grid-template-columns: 1fr;
            }
            
            header {
                padding: 15px;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .subtitle {
                font-size: 1rem;
            }
            
            .container {
                padding: 10px;
            }
        }
        
        /* TV screens (մեծ էկրաններ) */
        @media (min-width: 1600px) {
            .container {
                max-width: 1500px;
            }
            
            .cards-grid {
                grid-template-columns: repeat(5, 1fr);
                gap: 40px;
            }
            
            h1 {
                font-size: 3rem;
            }
            
            .subtitle {
                font-size: 1.5rem;
            }
        }
        
        /* Footer */
        footer {
            text-align: center;
            margin-top: 60px;
            padding: 20px;
            color: #777;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Իմ GitHub Նախագծեր</h1>
            <p class="subtitle">Բացահայտեք իմ բոլոր նախագծերն ու ներդրումները</p>
        </header>
        
        <div class="cards-grid">
            <!-- Քարտ 1 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/6e8efb/ffffff?text=Project+1" alt="Նախագիծ 1" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">React Weather App</h2>
                    <p class="card-description">Այս նախագիծը React-ով ստեղծված եղանակի հավելված է, որն օգտագործում է OpenWeatherMap API իրական տվյալներ ստանալու համար:</p>
                    <p class="card-date">Հունվար 15, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 2 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/a777e3/ffffff?text=Project+2" alt="Նախագիծ 2" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">Node.js Blog Platform</h2>
                    <p class="card-description">Ամբողջական բլոգային հարթակ Node.js-ով, Express-ով և MongoDB-ով՝ օգտագործողների ներդրման և բովանդակության կառավարման համար:</p>
                    <p class="card-date">Մարտ 8, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 3 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/ffa5a5/ffffff?text=Project+3" alt="Նախագիծ 3" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">Python Data Analyzer</h2>
                    <p class="card-description">Python գործիք, որը վերլուծում և պատկերացնում է տվյալներ՝ օգտագործելով Pandas, NumPy և Matplotlib գրադարանները:</p>
                    <p class="card-date">Ապրիլ 22, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 4 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/7cea9c/ffffff?text=Project+4" alt="Նախագիծ 4" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">Vue.js Task Manager</h2>
                    <p class="card-description">Առաջադրանքների կառավարման հավելված Vue.js-ով, Vuex-ով և LocalStorage-ով տվյալների պահպանման համար:</p>
                    <p class="card-date">Հունիս 5, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 5 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/ffdc5e/ffffff?text=Project+5" alt="Նախագիծ 5" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">Android Fitness App</h2>
                    <p class="card-description">Android-ի ֆիտնես հավելված Kotlin-ով, որը հետևում է օգտագործողի վարժություններին և սննդակարգին:</p>
                    <p class="card-date">Օգոստոս 18, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 6 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/5ee1ff/ffffff?text=Project+6" alt="Նախագիծ 6" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">Machine Learning Model</h2>
                    <p class="card-description">Մեքենական ուսուցման մոդել, որը կանխատեսում է տուների գները՝ հիմնվելով տարբեր հատկանիշների վրա՝ օգտագործելով Scikit-learn:</p>
                    <p class="card-date">Հոկտեմբեր 3, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 7 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/ff6b6b/ffffff?text=Project+7" alt="Նախագիծ 7" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">E-commerce Website</h2>
                    <p class="card-description">Ամբողջական էլեկտրոնային առևտրի կայք HTML, CSS, JavaScript-ով և PHP-ով՝ Stripe վճարումների ինտեգրմամբ:</p>
                    <p class="card-date">Նոյեմբեր 12, 2023</p>
                </div>
            </div>
            
            <!-- Քարտ 8 -->
            <div class="card">
                <img src="https://via.placeholder.com/250x250/9d65c9/ffffff?text=Project+8" alt="Նախագիծ 8" class="card-image">
                <div class="card-content">
                    <h2 class="card-title">iOS Meditation App</h2>
                    <p class="card-description">Meditation and mindfulness app for iOS built with SwiftUI, featuring guided sessions and progress tracking.</p>
                    <p class="card-date">Դեկտեմբեր 25, 2023</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Իմ GitHub Նախագծեր. Բոլոր իրավունքները պաշտպանված են:</p>
        </footer>
    </div>
</body>
</html>
