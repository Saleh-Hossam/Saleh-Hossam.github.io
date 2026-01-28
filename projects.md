---
layout: page
title: Projects
subtitle: Strategic Analysis & Technical Implementation
---

<style>
/* ============================================
   BENTO GRID - Self-Contained Styles
   ============================================ */

.project-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin: 3rem 0;
}

.project-card {
  background: #ffffff;
  border-radius: 16px;
  padding: 2rem;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  border: 1px solid rgba(0, 0, 0, 0.06);
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.15);
  border-color: rgba(0, 0, 0, 0.1);
}

.project-card h3 {
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 0.75rem;
  color: #1a1a1a;
  line-height: 1.3;
}

.project-card .project-goal {
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.5rem;
  font-size: 0.95rem;
}

.project-card ul {
  margin: 1rem 0 1.5rem 0;
  padding-left: 1.25rem;
}

.project-card ul li {
  margin-bottom: 0.5rem;
  color: #4a5568;
  line-height: 1.6;
}

.project-image-wrapper {
  margin: 1.5rem 0;
  border-radius: 12px;
  overflow: hidden;
  background: #f7fafc;
  flex-grow: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-image-wrapper img {
  width: 100%;
  height: auto;
  display: block;
  transition: transform 0.3s ease;
}

.project-card:hover .project-image-wrapper img {
  transform: scale(1.02);
}

.project-cta {
  margin-top: auto;
  padding-top: 1rem;
}

.project-cta .btn {
  width: 100%;
  padding: 0.75rem 1.5rem;
  font-weight: 500;
  border-radius: 8px;
  transition: all 0.2s ease;
  text-decoration: none;
  display: inline-block;
  text-align: center;
}

.project-cta .btn-primary {
  background: #007bff;
  border-color: #007bff;
}

.project-cta .btn-primary:hover {
  background: #0056b3;
  border-color: #0056b3;
  transform: translateY(-1px);
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .project-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
    margin: 2rem 0;
  }
  
  .project-card {
    padding: 1.5rem;
  }
  
  .project-card h3 {
    font-size: 1.35rem;
  }
}

/* Dark mode support (optional) */
@media (prefers-color-scheme: dark) {
  .project-card {
    background: #1a1a1a;
    border-color: rgba(255, 255, 255, 0.1);
  }
  
  .project-card:hover {
    border-color: rgba(255, 255, 255, 0.2);
  }
  
  .project-card h3 {
    color: #ffffff;
  }
  
  .project-card .project-goal {
    color: #e2e8f0;
  }
  
  .project-card ul li {
    color: #a0aec0;
  }
  
  .project-image-wrapper {
    background: #2d3748;
  }
}
</style>

<div class="project-grid">
  
  <!-- Project 1: Adventure Works -->
  <div class="project-card">
    <h3>🚲 Adventure Works Intelligence</h3>
    <p class="project-goal"><strong>Goal:</strong> Optimize inventory turnover and analyze revenue trends for a global manufacturer.</p>
    <ul>
      <li><strong>Tech Stack:</strong> Power BI, DAX, Power Pivot.</li>
      <li><strong>Key Insight:</strong> Identified <strong>$202K</strong> in potential revenue recovery by auditing the <em>Mountain-200</em> production line.</li>
    </ul>
    <div class="project-image-wrapper">
      <a href="https://github.com/Saleh-Hossam/Adventure-Works-Business-Intelligence">
        <img src="https://github.com/Saleh-Hossam/Adventure-Works-Business-Intelligence/blob/main/assets/overview.gif?raw=true" alt="Adventure Works Dashboard Preview">
      </a>
    </div>
    <div class="project-cta">
      <a href="https://github.com/Saleh-Hossam/Adventure-Works-Business-Intelligence" class="btn btn-primary">View Dashboard & Analysis</a>
    </div>
  </div>

  <!-- Project 2: Supply Chain -->
  <div class="project-card">
    <h3>📦 Supply Chain "The Hidden Loss"</h3>
    <p class="project-goal"><strong>Goal:</strong> Invalidate the stakeholder hypothesis ("Late Deliveries are killing us") and identify the true financial drain to save capital.</p>
    <ul>
      <li><strong>Tech Stack:</strong> SQL Server (Multi-Dimensional Aggregation), Power BI (Interactive Root-Cause Dashboard).</li>
      <li><strong>Key Insight:</strong> Proved "Late Orders" (20%) were a systemic constant, while "Inventory Loss" (5%) was the hidden financial bleed (32,000+ units).</li>
    </ul>
    <div class="project-image-wrapper">
      <a href="https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause">
        <img src="https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause/blob/main/assets/Preview__.gif?raw=true" alt="Supply Chain Dashboard Preview">
      </a>
    </div>
    <div class="project-cta">
      <a href="https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause" class="btn btn-primary">View Code & "Golden README"</a>
    </div>
  </div>

  <!-- Project 3: Danny's Diner -->
  <div class="project-card">
    <h3>🍜 Danny's Diner</h3>
    <p class="project-goal"><strong>Goal:</strong> Analyze customer spending habits and menu preferences for a restaurant loyalty program.</p>
    <ul>
      <li><strong>Tech Stack:</strong> SQL Server (Window Functions, CTEs, Multi-Table Joins).</li>
      <li><strong>Key Skill:</strong> Proved technical mastery by engineering rank analysis, customer retention metrics, and aggregate spending logic.</li>
    </ul>
    <div class="project-image-wrapper">
      <a href="https://github.com/Saleh-Hossam/Dannys-Diner-SQL">
        <img src="https://github.com/Saleh-Hossam/Dannys-Diner-SQL/blob/main/assets/Cover.png?raw=true" alt="Danny's Diner SQL Project">
      </a>
    </div>
    <div class="project-cta">
      <a href="https://github.com/Saleh-Hossam/Dannys-Diner-SQL" class="btn btn-primary">View SQL Code & Logic</a>
    </div>
  </div>

  <!-- Project 4: Strategic Sales -->
  <div class="project-card">
    <h3>🚀 Strategic Sales & RFM Intelligence</h3>
    <p class="project-goal"><strong>Goal:</strong> Transform raw sales data into a strategic decision engine for Executive, Operations, and Marketing stakeholders.</p>
    <ul>
      <li><strong>Tech Stack:</strong> Excel (Star Schema Data Model), Power Pivot (DAX), Power Query.</li>
      <li><strong>Key Insight:</strong> Engineered a <strong>Customer Retention System</strong> to detect high-value churn risks and applied <strong>Diverging Logic</strong> to isolate "Profit Leaks" in logistics.</li>
    </ul>
    <div class="project-image-wrapper">
      <a href="https://github.com/Saleh-Hossam/Strategic-Sales-RFM-Dashboard">
        <img src="https://github.com/Saleh-Hossam/Strategic-Sales-RFM-Dashboard/blob/main/assets/Overview.gif?raw=true" alt="Strategic Sales Dashboard Preview">
      </a>
    </div>
    <div class="project-cta">
      <a href="https://github.com/Saleh-Hossam/Strategic-Sales-RFM-Dashboard" class="btn btn-primary">View Strategy & Dashboards</a>
    </div>
  </div>

</div>
