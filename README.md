
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sihab Uddin - Industrial Engineering | Analytics | Supply Chain</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #f4f4f4;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
            display: none;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-icons {
            font-size: 24px;
            margin-right: 10px;
        }
        .publication {
            margin-bottom: 20px;
        }
    </style>
    <script>
        // JavaScript to show/hide sections based on anchor links
        document.addEventListener("DOMContentLoaded", function() {
            var sections = document.querySelectorAll("section");
            var navLinks = document.querySelectorAll("nav ul li a");

            navLinks.forEach(function(navLink) {
                navLink.addEventListener("click", function(event) {
                    event.preventDefault();
                    var targetId = this.getAttribute("href").substring(1);
                    sections.forEach(function(section) {
                        if (section.getAttribute("id") === targetId) {
                            section.style.display = "block";
                        } else {
                            section.style.display = "none";
                        }
                    });
                });
            });
        });
    </script>
</head>
<body>

<header>
    <h1>Sihab Uddin</h1>
    <p>Industrial Engineering | Analytics | Supply Chain</p>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#publications">Research Publications</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home">
    <h2>Home</h2>
    <p>I am a results-oriented professional with a passion for industrial engineering, analytics, and supply chain optimization. With a focus on delivering tangible results and driving operational excellence, I am dedicated to helping organizations achieve their goals through data-driven insights and process improvements.</p>
    <h3>Key Skills:</h3>
    <ul>
        <li>📊 Data Analytics & Visualization: Advanced Excel, IBM SPSS, Minitab, Tableau, Power BI</li>
        <li>💻 Programming Languages: C++, Python, R, SQL</li>
        <li>🛠️ ERP/MES: Siemens OpCenter, Oracle JD Edwards, SAP S/4HANA</li>
        <li>📐 Computer-Aided Drawings: PTC Creo, Autodesk Inventor, AUTOCAD</li>
        <li>🚀 Automation and Low Code App: Power Automate, Power Apps</li>
        <li>📋 Project Management Tools: JIRA, Confluence, Notion, Azure DevOps, MS Visio</li>
        <li>🔄 BPM and PM Methods: Lean Six Sigma, Agile, Scrum, Kanban, Kaizen, BPMN, VSM</li>
    </ul>
    <h3>Education:</h3>
    <ul>
        <li>
            <img src="concordia_logo.png" alt="Concordia University Logo" width="50px"> M.Eng. in Industrial Engineering<br>
            Concordia University<br>
            May 2022
        </li>
        <li>
            <img src="au_rak_logo.png" alt="American University of Ras Al Khaimah Logo" width="50px"> B.S. in Industrial Engineering<br>
            American University of Ras Al Khaimah, UAE<br>
            August 2017<br>
            Graduated with Cum Laude
        </li>
    </ul>
    <h3>Work Experience:</h3>
    <ul>
        <li><img src="intelcom_logo.png" alt="Intelcom Logo" width="50px"> Intelcom</li>
        <li><img src="brp_logo.png" alt="BRP Inc. Logo" width="50px"> BRP Inc.</li>
        <li><img src="siemens_energy_logo.png" alt="Siemens Energy Logo" width="50px"> Siemens Energy</li>
        <li><img src="weatherford_logo.png" alt="Weatherford Logo" width="50px"> Weatherford</li>
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>
    <!-- Add your projects here -->
</section>

<section id="publications">
    <h2>Research Publications</h2>
    <div class="publication">
        <h3><i class="fab fa-google"></i> Google Scholar</h3>
        <p><a href="https://scholar.google.ca/citations?user=7y1-KGgAAAAJ&hl=en" target="_blank">Visit my Google Scholar profile</a></p>
    </div>
    <div class="publication">
        <h3><i class="fas fa-book"></i> Support vector regression based electricity peak load forecasting</h3>
        <p>M. K. Azad, S. Uddin and M. Takruri, 2018 11th International Symposium on Mechatronics and its Applications (ISMA), Sharjah, United Arab Emirates, 2018, pp. 1-5, doi: 10.1109/ISMA.2018.8330143.</p>
        <p>Abstract: Electricity load demand forecasting is integral for planning and execution of various projects vital to urban development...</p>
        <p>Keywords: Support vector machines, Load forecasting, Forecasting, Support vector regression, RStudio</p>
        <p><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8330143&isnumber=8330114" target="_blank">Read more</a></p>
    </div>
    <div class="publication">
        <h3><i class="fas fa-book"></i> Integrating Internet of Things with maintenance spare parts' supply chain</h3>
        <p>S. Uddin and A. A. A. A. Sharif, 2016 5th International Conference on Electronic Devices, Systems and Applications (ICEDSA), Ras Al Khaimah, United Arab Emirates, 2016, pp. 1-4, doi: 10.1109/ICEDSA.2016.7818491.</p>
        <p>Abstract: The supply chain and logistics are integral part of any business...</p>
        <p>Keywords: Internet of Things, Supply chains, Radiofrequency identification, Companies, Internet of things, Supply chain, Logistics, Spare parts</p>
        <p><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7818491&isnumber=7818458" target="_blank">Read more</a></p>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <ul>
        <li><a href="https://www.linkedin.com/in/sihabuddinmh/" target="_blank"><i class="fab fa-linkedin contact-icons"></i>LinkedIn</a></li>
        <li><a href="https://github.com/sihabuddinmh" target="_blank"><i class="fab fa-github contact-icons"></i>GitHub</a></li>
        <li><a href="mailto:XX@XX.ca"><i class="far fa-envelope contact-icons"></i>Email</a></li>
    </ul>
</section>

<footer>
    <p>&copy; 2024 Sihab Uddin</p>
</footer>

</body>
</html>
