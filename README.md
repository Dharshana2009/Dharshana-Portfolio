# Dharshana-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharshana Dhanasekar | Portfolio</title>
    <style>
        :root {
            --primary-lavender: #E6E6FA;
            --deep-lilac: #967BB6;
            --soft-purple: #DCD0FF;
            --text-dark: #2D2D2D;
            --white: #ffffff;
        }

        body { font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; color: var(--text-dark); background: var(--white); }
        
        /* 1. PROFILE HEADER */
        header {
            height: 60vh;
            background: linear-gradient(rgba(230, 230, 250, 0.85), rgba(230, 230, 250, 0.85)), 
                        url('https://images.unsplash.com/photo-1576086213369-97a306dca665?auto=format&fit=crop&w=1000&q=80');
            background-size: cover;
            display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center;
        }

        .summary-box { max-width: 800px; padding: 20px; }
        h1 { color: var(--deep-lilac); font-size: 3rem; margin: 0; }
        .quote { font-style: italic; color: #666; margin-bottom: 20px; }

        /* 2. SKILLS SECTION (The 3 things) */
        .section { padding: 60px 20px; max-width: 1000px; margin: auto; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .card { background: var(--primary-lavender); padding: 20px; border-radius: 15px; border: 1px solid var(--soft-purple); }
        h2 { color: var(--deep-lilac); text-align: center; margin-bottom: 40px; }

        /* 3. JOURNEY SECTION (Timeline) */
        .journey-item {
            border-left: 3px solid var(--deep-lilac);
            margin-left: 20px;
            padding-left: 30px;
            position: relative;
            margin-bottom: 40px;
        }
        .journey-item::before {
            content: '';
            position: absolute; width: 15px; height: 15px;
            background: var(--deep-lilac);
            border-radius: 50%; left: -9px; top: 5px;
        }
        .date { font-weight: bold; color: var(--deep-lilac); }

        .btn {
            display: inline-block; background: var(--deep-lilac); color: white;
            padding: 12px 25px; border-radius: 25px; text-decoration: none; margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="summary-box">
        <h1>Dharshana Dhanasekar</h1>
        <p class="quote">"No great discovery was ever made without a bold guess." — Isaac Newton</p>
        <p><strong>Who I am:</strong> I am a Molecular Biologist specializing in Immunology and Infection Biology. Currently based in Lund, Sweden, I am completing my Master's at Lund University where I focus on the molecular interactions between hosts and pathogens.</p>
        <p><strong>What I am doing now:</strong> I am investigating immune-related genetic factors in tissue regeneration and optimizing in-vitro models for tuberculosis therapy. My goal is to build a foundation for future targeted immunotherapies.</p>
    </div>
</header>

<section class="section">
    <h2>Core Expertise</h2>
    <div class="grid">
        <div class="card">
            <h3>Molecular Techniques</h3>
            <p>Expertise in high-purity DNA/RNA extraction, precision PCR, and molecular cloning to manipulate and analyze genetic material.</p>
        </div>
        <div class="card">
            <h3>Microbiology (BSL-2)</h3>
            <p>Proficient in aseptic handling, bacterial culture maintenance, and streaking/plating within Biosafety Level 2 environments.</p>
        </div>
        <div class="card">
            <h3>Immunology</h3>
            <p>Hands-on experience with primary human immune cell isolation (PBMC), differentiation, and cell-based assays like ELISA.</p>
        </div>
    </div>
</section>

<section class="section" style="background: #fafafa; border-radius: 50px;">
    <h2>My Journey</h2>
    
    <div class="journey-item">
        <div class="date">2023 - 2025 | Lund University, Sweden</div>
        <h3>M.Sc. in Molecular Biology</h3>
        <p>Advanced my expertise in Infection Biology. Awarded the Educational Scholarship in Molecular Medicine (2025). Conducted deep-dive research into tuberculosis therapy complexes.</p>
    </div>

    <div class="journey-item">
        <div class="date">2023 | Research Internship</div>
        <h3>Biolim Laboratories, India</h3>
        <p>Evaluated anticancer compounds using MTT cytotoxicity assays. Learned to bridge the gap between lab data and project decision-making.</p>
    </div>

    <div class="journey-item">
        <div class="date">2019 - 2023 | St. Joseph's College of Engineering</div>
        <h3>B.Tech in Biotechnology</h3>
        <p>The beginning of my empire. Graduated with First Class Distinction. My thesis focused on the complex antibody responses to SARS-CoV-2 in HIV cohorts.</p>
    </div>
</section>

<section class="section" style="text-align: center;">
    <h2>Let's Connect</h2>
    <p>I am always open to discussing molecular immunology and research collaborations.</p>
    <a href="mailto:dharshanadhanasekar@gmail.com" class="btn">Email Me</a>
    <a href="#" class="btn" style="background: #8e74ae;">LinkedIn</a>
</section>

<footer>
    <p style="text-align: center; padding: 20px; color: #999;">&copy; 2026 Dharshana Dhanasekar</p>
</footer>

</body>
</html>
