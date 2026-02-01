<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saleh Hossam | Project Deep Dives</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        background: '#0a0a0a',
                        'gold': '#D4AF37',
                        'slate-blue': '#64748b',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            background-color: #0a0a0a;
            font-family: 'Inter', system-ui, sans-serif;
            color: #e2e8f0;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
            margin-top: 3rem;
        }
        .project-card {
            background: linear-gradient(145deg, rgba(255,255,255,0.03) 0%, rgba(255,255,255,0.01) 100%);
            border: 1px solid rgba(255,255,255,0.08);
            border-radius: 16px;
            padding: 2rem;
            display: flex;
            flex-direction: column;
            transition: all 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px rgba(212, 175, 55, 0.1);
            border-color: rgba(212, 175, 55, 0.3);
        }
        .project-card h3 {
            font-size: 1.75rem;
            font-weight: 700;
            margin-bottom: 0.75rem;
            color: #ffffff;
            line-height: 1.3;
        }
        .project-card .project-goal {
            font-weight: 500;
            color: #a0aec0;
            margin-bottom: 0.5rem;
            font-size: 0.95rem;
        }
        .project-card ul {
            margin: 1rem 0 1.5rem 0;
            padding-left: 1.25rem;
            list-style-type: disc;
        }
        .project-card ul li {
            margin-bottom: 0.5rem;
            color: #a0aec0;
            line-height: 1.6;
        }
        .project-image-wrapper {
            margin: 1.5rem 0;
            border-radius: 12px;
            overflow: hidden;
            background: rgba(0,0,0,0.2);
            flex-grow: 1;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 1px solid rgba(255,255,255,0.05);
        }
        .project-image-wrapper img {
            width: 100%;
            height: auto;
            display: block;
        }
        .project-cta {
            margin-top: auto;
            padding-top: 1rem;
        }
        .project-cta .btn {
            width: 100%;
            padding: 0.75rem 1.5rem;
            font-weight: 600;
            font-size: 0.9rem;
            border-radius: 8px;
            transition: all 0.2s ease;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            border: 1px solid #D4AF37;
            color: #D4AF37;
        }
        .project-cta .btn:hover {
            background: rgba(212, 175, 55, 0.1);
            color: #fff;
            transform: translateY(-1px);
        }
        @media (max-width: 768px) {
            .project-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body class="min-h-screen antialiased">

    <div class="max-w-6xl mx-auto px-4 py-8 md:py-16">
        <div class="text-left">
            <a href="index.html" class="inline-flex items-center gap-2 text-slate-400 hover:text-gold transition-colors text-sm font-medium">
                <i data-lucide="arrow-left" class="w-4 h-4"></i>
                <span>Back to Overview</span>
            </a>
            <h1 class="text-4xl md:text-5xl font-bold tracking-tight mt-4 text-white">Project Deep Dives<span class="text-gold">.</span></h1>
            <p class="text-slate-400 text-lg mt-2">Strategic Analysis & Technical Implementation.</p>
        </div>

        <div class="project-grid">

            <div id="adventure-works" class="project-card">
                <h3>🚲 Adventure Works Intelligence</h3>
                <p class="project-goal"><strong>Goal:</strong> Optimize inventory turnover and analyze revenue trends for a global manufacturer.</p>
                <ul>
                    <li><strong>Tech Stack:</strong> Power BI, DAX, Power Pivot.</li>
                    <li><strong>Key Insight:</strong> Identified <strong>$202K</strong> in potential revenue recovery by auditing the <em>Mountain-200</em> production line.</li>
                </ul>
                <div class="project-image-wrapper">
                    <img src="https://github.com/Saleh-Hossam/Adventure-Works-Business-Intelligence/blob/main/assets/overview.gif?raw=true" alt="Adventure Works Dashboard Preview">
                </div>
                <div class="project-cta">
                    <a href="https://github.com/Saleh-Hossam/Adventure-Works-Business-Intelligence" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>

            <div id="supply-chain" class="project-card">
                <h3>📦 Supply Chain "The Hidden Loss"</h3>
                <p class="project-goal"><strong>Goal:</strong> Invalidate the stakeholder hypothesis and identify the true financial drain to save capital.</p>
                <ul>
                    <li><strong>Tech Stack:</strong> SQL Server, Power BI.</li>
                    <li><strong>Key Insight:</strong> Proved "Late Orders" (20%) were a systemic constant, while "Inventory Loss" (5%) was the hidden financial bleed (32,000+ units).</li>
                </ul>
                <div class="project-image-wrapper">
                    <img src="https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause/blob/main/assets/Preview__.gif?raw=true" alt="Supply Chain Dashboard Preview">
                </div>
                <div class="project-cta">
                    <a href="https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>

            <div id="dannys-diner" class="project-card">
                <h3>🍜 Danny's Diner SQL Challenge</h3>
                <p class="project-goal"><strong>Goal:</strong> Analyze customer spending habits and menu preferences for a restaurant loyalty program.</p>
                <ul>
                    <li><strong>Tech Stack:</strong> SQL Server (Window Functions, CTEs).</li>
                    <li><strong>Key Skill:</strong> Engineered rank analysis, customer retention metrics, and aggregate spending logic from scratch.</li>
                </ul>
                <div class="project-image-wrapper">
                    <img src="https://github.com/Saleh-Hossam/Dannys-Diner-SQL/blob/main/assets/Cover.png?raw=true" alt="Danny's Diner SQL Project">
                </div>
                <div class="project-cta">
                    <a href="https://github.com/Saleh-Hossam/Dannys-Diner-SQL" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>

            <div id="strategic-sales" class="project-card">
                <h3>🚀 Strategic Sales & RFM Intelligence</h3>
                <p class="project-goal"><strong>Goal:</strong> Transform raw sales data into a decision engine for Executive, Operations, and Marketing stakeholders.</p>
                <ul>
                    <li><strong>Tech Stack:</strong> Excel, Power Pivot (DAX), Power Query.</li>
                    <li><strong>Key Insight:</strong> Engineered a Customer Retention System to detect high-value churn risks and isolated "Profit Leaks" in logistics.</li>
                </ul>
                <div class="project-image-wrapper">
                    <img src="https://github.com/Saleh-Hossam/Strategic-Sales-RFM-Dashboard/blob/main/assets/Overview.gif?raw=true" alt="Strategic Sales Dashboard Preview">
                </div>
                <div class="project-cta">
                    <a href="https://github.com/Saleh-Hossam/Strategic-Sales-RFM-Dashboard" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
