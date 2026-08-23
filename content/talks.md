---
title: "Talks & Presentations"
description: "Invited keynotes, departmental seminars, and contributed conference presentations in Statistics, Data Science, and Biostatistics."
hidemeta: true
---

<style>

.filter-container {
    background: var(--entry);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px;
    margin-bottom: 25px;
}
.filter-group {
    margin-bottom: 14px;
}
.filter-group:last-child {
    margin-bottom: 0;
}
.filter-label {
    font-weight: 700;
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    color: var(--secondary);
    margin-bottom: 8px;
    display: block;
}
.filter-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}
.filter-btn {
    background: transparent;
    border: 1px solid var(--border);
    color: var(--primary);
    padding: 5px 12px;
    border-radius: 20px;
    font-size: 0.85rem;
    cursor: pointer;
    transition: all 0.2s ease;
    text-decoration: none !important;
}
.filter-btn:hover {
    border-color: #008080;
    color: #008080;
}
.filter-btn.active {
    background: #008080;
    border-color: #008080;
    color: #ffffff !important;
    font-weight: 600;
}
.search-input {
    width: 100%;
    padding: 10px 15px;
    border-radius: 8px;
    border: 1px solid var(--border);
    background: var(--theme);
    color: var(--primary);
    font-size: 0.95rem;
    box-sizing: border-box;
    margin-top: 4px;
}
.talk-card {
    background: var(--entry);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px 24px;
    margin-bottom: 18px;
    transition: transform 0.15s ease, box-shadow 0.15s ease, border-color 0.15s ease;
}
.talk-card:hover {
    border-color: #008080;
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0, 128, 128, 0.08);
}
.talk-title {
    font-size: 1.15rem;
    font-weight: 700;
    color: var(--primary);
    margin: 0 0 8px 0;
    line-height: 1.4;
}
.talk-conf {
    font-size: 1.0rem;
    font-weight: 600;
    color: #008080;
    margin-bottom: 6px;
}
.talk-meta {
    font-size: 0.9rem;
    color: var(--secondary);
    margin-bottom: 12px;
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    align-items: center;
}
.pill-tag {
    display: inline-block;
    padding: 2px 9px;
    border-radius: 12px;
    font-size: 0.75rem;
    font-weight: 600;
    background: var(--theme);
    border: 1px solid var(--border);
}
.pill-invited {
    background: rgba(0, 128, 128, 0.12);
    color: #008080;
    border-color: rgba(0, 128, 128, 0.3);
}
.pill-award {
    background: rgba(230, 81, 0, 0.1);
    color: #e65100;
    border-color: rgba(230, 81, 0, 0.3);
}
.talk-details {
    font-size: 0.9rem;
    line-height: 1.5;
    color: var(--primary);
    border-top: 1px solid var(--border);
    padding-top: 10px;
    margin-top: 10px;
}
.talk-links {
    margin-top: 10px;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}
.talk-link-btn {
    font-size: 0.8rem;
    font-weight: 600;
    color: #008080 !important;
    border: 1px solid rgba(0, 128, 128, 0.4);
    padding: 3px 10px;
    border-radius: 6px;
    text-decoration: none !important;
    transition: all 0.15s ease;
}
.talk-link-btn:hover {
    background: #008080;
    color: #ffffff !important;
}
.results-count {
    font-size: 0.9rem;
    color: var(--secondary);
    margin-bottom: 16px;
    font-weight: 600;
}

</style>

This catalog contains my complete record of **42 presentations, invited keynotes, seminars, conference talks, and poster sessions** (2019–2026). Use the interactive filter tags and search below to slice by forum type, presentation category, format, or research project.

<div class="filter-container">
  <div class="filter-group">
    <input type="text" id="searchTalks" class="search-input" placeholder="🔍 Search by topic, conference, location, year, or award...">
  </div>
  <div class="filter-group">
    <span class="filter-label">Category</span>
    <div class="filter-buttons" id="catFilters">
      <button class="filter-btn active" data-filter-type="cat" data-filter-val="all">All Categories (42)</button>
      <button class="filter-btn" data-filter-type="cat" data-filter-val="Invited">Invited (12)</button>
      <button class="filter-btn" data-filter-type="cat" data-filter-val="Contributed">Contributed (30)</button>
    </div>
  </div>
  <div class="filter-group">
    <span class="filter-label">Forum Type</span>
    <div class="filter-buttons" id="forumFilters">
      <button class="filter-btn active" data-filter-type="forum" data-filter-val="all">All Forums</button>
      <button class="filter-btn" data-filter-type="forum" data-filter-val="Statistics">Statistics (14)</button>
      <button class="filter-btn" data-filter-type="forum" data-filter-val="Data Science">Data Science (13)</button>
      <button class="filter-btn" data-filter-type="forum" data-filter-val="Biostatistics">Biostatistics (9)</button>
      <button class="filter-btn" data-filter-type="forum" data-filter-val="Biomedical">Biomedical (6)</button>
    </div>
  </div>
  <div class="filter-group">
    <span class="filter-label">Format</span>
    <div class="filter-buttons" id="fmtFilters">
      <button class="filter-btn active" data-filter-type="fmt" data-filter-val="all">All Formats</button>
      <button class="filter-btn" data-filter-type="fmt" data-filter-val="Talk">Talk</button>
      <button class="filter-btn" data-filter-type="fmt" data-filter-val="Poster">Poster</button>
      <button class="filter-btn" data-filter-type="fmt" data-filter-val="Speed Talk, Poster">Speed Talk & Poster</button>
    </div>
  </div>
  <div class="filter-group">
    <span class="filter-label">Associated Research Project / Paper</span>
    <div class="filter-buttons" id="paperFilters">
      <button class="filter-btn active" data-filter-type="paper" data-filter-val="all">All Projects</button>
      <button class="filter-btn" data-filter-type="paper" data-filter-val="fiBAG (JASA 2024)">fiBAG (JASA 2024)</button>
      <button class="filter-btn" data-filter-type="paper" data-filter-val="TransPRECISE (JCO CCI 2020)">TransPRECISE (JCO 2020)</button>
      <button class="filter-btn" data-filter-type="paper" data-filter-val="COVID-19 Resilience">COVID-19 Resilience</button>
      <button class="filter-btn" data-filter-type="paper" data-filter-val="BaySyn (PSB 2023)">BaySyn (PSB 2023)</button>
      <button class="filter-btn" data-filter-type="paper" data-filter-val="GPVIBES">GPVIBES</button>
    </div>
  </div>
  <div class="filter-group">
    <span class="filter-label">Status</span>
    <div class="filter-buttons" id="statusFilters">
      <button class="filter-btn active" data-filter-type="status" data-filter-val="all">All Events (42)</button>
      <button class="filter-btn" data-filter-type="status" data-filter-val="Presented">Personally Presented (39)</button>
      <button class="filter-btn" data-filter-type="status" data-filter-val="awards_only">🏆 Award Winning (13)</button>
    </div>
  </div>
</div>

<div id="resultsCount" class="results-count">Showing all 42 presentations</div>

<div id="talksList">
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="GPVIBES" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2026"
     data-search="gpvibes: bayesian gaussian process-based varying coefficient models for incorporating tumor heterogeneity in clinicogenomic studies international indian statistical association annual conference (iisa 2026) banaras hindu university, varanasi, india gpvibes: bayesian gaussian process-based varying coefficient models for incorporating tumor heterogeneity in clinicogenomic studies (in prep) invited statistics none">
    <div class="talk-conf">International Indian Statistical Association Annual Conference (IISA 2026)</div>
    <h3 class="talk-title">GPVIBES: Bayesian Gaussian Process-based Varying Coefficient Models for Incorporating Tumor Heterogeneity in Clinicogenomic Studies</h3>
    <div class="talk-meta">
        <span>📅 <strong>December 2026</strong></span>
        <span>📍 Banaras Hindu University, Varanasi, India</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>GPVIBES: Bayesian Gaussian process-based varying coefficient models for incorporating tumor heterogeneity in clinicogenomic studies (In Prep)</em></div>
        
        <div class="talk-links"><a href="https://bayesrx.shinyapps.io/GPVIBES/" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/GPVIBES/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Selected (Did Not Present)" 
     data-has-award="false" 
     data-year="2026"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform clinicogenomic data international conference on artificial intelligence and statistics (aistats 2026) tangier, morocco functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed data science none">
    <div class="talk-conf">International Conference on Artificial Intelligence and Statistics (AISTATS 2026)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Clinicogenomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>May 2026</strong></span>
        <span>📍 Tangier, Morocco</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Data Science</span>
        <span class="pill-tag" style="background: rgba(100,100,100,0.15); color: var(--secondary);">Selected (Did Not Present)</span>
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Biostatistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2024"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform clinicogenomic data international biometric conference (ibc 2024) atlanta, ga, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) invited biostatistics none">
    <div class="talk-conf">International Biometric Conference (IBC 2024)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-dimensional Multiplatform Clinicogenomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>December 2024</strong></span>
        <span>📍 Atlanta, GA, USA</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Selected (Did Not Present)" 
     data-has-award="false" 
     data-year="2023"
     data-search="baysyn: bayesian evidence synthesis for multi-system multiomic integration joint statistical meetings (jsm 2023) toronto, on, canada baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) contributed statistics none">
    <div class="talk-conf">Joint Statistical Meetings (JSM 2023)</div>
    <h3 class="talk-title">BaySyn: Bayesian Evidence Synthesis for Multi-system Multiomic Integration</h3>
    <div class="talk-meta">
        <span>📅 <strong>August 2023</strong></span>
        <span>📍 Toronto, ON, Canada</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        <span class="pill-tag" style="background: rgba(100,100,100,0.15); color: var(--secondary);">Selected (Did Not Present)</span>
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2023"
     data-search="fibag: functional integrative bayesian analysis of high-dimensional multiplatform genomic data university of michigan biostatistics senior phd student research showcase symposium (spsrss 2023) university of michigan, ann arbor, mi, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biostatistics none">
    <div class="talk-conf">University of Michigan Biostatistics Senior PhD Student Research Showcase Symposium (SPSRSS 2023)</div>
    <h3 class="talk-title">fiBAG: Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>May 2023</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Speed Talk, Poster" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2023"
     data-search="baysyn: bayesian evidence synthesis for multi-system multiomic integration michigan student symposium for interdisciplinary statistical sciences (mssiss 2023) university of michigan, ann arbor, mi, usa baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) contributed statistics none">
    <div class="talk-conf">Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS 2023)</div>
    <h3 class="talk-title">BaySyn: Bayesian Evidence Synthesis for Multi-system Multiomic Integration</h3>
    <div class="talk-meta">
        <span>📅 <strong>April 2023</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Speed Talk, Poster</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Talk" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2023"
     data-search="baysyn: bayesian evidence synthesis for multi-system multiomic integration eastern north american region international biometric society spring meeting (enar 2023) nashville, tn, usa baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) contributed biostatistics none">
    <div class="talk-conf">Eastern North American Region International Biometric Society Spring Meeting (ENAR 2023)</div>
    <h3 class="talk-title">BaySyn: Bayesian Evidence Synthesis for Multi-system Multiomic Integration</h3>
    <div class="talk-meta">
        <span>📅 <strong>March 2023</strong></span>
        <span>📍 Nashville, TN, USA</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2023"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data advances in statistical and computational methods for analysis of biomedical, genetic, and omics data conference (abgod 2023) ut southwestern medical center, dallas, tx, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biostatistics travel award – national science foundation (nsf)">
    <div class="talk-conf">Advances in Statistical and Computational Methods for Analysis of Biomedical, Genetic, and Omics Data Conference (ABGOD 2023)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>March 2023</strong></span>
        <span>📍 UT Southwestern Medical Center, Dallas, TX, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – National Science Foundation (NSF)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Talk" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2023"
     data-search="baysyn: bayesian evidence synthesis for multi-system multiomic integration pacific symposium on biocomputing (psb 2023) big island, hi, usa baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) contributed biomedical travel award – national library of medicine / national institutes of health (nlm/nih)">
    <div class="talk-conf">Pacific Symposium on Biocomputing (PSB 2023)</div>
    <h3 class="talk-title">BaySyn: Bayesian Evidence Synthesis for Multi-System Multiomic Integration</h3>
    <div class="talk-meta">
        <span>📅 <strong>January 2023</strong></span>
        <span>📍 Big Island, HI, USA</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – National Library of Medicine / National Institutes of Health (NLM/NIH)</div>
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Selected (Did Not Present)" 
     data-has-award="true" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform clinicogenomic data international conference on statistics and data science (icsds 2022) virtual (university of florence, florence, italy) functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed data science travel award – international conference on statistics and data science (icsds)">
    <div class="talk-conf">International Conference on Statistics and Data Science (ICSDS 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Clinicogenomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>December 2022</strong></span>
        <span>📍 Virtual (University of Florence, Florence, Italy)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Data Science</span>
        <span class="pill-tag" style="background: rgba(100,100,100,0.15); color: var(--secondary);">Selected (Did Not Present)</span>
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – International Conference on Statistics and Data Science (ICSDS)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2022"
     data-search="fibag: functional integrative bayesian analysis of high-dimensional multiplatform genomic data michigan postdoctoral pioneer program symposium (mp3 2022) university of michigan, ann arbor, mi, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biomedical none">
    <div class="talk-conf">Michigan Postdoctoral Pioneer Program Symposium (MP3 2022)</div>
    <h3 class="talk-title">fiBAG: Functional Integrative Bayesian Analysis of High-dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>October 2022</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Biomedical" 
     data-fmt="Talk" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="baysyn: bayesian evidence synthesis for multi-system multiomic integration environmental mutagenesis and genomics society bioinformatics challenge (emgs 2022) virtual (palm springs, ca, usa) baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) invited biomedical presentation award (runner-up) – environmental mutagenesis and genomics society (emgs)">
    <div class="talk-conf">Environmental Mutagenesis and Genomics Society Bioinformatics Challenge (EMGS 2022)</div>
    <h3 class="talk-title">BaySyn: Bayesian Evidence Synthesis for Multi-system Multiomic Integration</h3>
    <div class="talk-meta">
        <span>📅 <strong>September 2022</strong></span>
        <span>📍 Virtual (Palm Springs, CA, USA)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Presentation Award (Runner-up) – Environmental Mutagenesis and Genomics Society (EMGS)</div>
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data american statistical association biopharmaceutical section regulatory-industry statistics workshop (biop 2022) virtual (rockville, md, usa) functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biostatistics none">
    <div class="talk-conf">American Statistical Association Biopharmaceutical Section Regulatory-Industry Statistics Workshop (BIOP 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>September 2022</strong></span>
        <span>📍 Virtual (Rockville, MD, USA)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data joint statistical meetings (jsm 2022) washington, dc, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed statistics travel award – university of michigan rackham graduate school (rackham)">
    <div class="talk-conf">Joint Statistical Meetings (JSM 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>August 2022</strong></span>
        <span>📍 Washington, DC, USA</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – University of Michigan Rackham Graduate School (Rackham)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data indian statistical institute interdisciplinary statistical research unit seminar (isru 2022) virtual (indian statistical institute, kolkata, india) functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) invited statistics none">
    <div class="talk-conf">Indian Statistical Institute Interdisciplinary Statistical Research Unit Seminar (ISRU 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>July 2022</strong></span>
        <span>📍 Virtual (Indian Statistical Institute, Kolkata, India)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Statistics" 
     data-fmt="Talk, Poster" 
     data-paper="BaySyn (PSB 2023)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="bayesian strategies for multi-study integration using biological hierarchies world meeting of the international society for bayesian analysis (isba 2022) montreal, qc, canada baysyn: bayesian evidence synthesis for multi-system multiomic integration (psb 2023) invited statistics travel award – international society for bayesian analysis (isba)">
    <div class="talk-conf">World Meeting of the International Society for Bayesian Analysis (ISBA 2022)</div>
    <h3 class="talk-title">Bayesian Strategies for Multi-study Integration using Biological Hierarchies</h3>
    <div class="talk-meta">
        <span>📅 <strong>June 2022</strong></span>
        <span>📍 Montreal, QC, Canada</span>
        <span class="pill-tag pill-invited">Invited Talk, Poster</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>BaySyn: Bayesian evidence synthesis for multi-system multiomic integration (PSB 2023)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – International Society for Bayesian Analysis (ISBA)</div>
        <div class="talk-links"><a href="https://doi.org/10.1142/9789811270611_0026" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/BaySyn/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Talk, Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data american statistical association symposium on data science and statistics (sdss 2022) pittsburgh, pa, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed data science travel award – american statistical association (asa)">
    <div class="talk-conf">American Statistical Association Symposium on Data Science and Statistics (SDSS 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>June 2022</strong></span>
        <span>📍 Pittsburgh, PA, USA</span>
        <span class="pill-tag ">Contributed Talk, Poster</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – American Statistical Association (ASA)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data texas a&m university conference on advances in data science (cads 2022) texas a&m university, college station, tx, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed data science travel award – national science foundation (nsf)">
    <div class="talk-conf">Texas A&M University Conference on Advances in Data Science (CADS 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>May 2022</strong></span>
        <span>📍 Texas A&M University, College Station, TX, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – National Science Foundation (NSF)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform clinicogenomic data statistical methods in oncology annual symposium (stat4onc 2022) virtual (university of chicago / stanford / uconn) functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biostatistics poster award (runner-up) – statistical methods in oncology (stat4onc)">
    <div class="talk-conf">Statistical Methods in Oncology Annual Symposium (Stat4Onc 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Clinicogenomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>May 2022</strong></span>
        <span>📍 Virtual (University of Chicago / Stanford / UConn)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Poster Award (Runner-up) – Statistical Methods in Oncology (Stat4Onc)</div>
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Speed Talk, Poster" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data michigan student symposium for interdisciplinary statistical sciences (mssiss 2022) university of michigan, ann arbor, mi, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed statistics none">
    <div class="talk-conf">Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-Dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>April 2022</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Speed Talk, Poster</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2022"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genomic data eastern north american region international biometric society spring meeting (enar 2022) houston, tx, usa functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed biostatistics none">
    <div class="talk-conf">Eastern North American Region International Biometric Society Spring Meeting (ENAR 2022)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-dimensional Multiplatform Genomic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>March 2022</strong></span>
        <span>📍 Houston, TX, USA</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2021"
     data-search="underreporting factors and vulnerability indices in context of covid-19: two case studies on india university of michigan department of statistics student seminar series (sss 2021) virtual (university of michigan, ann arbor, mi) role of multi-resolution vulnerability indices in covid-19 spread in india: a bayesian model-based analysis (bmj open 2022) invited statistics none">
    <div class="talk-conf">University of Michigan Department of Statistics Student Seminar Series (SSS 2021)</div>
    <h3 class="talk-title">Underreporting Factors and Vulnerability Indices in Context of COVID-19: Two Case Studies on India</h3>
    <div class="talk-meta">
        <span>📅 <strong>September 2021</strong></span>
        <span>📍 Virtual (University of Michigan, Ann Arbor, MI)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Role of multi-resolution vulnerability indices in COVID-19 spread in India: A Bayesian model-based analysis (BMJ Open 2022)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1136/bmjopen-2021-056292" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="fiBAG (JASA 2024)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2021"
     data-search="functional integrative bayesian analysis of high-dimensional multiplatform genetic data joint statistical meetings (jsm 2021) virtual (seattle, wa) functional integrative bayesian analysis of high-dimensional multiplatform genomic data (jasa 2024) contributed statistics none">
    <div class="talk-conf">Joint Statistical Meetings (JSM 2021)</div>
    <h3 class="talk-title">Functional Integrative Bayesian Analysis of High-dimensional Multiplatform Genetic Data</h3>
    <div class="talk-meta">
        <span>📅 <strong>August 2021</strong></span>
        <span>📍 Virtual (Seattle, WA)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Functional integrative Bayesian analysis of high-dimensional multiplatform genomic data (JASA 2024)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1080/01621459.2024.2388909" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/fiBAG/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2021"
     data-search="personalized network modeling of the pan-cancer patient and cell line interactome world meeting of the international society for bayesian analysis (isba 2021) virtual (kunming, china) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed statistics none">
    <div class="talk-conf">World Meeting of the International Society for Bayesian Analysis (ISBA 2021)</div>
    <h3 class="talk-title">Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>June 2021</strong></span>
        <span>📍 Virtual (Kunming, China)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2021"
     data-search="network-based modeling of covid-19 dynamics in india american statistical association symposium on data science and statistics (sdss 2021) virtual (american statistical association) network-based modeling of covid-19 dynamics: early pandemic spread in india (j. indian statistical association 2021) contributed data science funding award – american statistical association (asa)">
    <div class="talk-conf">American Statistical Association Symposium on Data Science and Statistics (SDSS 2021)</div>
    <h3 class="talk-title">Network-Based Modeling of COVID-19 Dynamics in India</h3>
    <div class="talk-meta">
        <span>📅 <strong>June 2021</strong></span>
        <span>📍 Virtual (American Statistical Association)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Network-based modeling of COVID-19 dynamics: early pandemic spread in India (J. Indian Statistical Association 2021)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Funding Award – American Statistical Association (ASA)</div>
        <div class="talk-links"><a href="https://www.indstatassoc.org/journal-jisa/previous-volumes/june-2022-vol-601" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/COV-N/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2021"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome international indian statistical association annual conference (iisa 2021) virtual (university of illinois chicago, chicago, il) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) invited statistics none">
    <div class="talk-conf">International Indian Statistical Association Annual Conference (IISA 2021)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>May 2021</strong></span>
        <span>📍 Virtual (University of Illinois Chicago, Chicago, IL)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Biomedical" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2021"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome university of michigan department of computational medicine and bioinformatics tools and technology seminar (dcmb 2021) virtual (university of michigan, ann arbor, mi) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) invited biomedical none">
    <div class="talk-conf">University of Michigan Department of Computational Medicine and Bioinformatics Tools and Technology Seminar (DCMB 2021)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>March 2021</strong></span>
        <span>📍 Virtual (University of Michigan, Ann Arbor, MI)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic university of connecticut statistical data science lab seminar (sdsl 2020) virtual (university of connecticut, storrs, ct) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) invited data science none">
    <div class="talk-conf">University of Connecticut Statistical Data Science Lab Seminar (SDSL 2020)</div>
    <h3 class="talk-title">Predictions, Role of Interventions and Effects of a Historic National Lockdown in India's Response to the COVID-19 Pandemic</h3>
    <div class="talk-meta">
        <span>📅 <strong>November 2020</strong></span>
        <span>📍 Virtual (University of Connecticut, Storrs, CT)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="transprecise: proteomics-based network modeling of the pan-cancer patient and cell line interactome harvard program in quantitative genomics annual conference (pqg 2020) virtual (harvard t.h. chan school of public health, boston, ma) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed biomedical none">
    <div class="talk-conf">Harvard Program in Quantitative Genomics Annual Conference (PQG 2020)</div>
    <h3 class="talk-title">TransPRECISE: Proteomics-Based Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>November 2020</strong></span>
        <span>📍 Virtual (Harvard T.H. Chan School of Public Health, Boston, MA)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic university of chicago institute for mathematical and statistical innovation workshop (imsi 2020) virtual (university of chicago, chicago, il) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) invited data science none">
    <div class="talk-conf">University of Chicago Institute for Mathematical and Statistical Innovation Workshop (IMSI 2020)</div>
    <h3 class="talk-title">Predictions, Role of Interventions and Effects of a Historic National Lockdown in India's Response to the COVID-19 Pandemic</h3>
    <div class="talk-meta">
        <span>📅 <strong>October 2020</strong></span>
        <span>📍 Virtual (University of Chicago, Chicago, IL)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Poster" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2020"
     data-search="predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic american public health association annual meeting (apha 2020) virtual (san francisco, ca) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) contributed biomedical poster award – american public health association applied public health statistics section (apha aphs)">
    <div class="talk-conf">American Public Health Association Annual Meeting (APHA 2020)</div>
    <h3 class="talk-title">Predictions, Role of Interventions and Effects of a Historic National Lockdown in India's Response to the COVID-19 Pandemic</h3>
    <div class="talk-meta">
        <span>📅 <strong>October 2020</strong></span>
        <span>📍 Virtual (San Francisco, CA)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Poster Award – American Public Health Association Applied Public Health Statistics Section (APHA APHS)</div>
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome national cancer institute informatics technology for cancer research annual meeting (nci itcr 2020) virtual (national cancer institute) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed biomedical none">
    <div class="talk-conf">National Cancer Institute Informatics Technology for Cancer Research Annual Meeting (NCI ITCR 2020)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>September 2020</strong></span>
        <span>📍 Virtual (National Cancer Institute)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biostatistics" 
     data-fmt="Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2020"
     data-search="transprecise: proteomics-based network modeling of the pan-cancer patient and cell line interactome american statistical association biopharmaceutical section regulatory-industry statistics workshop (biop 2020) virtual (rockville, md) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed biostatistics poster award – american statistical association biopharmaceutical section (asa biop)">
    <div class="talk-conf">American Statistical Association Biopharmaceutical Section Regulatory-Industry Statistics Workshop (BIOP 2020)</div>
    <h3 class="talk-title">TransPRECISE: Proteomics-Based Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>September 2020</strong></span>
        <span>📍 Virtual (Rockville, MD)</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biostatistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Poster Award – American Statistical Association Biopharmaceutical Section (ASA BIOP)</div>
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome joint statistical meetings (jsm 2020) virtual (philadelphia, pa) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed statistics none">
    <div class="talk-conf">Joint Statistical Meetings (JSM 2020)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>August 2020</strong></span>
        <span>📍 Virtual (Philadelphia, PA)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Talk" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2020"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome international indian statistical association student paper competition (iisa spc 2020) virtual (international indian statistical association) personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed statistics paper award – international indian statistical association (iisa)">
    <div class="talk-conf">International Indian Statistical Association Student Paper Competition (IISA SPC 2020)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>July 2020</strong></span>
        <span>📍 Virtual (International Indian Statistical Association)</span>
        <span class="pill-tag ">Contributed Talk</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Paper Award – International Indian Statistical Association (IISA)</div>
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic china data institute and future data lab webinar series (cdi/fdl 2020) virtual (harvard university / china data institute, cambridge, ma) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) invited data science none">
    <div class="talk-conf">China Data Institute and Future Data Lab Webinar Series (CDI/FDL 2020)</div>
    <h3 class="talk-title">Predictions, Role of Interventions and Effects of a Historic National Lockdown in India's Response to the COVID-19 Pandemic</h3>
    <div class="talk-meta">
        <span>📅 <strong>July 2020</strong></span>
        <span>📍 Virtual (Harvard University / China Data Institute, Cambridge, MA)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic national council of applied economic research policy seminar (ncaer 2020) virtual (ncaer, new delhi, india) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) invited data science none">
    <div class="talk-conf">National Council of Applied Economic Research Policy Seminar (NCAER 2020)</div>
    <h3 class="talk-title">Predictions, Role of Interventions and Effects of a Historic National Lockdown in India's Response to the COVID-19 Pandemic</h3>
    <div class="talk-meta">
        <span>📅 <strong>July 2020</strong></span>
        <span>📍 Virtual (NCAER, New Delhi, India)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Invited" 
     data-forum="Data Science" 
     data-fmt="Talk" 
     data-paper="COVID-19 Resilience" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="covid-19: a data science call to arms - modeling the pandemic in india michigan institute for data science covid-19 seminar (midas 2020) virtual (university of michigan, ann arbor, mi) predictions, role of interventions and effects of a historic national lockdown in india's response to the covid-19 pandemic (harvard data science review 2020) invited data science none">
    <div class="talk-conf">Michigan Institute for Data Science COVID-19 Seminar (MIDAS 2020)</div>
    <h3 class="talk-title">COVID-19: A Data Science Call to Arms - Modeling the Pandemic in India</h3>
    <div class="talk-meta">
        <span>📅 <strong>April 2020</strong></span>
        <span>📍 Virtual (University of Michigan, Ann Arbor, MI)</span>
        <span class="pill-tag pill-invited">Invited Talk</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Predictions, role of interventions and effects of a historic national lockdown in India's response to the COVID-19 pandemic (Harvard Data Science Review 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1162/99608f92.60e08ed5" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://umich-biostatistics.shinyapps.io/covid19/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Statistics" 
     data-fmt="Speed Talk, Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2020"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome michigan student symposium for interdisciplinary statistical sciences (mssiss 2020) university of michigan, ann arbor, mi, usa personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed statistics presentation award (best speed oral) – michigan student symposium for interdisciplinary statistical sciences (mssiss)">
    <div class="talk-conf">Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS 2020)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>February 2020</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Speed Talk, Poster</span>
        <span class="pill-tag">Statistics</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Presentation Award (Best Speed Oral) – Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS)</div>
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="false" 
     data-year="2020"
     data-search="transprecise: personalized network modeling of the pan-cancer patient and cell line interactome michigan institute for data science data for public good symposium (midas dpg 2020) university of michigan, ann arbor, mi, usa personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed data science none">
    <div class="talk-conf">Michigan Institute for Data Science Data for Public Good Symposium (MIDAS DPG 2020)</div>
    <h3 class="talk-title">TransPRECISE: Personalized Network Modeling of the Pan-Cancer Patient and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>February 2020</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Biomedical" 
     data-fmt="Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2019"
     data-search="transprecise: proteomics-based network modeling of pan-cancer human and cell line interactome integrative biostatistics research for imaging, genomics, and high-throughput technologies in precision medicine conference (ibright 2019) md anderson cancer center, houston, tx, usa personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed biomedical travel award – md anderson cancer center (mdacc)">
    <div class="talk-conf">Integrative Biostatistics Research for Imaging, Genomics, and High-throughput Technologies in Precision Medicine Conference (iBRIGHT 2019)</div>
    <h3 class="talk-title">TransPRECISE: Proteomics-based Network Modeling of Pan-cancer Human and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>November 2019</strong></span>
        <span>📍 MD Anderson Cancer Center, Houston, TX, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Biomedical</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> Travel Award – MD Anderson Cancer Center (MDACC)</div>
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
<div class="talk-card" 
     data-cat="Contributed" 
     data-forum="Data Science" 
     data-fmt="Poster" 
     data-paper="TransPRECISE (JCO CCI 2020)" 
     data-status="Presented" 
     data-has-award="true" 
     data-year="2019"
     data-search="transprecise: proteomics-based network modeling of pan-cancer human and cell line interactome michigan institute for data science annual symposium (midas 2019) university of michigan, ann arbor, mi, usa personalized network modeling of the pan-cancer patient and cell line interactome (jco clinical cancer informatics 2020) contributed data science 1. poster award (best overall poster) – michigan institute for data science (midas)<br>2. poster award (most innovative use of data) – michigan institute for data science (midas)">
    <div class="talk-conf">Michigan Institute for Data Science Annual Symposium (MIDAS 2019)</div>
    <h3 class="talk-title">TransPRECISE: Proteomics-based Network Modeling of Pan-cancer Human and Cell Line Interactome</h3>
    <div class="talk-meta">
        <span>📅 <strong>November 2019</strong></span>
        <span>📍 University of Michigan, Ann Arbor, MI, USA</span>
        <span class="pill-tag ">Contributed Poster</span>
        <span class="pill-tag">Data Science</span>
        
    </div>
    <div class="talk-details">
        <div>🔗 <strong>Project:</strong> <em>Personalized network modeling of the pan-cancer patient and cell line interactome (JCO Clinical Cancer Informatics 2020)</em></div>
        <div style="margin-top: 6px; font-size: 0.88rem;">🏆 <strong style="color: #e65100;">Award Won:</strong> 1. Poster Award (Best Overall Poster) – Michigan Institute for Data Science (MIDAS)<br>2. Poster Award (Most Innovative Use of Data) – Michigan Institute for Data Science (MIDAS)</div>
        <div class="talk-links"><a href="https://doi.org/10.1200/CCI.19.00140" target="_blank" class="talk-link-btn">📄 Associated Publication</a><a href="https://bayesrx.shinyapps.io/TransPRECISE/" target="_blank" class="talk-link-btn">🚀 R Shiny Dashboard</a></div>
    </div>
</div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
    const filters = {
        cat: 'all',
        forum: 'all',
        fmt: 'all',
        paper: 'all',
        status: 'all',
        search: ''
    };

    const cards = Array.from(document.querySelectorAll('.talk-card'));
    const countDisplay = document.getElementById('resultsCount');
    const searchInput = document.getElementById('searchTalks');

    function applyFilters() {
        let visibleCount = 0;
        const query = filters.search.trim().toLowerCase();

        cards.forEach(card => {
            const cardCat = card.getAttribute('data-cat');
            const cardForum = card.getAttribute('data-forum');
            const cardFmt = card.getAttribute('data-fmt');
            const cardPaper = card.getAttribute('data-paper');
            const cardStatus = card.getAttribute('data-status');
            const cardHasAward = card.getAttribute('data-has-award');
            const cardSearch = card.getAttribute('data-search');

            let matchCat = (filters.cat === 'all' || cardCat === filters.cat);
            let matchForum = (filters.forum === 'all' || cardForum === filters.forum);
            let matchFmt = (filters.fmt === 'all' || cardFmt.includes(filters.fmt));
            let matchPaper = (filters.paper === 'all' || cardPaper === filters.paper);
            
            let matchStatus = true;
            if (filters.status === 'Presented') {
                matchStatus = (cardStatus === 'Presented');
            } else if (filters.status === 'awards_only') {
                matchStatus = (cardHasAward === 'true');
            }

            let matchSearch = (!query || cardSearch.includes(query));

            if (matchCat && matchForum && matchFmt && matchPaper && matchStatus && matchSearch) {
                card.style.display = 'block';
                visibleCount++;
            } else {
                card.style.display = 'none';
            }
        });

        countDisplay.textContent = `Showing ${visibleCount} of ${cards.length} presentations`;
    }

    document.querySelectorAll('.filter-btn').forEach(btn => {
        btn.addEventListener('click', function (e) {
            e.preventDefault();
            const filterType = this.getAttribute('data-filter-type');
            const filterVal = this.getAttribute('data-filter-val');

            // Update button active state in same group
            const parent = this.parentElement;
            parent.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
            this.classList.add('active');

            filters[filterType] = filterVal;
            applyFilters();
        });
    });

    if (searchInput) {
        searchInput.addEventListener('input', function () {
            filters.search = this.value;
            applyFilters();
        });
    }
});
</script>
