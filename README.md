<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');

body {
 font-family: 'Agenda', 'Inter', sans-serif;
}

/* CONTAINER */
.hub-container {
 max-width: 1150px;
 margin: auto;
 padding: 20px;
}

/* HERO */
.hub-hero {
 background: linear-gradient(135deg, #003e7e, #257cb6);
 color: white;
 padding: 50px 30px;
 border-radius: 12px;
}

.hub-hero h1 {
 font-size: 34px;
 margin-bottom: 10px;
}

.hub-hero p {
 opacity: 0.9;
 max-width: 600px;
}

/* SECTION */
.section-title {
 font-size: 24px;
 margin: 40px 0 10px;
 font-weight: 600;
 color: #003e7e;
}

/* GRID */
.card-grid {
 display: grid;
 grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
 gap: 20px;
}

/* CARD */
.card {
 border-radius: 10px;
 padding: 20px;
 background: white;
 border: 1px solid #eee;
 transition: 0.3s;
 position: relative;
 overflow: hidden;
}

/* TOP ACCENT BAR */
.card::before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 height: 4px;
 width: 100%;
 background: #00c0f3;
}

.card:hover {
 transform: translateY(-6px);
 box-shadow: 0 12px 25px rgba(0,0,0,0.08);
}

/* TITLE */
.card h3 {
 color: #003e7e;
}

/* DESCRIPTION */
.card p {
 font-size: 14px;
 color: #555;
}

/* CTA */
.cta {
 display: inline-block;
 margin-top: 12px;
 font-size: 13px;
 color: #257cb6;
 text-decoration: none;
 font-weight: 600;
}

/* DIVIDER */
.divider {
 height: 1px;
 background: #eee;
 margin: 50px 0;
}

/* BOTTOM CTA */
.cta-section {
 background: #f5f9fc;
 border-radius: 12px;
 padding: 30px;
 display: flex;
 justify-content: space-between;
 align-items: center;
}

.cta-button {
 background: #00c0f3;
 color: white;
 padding: 12px 20px;
 border-radius: 6px;
 text-decoration: none;
 font-weight: 600;
}

</style>

<div class="hub-container">

<!-- HERO -->
<div class="hub-hero">
<h1>Grow. Lead. Succeed.</h1>
<p>Explore professional and leadership competencies designed to support your growth at Wintrust.</p>
</div>

<!-- PROFESSIONAL -->
<div class="section-title">Professional Competencies</div>

<div class="card-grid">
<div class="card">
<h3>Communication</h3>
<p>Communicate clearly and confidently to inform, influence, and inspire.</p>
<a href="#" class="cta">Explore Learning →</a>
</div>

<div class="card">
<h3>Analytical Thinking</h3>
<p>Evaluate information and make data-driven decisions.</p>
<a href="#" class="cta">Explore Learning →</a>
</div>

<div class="card">
<h3>Business Acumen</h3>
<p>Understand how your work impacts business performance.</p>
<a href="#" class="cta">Explore Learning →</a>
</div>
</div>

<div class="divider"></div>

<!-- LEADERSHIP -->
<div class="section-title">Leadership Competencies</div>

<div class="card-grid">
<div class="card">
<h3>Coaching & Development</h3>
<p>Empower others through feedback, support, and growth.</p>
<a href="#" class="cta">Explore Path →</a>
</div>

<div class="card">
<h3>Strategic Thinking</h3>
<p>Think critically and make forward-looking decisions.</p>
<a href="#" class="cta">Explore Path →</a>
</div>

<div class="card">
<h3>Emotional Intelligence</h3>
<p>Strengthen relationships through awareness and empathy.</p>
<a href="#" class="cta">Explore Path →</a>
</div>
</div>

<div class="divider"></div>

<!-- CTA -->
<div class="cta-section">
<div>
<h3 style="margin:0;">Not sure where to start?</h3>
<p style="margin:5px 0; color:#555;">Find learning tailored to your goals.</p>
</div>
<a href="#" class="cta-button">Find My Path</a>
</div>

</div>
