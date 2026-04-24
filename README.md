
<style>
body {
 font-family: Arial, sans-serif;
}

.hub-container {
 max-width: 1100px;
 margin: auto;
 padding: 20px;
}

/* HERO */
.hub-hero {
 text-align: center;
 padding: 40px 20px;
}

.hub-hero h1 {
 font-size: 32px;
 margin-bottom: 10px;
}

.hub-hero p {
 color: #555;
 font-size: 16px;
}

/* SECTION TITLES */
.section-title {
 font-size: 24px;
 margin: 40px 0 20px;
 font-weight: bold;
}

/* CARD GRID */
.card-grid {
 display: grid;
 grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
 gap: 20px;
}

/* CARD */
.card {
 border: 1px solid #e0e0e0;
 border-radius: 10px;
 padding: 20px;
 background: white;
 transition: 0.3s;
 position: relative;
}

.card:hover {
 transform: translateY(-5px);
 box-shadow: 0 8px 20px rgba(0,0,0,0.08);
}

/* CARD TITLE */
.card h3 {
 margin-bottom: 10px;
}

/* EXPANDABLE */
.card input {
 display: none;
}

.card label {
 color: #0073e6;
 font-size: 14px;
 cursor: pointer;
}

.card-content {
 max-height: 0;
 overflow: hidden;
 transition: max-height 0.3s ease;
 font-size: 14px;
 color: #444;
}

.card input:checked ~ .card-content {
 max-height: 200px;
 margin-top: 10px;
}

/* BUTTON */
.cta {
 display: inline-block;
 margin-top: 15px;
 padding: 8px 14px;
 background: #0073e6;
 color: white;
 border-radius: 5px;
 text-decoration: none;
 font-size: 13px;
}

/* DIVIDER */
.divider {
 height: 1px;
 background: #eee;
 margin: 50px 0;
}
</style>

<div class="hub-container">

<!-- HERO -->
<div class="hub-hero">
<h1>Grow Your Career at Wintrust</h1>
<p>Explore professional and leadership competencies designed to support your growth.</p>
</div>

<!-- PROFESSIONAL -->
<div class="section-title">Professional Competencies</div>

<div class="card-grid">

<div class="card">
<h3>Communication</h3>
<input type="checkbox" id="p1">
<label for="p1">Learn more</label>
<div class="card-content">
       Build clear, confident communication across teams and leadership levels.
<br>
<a href="#" class="cta">View Courses</a>
</div>
</div>

<div class="card">
<h3>Analytical Thinking</h3>
<input type="checkbox" id="p2">
<label for="p2">Learn more</label>
<div class="card-content">
       Strengthen your ability to analyze data and make informed decisions.
<br>
<a href="#" class="cta">View Courses</a>
</div>
</div>

<div class="card">
<h3>Business Acumen</h3>
<input type="checkbox" id="p3">
<label for="p3">Learn more</label>
<div class="card-content">
       Understand how your role impacts broader business strategy and performance.
<br>
<a href="#" class="cta">View Courses</a>
</div>
</div>

</div>

<div class="divider"></div>

<!-- LEADERSHIP -->
<div class="section-title">Leadership Competencies</div>

<div class="card-grid">

<div class="card">
<h3>Coaching & Development</h3>
<input type="checkbox" id="l1">
<label for="l1">Learn more</label>
<div class="card-content">
       Learn how to support and develop others through effective coaching.
<br>
<a href="#" class="cta">Explore Learning Path</a>
</div>
</div>

<div class="card">
<h3>Strategic Thinking</h3>
<input type="checkbox" id="l2">
<label for="l2">Learn more</label>
<div class="card-content">
       Develop long-term thinking and decision-making capabilities.
<br>
<a href="#" class="cta">Explore Learning Path</a>
</div>
</div>

<div class="card">
<h3>Emotional Intelligence</h3>
<input type="checkbox" id="l3">
<label for="l3">Learn more</label>
<div class="card-content">
       Build self-awareness and strengthen relationships across your team.
<br>
<a href="#" class="cta">Explore Learning Path</a>
</div>
</div>

</div>

</div>

