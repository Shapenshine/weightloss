<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shape N Shine - Achieve Your Best Self</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
            color: #334155; /* Darker text */
            line-height: 1.6;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 1.5rem; /* px-6 py-8 */
        }
        .section-title {
            font-size: 2.25rem; /* text-4xl */
            font-weight: 700;
            color: #1a202c; /* text-gray-900 */
            margin-bottom: 1.5rem; /* mb-6 */
            text-align: center;
        }
        .card {
            background-color: #ffffff;
            border-radius: 1rem; /* rounded-xl */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* shadow-xl */
            padding: 2rem; /* p-8 */
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .whatsapp-button {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: #25D366; /* WhatsApp green */
            color: white;
            padding: 12px 25px;
            border-radius: 9999px; /* Fully rounded */
            font-weight: 600;
            font-size: 1.125rem; /* text-lg */
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 10px rgba(37, 211, 102, 0.4);
            border: none;
            outline: none;
        }
        .whatsapp-button:hover {
            background-color: #1DA851; /* Darker green on hover */
            transform: translateY(-2px);
        }
        .whatsapp-button:active {
            transform: translateY(0);
            box-shadow: 0 2px 5px rgba(37, 211, 102, 0.4);
        }
        .icon {
            margin-right: 8px;
            width: 24px;
            height: 24px;
            fill: currentColor;
        }
        .quote-section {
            background-color: #e0f2f7; /* Light blue background for quote */
            border-left: 8px solid #00bcd4; /* Cyan border */
            padding: 2rem;
            border-radius: 0.75rem; /* rounded-lg */
            margin: 3rem auto; /* mt-12 mb-12 */
            max-width: 800px;
        }
        .quote-text {
            font-size: 1.5rem; /* text-2xl */
            font-style: italic;
            text-align: center;
            color: #00838f; /* Darker cyan text */
            margin-bottom: 1rem;
        }
        .quote-author {
            font-size: 1.125rem; /* text-lg */
            font-weight: 600;
            text-align: right;
            color: #00838f;
        }

        /* Responsive adjustments */
        @media (max-width: 640px) {
            .section-title {
                font-size: 1.75rem; /* text-3xl on small screens */
            }
            .card {
                padding: 1.5rem; /* p-6 on small screens */
            }
            .grid-cols-2 {
                grid-template-columns: 1fr; /* Stack columns on small screens */
            }
            .quote-text {
                font-size: 1.25rem; /* text-xl on small screens */
            }
        }
    </style>
</head>
<body class="antialiased">

        <header class="bg-gradient-to-r from-emerald-500 to-teal-600 text-white py-16 px-6 text-center rounded-b-3xl shadow-lg">
        <h1 class="text-5xl md:text-6xl font-bold mb-4">Shape N Shine</h1>
        <p class="text-xl md:text-2xl font-light mb-8">Unleash Your Potential. Transform Your Life.</p>
        <a href="https://wa.me/919111107790?text=Hello%2C%20I%20would%20like%20to%20know%20more%20about%20your%20services%21" target="_blank" class="whatsapp-button">
            <svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.0007 2C6.48622 2 2.00073 6.48549 2.00073 12.0007C2.00073 14.1956 2.69532 16.2163 3.86795 17.8864L2.00073 22.0007L6.23075 20.1293C7.80806 21.0506 9.80093 22.0007 12.0007 22.0007H12.0039C17.5147 22.0007 22.0007 17.5147 22.0007 12.0007C22.0007 6.48549 17.5147 2 12.0007 2ZM17.1506 15.109C17.0673 15.2891 16.9208 15.3409 16.7118 15.3927C16.5126 15.4445 15.0116 16.0378 14.7337 16.1413C14.4558 16.2449 14.2468 16.2758 14.0378 16.214C13.8288 16.1523 13.2081 15.9329 12.5186 15.3262C11.7584 14.6548 11.2304 14.1834 11.054 14.049C10.8776 13.9146 10.7412 13.8837 10.5322 13.9455C10.3232 14.0072 9.70255 14.2266 9.08186 14.5057C8.46117 14.7847 7.93322 14.8883 7.8286 14.9295C7.72397 14.9707 7.61935 14.9707 7.45269 14.9089C7.28604 14.8472 6.78498 14.3005 6.35712 13.7339C5.93006 13.1664 5.56711 12.5049 5.56711 11.8335C5.56711 11.7081 5.59798 11.5836 5.65974 11.3746C5.72151 11.1656 6.01211 10.513 6.17877 10.1471C6.34542 9.78122 6.42875 9.64677 6.53338 9.6159C6.63801 9.58502 6.75333 9.58502 6.87895 9.58502C6.98357 9.58502 7.0882 9.58502 7.18212 9.57466C7.29744 9.56429 7.46409 9.52316 7.66323 10.0306C7.8722 10.5283 8.35824 11.7001 8.35824 11.7001C8.35824 11.7001 8.44157 11.8993 8.32625 12.0437C8.21094 12.1882 8.0118 12.3873 7.74378 12.6865C7.47575 12.9856 7.21782 13.2536 7.48585 13.7153C7.75387 14.1771 8.78923 15.0117 9.81439 15.9126C10.9767 16.9489 11.868 17.2944 12.1558 17.4389C12.4437 17.5833 12.6329 17.573 12.822 17.4897C13.0112 17.4064 13.6212 17.0706 13.8892 16.7047C14.1572 16.3388 14.3336 16.1497 14.4382 16.088C14.5428 16.0262 14.6582 15.9953 14.8145 16.0571C15.1147 16.1606 16.4806 16.7329 16.8041 16.8872C17.1276 17.0416 17.2741 17.0934 17.336 17.0625C17.407 17.0317 17.407 16.5398 17.3552 16.2619C17.3034 15.984 17.2095 15.1834 17.1506 15.109Z" fill="currentColor"/>
            </svg>
            Chat with Us on WhatsApp
        </a>
    </header>

        <section class="container py-12">
        <div class="quote-section">
            <p class="quote-text">
                "The only bad workout is the one that didn't happen.
                <br>Your body can stand almost anything. It's your mind that you have to convince."
            </p>
            <p class="quote-author">- Anita Gupta</p>
        </div>
    </section>

        <section class="container py-16">
        <h2 class="section-title">About Shape N Shine</h2>
        <div class="card">
            <p class="text-lg text-center mb-4">
                At Shape N Shine, we believe that true well-being comes from a balanced approach to fitness, nutrition, and mental health. Our dedicated team is committed to guiding you on your journey to a healthier, happier, and more confident you.
            </p>
            <p class="text-lg text-center">
                Whether your goal is weight loss, muscle gain, improved energy, or simply a more active lifestyle, we provide personalized plans and expert support to help you achieve lasting results.
            </p>
        </div>
    </section>

        <section class="container py-16 bg-blue-50 rounded-xl shadow-inner">
        <h2 class="section-title">Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="card text-center">
                <img src="https://media.giphy.com/media/l4FGJd4vU5L7K1a76/giphy.gif" alt="Personalized Fitness Coaching GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Personalized Fitness Coaching</h3>
                <p class="text-gray-700">Customized workout plans tailored to your goals, fitness level, and preferences, delivered by certified trainers.</p>
            </div>
            <div class="card text-center">
                <img src="https://media.giphy.com/media/3o7TKEQfS5h2mQ63aE/giphy.gif" alt="Healthy Eating GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Expert Nutrition Guidance</h3>
                <p class="text-gray-700">Sustainable meal plans and dietary advice to fuel your body, optimize health, and support your fitness journey.</p>
            </div>
            <div class="card text-center">
                <img src="https://media.giphy.com/media/l0HlC2w1s54F2M0YE/giphy.gif" alt="Strength Training GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Strength & Conditioning</h3>
                <p class="text-gray-700">Build muscle, boost metabolism, and enhance your overall strength with our targeted programs.</p>
            </div>
            <div class="card text-center">
                <img src="https://media.giphy.com/media/l4FGJd4vU5L7K1a76/giphy.gif" alt="Mindfulness & Wellness GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Holistic Wellness Coaching</h3>
                <p class="text-gray-700">Guidance on stress management, sleep optimization, and mindfulness for complete well-being.</p>
            </div>
            <div class="card text-center">
                <img src="https://media.giphy.com/media/3o7TKSd0P910x4tFug/giphy.gif" alt="Progress Tracking GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Continuous Progress Tracking</h3>
                <p class="text-gray-700">Regular assessments and adjustments to your plan to ensure you're always moving forward and achieving your goals.</p>
            </div>
            <div class="card text-center">
                <img src="https://media.giphy.com/media/l4FGJd4vU5L7K1a76/giphy.gif" alt="Community Support GIF" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
                <h3 class="text-xl font-semibold mb-2">Supportive Community</h3>
                <p class="text-gray-700">Join a vibrant community of like-minded individuals who support and motivate each other.</p>
            </div>
        </div>
    </section>

        <section class="container py-16">
        <h2 class="section-title">What Our Clients Say</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="card">
                <p class="text-lg italic text-gray-700 mb-4">"Shape N Shine has transformed my life! The personalized attention and supportive trainers made all the difference. I've never felt better."</p>
                <p class="font-semibold text-right">- Aarti Sharma</p>
            </div>
            <div class="card">
                <p class="text-lg italic text-gray-700 mb-4">"The nutrition guidance helped me understand healthy eating without restrictive diets. I've lost weight and gained so much energy. Highly recommend!"</p>
            </div>
        </div>
    </section>

        <section class="container py-16 bg-blue-50 rounded-xl shadow-inner text-center">
        <h2 class="section-title">Get in Touch</h2>
        <p class="text-lg mb-8">Ready to start your transformation? Contact us today!</p>
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
            <a href="https://wa.me/919111107790?text=Hello%2C%20I%20would%20like%20to%20know%20more%20about%20your%20services%21" target="_blank" class="whatsapp-button">
                <svg class="icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12.0007 2C6.48622 2 2.00073 6.48549 2.00073 12.0007C2.00073 14.1956 2.69532 16.2163 3.86795 17.8864L2.00073 22.0007L6.23075 20.1293C7.80806 21.0506 9.80093 22.0007 12.0007 22.0007H12.0039C17.5147 22.0007 22.0007 17.5147 22.0007 12.0007C22.0007 6.48549 17.5147 2 12.0007 2ZM17.1506 15.109C17.0673 15.2891 16.9208 15.3409 16.7118 15.3927C16.5126 15.4445 15.0116 16.0378 14.7337 16.1413C14.4558 16.2449 14.2468 16.2758 14.0378 16.214C13.8288 16.1523 13.2081 15.9329 12.5186 15.3262C11.7584 14.6548 11.2304 14.1834 11.054 14.049C10.8776 13.9146 10.7412 13.8837 10.5322 13.9455C10.3232 14.0072 9.70255 14.2266 9.08186 14.5057C8.46117 14.7847 7.93322 14.8883 7.8286 14.9295C7.72397 14.9707 7.61935 14.9707 7.45269 14.9089C7.28604 14.8472 6.78498 14.3005 6.35712 13.7339C5.93006 13.1664 5.56711 12.5049 5.56711 11.8335C5.56711 11.7081 5.59798 11.5836 5.65974 11.3746C5.72151 11.1656 6.01211 10.513 6.17877 10.1471C6.34542 9.78122 6.42875 9.64677 6.53338 9.6159C6.63801 9.58502 6.75333 9.58502 6.87895 9.58502C6.98357 9.58502 7.0882 9.58502 7.18212 9.57466C7.29744 9.56429 7.46409 9.52316 7.66323 10.0306C7.8722 10.5283 8.35824 11.7001 8.35824 11.7001C8.35824 11.7001 8.44157 11.8993 8.32625 12.0437C8.21094 12.1882 8.0118 12.3873 7.74378 12.6865C7.47575 12.9856 7.21782 13.2536 7.48585 13.7153C7.75387 14.1771 8.78923 15.0117 9.81439 15.9126C10.9767 16.9489 11.868 17.2944 12.1558 17.4389C12.4437 17.5833 12.6329 17.573 12.822 17.4897C13.0112 17.4064 13.6212 17.0706 13.8892 16.7047C14.1572 16.3388 14.3336 16.1497 14.4382 16.088C14.5428 16.0262 14.6582 15.9953 14.8145 16.0571C15.1147 16.1606 16.4806 16.7329 16.8041 16.8872C17.1276 17.0416 17.2741 17.0934 17.336 17.0625C17.407 17.0317 17.407 16.5398 17.3552 16.2619C17.3034 15.984 17.2095 15.1834 17.1506 15.109Z" fill="currentColor"/>
                </svg>
                Chat with Us on WhatsApp
            </a>
            <div class="text-gray-700 text-lg">
                <p>Email: info@shapenshine.com</p>
                <p>Phone: +91 9111107790</p>
                <p>Address: Devendra Nagar, Raipur</p>
            </div>
        </div>
    </section>

        <footer class="bg-gray-800 text-white text-center py-8 px-6 rounded-t-3xl mt-10">
        <p>&copy; 2024 Shape N Shine. All rights reserved.</p>
    </footer>

</body>
</html>
