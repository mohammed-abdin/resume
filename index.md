<style>
  /* Global Styles */
  body {
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #333333;
    max-width: 800px;
    margin: 40px auto;
    padding: 0 20px;
    background-color: #f8f9fa;
  }
  
  /* Header UI */
  .header-container {
    text-align: center;
    margin-bottom: 30px;
  }
  .header-container h1 {
    color: #232f3e; /* Amazon Navy */
    margin-bottom: 5px;
    font-size: 32px;
    font-weight: 700;
  }
  .title-sub {
    font-weight: 600;
    color: #ff9900; /* Amazon Orange Accent */
    margin: 0 0 12px 0;
    font-size: 18px;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  .contact-info {
    font-size: 14px;
    color: #555555;
    margin: 0 0 20px 0;
  }
  
  /* Button Styling */
  .btn-container {
    margin-bottom: 25px;
    text-align: center;
  }
  .download-btn {
    display: inline-flex;
    align-items: center;
    background-color: #232f3e;
    color: white !important;
    padding: 10px 20px;
    font-size: 14px;
    font-weight: 600;
    border-radius: 4px;
    text-decoration: none;
    border: none;
    cursor: pointer;
    transition: background-color 0.2s ease, transform 0.1s ease;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  .download-btn:hover {
    background-color: #ff9900;
    transform: translateY(-1px);
  }
  .download-btn:active {
    transform: translateY(1px);
  }
  .download-btn svg {
    margin-right: 8px;
    fill: currentColor;
  }

  /* Structural Sections */
  h2 {
    color: #232f3e;
    font-size: 18px;
    border-bottom: 2px solid #ff9900;
    padding-bottom: 5px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-top: 35px;
  }
  h3 {
    margin: 0;
    font-size: 16px;
    color: #111111;
  }
  .job-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 2px;
  }
  .job-meta {
    margin: 2px 0 10px 0;
    font-style: italic;
    font-size: 14px;
    color: #555555;
  }
  ul {
    font-size: 14px;
    padding-left: 20px;
    margin: 0 0 20px 0;
  }
  li {
    margin-bottom: 6px;
  }
  
  /* PRINT OPTIMIZATION (For perfect PDF rendering) */
  @media print {
    body {
      background-color: #ffffff;
      color: #000000;
      margin: 0;
      padding: 0;
      max-width: 100%;
    }
    .btn-container, .download-btn {
      display: none !important; /* Hide button on PDF print */
    }
    .header-container h1 {
      color: #111111;
    }
    h2 {
      color: #111111;
      border-bottom: 1.5px solid #333333;
    }
    .job-header h3 {
      color: #000000;
    }
    /* Prevents messy multi-page cutoffs */
    .job-block {
      page-break-inside: avoid;
    }
  }
</style>

<div class="header-container">
  <h1>Mohammed Abdin</h1>
  <p class="title-sub">Senior Business Intelligence Engineer</p>
  <p class="contact-info">San Jose, CA | +1(408) 834-6864 | moh.yasser27@gmail.com</p>
</div>

<div class="btn-container">
  <button class="download-btn" onclick="window.print()">
    <svg width="16" height="16" viewBox="0 0 24 24">
      <path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/>
    </svg>
    Download PDF Resume
  </button>
</div>

<h2>Professional Summary</h2>
<p style="font-size: 14px; margin-bottom: 20px;">Senior Business Intelligence Engineer with over five years of experience translating complex data into strategic business solutions. Proven track record of owning entire analytical pipelines, from scalable data warehousing and multi-tier Medallion architectures to executive-level business dashboards. Skilled in robust dimensional data modeling, implementing end-to-end data quality frameworks, and leveraging agentic AI tools like Claude Code to accelerate pipeline development and boost developer productivity. Adept at bridging the gap between technical infrastructure and stakeholder requirements to drive data accuracy and accessibility across the organization.</p>

<h2>Technical Skills</h2>
<ul>
  <li style="margin-bottom: 8px;"><strong>Business Intelligence & Analytics:</strong> Tableau, Power BI, Looker Studio, Streamlit, Executive Dashboards, Command Centers, Key Performance Indicators (KPIs), Variance Tracking, Statistical Analysis (Black Belt Six Sigma), Risk and Operational Mitigation Modeling.</li>
  <li style="margin-bottom: 8px;"><strong>Data Engineering & Architecture:</strong> SQL and Database Programming, Data Warehousing (AWS Redshift, Snowflake, Databricks), Medallion Architecture (Bronze, Silver, Gold stages), Dimensional Data Modeling (Star and Snowflake Schemas), ETL and ELT Pipeline Design (DBT, AWS Glue, Spark, PySpark), Data Quality, Governance, Scripting Languages (Python, Shell, Git).</li>
  <li style="margin-bottom: 8px;"><strong>Productivity & AI Tools:</strong> Claude Code, Agentic Coding Workflows, Prompt Engineering, Automated Unit Testing, CI/CD Deployment Pipelines.</li>
</ul>

<h2>Professional Experience</h2>

<div class="job-block" style="margin-bottom: 25px;">
  <div class="job-header">
    <h3>Amazon</h3>
    <span style="font-size: 14px; color: #555;">Palo Alto, CA</span>
  </div>
  <p class="job-meta">Business Intelligence Engineer, Data Engineering | October 2024 to Current</p>
  <ul>
    <li style="margin-bottom: 5px;">Integrated Claude Code into local development environments to automate boilerplate Python scripting and complex SQL syntax generation, accelerating developer velocity and reducing pipeline development-to-production cycles by 35%.</li>
    <li style="margin-bottom: 5px;">Architected and implemented modular ETL pipelines using a Medallion Architecture (Bronze, Silver, Gold stages) to streamline raw data processing into high-performance analytical layers.</li>
    <li style="margin-bottom: 5px;">Designed and optimized dimensional data models in Redshift, utilizing star schemas to support executive reporting and drastically improve query execution times.</li>
    <li style="margin-bottom: 5px;">Engineered a serverless data architecture using AWS S3, Glue, and Athena that automated data workflows, reducing processing time by 60% and empowering senior leadership with real-time, self-service analytics to identify operational anomalies.</li>
    <li style="margin-bottom: 5px;">Developed a PySpark data quality testing framework with Great Expectations, establishing automated risk controls and programmatic anomaly detection that reduced reporting defects by 90%.</li>
    <li style="margin-bottom: 5px;">Led the migration of legacy reporting systems to AWS cloud infrastructure, achieving 99.9% system availability and a 50% cost reduction.</li>
    <li style="margin-bottom: 5px;">Mentored 3 junior BIEs/DEs on AWS best practices and BI development standards, accelerating team delivery velocity and technical excellence.</li>
  </ul>
</div>

<div class="job-block" style="margin-bottom: 25px;">
  <div class="job-header">
    <h3>Meta</h3>
    <span style="font-size: 14px; color: #555;">Sunnyvale, CA</span>
  </div>
  <p class="job-meta">Data Engineer, Analytics | September 2022 to October 2024</p>
  <ul>
    <li style="margin-bottom: 5px;">Drove a 25% reduction in ETL processing time and operational overhead through the design and implementation of modern data pipelines in AWS, Snowflake, and DBT.</li>
    <li style="margin-bottom: 5px;">Designed and implemented highly scalable dimensional data models in Snowflake, enforcing rigorous data quality rules and reducing downstream storage overhead by 25%.</li>
    <li style="margin-bottom: 5px;">Analyzed source data to establish automated data quality strategies, reducing analytical reporting errors and data inconsistencies by 30%.</li>
    <li style="margin-bottom: 5px;">Partnered with cross-functional teams to build comprehensive data dictionaries and standards, aligning metrics and improving data reliability across the organization.</li>
    <li style="margin-bottom: 5px;">Designed and launched executive-level Tableau and Power BI command dashboards, enabling VPs and stakeholders to proactively track critical variance metrics and mitigate high-priority operational risks.</li>
  </ul>
</div>

<div class="job-block" style="margin-bottom: 25px;">
  <div class="job-header">
    <h3>Tesla</h3>
    <span style="font-size: 14px; color: #555;">Fremont, CA</span>
  </div>
  <p class="job-meta">Analytics Engineer, Cell Manufacturing | April 2020 to September 2022</p>
  <ul>
    <li style="margin-bottom: 5px;">Built and managed robust batch data pipelines, driving data visibility that directly contributed to a 30% increase in monthly manufacturing yield.</li>
    <li style="margin-bottom: 5px;">Initiated automated ETL and data management solutions that eliminated manual intervention, achieving 75% data automation and reducing operational vulnerabilities.</li>
    <li style="margin-bottom: 5px;">Established automated data quality audits to ensure analytics integrity, reducing data errors and down-time reporting inconsistencies by 20%.</li>
    <li style="margin-bottom: 5px;">Implemented an OLAP cube and semantic layer with over 98% accuracy, reducing business reporting time requirements by 75%.</li>
    <li style="margin-bottom: 5px;">Optimized data capture and replication workflows, achieving a 50% reduction in data duplication.</li>
  </ul>
</div>

<div class="job-block" style="margin-bottom: 25px;">
  <div class="job-header">
    <h3>Stantec Inc.</h3>
    <span style="font-size: 14px; color: #555;">San Jose, CA</span>
  </div>
  <p class="job-meta">Junior Data Engineer | July 2019 to May 2020</p>
  <ul>
    <li style="margin-bottom: 5px;">Automated data integration workflows to increase transaction tracking efficiency by 25%, empowering teams to accurately track operational trends.</li>
    <li style="margin-bottom: 5px;">Audited source databases to mitigate data quality issues, leading to a 30% drop in reporting inconsistencies.</li>
    <li style="margin-bottom: 5px;">Developed and maintained Snowflake data models to support data warehouse and analytical reporting, enhancing data accessibility by 20%.</li>
  </ul>
</div>

<div class="job-block" style="margin-bottom: 25px;">
  <div class="job-header">
    <h3>Western Digital</h3>
    <span style="font-size: 14px; color: #555;">San Jose, CA</span>
  </div>
  <p class="job-meta">Data Analyst Intern | June 2018 to October 2018</p>
  <ul>
    <li style="margin-bottom: 5px;">Conducted rigorous data cleaning, engineering, and preparation tasks utilizing SQL and Python.</li>
    <li style="margin-bottom: 5px;">Partnered with data engineering teams to scale pipeline architectures, improving baseline data quality and user accessibility.</li>
  </ul>
</div>

<h2>Education</h2>
<ul>
  <li style="margin-bottom: 5px;"><strong>MSc. in Analytics (ETL Developer and Analytics Concentration)</strong> | Georgia Institute of Technology | <em>January 2022</em></li>
  <li style="margin-bottom: 5px;"><strong>BSc. in Chemical Engineering (Minor in Computer Science)</strong> | San Jose State University | <em>May 2019</em></li>
</ul>

<h2>Certifications</h2>
<ul>
  <li style="margin-bottom: 5px;"><strong>Professional Certificate in Data Engineering</strong> – Massachusetts Institute of Technology (<em>Mar 2025</em>)</li>
  <li style="margin-bottom: 5px;"><strong>Data Engineer Bootcamp (Specializing in Analytics)</strong> – Via DataExpert.io (<em>Feb 2024</em>)</li>
  <li style="margin-bottom: 5px;"><strong>Data Science Bootcamp</strong> – Via Springboard (<em>Mar 2023</em>)</li>
</ul>
