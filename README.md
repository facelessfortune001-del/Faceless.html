<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Faceless Fortune Finder - Stop Wasting Time on Dead-End Niches</title>
    <meta name="description" content="50 pre-validated profitable YouTube niches with CPM data, competition analysis, and 500 video ideas. Skip months of research and start building a channel that actually pays.">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.7;
            color: #1a1a1a;
            background: #ffffff;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 30px;
        }
        
        /* HERO SECTION */
        .hero {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #7e22ce 100%);
            color: white;
            padding: 80px 0 100px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".1" fill="%23fff"/></svg>') no-repeat bottom;
            background-size: cover;
            opacity: 0.1;
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
        }
        
        .pre-headline {
            font-size: 16px;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
            opacity: 0.9;
            font-weight: 600;
        }
        
        .hero h1 {
            font-size: 56px;
            font-weight: 900;
            line-height: 1.2;
            margin-bottom: 25px;
            text-shadow: 2px 2px 20px rgba(0,0,0,0.3);
        }
        
        .hero .subheadline {
            font-size: 22px;
            line-height: 1.5;
            max-width: 900px;
            margin: 0 auto 40px;
            opacity: 0.95;
        }
        
        /* CTA BUTTON */
        .cta-button {
            display: inline-block;
            background: #28a745;
            color: white;
            padding: 20px 50px;
            font-size: 24px;
            font-weight: 800;
            border-radius: 50px;
            text-decoration: none;
            box-shadow: 0 10px 30px rgba(40, 167, 69, 0.4);
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(40, 167, 69, 0.5);
        }
        
        .cta-subtext {
            margin-top: 15px;
            font-size: 14px;
            opacity: 0.8;
        }
        
        /* PROBLEM SECTION */
        .section {
            padding: 80px 0;
        }
        
        .section-title {
            font-size: 42px;
            font-weight: 800;
            margin-bottom: 30px;
            color: #1a1a1a;
        }
        
        .section-subtitle {
            font-size: 20px;
            color: #666;
            margin-bottom: 40px;
            max-width: 800px;
        }
        
        .problem-box {
            background: linear-gradient(135deg, #fff5f5 0%, #ffe5e5 100%);
            border-left: 5px solid #dc3545;
            padding: 40px;
            border-radius: 15px;
            margin: 30px 0;
        }
        
        .problem-box h3 {
            font-size: 28px;
            color: #dc3545;
            margin-bottom: 20px;
            font-weight: 700;
        }
        
        .problem-box p {
            font-size: 18px;
            line-height: 1.7;
            color: #333;
        }
        
        .timeline {
            margin: 40px 0;
        }
        
        .timeline-item {
            display: flex;
            margin: 30px 0;
            align-items: flex-start;
        }
        
        .timeline-marker {
            background: #667eea;
            color: white;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 800;
            font-size: 18px;
            flex-shrink: 0;
            margin-right: 30px;
        }
        
        .timeline-content h4 {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .timeline-content p {
            font-size: 17px;
            color: #555;
        }
        
        /* PRODUCT SHOWCASE */
        .showcase {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 100px 0;
            color: white;
        }
        
        .showcase h2 {
            color: white;
            text-align: center;
            margin-bottom: 60px;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }
        
        .product-visual-main {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 30px 90px rgba(0,0,0,0.3);
            transform: rotate(-2deg);
            transition: transform 0.3s ease;
        }
        
        .product-visual-main:hover {
            transform: rotate(0deg) scale(1.02);
        }
        
        .product-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            margin-bottom: 20px;
        }
        
        .product-icon {
            font-size: 60px;
            margin-bottom: 15px;
        }
        
        .product-title {
            font-size: 28px;
            font-weight: 800;
            margin-bottom: 10px;
        }
        
        .product-subtitle {
            font-size: 16px;
            opacity: 0.95;
        }
        
        .product-lines {
            padding: 20px;
        }
        
        .line {
            height: 10px;
            background: linear-gradient(90deg, #667eea 0%, transparent 100%);
            margin: 12px 0;
            border-radius: 5px;
            opacity: 0.3;
        }
        
        .line.short {
            width: 60%;
        }
        
        .line.medium {
            width: 80%;
        }
        
        .features-grid {
            display: grid;
            gap: 25px;
        }
        
        .feature-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255,255,255,0.2);
            border-radius: 15px;
            padding: 25px;
            display: flex;
            align-items: flex-start;
        }
        
        .feature-icon {
            font-size: 36px;
            margin-right: 20px;
            flex-shrink: 0;
        }
        
        .feature-card h3 {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 8px;
        }
        
        .feature-card p {
            font-size: 15px;
            opacity: 0.9;
            line-height: 1.6;
        }
        
        /* VALUE STACK */
        .value-section {
            background: #f8f9fa;
        }
        
        .value-stack {
            background: white;
            border-radius: 20px;
            padding: 50px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
            max-width: 800px;
            margin: 0 auto;
        }
        
        .value-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
            border-bottom: 2px solid #f0f0f0;
        }
        
        .value-item:last-of-type {
            border-bottom: 3px solid #667eea;
            margin-bottom: 30px;
        }
        
        .value-name {
            font-size: 18px;
            font-weight: 600;
            color: #1a1a1a;
        }
        
        .value-price {
            font-size: 22px;
            font-weight: 700;
            color: #667eea;
        }
        
        .total-value {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
        }
        
        .total-label {
            font-size: 18px;
            opacity: 0.9;
            margin-bottom: 10px;
        }
        
        .total-amount {
            font-size: 48px;
            font-weight: 900;
            text-decoration: line-through;
            opacity: 0.8;
        }
        
        .your-price {
            background: #28a745;
            padding: 40px;
            border-radius: 15px;
            margin-top: 20px;
            text-align: center;
        }
        
        .your-price-label {
            font-size: 20px;
            margin-bottom: 10px;
        }
        
        .your-price-amount {
            font-size: 72px;
            font-weight: 900;
        }
        
        /* BONUSES */
        .bonuses {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
        }
        
        .bonus-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        
        .bonus-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255,255,255,0.3);
            border-radius: 20px;
            padding: 35px;
            text-align: center;
        }
        
        .bonus-icon {
            font-size: 60px;
            margin-bottom: 20px;
        }
        
        .bonus-title {
            font-size: 24px;
            font-weight: 800;
            margin-bottom: 15px;
        }
        
        .bonus-value {
            font-size: 28px;
            font-weight: 700;
            color: #ffd700;
            margin-bottom: 15px;
        }
        
        .bonus-desc {
            font-size: 16px;
            opacity: 0.95;
            line-height: 1.6;
        }
        
        /* TESTIMONIALS PLACEHOLDER */
        .testimonials {
            background: #f8f9fa;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        
        .testimonial {
            background: white;
            padding: 35px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
        }
        
        .stars {
            color: #ffc107;
            font-size: 20px;
            margin-bottom: 15px;
        }
        
        .testimonial-text {
            font-size: 16px;
            font-style: italic;
            color: #333;
            margin-bottom: 20px;
            line-height: 1.7;
        }
        
        .testimonial-author {
            font-weight: 700;
            color: #667eea;
        }
        
        /* GUARANTEE */
        .guarantee {
            text-align: center;
            padding: 80px 0;
            background: white;
        }
        
        .guarantee-badge {
            background: linear-gradient(135deg, #d4edda 0%, #c3e6cb 100%);
            border: 4px solid #28a745;
            border-radius: 20px;
            padding: 50px;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .guarantee-icon {
            font-size: 80px;
            margin-bottom: 20px;
        }
        
        .guarantee-title {
            font-size: 36px;
            font-weight: 800;
            color: #28a745;
            margin-bottom: 20px;
        }
        
        .guarantee-text {
            font-size: 18px;
            color: #155724;
            line-height: 1.7;
        }
        
        /* FAQ */
        .faq {
            background: #f8f9fa;
        }
        
        .faq-item {
            background: white;
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .faq-question {
            font-size: 20px;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 15px;
        }
        
        .faq-answer {
            font-size: 16px;
            color: #555;
            line-height: 1.7;
        }
        
        /* FINAL CTA */
        .final-cta {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #7e22ce 100%);
            color: white;
            text-align: center;
            padding: 100px 0;
        }
        
        .final-cta h2 {
            color: white;
            font-size: 48px;
            margin-bottom: 30px;
        }
        
        .final-cta p {
            font-size: 22px;
            margin-bottom: 40px;
            opacity: 0.95;
        }
        
        .cta-box {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255,255,255,0.3);
            border-radius: 20px;
            padding: 50px;
            max-width: 600px;
            margin: 0 auto 40px;
        }
        
        .price-display {
            font-size: 80px;
            font-weight: 900;
            margin: 20px 0;
        }
        
        /* FOOTER */
        footer {
            background: #1a1a1a;
            color: white;
            text-align: center;
            padding: 40px 0;
        }
        
        footer p {
            font-size: 14px;
            opacity: 0.7;
            line-height: 1.8;
        }
        
        /* RESPONSIVE */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 36px;
            }
            
            .hero .subheadline {
                font-size: 18px;
            }
            
            .product-grid {
                grid-template-columns: 1fr;
                gap: 40px;
            }
            
            .section-title {
                font-size: 32px;
            }
            
            .cta-button {
                font-size: 20px;
                padding: 18px 40px;
            }
            
            .price-display {
                font-size: 60px;
            }
            
            .your-price-amount {
                font-size: 56px;
            }
        }
        
        /* SMOOTH SCROLL */
        html {
            scroll-behavior: smooth;
        }
        
        /* HIGHLIGHT ANIMATION */
        .highlight {
            background: linear-gradient(120deg, #ffd700 0%, #ffd700 100%);
            background-repeat: no-repeat;
            background-size: 100% 40%;
            background-position: 0 85%;
        }
    </style>
</head>
<body>

    <!-- HERO SECTION -->
    <section class="hero">
        <div class="container hero-content">
            <p class="pre-headline">For Aspiring Faceless Channel Creators</p>
            <h1>Stop Wasting Months on<br>Dead-End Niches That'll<br>Never Make You Money</h1>
            <p class="subheadline">The Faceless Fortune Finder reveals 50 pre-validated, profitable YouTube niches with exact CPM ranges, competition scores, and 500 ready-to-use video ideas—so you can skip the research phase and start building a channel that actually pays.</p>
            <div style="margin-top: 50px;">
                <a href="#pricing" class="cta-button">GET INSTANT ACCESS - $47</a>
                <p class="cta-subtext">✓ Instant Download  ✓ 30-Day Guarantee  ✓ Lifetime Updates</p>
            </div>
        </div>
    </section>

    <!-- PROBLEM SECTION -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">You're About to Make a $10,000 Mistake</h2>
            <p class="section-subtitle">Here's what happens to 9 out of 10 people who start faceless YouTube channels:</p>
            
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-marker">Month<br>1</div>
                    <div class="timeline-content">
                        <h4>The Hopeful Beginning</h4>
                        <p>You pick a niche that "feels right." Maybe stoicism. Maybe motivation. Maybe luxury lifestyle. You spend weeks setting up your channel, learning the tools, creating your first videos.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-marker">Month<br>2-3</div>
                    <div class="timeline-content">
                        <h4>The Grind Begins</h4>
                        <p>You're posting consistently. 20 videos in. Views are... okay. Not great. You're getting 500-2,000 views per video. You tell yourself it takes time.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-marker">Month<br>4-5</div>
                    <div class="timeline-content">
                        <h4>The Disappointing Reality</h4>
                        <p>You hit 1,000 subscribers. Finally! You monetize. Your first payment arrives: <strong>$47.</strong> You do the math. At this rate, you'd need 200,000 views per month just to make $1,000.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-marker">Month<br>6</div>
                    <div class="timeline-content">
                        <h4>The Brutal Truth</h4>
                        <p class="highlight">You just wasted 6 months and hundreds of hours of work.</strong> Your CPM is $3. The market is oversaturated. There are no good affiliate programs. You picked the wrong niche.</p>
                    </div>
                </div>
            </div>
            
            <div class="problem-box">
                <h3>The worst part?</h3>
                <p>You could have avoided all of this with 30 minutes of proper research.</p>
            </div>
        </div>
    </section>

    <!-- PRODUCT SHOWCASE -->
    <section class="showcase">
        <div class="container">
            <h2 class="section-title">Introducing: The Faceless Fortune Finder</h2>
            
            <div class="product-grid">
                <div class="product-visual-main">
                    <div class="product-header">
                        <div class="product-icon">🎯</div>
                        <div class="product-title">50 Niches Database</div>
                        <div class="product-subtitle">Pre-Validated & Ready to Launch</div>
                    </div>
                    <div class="product-lines">
                        <div class="line"></div>
                        <div class="line medium"></div>
                        <div class="line"></div>
                        <div class="line short"></div>
                        <div class="line"></div>
                        <div class="line medium"></div>
                        <div class="line"></div>
                    </div>
                </div>
                
                <div class="features-grid">
                    <div class="feature-card">
                        <div class="feature-icon">✅</div>
                        <div>
                            <h3>50 Pre-Validated Niches</h3>
                            <p>Each scored across 5 pillars: Profit, Competition, Sustainability, Desperation, AI-Friendliness</p>
                        </div>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">💵</div>
                        <div>
                            <h3>Exact CPM Ranges</h3>
                            <p>Know how much you'll earn per 1,000 views ($6-$40 depending on niche)</p>
                        </div>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">🎬</div>
                        <div>
                            <h3>500 Proven Video Ideas</h3>
                            <p>10 tested topics per niche - never run out of content ideas</p>
                        </div>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">🔗</div>
                        <div>
                            <h3>Complete Affiliate Programs</h3>
                            <p>Direct links with commission rates ($50-$1,000+ per sale)</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- VALUE STACK -->
    <section class="section value-section" id="pricing">
        <div class="container">
            <h2 class="section-title" style="text-align: center;">Here's Everything You Get</h2>
            
            <div class="value-stack">
                <div class="value-item">
                    <div class="value-name">📦 50-Niche Database with Full Analysis</div>
                    <div class="value-price">$147</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">🎯 5-Pillar Niche Validator Framework</div>
                    <div class="value-price">$97</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">📝 Niche Research Template</div>
                    <div class="value-price">$47</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">🔄 Strategic Niche Combinations Guide</div>
                    <div class="value-price">$67</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">⚡ Quick-Start 7-Day Action Plan</div>
                    <div class="value-price">$37</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">🎁 BONUS: My Top 10 Picks Video</div>
                    <div class="value-price">$27</div>
                </div>
                
                <div class="value-item">
                    <div class="value-name">🔄 BONUS: Quarterly Updates (1 Year)</div>
                    <div class="value-price">$97</div>
                </div>
                
                <div class="total-value">
                    <div class="total-label">Total Value:</div>
                    <div class="total-amount">$519</div>
                </div>
                
                <div class="your-price">
                    <div class="your-price-label">Your Investment Today:</div>
                    <div class="your-price-amount">$47</div>
                </div>
                
                <div style="text-align: center; margin-top: 40px;">
                    <a href="#order" class="cta-button">GET INSTANT ACCESS NOW</a>
                    <p class="cta-subtext" style="color: #666;">One-time payment • Instant download • 30-day guarantee</p>
                </div>
            </div>
        </div>
    </section>

    <!-- BONUSES -->
    <section class="section bonuses">
        <div class="container">
            <h2 class="section-title" style="color: white; text-align: center;">Limited-Time Bonuses</h2>
            <p style="text-align: center; font-size: 20px; margin-bottom: 20px;">Order in the next 72 hours and get these exclusive bonuses:</p>
            
            <div class="bonus-grid">
                <div class="bonus-card">
                    <div class="bonus-icon">🎁</div>
                    <div class="bonus-title">BONUS #1</div>
                    <div class="bonus-value">$97 VALUE</div>
                    <h3 class="bonus-title">5-Pillar Framework Guide</h3>
                    <p class="bonus-desc">12-page illustrated PDF teaching you the exact validation system I use. You'll never pick a bad niche again.</p>
                </div>
                
                <div class="bonus-card">
                    <div class="bonus-icon">📊</div>
                    <div class="bonus-title">BONUS #2</div>
                    <div class="bonus-value">$47 VALUE</div>
                    <h3 class="bonus-title">Research Template</h3>
                    <p class="bonus-desc">Fill-in-the-blank worksheet to validate ANY niche idea yourself in under 30 minutes.</p>
                </div>
                
                <div class="bonus-card">
                    <div class="bonus-icon">🎬</div>
                    <div class="bonus-title">BONUS #3</div>
                    <div class="bonus-value">$27 VALUE</div>
                    <h3 class="bonus-title">My Top 10 Picks</h3>
                    <p class="bonus-desc">Video walkthrough of my personal top 10 niches to start TODAY, with exact launch strategies.</p>
                </div>
                
                <div class="bonus-card">
                    <div class="bonus-icon">🔄</div>
                    <div class="bonus-title">BONUS #4</div>
                    <div class="bonus-value">$97 VALUE</div>
                    <h3 class="bonus-title">Quarterly Updates</h3>
                    <p class="bonus-desc">Every 3 months, get 10 NEW validated niches with updated CPM data and emerging opportunities.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- GUARANTEE -->
    <section class="guarantee">
        <div class="container">
            <div class="guarantee-badge">
                <div class="guarantee-icon">✅</div>
                <div class="guarantee-title">30-Day Money-Back Guarantee</div>
                <p class="guarantee-text">Use The Faceless Fortune Finder for 30 days. If you don't find at least 3 profitable niches you're excited about, email us for a full refund. No questions asked. No hoops to jump through.</p>
            </div>
        </div>
    </section>

    <!-- TESTIMONIALS PLACEHOLDER -->
    <section class="section testimonials">
        <div class="container">
            <h2 class="section-title" style="text-align: center;">What Early Users Are Saying</h2>
            
            <div class="testimonial-grid">
                <div class="testimonial">
                    <div class="stars">★★★★★</div>
                    <p class="testimonial-text">"I wasted 4 months in a dead-end niche before finding this. The CPM data alone saved me from making another mistake. Chose a niche from the database and my first monetized month was $847. This paid for itself 17x over."</p>
                    <p class="testimonial-author">— Marcus T., Faceless Creator</p>
                </div>
                
                <div class="testimonial">
                    <div class="stars">★★★★★</div>
                    <p class="testimonial-text">"The 5-Pillar Framework is genius. I validated 3 niche ideas in an hour and finally picked one I'm confident about. The affiliate program list is worth the price alone - I'm making more from affiliates than AdSense now."</p>
                    <p class="testimonial-author">— Sarah K., YouTube Entrepreneur</p>
                </div>
                
                <div class="testimonial">
                    <div class="stars">★★★★★</div>
                    <p class="testimonial-text">"I was stuck in analysis paralysis for weeks. This database gave me the data I needed to make a decision in 20 minutes. Now I have 30 videos published and I'm growing fast. Best $47 I've spent."</p>
                    <p class="testimonial-author">— James R., Content Creator</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="section faq">
        <div class="container">
            <h2 class="section-title" style="text-align: center;">Frequently Asked Questions</h2>
            
            <div class="faq-item">
                <div class="faq-question">Q: Can't I just research this myself?</div>
                <div class="faq-answer">Absolutely. You can spend 750+ hours doing what I've already done. Or you can spend $47 and 30 minutes. This database includes 15+ hours of research per niche category, testing actual channels, verifying CPMs, finding affiliate programs, and scoring competition. Your time. Your choice.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: How do I know this information is accurate?</div>
                <div class="faq-answer">Every niche includes real channel examples you can verify yourself, CPM ranges from industry data, affiliate programs you can check exist, and competition analysis you can see with your own eyes. This isn't theory—it's data from actual channels making actual money.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: What if I pick the wrong niche from your list?</div>
                <div class="faq-answer">Then you pick another one. You get 50 options scored and analyzed. If you can't find 3 that work for you, this isn't a niche problem—it's a commitment problem. Plus, you have 30 days to decide with zero risk.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: Is this just a list I could find on Google?</div>
                <div class="faq-answer">Try it. Google "most profitable faceless YouTube niches" and you'll get generic top 10 lists with no CPM data, no competition analysis, no affiliate programs, and no validation framework. I've done 15+ hours of actual research with verified data. Google hasn't.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: Do I need YouTube experience?</div>
                <div class="faq-answer">No. This is perfect for beginners. The framework teaches you exactly what to look for when choosing a niche. If you're experienced, it'll save you months of trial and error and help you pivot into more profitable niches.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: What format is the product in?</div>
                <div class="faq-answer">100% digital. You'll get instant access to: PDF database with all 50 niches, Excel/Google Sheets version (sortable by any metric), Framework guide PDF, and all bonus materials. Works on any device.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: When do I get access?</div>
                <div class="faq-answer">Immediately after purchase. Check your email for the download link. You'll be analyzing niches within 5 minutes of ordering.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: What if I want a refund?</div>
                <div class="faq-answer">Email me within 30 days and I'll refund you immediately. No drama, no questions asked. I want you to succeed, not feel trapped.</div>
            </div>
        </div>
    </section>

    <!-- FINAL CTA -->
    <section class="final-cta" id="order">
        <div class="container">
            <h2>Two Paths Forward</h2>
            
            <div style="max-width: 900px; margin: 0 auto;">
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 40px; margin: 50px 0;">
                    <div style="background: rgba(255,255,255,0.1); padding: 40px; border-radius: 15px; backdrop-filter: blur(10px); border: 2px solid rgba(255,255,255,0.2);">
                        <h3 style="font-size: 28px; margin-bottom: 20px; color: #ff6b6b;">❌ PATH 1: Do Nothing</h3>
                        <p style="font-size: 17px; line-height: 1.7;">Close this page. Tell yourself you'll "figure it out later."</p>
                        <p style="font-size: 17px; line-height: 1.7; margin-top: 20px;">Six months from now, you're either:</p>
                        <ul style="text-align: left; margin-left: 30px; margin-top: 15px; font-size: 16px;">
                            <li>Still researching and overthinking</li>
                            <li>Stuck in a dead-end niche making $50/month</li>
                            <li>Watching others succeed in niches you "thought about"</li>
                        </ul>
                    </div>
                    
                    <div style="background: rgba(40, 167, 69, 0.2); padding: 40px; border-radius: 15px; backdrop-filter: blur(10px); border: 2px solid #28a745;">
                        <h3 style="font-size: 28px; margin-bottom: 20px; color: #28a745;">✅ PATH 2: Take Action</h3>
                        <p style="font-size: 17px; line-height: 1.7;">Invest $47 today. Get instant access to everything.</p>
                        <p style="font-size: 17px; line-height: 1.7; margin-top: 20px;">Your timeline:</p>
                        <ul style="text-align: left; margin-left: 30px; margin-top: 15px; font-size: 16px;">
                            <li>30 minutes: Know your niche</li>
                            <li>Tomorrow: Create first video</li>
                            <li>Next month: 10 videos published</li>
                            <li>6 months: Monetized channel generating income</li>
                        </ul>
                    </div>
                </div>
                
                <div class="cta-box">
                    <h3 style="font-size: 32px; margin-bottom: 20px;">What Will You Choose?</h3>
                    <p style="font-size: 18px; margin-bottom: 20px;">The research is done. The path is clear. The opportunity is NOW.</p>
                    <div class="price-display">$47</div>
                    <p style="font-size: 16px; opacity: 0.9; margin-bottom: 30px;">One-time payment • Instant access • Lifetime updates</p>
                    
                    <!-- REPLACE THIS HREF WITH YOUR ACTUAL PAYMENT LINK -->
                    <a href="#" class="cta-button" style="display: inline-block; margin-bottom: 20px;">GET INSTANT ACCESS NOW</a>
                    
                    <p style="font-size: 14px; opacity: 0.8;">✓ Secure Checkout  ✓ Instant Download  ✓ 30-Day Guarantee</p>
                </div>
                
                <div style="background: rgba(255,255,255,0.1); padding: 30px; border-radius: 15px; margin-top: 40px; backdrop-filter: blur(10px);">
                    <h3 style="font-size: 24px; margin-bottom: 15px;">Remember:</h3>
                    <ul style="font-size: 17px; line-height: 2; text-align: left; list-style: none;">
                        <li>✅ 30-day money-back guarantee</li>
                        <li>✅ Instant access (nothing shipped)</li>
                        <li>✅ Lifetime updates included</li>
                        <li>✅ 50 validated niches</li>
                        <li>✅ 500 video ideas ready to use</li>
                        <li>✅ Complete monetization roadmap</li>
                        <li>✅ Over 15 hours of research done for you</li>
                    </ul>
                    <p style="font-size: 20px; margin-top: 25px; font-weight: 700;">You risk nothing. You gain everything.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- URGENCY SECTION -->
    <section class="section" style="background: #fff3cd; border-top: 5px solid #ffc107; border-bottom: 5px solid #ffc107;">
        <div class="container" style="text-align: center;">
            <h2 class="section-title" style="color: #856404;">⚠️ The Window Is Closing</h2>
            <p style="font-size: 20px; color: #856404; max-width: 800px; margin: 0 auto 30px; line-height: 1.7;">Every day you wait, competition increases. Right now, there are underserved niches with high CPMs, low competition, desperate audiences, and strong affiliate programs. In 6 months? Those niches will be saturated.</p>
            <p style="font-size: 22px; color: #856404; font-weight: 700;">The creators who move NOW will build audiences while the opportunity is fresh.</p>
            <p style="font-size: 22px; color: #856404; font-weight: 700; margin-top: 15px;">The creators who "think about it" will enter when it's too late.</p>
            
            <div style="margin-top: 40px;">
                <a href="#order" class="cta-button">CLAIM YOUR COPY NOW - $47</a>
            </div>
        </div>
    </section>

    <!-- FINAL TESTIMONIAL SECTION -->
    <section class="section" style="background: #f8f9fa;">
        <div class="container" style="text-align: center;">
            <h2 class="section-title">One Last Thing...</h2>
            <div style="max-width: 800px; margin: 0 auto;">
                <p style="font-size: 19px; line-height: 1.8; color: #333; margin-bottom: 30px;">I created The Faceless Fortune Finder because I was tired of watching people waste months on bad niches.</p>
                
                <p style="font-size: 19px; line-height: 1.8; color: #333; margin-bottom: 30px;">I've seen too many creators burn out after 50 videos in oversaturated markets, earn $2 CPMs while working twice as hard, and quit right before they could have succeeded—if they'd just picked better.</p>
                
                <p style="font-size: 19px; line-height: 1.8; color: #333; margin-bottom: 30px;"><strong>You don't have to be one of them.</strong></p>
                
                <p style="font-size: 19px; line-height: 1.8; color: #333; margin-bottom: 40px;">The data exists. The opportunities exist. The roadmap exists. All you need to do is choose.</p>
                
                <p style="font-size: 24px; font-weight: 700; color: #667eea; margin-bottom: 40px;">See you inside.</p>
                
                <a href="#order" class="cta-button">GET INSTANT ACCESS - $47</a>
                
                <p style="font-size: 16px; color: #666; margin-top: 30px; line-height: 1.7;"><strong>P.S.</strong> The $47 launch price expires in 72 hours. After that, it's $67, then $97. The bonuses disappear too. If you're going to do this, do it now.</p>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="container">
            <p>© 2025 The Faceless Fortune Finder. All Rights Reserved.</p>
            <p style="margin-top: 15px;">This site is not affiliated with YouTube or Google. Results vary based on effort, consistency, and execution.<br>We cannot guarantee income. Your success depends on your work.</p>
            <p style="margin-top: 15px;"><a href="#" style="color: rgba(255,255,255,0.7); text-decoration: none;">Privacy Policy</a> | <a href="#" style="color: rgba(255,255,255,0.7); text-decoration: none;">Terms of Service</a> | <a href="#" style="color: rgba(255,255,255,0.7); text-decoration: none;">Contact</a></p>
        </div>
    </footer>

    <!-- Smooth Scroll Script -->
    <script>
        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Optional: Add scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observe all sections
        document.querySelectorAll('.section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(30px)';
            section.style.transition = 'all 0.6s ease-out';
            observer.observe(section);
        });
    </script>

</body>
</html>
