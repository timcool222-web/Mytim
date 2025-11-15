<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ทรัพย์สินขนส่ง - ขนส่งสัตว์เลี้ยง มอเตอร์ไซค์ ย้ายบ้าน ทั่วไทย</title>
    <meta name="description" content="บริการขนส่งสัตว์เลี้ยง มอเตอร์ไซค์ ย้ายบ้านทั่วไทย ทีมงานขับเองทุกงาน รับผิดชอบสูงสุด 10,000 บาท ตอบไวภายใน 15 นาที">
    <meta name="keywords" content="ขนส่งสัตว์เลี้ยง, ส่งมอเตอร์ไซค์, ย้ายบ้าน, ขนส่งทั่วไทย, ทรัพย์สินขนส่ง">
    <meta name="author" content="ทรัพย์สินขนส่ง">
    
    <!-- Open Graph -->
    <meta property="og:title" content="ทรัพย์สินขนส่ง - ขนส่งสัตว์เลี้ยง มอเตอร์ไซค์ ย้ายบ้าน">
    <meta property="og:description" content="บริการขนส่งสัตว์เลี้ยง มอเตอร์ไซค์ ย้ายบ้านทั่วไทย ทีมงานขับเองทุกงาน">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://i.ibb.co/0yJ9tS6L/1763048114159.jpg">
    <meta property="og:url" content="https://ทรัพย์สินขนส่ง.com">
    <meta name="twitter:card" content="summary_large_image">
    
    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🚚</text></svg>">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@400;500;600;700&family=Sarabun:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- PWA Manifest -->
    <link rel="manifest" href="manifest.json">
    <meta name="theme-color" content="#0A1F44">
    
    <style>
        :root {
            --navy: #0A1F44;
            --accent: #F9C80E;
            --bg: #F7F9FB;
            --muted: #6B7280;
            --card: #FFFFFF;
            --radius: 12px;
            --maxw: 1100px;
            --shadow: 0 10px 30px rgba(10,31,68,0.08);
            --success: #10B981;
            --error: #EF4444;
            --facebook: #1877F2;
            --tiktok: #000000;
            font-family: "Noto Sans Thai", "Sarabun", system-ui, -apple-system, "Segoe UI", Roboto, Arial;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html, body {
            height: 100%;
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            background: var(--bg);
            color: #0b1220;
            -webkit-font-smoothing: antialiased;
            min-height: 100vh;
            line-height: 1.6;
        }

        .wrap {
            max-width: var(--maxw);
            margin: 18px auto;
            padding: 16px;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
            padding: 14px;
            border-radius: 12px;
            background: linear-gradient(90deg, var(--navy), #072039);
            color: #fff;
            box-shadow: var(--shadow);
            position: sticky;
            top: 16px;
            z-index: 100;
        }

        .brand {
            display: flex;
            gap: 12px;
            align-items: center;
        }

        .logo {
            width: 56px;
            height: 56px;
            border-radius: 10px;
            background: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 800;
            color: #111;
            font-size: 18px;
            overflow: hidden;
        }

        .logo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 10px;
        }

        .brand h1 {
            margin: 0;
            font-size: 18px;
        }

        .brand p {
            margin: 0;
            font-size: 13px;
            opacity: 0.95;
        }

        nav.main-nav {
            display: flex;
            gap: 10px;
            align-items: center;
        }

        nav.main-nav a {
            color: rgba(255,255,255,0.95);
            font-weight: 700;
            padding: 8px 10px;
            border-radius: 8px;
            transition: background 0.2s;
        }

        nav.main-nav a:hover {
            background: rgba(255,255,255,0.1);
        }

        .header-actions {
            display: flex;
            gap: 8px;
            align-items: center;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 12px;
            border-radius: 10px;
            font-weight: 700;
            border: 0;
            cursor: pointer;
            transition: all 0.2s;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }

        .btn-line {
            background: var(--accent);
            color: #111;
        }

        .btn-call {
            background: transparent;
            border: 2px solid rgba(255,255,255,0.12);
            color: #fff;
        }

        .btn-facebook {
            background: var(--facebook);
            color: #fff;
        }

        .btn-tiktok {
            background: var(--tiktok);
            color: #fff;
        }

        .badge {
            background: rgba(255,255,255,0.08);
            padding: 6px 10px;
            border-radius: 999px;
            font-size: 13px;
        }

        main {
            margin-top: 18px;
        }

        /* HERO */
        .hero {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
            align-items: start;
        }

        .hero-card {
            background: linear-gradient(180deg, #fff, #fbfdff);
            padding: 18px;
            border-radius: 16px;
            box-shadow: var(--shadow);
        }

        .hero-title {
            font-size: 24px;
            color: var(--navy);
            margin: 0;
        }

        .lead {
            color: var(--muted);
            margin: 6px 0 0 0;
            font-size: 15px;
        }

        .cta-row {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 12px;
        }

        .pill {
            display: inline-block;
            background: #EFF6FF;
            padding: 6px 10px;
            border-radius: 999px;
            color: var(--navy);
            font-weight: 700;
            font-size: 13px;
        }

        /* Layout */
        .section {
            margin-top: 18px;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr;
            gap: 14px;
        }

        .panel {
            background: var(--card);
            padding: 16px;
            border-radius: 12px;
            box-shadow: var(--shadow);
        }

        label {
            display: block;
            font-size: 13px;
            color: var(--muted);
            margin-bottom: 6px;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px 12px;
            border-radius: 10px;
            border: 1px solid #E6E9EE;
            font-size: 14px;
            font-family: inherit;
            transition: border 0.2s;
        }

        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: var(--navy);
            box-shadow: 0 0 0 3px rgba(10, 31, 68, 0.1);
        }

        .row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        .muted {
            color: var(--muted);
        }

        .small {
            font-size: 13px;
        }

        .mt {
            margin-top: 12px;
        }

        /* Services */
        .services {
            display: grid;
            grid-template-columns: 1fr;
            gap: 12px;
        }

        .service {
            display: flex;
            gap: 12px;
            align-items: flex-start;
            padding: 12px;
            border-radius: 12px;
            background: linear-gradient(180deg, #fff, #fbfdff);
            box-shadow: 0 6px 20px rgba(10,31,68,0.04);
            transition: transform 0.2s;
        }

        .service:hover {
            transform: translateY(-4px);
        }

        .service .icon {
            width: 56px;
            height: 56px;
            border-radius: 10px;
            background: linear-gradient(180deg, #F9F080, #fff);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 800;
            color: var(--navy);
            flex-shrink: 0;
        }

        /* Estimator */
        .est-row {
            display: grid;
            grid-template-columns: 1fr;
            gap: 12px;
        }

        .est-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        .est-result {
            font-size: 18px;
            font-weight: 800;
            color: var(--navy);
            margin-top: 8px;
        }

        /* Pet section specifics */
        .pet-hero {
            display: flex;
            gap: 12px;
            align-items: flex-start;
            flex-wrap: wrap;
        }

        .pet-hero .left {
            flex: 1;
        }

        .pet-hero .right {
            width: 320px;
            min-width: 260px;
        }

        /* Gallery & Slider Styles */
        .gallery {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .photo {
            height: 120px;
            border-radius: 10px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            background: linear-gradient(135deg, #e9f2ff, #fff);
        }

        .photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .photo:hover img {
            transform: scale(1.05);
        }

        .photo-label {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(10, 31, 68, 0.8);
            color: white;
            padding: 6px 8px;
            font-size: 12px;
            font-weight: 600;
            text-align: center;
        }

        /* Loading state for images */
        .photo.loading {
            background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
            background-size: 200% 100%;
            animation: loading 1.5s infinite;
        }

        @keyframes loading {
            0% { background-position: 200% 0; }
            100% { background-position: -200% 0; }
        }

        /* Slider Styles */
        .slider-container {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: var(--shadow);
            margin: 16px 0;
        }

        .slider {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }

        .slide {
            min-width: 100%;
            height: 300px;
            position: relative;
        }

        .slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
        }

        .slide-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 10px;
            text-align: center;
            font-size: 14px;
        }

        .slider-nav {
            position: absolute;
            top: 50%;
            width: 100%;
            display: flex;
            justify-content: space-between;
            transform: translateY(-50%);
            padding: 0 10px;
        }

        .slider-btn {
            background: rgba(255, 255, 255, 0.8);
            border: none;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 18px;
            transition: all 0.3s;
        }

        .slider-btn:hover {
            background: white;
            transform: scale(1.1);
        }

        .slider-dots {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin-top: 12px;
        }

        .dot {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background: #ddd;
            cursor: pointer;
            transition: background 0.3s;
        }

        .dot.active {
            background: var(--navy);
        }

        /* reviews */
        .reviews {
            display: flex;
            gap: 10px;
            overflow: hidden;
            padding-top: 8px;
        }

        .rev-card {
            min-width: 260px;
            background: var(--card);
            padding: 12px;
            border-radius: 12px;
            box-shadow: var(--shadow);
        }

        /* FAQ/trust */
        .trust-row {
            display: grid;
            grid-template-columns: 1fr;
            gap: 10px;
        }

        /* Featured Services */
        .featured-services {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
            margin-top: 24px;
        }

        .featured-service {
            background: linear-gradient(135deg, var(--navy), #0d2a5c);
            color: white;
            padding: 20px;
            border-radius: 16px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .featured-service h3 {
            font-size: 20px;
            margin: 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .featured-service .price {
            font-size: 24px;
            font-weight: 800;
            color: var(--accent);
        }

        /* Trust Signals */
        .trust-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            justify-content: center;
            margin: 20px 0;
        }

        .trust-item {
            display: flex;
            align-items: center;
            gap: 8px;
            background: white;
            padding: 10px 16px;
            border-radius: 999px;
            box-shadow: var(--shadow);
            font-weight: 600;
            font-size: 14px;
        }

        /* Customer Testimonials */
        .testimonials {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
            margin-top: 24px;
        }

        .testimonial {
            background: var(--card);
            padding: 20px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            position: relative;
        }

        .testimonial:before {
            content: """;
            font-size: 60px;
            color: var(--accent);
            position: absolute;
            top: -10px;
            left: 10px;
            opacity: 0.3;
        }

        .testimonial-rating {
            color: var(--accent);
            font-size: 18px;
            margin-bottom: 8px;
        }

        /* Expanded FAQ */
        .faq-expanded {
            display: grid;
            gap: 16px;
        }

        .faq-item {
            background: var(--card);
            padding: 16px;
            border-radius: 12px;
            box-shadow: var(--shadow);
        }

        .faq-question {
            font-weight: 700;
            color: var(--navy);
            margin-bottom: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
        }

        .faq-answer {
            color: var(--muted);
            font-size: 14px;
            line-height: 1.6;
        }

        /* Mobile Menu */
        .menu-toggle {
            display: none;
            flex-direction: column;
            justify-content: space-between;
            width: 30px;
            height: 21px;
            background: transparent;
            border: none;
            cursor: pointer;
            padding: 0;
        }

        .menu-toggle span {
            display: block;
            height: 3px;
            width: 100%;
            background-color: white;
            border-radius: 3px;
            transition: all 0.3s ease;
        }

        .mobile-nav {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--navy);
            z-index: 1000;
            padding: 80px 20px 20px;
            transform: translateX(-100%);
            transition: transform 0.3s ease;
        }

        .mobile-nav.active {
            transform: translateX(0);
        }

        .mobile-nav a {
            display: block;
            color: white;
            padding: 16px;
            font-size: 18px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .close-menu {
            position: absolute;
            top: 20px;
            right: 20px;
            background: none;
            border: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
        }

        /* Footer */
        footer {
            margin-top: 18px;
            padding: 16px;
            border-radius: 12px;
            background: linear-gradient(90deg, #072039, #052432);
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 12px;
        }

        /* floating CTA */
        .floating {
            position: fixed;
            left: 12px;
            right: 12px;
            bottom: 14px;
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            gap: 10px;
            z-index: 80;
            background: linear-gradient(90deg, #fff, #fff);
            padding: 8px;
            border-radius: 14px;
            box-shadow: 0 12px 40px rgba(10,31,68,0.12);
        }

        .floating a {
            flex: 1;
            text-align: center;
            padding: 12px;
            border-radius: 10px;
            font-weight: 800;
            text-decoration: none;
        }

        .floating .call {
            background: var(--navy);
            color: #fff;
        }

        .floating .line {
            background: var(--accent);
            color: #111;
        }

        /* Social Media Floating */
        .social-floating {
            position: fixed;
            right: 20px;
            bottom: 100px;
            z-index: 90;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .social-btn {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 20px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            transition: all 0.3s;
            cursor: pointer;
        }

        .social-btn:hover {
            transform: scale(1.1);
        }

        .social-fb {
            background: var(--facebook);
        }

        .social-tiktok {
            background: var(--tiktok);
        }

        .social-expand {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--navy);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 20px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            cursor: pointer;
            transition: all 0.3s;
        }

        .social-expand:hover {
            transform: scale(1.1);
        }

        .social-menu {
            display: none;
            flex-direction: column;
            gap: 10px;
        }

        .social-menu.active {
            display: flex;
        }

        /* micro interactions */
        .pulse {
            animation: pulse 1.6s infinite;
        }

        @keyframes pulse {
            0% { transform: translateY(0); }
            50% { transform: translateY(-3px); }
            100% { transform: translateY(0); }
        }

        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid rgba(255,255,255,.3);
            border-radius: 50%;
            border-top-color: #fff;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* Form validation */
        .error-message {
            color: var(--error);
            font-size: 12px;
            margin-top: 4px;
            display: none;
        }

        .input-error {
            border-color: var(--error);
        }

        .success-message {
            color: var(--success);
            font-size: 14px;
            margin-top: 8px;
            display: none;
        }

        /* New Features Styles */
        
        /* Real-time Tracking */
        .tracking-container {
            background: var(--card);
            padding: 20px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            margin-top: 20px;
        }
        
        .tracking-map {
            height: 200px;
            background: #e9f2ff;
            border-radius: 8px;
            margin: 15px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--muted);
        }
        
        .tracking-steps {
            display: flex;
            justify-content: space-between;
            position: relative;
            margin: 20px 0;
        }
        
        .tracking-steps:before {
            content: '';
            position: absolute;
            top: 15px;
            left: 0;
            right: 0;
            height: 2px;
            background: #e6e9ee;
            z-index: 1;
        }
        
        .tracking-step {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            z-index: 2;
        }
        
        .step-icon {
            width: 32px;
            height: 32px;
            border-radius: 50%;
            background: #e6e9ee;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 8px;
            font-size: 14px;
        }
        
        .step-active .step-icon {
            background: var(--success);
            color: white;
        }
        
        .step-label {
            font-size: 12px;
            text-align: center;
            color: var(--muted);
        }
        
        .step-active .step-label {
            color: var(--navy);
            font-weight: 600;
        }
        
        /* AI Chatbot */
        .chatbot-toggle {
            position: fixed;
            bottom: 80px;
            left: 20px;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: var(--navy);
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            cursor: pointer;
            z-index: 90;
            font-size: 24px;
        }
        
        .chatbot-container {
            position: fixed;
            bottom: 150px;
            left: 20px;
            width: 320px;
            height: 400px;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            z-index: 90;
            display: none;
            flex-direction: column;
            overflow: hidden;
        }
        
        .chatbot-header {
            background: var(--navy);
            color: white;
            padding: 12px 16px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .chatbot-messages {
            flex: 1;
            padding: 16px;
            overflow-y: auto;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        
        .message {
            padding: 10px 12px;
            border-radius: 12px;
            max-width: 80%;
            font-size: 14px;
        }
        
        .message-bot {
            background: #f0f4f8;
            align-self: flex-start;
        }
        
        .message-user {
            background: var(--navy);
            color: white;
            align-self: flex-end;
        }
        
        .chatbot-input {
            padding: 12px 16px;
            border-top: 1px solid #e6e9ee;
            display: flex;
            gap: 8px;
        }
        
        .chatbot-input input {
            flex: 1;
            border: 1px solid #e6e9ee;
            border-radius: 20px;
            padding: 8px 12px;
        }
        
        .chatbot-input button {
            background: var(--navy);
            color: white;
            border: none;
            border-radius: 50%;
            width: 36px;
            height: 36px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
        }
        
        /* Analytics Dashboard (Admin) */
        .analytics-panel {
            background: var(--card);
            padding: 20px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            margin-top: 20px;
        }
        
        .kpi-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 16px;
            margin-top: 16px;
        }
        
        .kpi-card {
            background: #f7f9fb;
            padding: 16px;
            border-radius: 8px;
            text-align: center;
        }
        
        .kpi-value {
            font-size: 24px;
            font-weight: 800;
            color: var(--navy);
            margin: 8px 0;
        }
        
        .kpi-label {
            font-size: 12px;
            color: var(--muted);
        }
        
        /* Multi-language */
        .lang-selector {
            position: relative;
            display: inline-block;
        }
        
        .lang-btn {
            background: rgba(255,255,255,0.1);
            border: none;
            color: white;
            padding: 6px 10px;
            border-radius: 6px;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 6px;
        }
        
        .lang-dropdown {
            position: absolute;
            top: 100%;
            right: 0;
            background: white;
            border-radius: 8px;
            box-shadow: var(--shadow);
            padding: 8px 0;
            min-width: 120px;
            display: none;
            z-index: 100;
        }
        
        .lang-dropdown.active {
            display: block;
        }
        
        .lang-option {
            padding: 8px 16px;
            cursor: pointer;
            color: var(--navy);
        }
        
        .lang-option:hover {
            background: #f7f9fb;
        }
        
        /* Advanced Booking */
        .booking-calendar {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 8px;
            margin-top: 16px;
        }
        
        .calendar-header {
            text-align: center;
            font-weight: 600;
            padding: 8px;
            color: var(--navy);
        }
        
        .calendar-day {
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.2s;
        }
        
        .calendar-day:hover {
            background: #f0f4f8;
        }
        
        .calendar-day.selected {
            background: var(--navy);
            color: white;
        }
        
        .calendar-day.disabled {
            color: #ccc;
            cursor: not-allowed;
        }
        
        /* NEW: Order Management System */
        .order-management {
            background: var(--card);
            padding: 20px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            margin-top: 20px;
        }
        
        .order-form {
            display: grid;
            gap: 12px;
            margin-top: 16px;
        }
        
        .order-list {
            margin-top: 20px;
        }
        
        .order-item {
            background: #f7f9fb;
            padding: 16px;
            border-radius: 8px;
            margin-bottom: 12px;
            border-left: 4px solid var(--navy);
        }
        
        .order-status {
            display: inline-block;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 12px;
            font-weight: 600;
            margin-left: 8px;
        }
        
        .status-pending {
            background: #FEF3C7;
            color: #92400E;
        }
        
        .status-confirmed {
            background: #D1FAE5;
            color: #065F46;
        }
        
        .status-shipping {
            background: #DBEAFE;
            color: #1E40AF;
        }
        
        .status-delivered {
            background: #E5E7EB;
            color: #374151;
        }
        
        /* NEW: Notification System */
        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 16px;
            border-radius: 8px;
            box-shadow: var(--shadow);
            z-index: 1000;
            display: none;
            max-width: 300px;
        }
        
        .notification-success {
            background: var(--success);
            color: white;
        }
        
        .notification-error {
            background: var(--error);
            color: white;
        }
        
        /* NEW: Customer Management */
        .customer-section {
            background: var(--card);
            padding: 20px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            margin-top: 20px;
        }
        
        .customer-list {
            margin-top: 16px;
        }
        
        .customer-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px;
            border-bottom: 1px solid #e6e9ee;
        }
        
        /* responsive */
        @media (min-width: 960px) {
            .hero {
                grid-template-columns: 1fr .55fr;
            }
            .grid-2 {
                grid-template-columns: 1fr .48fr;
            }
            .gallery {
                grid-template-columns: repeat(4, 1fr);
            }
            .est-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            .services {
                grid-template-columns: repeat(3, 1fr);
            }
            .pet-hero {
                gap: 20px;
            }
            .featured-services {
                grid-template-columns: repeat(3, 1fr);
            }
            .testimonials {
                grid-template-columns: repeat(3, 1fr);
            }
            .kpi-grid {
                grid-template-columns: repeat(4, 1fr);
            }
        }

        @media (max-width: 959px) {
            nav.main-nav {
                display: none;
            }
            
            .menu-toggle {
                display: flex;
            }
            
            .social-floating {
                right: 10px;
                bottom: 90px;
            }
            
            .slide {
                height: 250px;
            }
            
            .trust-badges {
                flex-direction: column;
                align-items: center;
            }
            
            .trust-item {
                width: 100%;
                max-width: 300px;
                justify-content: center;
            }
            
            .chatbot-container {
                width: calc(100% - 40px);
                left: 20px;
                right: 20px;
            }
        }

        /* tiny util */
        .center {
            text-align: center;
        }
        .muted-quiet {
            color: #9CA3AF;
        }
        .hidden {
            display: none;
        }
    </style>
</head>

<body>
    <!-- Schema.org Structured Data -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "LocalBusiness",
        "name": "ทรัพย์สินขนส่ง",
        "description": "บริการขนส่งสัตว์เลี้ยง มอเตอร์ไซค์ ย้ายบ้านทั่วไทย ทีมงานขับเองทุกงาน",
        "url": "https://ทรัพย์สินขนส่ง.com",
        "telephone": "+66-96-410-4396",
        "address": {
            "@type": "PostalAddress",
            "addressCountry": "TH"
        },
        "areaServed": "Thailand",
        "serviceType": "ขนส่งสัตว์เลี้ยง, ส่งมอเตอร์ไซค์, ย้ายบ้าน",
        "openingHours": "Mo-Su 08:00-20:00"
    }
    </script>

    <div class="wrap">
        <header>
            <div class="brand">
                <div class="logo">
                    <img src="https://i.ibb.co/d4DWPmM3/file-0000000044e47208ac399f062eae9068.png" alt="ทรัพย์สินขนส่ง" style="width:100%;height:100%;border-radius:10px;object-fit:cover">
                </div>
                <div>
                    <h1>ทรัพย์สินขนส่ง</h1>
                    <p>ทีมงานขับเองทุกงาน • รับทั่วไทย</p>
                </div>
            </div>
            
            <nav class="main-nav" aria-label="หลัก">
                <a href="#hero">หน้าแรก</a>
                <a href="#services">บริการ</a>
                <a href="#featured">บริการยอดนิยม</a>
                <a href="#estimator">เช็คราคา</a>
                <a href="#pet">ส่งสัตว์เลี้ยง</a>
                <a href="#reviews">รีวิว</a>
                <a href="#contact">ติดต่อ</a>
            </nav>
            
            <div class="header-actions" role="navigation" aria-label="actions">
                <div class="lang-selector">
                    <button class="lang-btn" id="langToggle" aria-expanded="false" aria-haspopup="true">
                        TH <span style="font-size:12px">▼</span>
                    </button>
                    <div class="lang-dropdown" id="langDropdown">
                        <div class="lang-option" data-lang="th">ไทย</div>
                        <div class="lang-option" data-lang="en">English</div>
                        <div class="lang-option" data-lang="zh">中文</div>
                    </div>
                </div>
                <div class="badge">ตอบไวภายใน 15 นาที</div>
                <a class="btn btn-call" href="tel:0964104396" aria-label="โทร">โทร</a>
                <a class="btn btn-line pulse" href="https://lin.ee/nOeqY7l3" target="_blank" rel="noopener" aria-label="แอดไลน์">ทัก LINE</a>
            </div>
            
            <button class="menu-toggle" aria-label="เปิดเมนูหลัก" aria-expanded="false" aria-controls="mobileNav">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </header>

        <!-- Mobile Navigation -->
        <nav class="mobile-nav" id="mobileNav">
            <button class="close-menu" aria-label="ปิดเมนู">×</button>
            <a href="#hero">หน้าแรก</a>
            <a href="#services">บริการ</a>
            <a href="#featured">บริการยอดนิยม</a>
            <a href="#estimator">เช็คราคา</a>
            <a href="#pet">ส่งสัตว์เลี้ยง</a>
            <a href="#reviews">รีวิว</a>
            <a href="#contact">ติดต่อ</a>
            <div style="margin-top: 20px; padding: 16px; border-top: 1px solid rgba(255,255,255,0.1);">
                <a href="tel:0964104396" style="display: block; background: var(--accent); color: #111; text-align: center; padding: 12px; border-radius: 10px; font-weight: 800; margin-bottom: 10px;">โทร 096-410-4396</a>
                <a href="https://lin.ee/nOeqY7l3" target="_blank" style="display: block; background: white; color: var(--navy); text-align: center; padding: 12px; border-radius: 10px; font-weight: 800;">ทัก LINE</a>
            </div>
        </nav>

        <main role="main">
            <!-- Hero Section -->
            <section id="hero" class="hero" aria-labelledby="hero-title">
                <div class="hero-card">
                    <h1 id="hero-title" class="hero-title">ทรัพย์สินขนส่ง — ขับเองทุกงาน ส่งทั่วไทย</h1>
                    <p class="lead">บริการขนส่งสินค้า สัตว์เลี้ยง มอเตอร์ไซค์ และย้ายบ้าน — ทีมงานขับเอง มาตรฐานมืออาชีพ ตอบไว ทำงานตรงเวลา</p>
                    
                    <div class="cta-row">
                        <a class="btn btn-line" href="https://lin.ee/nOeqY7l3" target="_blank">ทัก LINE ขอราคา</a>
                        <a class="btn btn-call" href="tel:0964104396">โทรเลย 096-410-4396</a>
                        <a class="btn" href="#estimator" style="background:transparent;border:1px solid var(--navy);color:var(--navy)">เช็คราคาด่วน</a>
                    </div>
                    
                    <div style="margin-top:12px;display:flex;gap:8px;flex-wrap:wrap">
                        <div class="pill">ขับเองทุกงาน</div>
                        <div class="pill">รายงานตลอดทาง</div>
                        <div class="pill">ชดเชยสูงสุด 10,000 ฿</div>
                    </div>
                    
                    <!-- Real-time Tracking Demo -->
                    <div class="tracking-container" id="trackingDemo">
                        <h3 style="margin:0 0 12px 0;color:var(--navy)">ติดตามพัสดุแบบเรียลไทม์</h3>
                        <div class="tracking-map" id="trackingMap">
                            กำลังโหลดแผนที่...
                        </div>
                        <div class="tracking-steps">
                            <div class="tracking-step step-active">
                                <div class="step-icon">✓</div>
                                <div class="step-label">รับพัสดุ</div>
                            </div>
                            <div class="tracking-step step-active">
                                <div class="step-icon">✓</div>
                                <div class="step-label">อยู่ที่ศูนย์</div>
                            </div>
                            <div class="tracking-step">
                                <div class="step-icon">3</div>
                                <div class="step-label">กำลังขนส่ง</div>
                            </div>
                            <div class="tracking-step">
                                <div class="step-icon">4</div>
                                <div class="step-label">ถึงปลายทาง</div>
                            </div>
                        </div>
                        <button class="btn" style="background:var(--navy);color:#fff;width:100%" id="simulateTracking">
                            จำลองการอัพเดทสถานะ
                        </button>
                    </div>
                </div>
                
                <aside class="panel" aria-label="quick estimator">
                    <h3 style="margin:0 0 6px 0;color:var(--navy)">คำนวณราคาเร็ว</h3>
                    <p class="muted small" style="margin:0 0 10px 0">เลือกต้นทาง-ปลายทาง และประเภทงาน — ดูราคาโดยประมาณก่อนทัก</p>
                    
                    <div class="est-grid" id="estimator">
                        <div>
                            <label for="from">ต้นทาง</label>
                            <select id="from">
                                <option value="">— เลือกต้นทาง —</option>
                                <option value="bkk">กรุงเทพ / ปริมณฑล</option>
                                <option value="central">ภาคกลาง</option>
                                <option value="east">ภาคตะวันออก</option>
                                <option value="north">ภาคเหนือ</option>
                                <option value="isan">ภาคอีสาน</option>
                                <option value="south1">ภาคใต้ตอนบน</option>
                                <option value="south2">ภาคใต้ตอนล่าง / เกาะ</option>
                            </select>
                            <div id="from-error" class="error-message">กรุณาเลือกต้นทาง</div>
                        </div>
                        <div>
                            <label for="to">ปลายทาง</label>
                            <select id="to">
                                <option value="">— เลือกปลายทาง —</option>
                                <option value="bkk">กรุงเทพ / ปริมณฑล</option>
                                <option value="central">ภาคกลาง</option>
                                <option value="east">ภาคตะวันออก</option>
                                <option value="north">ภาคเหนือ</option>
                                <option value="isan">ภาคอีสาน</option>
                                <option value="south1">ภาคใต้ตอนบน</option>
                                <option value="south2">ภาคใต้ตอนล่าง / เกาะ</option>
                            </select>
                            <div id="to-error" class="error-message">กรุณาเลือกปลายทาง</div>
                        </div>
                    </div>
                    
                    <div class="mt">
                        <label for="jobtype">ประเภทงาน</label>
                        <select id="jobtype">
                            <option value="normal">งานเหมา / งานด่วน</option>
                            <option value="parcel">ฝากส่งสินค้า</option>
                            <option value="bike">ส่งมอเตอร์ไซค์</option>
                            <option value="house">ย้ายบ้าน</option>
                            <option value="pet">ส่งสัตว์เลี้ยง</option>
                        </select>
                    </div>
                    
                    <div class="mt row">
                        <div>
                            <label for="size">ขนาด/น้ำหนัก (ถ้ามี)</label>
                            <input id="size" placeholder="เช่น 30 kg หรือ ขนาดกล่อง 120x60x60" />
                        </div>
                        <div>
                            <label for="phone">เบอร์ติดต่อ</label>
                            <input id="phone" type="tel" placeholder="08x-xxx-xxxx" inputmode="tel" />
                            <div id="phone-error" class="error-message">กรุณากรอกเบอร์โทรศัพท์ให้ถูกต้อง</div>
                        </div>
                    </div>
                    
                    <!-- Advanced Booking -->
                    <div class="mt">
                        <label for="booking-date">วันที่ต้องการบริการ (เลือกได้)</label>
                        <div class="booking-calendar" id="bookingCalendar">
                            <!-- Calendar will be generated by JavaScript -->
                        </div>
                    </div>
                    
                    <div style="display:flex;gap:8px;margin-top:12px">
                        <button id="calc" class="btn" style="background:var(--navy);color:#fff;padding:10px 12px;border-radius:10px">
                            <span id="calc-text">คำนวณราคา</span>
                            <span id="calc-loading" class="loading hidden"></span>
                        </button>
                        <button id="calc-send" class="btn btn-line" style="display:none">ส่งผลไป LINE</button>
                    </div>
                    
                    <div id="est-result" class="est-result" style="display:none"></div>
                    <div id="est-note" class="muted small" style="display:none">* ราคาโดยประมาณ — ยืนยันอีกครั้งใน LINE</div>
                    <div id="est-success" class="success-message"></div>
                </aside>
            </section>

            <!-- Trust Signals -->
            <div class="trust-badges">
                <div class="trust-item">✅ รับประกันความปลอดภัย</div>
                <div class="trust-item">🛡️ รับผิดชอบสูงสุด 10,000 บาท</div>
                <div class="trust-item">⏰ ตอบกลับภายใน 15 นาที</div>
                <div class="trust-item">🚚 ทีมงานขับเองทุกงาน</div>
            </div>

            <!-- Services Section -->
            <section id="services" class="section" aria-labelledby="services-title">
                <h2 id="services-title" style="margin:0 0 8px 0;color:var(--navy)">บริการของเรา</h2>
                <div class="services">
                    <div class="service">
                        <div class="icon">🚚</div>
                        <div>
                            <h3 style="margin:0">งานเหมา / งานด่วน</h3>
                            <p class="muted small" style="margin-top:6px">ส่งด่วน ข้ามจังหวัด — ทีมงานพร้อมออกทันที</p>
                        </div>
                    </div>
                    <div class="service">
                        <div class="icon">🐶</div>
                        <div>
                            <h3 style="margin:0">ส่งสัตว์เลี้ยง (Pet Mover)</h3>
                            <p class="muted small" style="margin-top:6px">แยกช่องระบายอากาศ รายงานสภาพตลอดทาง และการดูแลพิเศษ</p>
                        </div>
                    </div>
                    <div class="service">
                        <div class="icon">🏍️</div>
                        <div>
                            <h3 style="margin:0">ส่งมอเตอร์ไซค์</h3>
                            <p class="muted small" style="margin-top:6px">ล็อกแน่น ใช้อุปกรณ์รองรับ ป้องกันรอยและความเสียหาย</p>
                        </div>
                    </div>
                    <div class="service">
                        <div class="icon">🏠</div>
                        <div>
                            <h3 style="margin:0">ย้ายบ้าน / คอนโด</h3>
                            <p class="muted small" style="margin-top:6px">แพ็กกิ้ง ถอดประกอบ และขนย้ายแบบครบวงจร</p>
                        </div>
                    </div>
                    <div class="service">
                        <div class="icon">📦</div>
                        <div>
                            <h3 style="margin:0">ฝากส่งสินค้า</h3>
                            <p class="muted small" style="margin-top:6px">รับสินค้าจากโรงงาน/ร้านค้า พร้อมจัดส่งตามตาราง</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Featured Services Section -->
            <section id="featured" class="section" aria-labelledby="featured-title">
                <h2 id="featured-title" style="margin:0 0 8px 0;color:var(--navy)">บริการยอดนิยม</h2>
                <div class="featured-services">
                    <div class="featured-service">
                        <h3>🚚 ส่งมอเตอร์ไซค์</h3>
                        <p>บริการส่งมอเตอร์ไซค์ทั่วไทย ปลอดภัย ไร้รอยขีดข่วน</p>
                        <div class="price">เริ่มต้น 800 บาท</div>
                        <a href="#estimator" style="background:var(--accent);color:#111;padding:10px;border-radius:8px;text-align:center;font-weight:700;margin-top:auto;">คำนวณราคา</a>
                    </div>
                    <div class="featured-service">
                        <h3>🐶 ส่งสัตว์เลี้ยง</h3>
                        <p>บริการส่งสัตว์เลี้ยงโดยเฉพาะ ดูแลอย่างใส่ใจตลอดทาง</p>
                        <div class="price">เริ่มต้น 600 บาท</div>
                        <a href="#estimator" style="background:var(--accent);color:#111;padding:10px;border-radius:8px;text-align:center;font-weight:700;margin-top:auto;">คำนวณราคา</a>
                    </div>
                    <div class="featured-service">
                        <h3>🏠 ย้ายบ้าน</h3>
                        <p>บริการย้ายบ้านครบวงจร ตั้งแต่แพ็กกิ้งจนถึงจัดวาง</p>
                        <div class="price">เริ่มต้น 1,500 บาท</div>
                        <a href="#estimator" style="background:var(--accent);color:#111;padding:10px;border-radius:8px;text-align:center;font-weight:700;margin-top:auto;">คำนวณราคา</a>
                    </div>
                </div>
            </section>

            <!-- NEW: Order Management System -->
            <section class="section order-management" id="orderManagement">
                <h2 style="margin:0 0 16px 0;color:var(--navy)">ระบบจัดการคำสั่งซื้อ</h2>
                <div class="order-form">
                    <div class="row">
                        <div>
                            <label for="customer-name">ชื่อลูกค้า</label>
                            <input type="text" id="customer-name" placeholder="ชื่อ-นามสกุล">
                        </div>
                        <div>
                            <label for="customer-phone">เบอร์โทร</label>
                            <input type="tel" id="customer-phone" placeholder="08x-xxx-xxxx">
                        </div>
                    </div>
                    <div class="row">
                        <div>
                            <label for="order-type">ประเภทบริการ</label>
                            <select id="order-type">
                                <option value="bike">ส่งมอเตอร์ไซค์</option>
                                <option value="pet">ส่งสัตว์เลี้ยง</option>
                                <option value="house">ย้ายบ้าน</option>
                                <option value="parcel">ส่งสินค้า</option>
                                <option value="normal">งานเหมา/ด่วน</option>
                            </select>
                        </div>
                        <div>
                            <label for="order-price">ราคา (บาท)</label>
                            <input type="number" id="order-price" placeholder="0">
                        </div>
                    </div>
                    <div>
                        <label for="order-details">รายละเอียดเพิ่มเติม</label>
                        <textarea id="order-details" rows="3" placeholder="รายละเอียดคำสั่งซื้อ..."></textarea>
                    </div>
                    <button id="add-order" class="btn" style="background:var(--navy);color:#fff">เพิ่มคำสั่งซื้อ</button>
                </div>
                
                <div class="order-list" id="orderList">
                    <h3 style="margin:20px 0 12px 0">รายการคำสั่งซื้อล่าสุด</h3>
                    <!-- Orders will be populated by JavaScript -->
                </div>
            </section>

            <!-- Analytics Dashboard (Hidden by default, accessible via special URL) -->
            <div id="analyticsDashboard" class="analytics-panel" style="display:none">
                <h3 style="margin:0 0 16px 0;color:var(--navy)">แดชบอร์ดวิเคราะห์ข้อมูล</h3>
                <div class="kpi-grid">
                    <div class="kpi-card">
                        <div class="kpi-value" id="kpiOrders">0</div>
                        <div class="kpi-label">คำสั่งซื้อวันนี้</div>
                    </div>
                    <div class="kpi-card">
                        <div class="kpi-value" id="kpiRevenue">0</div>
                        <div class="kpi-label">รายได้วันนี้ (บาท)</div>
                    </div>
                    <div class="kpi-card">
                        <div class="kpi-value" id="kpiConversion">0%</div>
                        <div class="kpi-label">อัตราการแปลง</div>
                    </div>
                    <div class="kpi-card">
                        <div class="kpi-value" id="kpiSatisfaction">0%</div>
                        <div class="kpi-label">ความพึงพอใจ</div>
                    </div>
                </div>
                <button class="btn" style="background:var(--navy);color:#fff;margin-top:16px" id="refreshAnalytics">
                    รีเฟรชข้อมูล
                </button>
            </div>

            <!-- Pet Mover Detailed Section -->
            <section id="pet" class="section" aria-labelledby="pet-title">
                <h2 id="pet-title" style="margin:0 0 8px 0;color:var(--navy)">บริการส่งสัตว์เลี้ยง — รายละเอียด</h2>
                <div class="pet-hero">
                    <div class="left panel">
                        <h3 style="margin:0 0 6px 0">บริการของเรา (Pet Mover)</h3>
                        <p class="muted small" style="margin:0 0 10px 0">เราดูแลสัตว์เลี้ยงของลูกค้าเหมือนเป็นของเราเอง — แยกช่องพัก รายงานรูปสภาพ ระยะพักตามความเหมาะสม</p>
                        
                        <div style="display:grid;gap:10px;margin-top:8px">
                            <div class="panel">
                                <strong>สิ่งที่รวมในบริการ</strong>
                                <ul style="margin:8px 0 0 18px">
                                    <li class="muted small">แยกช่องพัก/กรงและยึดล็อกอย่างปลอดภัย</li>
                                    <li class="muted small">รายงานรูป/ข้อความตามช่วงทาง</li>
                                    <li class="muted small">พักให้ตามสภาพสัตว์และระยะทาง</li>
                                    <li class="muted small">มีอุปกรณ์รองรับ (กรง/ผ้า/คลิปล็อก)</li>
                                </ul>
                            </div>
                            <div class="panel">
                                <strong>นโยบายความรับผิดชอบ</strong>
                                <div class="muted small" style="margin-top:8px">เรารับผิดชอบตามเงื่อนไขที่ตกลง — ชดเชยตามหลักฐาน ภาพถ่าย และมูลค่าจริง สูงสุดจนถึง 10,000 บาท (รายละเอียดในหน้าติดต่อ)</div>
                            </div>
                            <div class="panel">
                                <strong>ราคาเบื้องต้น (ตัวอย่าง)</strong>
                                <div class="muted small" style="margin-top:8px">กทม → ภาคใต้ตอนล่าง/เกาะ เริ่มประมาณ 2,500 บาท / กทม → ภาคเหนือ เริ่มประมาณ 1,500 บาท (ราคาจริงขึ้นกับขนาดและเงื่อนไข)</div>
                            </div>
                            <div class="panel">
                                <strong>📞 ติดต่อสอบถามบริการสัตว์เลี้ยง</strong>
                                <div class="muted small" style="margin-top:8px">
                                    สนใจบริการส่งสัตว์เลี้ยงโดยเฉพาะ? ติดต่อเราได้ที่ Facebook พิเศษสำหรับบริการสัตว์เลี้ยง   
                                    <strong>แอดมินคนสวย 💖 รีวิวเพียบ!</strong>
                                    <a href="https://www.facebook.com/share/1BcPKfeDgW/" target="_blank" style="display: inline-block; margin-top: 8px; padding: 8px 12px; background: var(--facebook); color: white; border-radius: 8px; font-weight: bold;">ติดต่อผ่าน Facebook</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="right panel">
                        <h4 style="margin:0 0 8px 0;color:var(--navy)">เช็คราคาเฉพาะ Pet Mover</h4>
                        
                        <label for="pe-from">ต้นทาง</label>
                        <select id="pe-from">
                            <option value="">— เลือกต้นทาง —</option>
                            <option value="bkk">กรุงเทพ / ปริมณฑล</option>
                            <option value="central">ภาคกลาง</option>
                            <option value="north">ภาคเหนือ</option>
                            <option value="isan">ภาคอีสาน</option>
                            <option value="south1">ภาคใต้ตอนบน</option>
                            <option value="south2">ภาคใต้ตอนล่าง / เกาะ</option>
                        </select>
                        <div id="pe-from-error" class="error-message">กรุณาเลือกต้นทาง</div>
                        
                        <label class="mt" for="pe-to">ปลายทาง</label>
                        <select id="pe-to">
                            <option value="">— เลือกปลายทาง —</option>
                            <option value="bkk">กรุงเทพ / ปริมณฑล</option>
                            <option value="central">ภาคกลาง</option>
                            <option value="north">ภาคเหนือ</option>
                            <option value="isan">ภาคอีสาน</option>
                            <option value="south1">ภาคใต้ตอนบน</option>
                            <option value="south2">ภาคใต้ตอนล่าง / เกาะ</option>
                        </select>
                        <div id="pe-to-error" class="error-message">กรุณาเลือกปลายทาง</div>
                        
                        <label class="mt" for="pe-size">ขนาด/น้ำหนักสัตว์</label>
                        <select id="pe-size">
                            <option value="small">เล็ก (≤10 kg)</option>
                            <option value="medium">กลาง (11–25 kg)</option>
                            <option value="large">ใหญ่ (26–50 kg)</option>
                            <option value="xlarge">ใหญ่มาก (>50 kg)</option>
                        </select>
                        
                        <label class="mt" for="pe-date">วันที่ประมาณเดินทาง</label>
                        <input id="pe-date" type="date" />
                        
                        <label class="mt" for="pe-phone">เบอร์ติดต่อ</label>
                        <input id="pe-phone" type="tel" inputmode="tel" placeholder="08x-xxx-xxxx" />
                        <div id="pe-phone-error" class="error-message">กรุณากรอกเบอร์โทรศัพท์ให้ถูกต้อง</div>
                        
                        <div style="display:flex;gap:8px;margin-top:12px">
                            <button id="pe-calc" class="btn" style="background:var(--navy);color:#fff">
                                <span id="pe-calc-text">คำนวณราคา</span>
                                <span id="pe-calc-loading" class="loading hidden"></span>
                            </button>
                            <button id="pe-send" class="btn btn-line" style="display:none">ส่งข้อมูลไป LINE</button>
                        </div>
                        
                        <div id="pe-result" class="est-result" style="display:none"></div>
                        <div id="pe-note" class="muted small" style="display:none">* เป็นราคาโดยประมาณ — ยืนยันใน LINE ก่อนเริ่มงาน</div>
                        <div id="pe-success" class="success-message"></div>
                    </div>
                </div>
            </section>

            <!-- Customer Testimonials -->
            <section class="section" aria-labelledby="testimonials-title">
                <h2 id="testimonials-title" style="margin:0 0 8px 0;color:var(--navy)">เสียงจากลูกค้าของเรา</h2>
                <div class="testimonials">
                    <div class="testimonial">
                        <div class="testimonial-rating">★★★★★</div>
                        <p>"ส่งน้องหมาถึงบ้านปลอดภัยมาก รายงานตลอดทาง ขอบคุณทีมงานมากๆ เลยค่ะ"</p>
                        <div class="muted-quiet" style="margin-top:12px">— คุณสมชาย, ขนส่งสัตว์เลี้ยงจากกรุงเทพไปเชียงใหม่</div>
                    </div>
                    <div class="testimonial">
                        <div class="testimonial-rating">★★★★★</div>
                        <p>"มอเตอร์ไซค์ไปถึงอย่างปลอดภัย ไม่มีรอยขีดข่วนเลย ประทับใจบริการมากครับ"</p>
                        <div class="muted-quiet" style="margin-top:12px">— คุณอร, ขนส่งมอเตอร์ไซค์จากภูเก็ตไปกรุงเทพ</div>
                    </div>
                    <div class="testimonial">
                        <div class="testimonial-rating">★★★★★</div>
                        <p>"ย้ายบ้านรวดเร็ว ทีมงานช่วยแพ็กของให้เรียบร้อยมาก ราคาก็คุ้มค่าครับ"</p>
                        <div class="muted-quiet" style="margin-top:12px">— คุณปิ่น, ย้ายบ้านจากบางพลีไปนนทบุรี</div>
                    </div>
                </div>
            </section>

            <!-- Gallery & Reviews Section -->
            <section id="reviews" class="section" aria-labelledby="reviews-title">
                <h2 id="reviews-title" style="margin:0 0 8px 0;color:var(--navy)">ภาพงานจริง & รีวิว</h2>
                
                <!-- รูปภาพมอเตอร์ไซค์แบบสไลด์ -->
                <div class="slider-container">
                    <div class="slider" id="bikeSlider">
                        <!-- รูปที่ 1 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/0yJ9tS6L/1763048114159.jpg" alt="ขนส่งมอเตอร์ไซค์ 1" loading="lazy">
                            <div class="slide-caption">มอเตอร์ไซค์ก่อนขนส่ง - จัดเตรียมอุปกรณ์ป้องกัน</div>
                        </div>
                        <!-- รูปที่ 2 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/0jr83MLy/1763048266051.jpg" alt="ขนส่งมอเตอร์ไซค์ 2" loading="lazy">
                            <div class="slide-caption">การห่อหุ้มมอเตอร์ไซค์อย่างพิถีพิถัน</div>
                        </div>
                        <!-- รูปที่ 3 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/Pvx967B7/1763048342426.jpg" alt="ขนส่งมอเตอร์ไซค์ 3" loading="lazy">
                            <div class="slide-caption">ยึดล็อกมอเตอร์ไซค์อย่างปลอดภัยในรถขนส่ง</div>
                        </div>
                        <!-- รูปที่ 4 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/YB0T71JT/1763048215131.jpg" alt="ขนส่งมอเตอร์ไซค์ 4" loading="lazy">
                            <div class="slide-caption">มอเตอร์ไซค์พร้อมส่งถึงมือลูกค้า</div>
                        </div>
                        <!-- รูปที่ 5 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/hRyHQwV2/1763048331927.jpg" alt="ขนส่งมอเตอร์ไซค์ 5" loading="lazy">
                            <div class="slide-caption">ทีมงานเช็คสภาพก่อนส่งมอบ</div>
                        </div>
                        <!-- รูปที่ 6 -->
                        <div class="slide">
                            <img src="https://i.ibb.co/S79zbrFb/1763044651491.jpg" alt="ขนส่งมอเตอร์ไซค์ 6" loading="lazy">
                            <div class="slide-caption">ลูกค้าพอใจกับการบริการ</div>
                        </div>
                    </div>
                    <div class="slider-nav">
                        <button class="slider-btn prev" onclick="prevSlide()">❮</button>
                        <button class="slider-btn next" onclick="nextSlide()">❯</button>
                    </div>
                    <div class="slider-dots" id="sliderDots">
                        <!-- Dots will be generated by JavaScript -->
                    </div>
                </div>
                
                <div class="gallery">
                    <div class="photo">
                        <img src="https://i.ibb.co/S79zbrFb/1763044651491.jpg" alt="ขนส่งสัตว์เลี้ยง" loading="lazy">
                        <div class="photo-label">ขนส่งสัตว์เลี้ยง</div>
                    </div>
                    <div class="photo">
                        <img src="https://i.ibb.co/0yJ9tS6L/1763048114159.jpg" alt="ขนส่งมอเตอร์ไซค์" loading="lazy">
                        <div class="photo-label">ขนส่งมอเตอร์ไซค์</div>
                    </div>
                    <div class="photo">
                        <img src="https://i.ibb.co/Pvx967B7/1763048342426.jpg" alt="ย้ายบ้าน" loading="lazy">
                        <div class="photo-label">ย้ายบ้าน</div>
                    </div>
                    <div class="photo">
                        <img src="https://i.ibb.co/hRyHQwV2/1763048331927.jpg" alt="ทีมงานขนส่ง" loading="lazy">
                        <div class="photo-label">ทีมงานขนส่ง</div>
                    </div>
                </div>
            </section>

            <!-- Expanded FAQ Section -->
            <section class="section" aria-labelledby="faq-expanded-title">
                <h2 id="faq-expanded-title" style="margin:0 0 8px 0;color:var(--navy)">คำถามที่พบบ่อย</h2>
                <div class="faq-expanded">
                    <div class="faq-item">
                        <div class="faq-question">ต้องเตรียมอะไรบ้างก่อนส่งสัตว์เลี้ยง?</div>
                        <div class="faq-answer">กรง/ลังที่แข็งแรง ติดป้ายชื่อ เบอร์ติดต่อ และอาหารเล็กน้อยสำหรับทางไกล รวมถึงเอกสารการฉีดวัคซีน (ถ้ามี)</div>
                    </div>
                    <div class="faq-item">
                        <div class="faq-question">มีเงื่อนไขการชดเชยความเสียหายอย่างไร?</div>
                        <div class="faq-answer">เรารับผิดชอบตามเงื่อนไขที่ตกลงและมีหลักฐานภาพ — ชดเชยตามมูลค่าจริง สูงสุด 10,000 บาท โดยต้องมีภาพก่อนและหลังการขนส่ง</div>
                    </div>
                    <div class="faq-item">
                        <div class="faq-question">วิธีการชำระเงินมีอะไรบ้าง?</div>
                        <div class="faq-answer">รับชำระเป็นเงินสด เงินโอน หรือเก็บเงินปลายทาง (กรุณาแจ้งล่วงหน้าก่อนออกเดินทาง)</div>
                    </div>
                    <div class="faq-item">
                        <div class="faq-question">สามารถติดตามสถานะการขนส่งได้ไหม?</div>
                        <div class="faq-answer">ได้แน่นอน! เราจะส่งรายงานภาพและอัพเดทสถานะผ่าน LINE ตลอดการเดินทาง</div>
                    </div>
                    <div class="faq-item">
                        <div class="faq-question">ต้องจองล่วงหน้ากี่วัน?</div>
                        <div class="faq-answer">แนะนำจองล่วงหน้า 2-3 วัน แต่หากเป็นงานด่วนสามารถติดต่อได้ตลอดเวลา เราพร้อมบริการภายใน 24 ชั่วโมง</div>
                    </div>
                </div>
            </section>

            <!-- Contact / Footer Section -->
            <section id="contact" class="section" style="margin-top:18px">
                <div class="panel" style="display:flex;gap:12px;flex-wrap:wrap;align-items:center">
                    <div style="flex:1;min-width:220px">
                        <div style="font-weight:800;color:var(--navy);font-size:18px">ทรัพย์สินขนส่ง</div>
                        <div class="muted small" style="margin-top:6px">ทีมงานขับเองทุกงาน • ดูแลงานเหมือนของเราเอง</div>
                        <div style="margin-top:8px" class="muted small">โทร: <a href="tel:0964104396">096-410-4396</a> • LINE: <a href="https://lin.ee/nOeqY7l3" target="_blank">ทรัพย์สินขนส่ง</a></div>
                        <div style="margin-top:8px" class="muted small">Facebook: <a href="https://www.facebook.com/share/1D215oaApv/" target="_blank">บริการขนส่งทั่วไป</a> • <a href="https://www.facebook.com/share/1BcPKfeDgW/" target="_blank">บริการสัตว์เลี้ยง</a></div>
                        <div style="margin-top:8px" class="muted small">TikTok: <a href="https://www.tiktok.com/@ceo_sst?_r=1&_t=ZS-91N18ogCzdX" target="_blank">@หมีอุ้มแมว</a></div>
                    </div>
                    <div style="min-width:220px">
                        <strong>ทักเราตอนนี้</strong>
                        <div style="margin-top:6px;display:flex;gap:8px;flex-wrap:wrap">
                            <a class="btn btn-line" href="https://lin.ee/nOeqY7l3" target="_blank">ทัก LINE</a>
                            <a class="btn btn-facebook" href="https://www.facebook.com/share/1D215oaApv/" target="_blank">Facebook</a>
                            <a class="btn btn-tiktok" href="https://www.tiktok.com/@ceo_sst?_r=1&_t=ZS-91N18ogCzdX" target="_blank">TikTok</a>
                            <a class="btn btn-call" href="tel:0964104396">โทร</a>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer>
            <div style="display:flex;justify-content:space-between;gap:12px;align-items:center;flex-wrap:wrap">
                <div style="display:flex;flex-direction:column;gap:6px">
                    <div style="font-weight:800;color:#fff;background:linear-gradient(90deg,#072039,#052432);padding:10px;border-radius:8px;display:inline-block">ทรัพย์สินขนส่ง</div>
                    <div class="muted small" style="margin-top:6px;color:#d1d5db">© ทรัพย์สินขนส่ง</div>
                </div>
                <div style="text-align:right;color:#d1d5db" class="small">ออกแบบเพื่อการปิดงานไว • ตอบไวภายใน 15 นาที</div>
            </div>
        </footer>
    </div>

    <!-- Floating CTA -->
    <div class="floating">
        <a class="call" href="tel:0964104396">โทรด่วน</a>
        <a class="line" href="https://lin.ee/nOeqY7l3" target="_blank">ทัก LINE</a>
    </div>

    <!-- Social Media Floating Buttons -->
    <div class="social-floating">
        <div class="social-menu" id="socialMenu">
            <a href="https://www.facebook.com/share/1D215oaApv/" target="_blank" class="social-btn social-fb" aria-label="Facebook">
                f
            </a>
            <a href="https://www.tiktok.com/@ceo_sst?_r=1&_t=ZS-91N18ogCzdX" target="_blank" class="social-btn social-tiktok" aria-label="TikTok">
                t
            </a>
        </div>
        <div class="social-expand" id="socialExpand" aria-label="เปิดช่องทางติดต่ออื่นๆ">
            +
        </div>
    </div>

    <!-- AI Chatbot -->
    <div class="chatbot-toggle" id="chatbotToggle">
        💬
    </div>
    
    <div class="chatbot-container" id="chatbotContainer">
        <div class="chatbot-header">
            <div>แชทบอททรัพย์สินขนส่ง</div>
            <button id="closeChatbot" style="background:none;border:none;color:white;cursor:pointer">×</button>
        </div>
        <div class="chatbot-messages" id="chatbotMessages">
            <div class="message message-bot">
                สวัสดีค่ะ! ยินดีต้อนรับสู่บริการทรัพย์สินขนส่ง   
                มีอะไรให้เราช่วยเหลือไหมคะ? 😊  
            </div>
        </div>
        <div class="chatbot-input">
            <input type="text" id="chatbotInput" placeholder="พิมพ์ข้อความที่นี่...">
            <button id="sendChatbotMessage">➤</button>
        </div>
    </div>

    <!-- NEW: Notification System -->
    <div class="notification" id="notification"></div>

    <!-- PWA Service Worker Registration -->
    <script>
        // Register service worker for PWA functionality
        if ('serviceWorker' in navigator) {
            window.addEventListener('load', function() {
                navigator.serviceWorker.register('/sw.js')
                    .then(function(registration) {
                        console.log('ServiceWorker registration successful');
                    })
                    .catch(function(err) {
                        console.log('ServiceWorker registration failed: ', err);
                    });
            });
        }
        
        // Create a simple manifest for PWA
        const manifest = {
            "name": "ทรัพย์สินขนส่ง",
            "short_name": "Sapsin",
            "theme_color": "#0A1F44",
            "background_color": "#F7F9FB",
            "display": "standalone",
            "start_url": "/"
        };
    </script>

    <!-- Main JavaScript -->
    <script>
        // ========== MODULE PATTERN IMPLEMENTATION ==========
        
        // App Namespace
        const SapsinApp = {
            // Configuration
            config: {
                serviceRates: {
                    normal: 8,
                    parcel: 7,
                    bike: 12,
                    house: 15,
                    pet: 10
                },
                minimumCharges: {
                    normal: 500,
                    parcel: 300,
                    bike: 800,
                    house: 1500,
                    pet: 600
                },
                zoneDistance: {
                    bkk: { bkk: 0, central: 80, east: 120, north: 650, isan: 450, south1: 800, south2: 950 },
                    central: { bkk: 80, central: 0, east: 150, north: 600, isan: 400, south1: 750, south2: 900 },
                    east: { bkk: 120, central: 150, east: 0, north: 700, isan: 500, south1: 850, south2: 1000 },
                    north: { bkk: 650, central: 600, east: 700, north: 0, isan: 550, south1: 1400, south2: 1600 },
                    isan: { bkk: 450, central: 400, east: 500, north: 550, isan: 0, south1: 1200, south2: 1400 },
                    south1: { bkk: 800, central: 750, east: 850, north: 1400, isan: 1200, south1: 0, south2: 250 },
                    south2: { bkk: 950, central: 900, east: 1000, north: 1600, isan: 1400, south1: 250, south2: 0 }
                },
                petSizeMultipliers: {
                    small: 1.0,
                    medium: 1.3,
                    large: 1.7,
                    xlarge: 2.2
                }
            },
            
            // Data Storage
            data: {
                orders: JSON.parse(localStorage.getItem('sapsin_orders')) || [],
                customers: JSON.parse(localStorage.getItem('sapsin_customers')) || []
            },
            
            // Initialize all modules
            init: function() {
                this.MobileMenu.init();
                this.Slider.init();
                this.PriceCalculator.init();
                this.Chatbot.init();
                this.Tracking.init();
                this.Analytics.init();
                this.Language.init();
                this.Booking.init();
                this.Accessibility.init();
                this.OrderManagement.init();
                this.Notification.init();
            },
            
            // Utility functions
            utils: {
                validatePhone: function(phone) {
                    const cleaned = phone.replace(/[- ]/g, '');
                    return /^0[0-9]{1,2}[0-9]{7}$/.test(cleaned);
                },
                
                showToast: function(msg, elId='est-result', t=2400, isError=false) {
                    const el = document.getElementById(elId);
                    el.style.display = 'block';
                    el.textContent = msg;
                    el.style.color = isError ? '#EF4444' : '#0A1F44';
                    
                    setTimeout(()=> {
                        if(el.textContent === msg) el.style.display = 'none';
                    }, t);
                },
                
                setLoading: function(buttonId, isLoading) {
                    const btn = document.getElementById(buttonId);
                    const text = document.getElementById(`${buttonId}-text`);
                    const loading = document.getElementById(`${buttonId}-loading`);
                    
                    if (isLoading) {
                        text.classList.add('hidden');
                        loading.classList.remove('hidden');
                        btn.disabled = true;
                    } else {
                        text.classList.remove('hidden');
                        loading.classList.add('hidden');
                        btn.disabled = false;
                    }
                },
                
                clearErrors: function() {
                    document.querySelectorAll('.error-message').forEach(el => {
                        el.style.display = 'none';
                    });
                    document.querySelectorAll('.input-error').forEach(el => {
                        el.classList.remove('input-error');
                    });
                },
                
                // NEW: Save data to localStorage
                saveData: function() {
                    try {
                        localStorage.setItem('sapsin_orders', JSON.stringify(SapsinApp.data.orders));
                        localStorage.setItem('sapsin_customers', JSON.stringify(SapsinApp.data.customers));
                    } catch(e) {
                        console.error('Error saving data:', e);
                    }
                }
            }
        };

        // Mobile Menu Module
        SapsinApp.MobileMenu = {
            init: function() {
                this.menuToggle = document.querySelector('.menu-toggle');
                this.mobileNav = document.getElementById('mobileNav');
                this.closeMenu = document.querySelector('.close-menu');
                
                this.bindEvents();
            },
            
            bindEvents: function() {
                this.menuToggle.addEventListener('click', () => this.toggleMenu());
                this.closeMenu.addEventListener('click', () => this.closeMenuFunc());
                
                // Close menu when clicking on a link
                this.mobileNav.querySelectorAll('a').forEach(link => {
                    link.addEventListener('click', () => this.closeMenuFunc());
                });
            },
            
            toggleMenu: function() {
                this.mobileNav.classList.add('active');
                document.body.style.overflow = 'hidden';
                this.menuToggle.setAttribute('aria-expanded', 'true');
            },
            
            closeMenuFunc: function() {
                this.mobileNav.classList.remove('active');
                document.body.style.overflow = '';
                this.menuToggle.setAttribute('aria-expanded', 'false');
            }
        };

        // Slider Module
        SapsinApp.Slider = {
            init: function() {
                this.currentSlide = 0;
                this.slides = document.querySelectorAll('.slide');
                this.totalSlides = this.slides.length;
                this.slideInterval = null;
                
                this.createDots();
                this.updateSlider();
                this.startAutoSlide();
                this.bindEvents();
            },
            
            createDots: function() {
                const dotsContainer = document.getElementById('sliderDots');
                dotsContainer.innerHTML = '';
                
                for (let i = 0; i < this.totalSlides; i++) {
                    const dot = document.createElement('div');
                    dot.classList.add('dot');
                    if (i === 0) dot.classList.add('active');
                    dot.addEventListener('click', () => this.goToSlide(i));
                    dotsContainer.appendChild(dot);
                }
            },
            
            updateSlider: function() {
                const slider = document.getElementById('bikeSlider');
                slider.style.transform = `translateX(-${this.currentSlide * 100}%)`;
                
                // Update active dot
                document.querySelectorAll('.dot').forEach((dot, index) => {
                    dot.classList.toggle('active', index === this.currentSlide);
                });
            },
            
            nextSlide: function() {
                this.currentSlide = (this.currentSlide + 1) % this.totalSlides;
                this.updateSlider();
                this.resetAutoSlide();
            },
            
            prevSlide: function() {
                this.currentSlide = (this.currentSlide - 1 + this.totalSlides) % this.totalSlides;
                this.updateSlider();
                this.resetAutoSlide();
            },
            
            goToSlide: function(index) {
                this.currentSlide = index;
                this.updateSlider();
                this.resetAutoSlide();
            },
            
            startAutoSlide: function() {
                this.slideInterval = setInterval(() => this.nextSlide(), 5000);
            },
            
            resetAutoSlide: function() {
                clearInterval(this.slideInterval);
                this.startAutoSlide();
            },
            
            bindEvents: function() {
                // Make functions globally available for onclick attributes
                window.nextSlide = () => this.nextSlide();
                window.prevSlide = () => this.prevSlide();
            }
        };

        // Price Calculator Module
        SapsinApp.PriceCalculator = {
            init: function() {
                this.bindEvents();
                this.restoreSavedData();
            },
            
            bindEvents: function() {
                // Main calculator
                document.getElementById('calc').addEventListener('click', () => this.calculatePrice('main'));
                document.getElementById('calc-send').addEventListener('click', () => this.sendToLine('main'));
                
                // Pet calculator
                document.getElementById('pe-calc').addEventListener('click', () => this.calculatePrice('pet'));
                document.getElementById('pe-send').addEventListener('click', () => this.sendToLine('pet'));
                
                // Enter key support
                ['phone','pe-phone'].forEach(id => {
                    const el = document.getElementById(id);
                    if(!el) return;
                    
                    el.addEventListener('keydown', (e) => {
                        if(e.key === 'Enter'){
                            e.preventDefault();
                            if(id === 'phone') {
                                this.calculatePrice('main');
                            } else {
                                this.calculatePrice('pet');
                            }
                        }
                    });
                });
            },
            
            calculatePrice: function(type) {
                SapsinApp.utils.clearErrors();
                
                const prefix = type === 'pet' ? 'pe-' : '';
                const f = document.getElementById(`${prefix}from`).value;
                const t = document.getElementById(`${prefix}to`).value;
                const jt = type === 'pet' ? 'pet' : document.getElementById('jobtype').value;
                const phone = document.getElementById(`${prefix}phone`).value.trim();
                const size = type === 'pet' ? document.getElementById(`${prefix}size`).value : null;
                
                let hasError = false;
                
                if(!f){
                    document.getElementById(`${prefix}from-error`).style.display = 'block';
                    document.getElementById(`${prefix}from`).classList.add('input-error');
                    hasError = true;
                }
                
                if(!t){
                    document.getElementById(`${prefix}to-error`).style.display = 'block';
                    document.getElementById(`${prefix}to`).classList.add('input-error');
                    hasError = true;
                }
                
                if(!phone || !SapsinApp.utils.validatePhone(phone)){
                    document.getElementById(`${prefix}phone-error`).style.display = 'block';
                    document.getElementById(`${prefix}phone`).classList.add('input-error');
                    hasError = true;
                }
                
                if(hasError) return;
                
                SapsinApp.utils.setLoading(`${prefix}calc`, true);
                
                // Simulate API call delay
                setTimeout(() => {
                    const price = this.computePrice(f, t, jt, size);
                    
                    if(price === null){
                        SapsinApp.utils.showToast('เส้นทางนี้ต้องสอบถามเพิ่มเติม กรุณาทัก LINE', `${prefix}result`, 3000, true);
                        SapsinApp.utils.setLoading(`${prefix}calc`, false);
                        return;
                    }
                    
                    const text = `ราคาโดยประมาณ${type === 'pet' ? ' (สัตว์เลี้ยง)' : ''}: ${price.toLocaleString()} บาท`;
                    const res = document.getElementById(`${prefix}result`);
                    res.style.display = 'block';
                    res.textContent = text;
                    document.getElementById(`${prefix}note`).style.display = 'block';
                    
                    const sendBtn = document.getElementById(`${prefix}send`);
                    sendBtn.style.display = 'inline-block';
                    sendBtn.dataset.message = this.buildMessage(type, f, t, jt, phone, price, size);
                    
                    // Save phone to localStorage
                    try{
                        localStorage.setItem(`ps_${type}_phone`, phone);
                    }catch(e){}
                    
                    SapsinApp.utils.setLoading(`${prefix}calc`, false);
                }, 1000);
            },
            
            computePrice: function(from, to, serviceType, petSize = null) {
                // Get distance between zones
                const distance = SapsinApp.config.zoneDistance[from] && 
                                SapsinApp.config.zoneDistance[from][to] ? 
                                SapsinApp.config.zoneDistance[from][to] : null;
                
                if (distance === null || distance === 0) {
                    return null; // Invalid route
                }
                
                // Calculate base price
                const baseRate = SapsinApp.config.serviceRates[serviceType] || SapsinApp.config.serviceRates.normal;
                let price = Math.round(distance * baseRate);
                
                // Apply minimum charge
                const minCharge = SapsinApp.config.minimumCharges[serviceType] || SapsinApp.config.minimumCharges.normal;
                price = Math.max(price, minCharge);
                
                // Apply specific price adjustments based on service type and route
                if (serviceType === 'bike') {
                    if (!(from === 'central' || to === 'central' || from === 'east' || to === 'east')) {
                        price = Math.round(price * 0.5);
                    }
                } else if (serviceType === 'pet') {
                    if (from === 'south1' || to === 'south1' || from === 'south2' || to === 'south2' || 
                        from === 'north' || to === 'north') {
                        price = Math.round(price * 0.5);
                    }
                } else if (serviceType === 'house') {
                    if (from === 'central' || to === 'central') {
                        price = 2000;
                    } else if (from === 'east' || to === 'east') {
                        price = 3500;
                    } else if (from === 'south1' || to === 'south1') {
                        price = 5000;
                    } else if (from === 'south2' || to === 'south2') {
                        price = 12000;
                    }
                }
                
                // Apply pet size multiplier if applicable
                if (serviceType === 'pet' && petSize && SapsinApp.config.petSizeMultipliers[petSize]) {
                    price = Math.round(price * SapsinApp.config.petSizeMultipliers[petSize]);
                }
                
                return price;
            },
            
            buildMessage: function(type, from, to, serviceType, phone, price, size) {
                const fromText = document.getElementById(`${type === 'pet' ? 'pe-' : ''}from`).options[document.getElementById(`${type === 'pet' ? 'pe-' : ''}from`).selectedIndex].text;
                const toText = document.getElementById(`${type === 'pet' ? 'pe-' : ''}to`).options[document.getElementById(`${type === 'pet' ? 'pe-' : ''}to`).selectedIndex].text;
                
                let message = type === 'pet' ? 
                    ['ขอราคา - บริการส่งสัตว์เลี้ยง'] : 
                    ['ขอราคา', `บริการ: ${document.getElementById('jobtype').options[document.getElementById('jobtype').selectedIndex].text}`];
                
                message.push(
                    `ต้นทาง: ${fromText}`,
                    `ปลายทาง: ${toText}`
                );
                
                if (type === 'pet') {
                    message.push(`ขนาดสัตว์: ${document.getElementById('pe-size').options[document.getElementById('pe-size').selectedIndex].text}`);
                } else {
                    const sizeVal = document.getElementById('size').value;
                    if (sizeVal) message.push(`รายละเอียด: ${sizeVal}`);
                }
                
                message.push(
                    `เบอร์: ${phone}`,
                    `ราคาโดยประมาณ: ${price} บาท`,
                    'กรุณายืนยันราคาในแชท'
                );
                
                return message.join('\n');
            },
            
            sendToLine: function(type) {
                const prefix = type === 'pet' ? 'pe-' : '';
                const msg = document.getElementById(`${prefix}send`).dataset.message || 'ขอราคา';
                const web = 'https://lin.ee/nOeqY7l3';
                
                window.open(web, '_blank');
                
                SapsinApp.utils.showToast('เปิด LINE เพื่อส่งข้อมูล…', `${prefix}result`, 1200);
                setTimeout(() => {
                    document.getElementById(`${prefix}result`).textContent = 'ส่งข้อมูลใน LINE แล้ว — รอการยืนยันจากทีมงาน';
                    document.getElementById(`${prefix}success`).textContent = 'ส่งข้อมูลเรียบร้อยแล้ว! ทีมงานจะติดต่อกลับภายใน 15 นาที';
                    document.getElementById(`${prefix}success`).style.display = 'block';
                }, 1200);
            },
            
            restoreSavedData: function() {
                try{
                    const ph = localStorage.getItem('ps_phone');
                    if(ph) document.getElementById('phone').value = ph;
                    
                    const p2 = localStorage.getItem('ps_pet_phone');
                    if(p2) document.getElementById('pe-phone').value = p2;
                }catch(e){}
            }
        };

        // AI Chatbot Module
        SapsinApp.Chatbot = {
            init: function() {
                this.toggle = document.getElementById('chatbotToggle');
                this.container = document.getElementById('chatbotContainer');
                this.messages = document.getElementById('chatbotMessages');
                this.input = document.getElementById('chatbotInput');
                this.sendBtn = document.getElementById('sendChatbotMessage');
                this.closeBtn = document.getElementById('closeChatbot');
                
                this.isOpen = false;
                this.bindEvents();
            },
            
            bindEvents: function() {
                this.toggle.addEventListener('click', () => this.toggleChatbot());
                this.closeBtn.addEventListener('click', () => this.closeChatbot());
                this.sendBtn.addEventListener('click', () => this.sendMessage());
                this.input.addEventListener('keypress', (e) => {
                    if (e.key === 'Enter') this.sendMessage();
                });
            },
            
            toggleChatbot: function() {
                this.isOpen = !this.isOpen;
                this.container.style.display = this.isOpen ? 'flex' : 'none';
                if (this.isOpen) this.input.focus();
            },
            
            closeChatbot: function() {
                this.isOpen = false;
                this.container.style.display = 'none';
            },
            
            sendMessage: function() {
                const message = this.input.value.trim();
                if (!message) return;
                
                // Add user message
                this.addMessage(message, 'user');
                this.input.value = '';
                
                // Simulate AI response
                setTimeout(() => {
                    const response = this.generateResponse(message);
                    this.addMessage(response, 'bot');
                }, 1000);
            },
            
            addMessage: function(text, sender) {
                const messageEl = document.createElement('div');
                messageEl.classList.add('message', `message-${sender}`);
                messageEl.textContent = text;
                this.messages.appendChild(messageEl);
                this.messages.scrollTop = this.messages.scrollHeight;
            },
            
            generateResponse: function(userMessage) {
                const lowerMessage = userMessage.toLowerCase();
                
                if (lowerMessage.includes('ราคา') || lowerMessage.includes('ค่าใช้จ่าย')) {
                    return "สำหรับการคำนวณราคาที่แม่นยำ กรุณาใช้เครื่องมือคำนวณราคาด้านบน หรือทัก LINE มาได้เลยค่ะ เราจะให้ราคาที่ถูกต้องที่สุด! 💰";
                } else if (lowerMessage.includes('สัตว์เลี้ยง') || lowerMessage.includes('หมา') || lowerMessage.includes('แมว')) {
                    return "เรามีบริการส่งสัตว์เลี้ยงโดยเฉพาะ哦! แยกช่องพัก รายงานสภาพตลอดทาง และดูแลอย่างใส่ใจ 🐶🐱 สามารถเช็คราคาได้ในส่วนบริการสัตว์เลี้ยงด้านบนเลยค่ะ";
                } else if (lowerMessage.includes('มอเตอร์ไซค์') || lowerMessage.includes('รถ')) {
                    return "บริการส่งมอเตอร์ไซค์ของเรา ปลอดภัยไร้รอยขีดข่วนแน่นอน! 🏍️ ใช้อุปกรณ์รองรับพิเศษและล็อกอย่างมั่นใจ";
                } else if (lowerMessage.includes('ติดตาม') || lowerMessage.includes('track')) {
                    return "เรามีระบบติดตามพัสดุแบบเรียลไทม์哦! จะอัพเดทสถานะและส่งรูปให้ตลอดทาง 📍";
                } else if (lowerMessage.includes('ย้ายบ้าน') || lowerMessage.includes('ขนย้าย')) {
                    return "บริการย้ายบ้านครบวงจร จากแพ็กกิ้งจนถึงจัดวางใหม่ 🏠 มีทีมงานช่วยเหลือทุกขั้นตอนค่ะ";
                } else {
                    return "ขอบคุณสำหรับข้อความค่ะ! 😊 สำหรับข้อมูลที่ละเอียดกว่ากรุณาใช้เครื่องมือคำนวณราคาด้านบน หรือติดต่อเราผ่าน LINE ที่ลิงก์ด้านล่างก็ได้นะคะ";
                }
            }
        };

        // Real-time Tracking Module
        SapsinApp.Tracking = {
            init: function() {
                this.steps = document.querySelectorAll('.tracking-step');
                this.simulateBtn = document.getElementById('simulateTracking');
                this.currentStep = 2; // Start at step 2 (already completed first two)
                
                this.bindEvents();
                this.updateTrackingMap();
            },
            
            bindEvents: function() {
                this.simulateBtn.addEventListener('click', () => this.simulateTrackingUpdate());
            },
            
            simulateTrackingUpdate: function() {
                if (this.currentStep < this.steps.length) {
                    this.steps[this.currentStep].classList.add('step-active');
                    this.currentStep++;
                    this.updateTrackingMap();
                    
                    if (this.currentStep === this.steps.length) {
                        this.simulateBtn.textContent = 'รีเซ็ตการติดตาม';
                        this.simulateBtn.onclick = () => this.resetTracking();
                    }
                }
            },
            
            resetTracking: function() {
                this.steps.forEach((step, index) => {
                    if (index > 1) { // Keep first two steps completed
                        step.classList.remove('step-active');
                    }
                });
                this.currentStep = 2;
                this.updateTrackingMap();
                this.simulateBtn.textContent = 'จำลองการอัพเดทสถานะ';
                this.simulateBtn.onclick = () => this.simulateTrackingUpdate();
            },
            
            updateTrackingMap: function() {
                const statuses = [
                    'รับพัสดุเรียบร้อย',
                    'อยู่ที่ศูนย์กระจายสินค้า',
                    'กำลังขนส่ง',
                    'ถึงปลายทางแล้ว'
                ];
                
                const map = document.getElementById('trackingMap');
                map.textContent = `สถานะปัจจุบัน: ${statuses[this.currentStep - 1]}`;
            }
        };

        // Analytics Dashboard Module
        SapsinApp.Analytics = {
            init: function() {
                this.dashboard = document.getElementById('analyticsDashboard');
                this.refreshBtn = document.getElementById('refreshAnalytics');
                
                // Show dashboard if URL has analytics parameter
                if (window.location.search.includes('analytics=true')) {
                    this.dashboard.style.display = 'block';
                }
                
                this.bindEvents();
                this.loadAnalyticsData();
            },
            
            bindEvents: function() {
                if (this.refreshBtn) {
                    this.refreshBtn.addEventListener('click', () => this.loadAnalyticsData());
                }
            },
            
            loadAnalyticsData: function() {
                // Simulate loading data
                document.getElementById('kpiOrders').textContent = Math.floor(Math.random() * 20) + 5;
                document.getElementById('kpiRevenue').textContent = (Math.floor(Math.random() * 50000) + 10000).toLocaleString();
                document.getElementById('kpiConversion').textContent = (Math.floor(Math.random() * 30) + 10) + '%';
                document.getElementById('kpiSatisfaction').textContent = (Math.floor(Math.random() * 30) + 70) + '%';
            }
        };

        // Multi-language Module
        SapsinApp.Language = {
            init: function() {
                this.currentLang = 'th';
                this.toggle = document.getElementById('langToggle');
                this.dropdown = document.getElementById('langDropdown');
                this.options = document.querySelectorAll('.lang-option');
                
                this.bindEvents();
            },
            
            bindEvents: function() {
                this.toggle.addEventListener('click', (e) => {
                    e.stopPropagation();
                    this.dropdown.classList.toggle('active');
                    this.toggle.setAttribute('aria-expanded', 
                        this.dropdown.classList.contains('active').toString());
                });
                
                this.options.forEach(option => {
                    option.addEventListener('click', () => {
                        const lang = option.dataset.lang;
                        this.changeLanguage(lang);
                        this.dropdown.classList.remove('active');
                        this.toggle.setAttribute('aria-expanded', 'false');
                    });
                });
                
                // Close dropdown when clicking outside
                document.addEventListener('click', () => {
                    this.dropdown.classList.remove('active');
                    this.toggle.setAttribute('aria-expanded', 'false');
                });
            },
            
            changeLanguage: function(lang) {
                this.currentLang = lang;
                this.toggle.innerHTML = lang.toUpperCase() + ' <span style="font-size:12px">▼</span>';
                
                // In a real implementation, you would load translations here
                console.log(`Changing language to: ${lang}`);
                // this.loadTranslations(lang);
            },
            
            loadTranslations: function(lang) {
                // This would typically fetch a JSON file with translations
                // For now, we'll just log to console
                console.log(`Loading ${lang} translations...`);
            }
        };

        // Advanced Booking Module
        SapsinApp.Booking = {
            init: function() {
                this.calendar = document.getElementById('bookingCalendar');
                this.generateCalendar();
            },
            
            generateCalendar: function() {
                const daysOfWeek = ['อา', 'จ', 'อ', 'พ', 'พฤ', 'ศ', 'ส'];
                const today = new Date();
                const currentMonth = today.getMonth();
                const currentYear = today.getFullYear();
                
                // Add day headers
                daysOfWeek.forEach(day => {
                    const dayEl = document.createElement('div');
                    dayEl.classList.add('calendar-header');
                    dayEl.textContent = day;
                    this.calendar.appendChild(dayEl);
                });
                
                // Get first day of month
                const firstDay = new Date(currentYear, currentMonth, 1).getDay();
                
                // Add empty cells for days before first day of month
                for (let i = 0; i < firstDay; i++) {
                    const emptyEl = document.createElement('div');
                    emptyEl.classList.add('calendar-day', 'disabled');
                    this.calendar.appendChild(emptyEl);
                }
                
                // Add days of month
                const daysInMonth = new Date(currentYear, currentMonth + 1, 0).getDate();
                for (let i = 1; i <= daysInMonth; i++) {
                    const dayEl = document.createElement('div');
                    dayEl.classList.add('calendar-day');
                    dayEl.textContent = i;
                    
                    // Disable past days
                    if (i < today.getDate() && currentMonth === today.getMonth()) {
                        dayEl.classList.add('disabled');
                    } else {
                        dayEl.addEventListener('click', () => this.selectDate(dayEl, i));
                    }
                    
                    this.calendar.appendChild(dayEl);
                }
            },
            
            selectDate: function(element, day) {
                // Remove selection from all days
                document.querySelectorAll('.calendar-day').forEach(dayEl => {
                    dayEl.classList.remove('selected');
                });
                
                // Add selection to clicked day
                element.classList.add('selected');
                
                // In a real implementation, you would store the selected date
                console.log(`Selected date: ${day}`);
            }
        };

        // NEW: Order Management Module
        SapsinApp.OrderManagement = {
            init: function() {
                this.bindEvents();
                this.renderOrders();
            },
            
            bindEvents: function() {
                document.getElementById('add-order').addEventListener('click', () => this.addOrder());
            },
            
            addOrder: function() {
                const name = document.getElementById('customer-name').value.trim();
                const phone = document.getElementById('customer-phone').value.trim();
                const type = document.getElementById('order-type').value;
                const price = document.getElementById('order-price').value;
                const details = document.getElementById('order-details').value.trim();
                
                if (!name || !phone || !price) {
                    SapsinApp.Notification.show('กรุณากรอกข้อมูลให้ครบถ้วน', 'error');
                    return;
                }
                
                const order = {
                    id: Date.now(),
                    customerName: name,
                    customerPhone: phone,
                    serviceType: type,
                    price: parseInt(price),
                    details: details,
                    status: 'pending',
                    createdAt: new Date().toISOString()
                };
                
                SapsinApp.data.orders.unshift(order);
                SapsinApp.utils.saveData();
                
                // Clear form
                document.getElementById('customer-name').value = '';
                document.getElementById('customer-phone').value = '';
                document.getElementById('order-price').value = '';
                document.getElementById('order-details').value = '';
                
                this.renderOrders();
                SapsinApp.Notification.show('เพิ่มคำสั่งซื้อเรียบร้อยแล้ว', 'success');
            },
            
            renderOrders: function() {
                const orderList = document.getElementById('orderList');
                const orders = SapsinApp.data.orders.slice(0, 5); // Show last 5 orders
                
                if (orders.length === 0) {
                    orderList.innerHTML = '<p class="muted small">ยังไม่มีคำสั่งซื้อ</p>';
                    return;
                }
                
                let html = '';
                orders.forEach(order => {
                    const statusText = this.getStatusText(order.status);
                    const statusClass = this.getStatusClass(order.status);
                    const serviceType = this.getServiceTypeText(order.serviceType);
                    
                    html += `
                        <div class="order-item">
                            <div style="display:flex;justify-content:space-between;align-items:flex-start">
                                <div>
                                    <strong>${order.customerName}</strong>
                                    <span class="order-status ${statusClass}">${statusText}</span>
                                    <div class="muted small">${order.customerPhone}</div>
                                    <div class="muted small">${serviceType} - ${order.price.toLocaleString()} บาท</div>
                                    ${order.details ? `<div class="muted small">${order.details}</div>` : ''}
                                </div>
                                <div>
                                    <button class="btn small" onclick="SapsinApp.OrderManagement.updateStatus(${order.id}, 'confirmed')" style="background:var(--success);color:#fff;padding:4px 8px;font-size:12px">ยืนยัน</button>
                                    <button class="btn small" onclick="SapsinApp.OrderManagement.updateStatus(${order.id}, 'shipping')" style="background:var(--navy);color:#fff;padding:4px 8px;font-size:12px">ส่งแล้ว</button>
                                </div>
                            </div>
                        </div>
                    `;
                });
                
                orderList.innerHTML = html;
            },
            
            updateStatus: function(orderId, newStatus) {
                const order = SapsinApp.data.orders.find(o => o.id === orderId);
                if (order) {
                    order.status = newStatus;
                    SapsinApp.utils.saveData();
                    this.renderOrders();
                    SapsinApp.Notification.show('อัพเดทสถานะเรียบร้อยแล้ว', 'success');
                }
            },
            
            getStatusText: function(status) {
                const statusMap = {
                    'pending': 'รอดำเนินการ',
                    'confirmed': 'ยืนยันแล้ว',
                    'shipping': 'กำลังขนส่ง',
                    'delivered': 'ส่งแล้ว'
                };
                return statusMap[status] || status;
            },
            
            getStatusClass: function(status) {
                const classMap = {
                    'pending': 'status-pending',
                    'confirmed': 'status-confirmed',
                    'shipping': 'status-shipping',
                    'delivered': 'status-delivered'
                };
                return classMap[status] || 'status-pending';
            },
            
            getServiceTypeText: function(type) {
                const typeMap = {
                    'bike': 'ส่งมอเตอร์ไซค์',
                    'pet': 'ส่งสัตว์เลี้ยง',
                    'house': 'ย้ายบ้าน',
                    'parcel': 'ส่งสินค้า',
                    'normal': 'งานเหมา/ด่วน'
                };
                return typeMap[type] || type;
            }
        };

        // NEW: Notification Module
        SapsinApp.Notification = {
            init: function() {
                this.notification = document.getElementById('notification');
            },
            
            show: function(message, type = 'success') {
                this.notification.textContent = message;
                this.notification.className = `notification notification-${type}`;
                this.notification.style.display = 'block';
                
                setTimeout(() => {
                    this.notification.style.display = 'none';
                }, 3000);
            }
        };

        // Accessibility Module
        SapsinApp.Accessibility = {
            init: function() {
                this.bindEvents();
                this.handleImageErrors();
            },
            
            bindEvents: function() {
                // Social media expand button
                const socialExpand = document.getElementById('socialExpand');
                const socialMenu = document.getElementById('socialMenu');
                
                if (socialExpand && socialMenu) {
                    socialExpand.addEventListener('click', () => {
                        socialMenu.classList.toggle('active');
                        socialExpand.textContent = socialMenu.classList.contains('active') ? '−' : '+';
                    });
                }
                
                // FAQ toggle functionality
                document.querySelectorAll('.faq-question').forEach(question => {
                    question.addEventListener('click', function() {
                        const answer = this.nextElementSibling;
                        const isVisible = answer.style.display === 'block';
                        
                        // Close all answers
                        document.querySelectorAll('.faq-answer').forEach(ans => {
                            ans.style.display = 'none';
                        });
                        
                        // Toggle current answer
                        answer.style.display = isVisible ? 'none' : 'block';
                    });
                });
                
                // Initially hide all FAQ answers
                document.querySelectorAll('.faq-answer').forEach(answer => {
                    answer.style.display = 'none';
                });
            },
            
            handleImageErrors: function() {
                document.querySelectorAll('img').forEach(img => {
                    img.addEventListener('load', function() {
                        this.parentElement.classList.remove('loading');
                    });
                    
                    img.addEventListener('error', function() {
                        this.src = 'data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><rect width="100" height="100" fill="%23f0f0f0"/><text x="50" y="50" font-size="10" text-anchor="middle" fill="%23666">ไม่มีรูปภาพ</text></svg>';
                        this.alt = 'รูปภาพไม่สามารถโหลดได้';
                        this.parentElement.classList.remove('loading');
                    });
                    
                    // Set loading state initially
                    if (!img.complete) {
                        img.parentElement.classList.add('loading');
                    }
                });
            }
        };

        // Initialize the application when DOM is loaded
        document.addEventListener('DOMContentLoaded', function() {
            SapsinApp.init();
        });

        // Global functions for onclick attributes (for backward compatibility)
        function prevSlide() {
            SapsinApp.Slider.prevSlide();
        }

        function nextSlide() {
            SapsinApp.Slider.nextSlide();
        }
    </script>
</body>
</html>
