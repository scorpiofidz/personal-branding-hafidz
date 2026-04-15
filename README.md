<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hafidz Maulana Yusuf | Executive Branding Portfolio</title>
    <title>Hafidz Maulana Yusuf | Executive Branding Portofolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700&family=Montserrat:wght@300;400;700;900&display=swap" rel="stylesheet">
@@ -80,78 +80,6 @@
            filter: blur(10px);
            opacity: 0.5;
        }
        :root {
    --gold: #c5a059;
    --dark-black: #0a0a0a;
    --mu-red: #da291c;
    --text-gray: #a0a0a0;
}

.section-container {
    padding: 100px 10%;
    background-color: var(--dark-black);
    color: white;
    font-family: 'Montserrat', sans-serif;
}

.gold-text {
    color: var(--gold);
    font-size: 2.5rem;
    letter-spacing: 3px;
    margin-bottom: 30px;
    text-transform: uppercase;
}

/* Identity Cards */
.identity-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 40px;
}

.identity-card {
    border: 1px solid var(--gold);
    padding: 30px;
    transition: 0.4s;
}

.identity-card:hover {
    background-color: var(--gold);
    color: black;
}

/* Portfolio Hover Effect */
.portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 15px;
}

.portfolio-item {
    position: relative;
    overflow: hidden;
    height: 400px;
}

.item-overlay {
    position: absolute;
    bottom: -100%;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0, 0.8);
    display: flex;
    align-items: center;
    justify-content: center;
    transition: 0.5s;
    border-top: 3px solid var(--mu-red);
}

.portfolio-item:hover .item-overlay {
    bottom: 0;
}

    </style>
</head>
<body>
@@ -166,55 +94,6 @@
            <a href="#" class="hover:text-mu-gold transition">Portofolio</a>
        </div>
    </nav>
<!-- IDENTITY SECTION -->

    <div class="content-wrapper">
        <h2 class="gold-text">THE LEGACY</h2>
        <p class="sub-text">Hafidz Maulana Yusuf adalah perpaduan antara presisi teknis dan visi strategis. Layaknya 'The Red Devils', saya membangun identitas di atas pondasi dedikasi dan mentalitas pemenang.</p>
        
            
                <h3>Visi</h3>
                <p>Menjadi pionir dalam transformasi digital yang elegan.</p>
            </div>
            
                <h3>Misi</h3>
                <p>Menerapkan strategi kelas dunia untuk solusi digital yang abadi.</p>
            </div>
        </div>
    </div>
</section>

<!-- BRANDING SECTION -->
<section id="branding" class="section-container dark-bg">
    <div class="content-wrapper">
        <h2 class="gold-text">STRATEGIC BRANDING</h2>
        <div class="branding-feature">
            <div class="feature-item">
                <span class="icon">⚽</span>
                <h4>Theatre of Dreams Strategy</h4>
                <p>Membangun platform yang bukan sekadar fungsional, tapi inspirasional.</p>
            </div>
            <!-- Tambahkan item lain sesuai isi Canva -->
        </div>
    </div>
</section>

<!-- PORTFOLIO SECTION -->
<section id="portfolio" class="section-container">
    <div class="content-wrapper">
        <h2 class="gold-text">SELECTED WORKS</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <div class="item-overlay">
                    <span>Project Name</span>
                </div>
                <img src="path-to-your-image.jpg" alt="Portfolio 1">
            </div>
            <!-- Repeat for other projects -->
        </div>
    </div>
</section>

    <section class="flex flex-col-reverse md:flex-row items-center justify-between px-10 py-12 max-w-7xl mx-auto min-h-[75vh]">
        <div class="md:w-3/5 space-y-6">
            <h4 class="text-mu-gold font-bold tracking-[0.5em] text-xs uppercase italic">The Theatre of Digital Dreams</h4>
@@ -235,5 +114,3 @@ <h1 class="text-6xl md:text-8xl font-black leading-tight">
                <div class="flex space-x-6 text-gray-500">
                    <a href="#" class="hover:text-mu-gold transition"><i class="fab fa-instagram text-xl"></i></a>
                    <a href="#" class="hover:text-mu-gold transition">
