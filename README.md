<!DOCTYPE html>
<html>
<head>
    <title>Demo Cloud Agoyikaz UNPAM</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 20px;
            background: linear-gradient(45deg, #1a237e, #283593, #303f9f, #3949ab);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: white;
            min-height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .container {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            max-width: 700px;
            width: 90%;
        }
        
        .unpam-logo {
            width: 120px;
            height: 120px;
            margin: 0 auto 20px;
            background: white;
            border-radius: 50%;
            padding: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 14px;
            color: #1a237e;
            text-align: center;
            border: 3px solid #ffd700;
        }
        
        .title {
            font-size: 2.5em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #ffd700, #ffeb3b);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .subtitle {
            font-size: 1.2em;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .info-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 15px;
            margin: 15px 0;
            border-left: 4px solid #ffd700;
            text-align: left;
        }
        
        .info-card h3 {
            margin-top: 0;
            color: #ffd700;
            border-bottom: 2px solid rgba(255, 215, 0, 0.3);
            padding-bottom: 8px;
        }
        
        .tech-badge {
            display: inline-block;
            background: rgba(255, 215, 0, 0.2);
            padding: 5px 15px;
            border-radius: 20px;
            margin: 5px;
            border: 1px solid #ffd700;
            font-size: 0.9em;
        }
        
        .footer {
            margin-top: 30px;
            font-size: 0.9em;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- LOGO UNPAM -->
        <div class="unpam-logo">
            UNIVERSITAS<br>PAMULANG
        </div>
        
        <h1 class="title">🔰 AGOYIKAZ UNPAM - CLOUD COMPUTING</h1>
        <div class="subtitle">🚀 Presentasi Cloud Computing</div>
        
        <!-- INFORMASI PRIBADI -->
        <div class="info-card">
            <h3>📋 Identitas Mahasiswa</h3>
            <p><strong>Nama:</strong> AGOYIKAZ</p>
            <p><strong>NIM:</strong> [Isi NIM Anda]</p>
            <p><strong>Fakultas:</strong> Ilmu Komputer</p>
            <p><strong>Program Studi:</strong> [Isi Program Studi Anda]</p>
        </div>
        
        <!-- INFORMASI CLOUD -->
        <div class="info-card">
            <h3>☁️ Teknologi Cloud</h3>
            <p><strong>Platform:</strong> Netlify</p>
            <p><strong>Jenis Layanan:</strong> Managed Cloud Hosting</p>
            <p><strong>URL Demo:</strong> https://kuda-laut-riang-fc50ab.netlify.app</p>
            
            <div style="margin-top: 15px;">
                <span class="tech-badge">GitHub</span>
                <span class="tech-badge">HTML5</span>
                <span class="tech-badge">CSS3</span>
                <span class="tech-badge">Netlify</span>
                <span class="tech-badge">Cloud Computing</span>
            </div>
        </div>
        
        <!-- DESKRIPSI -->
        <div class="info-card">
            <h3>💡 Tentang Demo Ini</h3>
            <p>Website ini merupakan demonstrasi deploy aplikasi web menggunakan layanan <strong>managed cloud Netlify</strong>. Proses deploy dilakukan secara otomatis melalui integrasi dengan GitHub.</p>
            <p><em>"Dari code ke production dalam hitungan menit!"</em></p>
        </div>
        
        <div class="footer">
            © 2025 AGOYIKAZ UNPAM - Cloud Computing Presentation
        </div>
    </div>
</body>
</html>
