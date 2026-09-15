---
layout: default
---

# Projects & Achievements

<div class="tab-buttons">
    <button class="tab-btn active" onclick="showTab('softdev_tab')">Software Development</button>
    <button class="tab-btn" onclick="showTab('data_tab')">Database Administration / Data Engineering</button>
    <button class="tab-btn" onclick="showTab('others_tab')">Others</button>
</div>

<div id="softdev_tab" class="tab-content active">
    <h2>Local Notion Clone with NotebookLM Features and RAG</h2>
    <p>
       A Notion clone integrated with NotebookLM AI capabilities.
       <ul>
       <li>Smart Note Enhancement: Allows AI to directly edit, enrich, and proofread your notes.</li>
       <li>100% Local AI: Powered by local models running through LM Studio for privacy and offline control.</li>
       <li>RAG Integration: Filters and retrieves context from your knowledge base to ensure accurate, context-aware AI outputs.</li>
       </ul>
       This app combines Notion’s clean workspace UI with NotebookLM’s contextual AI assistance. Operating on a local LLM pipeline via LM Studio and powered by RAG, it enables in-editor AI content expansion and real-time grammatical corrections in your notes.
    </p>
    <h3>Tech Stack:</h3>
    <ul>
        <li>React</li>
        <li>Convex</li>
        <li>Tailwind</li>
    </ul>
    <h3>Screenshots:</h3>
    <img src="assets/images/Notion Clone Front page.png" alt="Notion Clone Index Page" width="600" height="337" style="max-width: 100%; height: auto;" />
    <h3>Repo Link:</h3>
    <a href="https://github.com/muchcauliflower/ai-saas">https://github.com/muchcauliflower/ai-saas</a>
    <hr>
    <h2>RESPONdr.</h2>
    <p>
        RESPONDr. is a prototype app designed to standardize contacts and streamline communication between a caller and an emergency responder. This is based on Singapore's ActiveSG to tackle the problems in Philippine emergency hotlines.
    </p>
    <h3>Problem:</h3>
    <p>
        The app had plans to tackle the main issues in Philippine emergency hotlines:
    </p>
    <h4>Generalized Hotlines</h4>
    <p>
        Unlike Singapore, Philippines is a much bigger country, with multiple islands and have their own provinces. Each town having emergency services with own distinctive phone numbers. And because of it, despite the efforts of the government providing their numbers, most people would only know the national emergency hotline, 991.
        <br><br>
        This provides a solution but because it is a national emergency hotline, the process may include transferring calls to the right stations to deploy services, this would waste valuable time. Also with a general hotline, it would be more congested as calls would be made to the same hotline regardless of location.
    </p>
    <h4>Uninformed Citizens</h4>
    <p>
        Not everyone has the privilege to be well informed on how to handle crises. It is not a requirement nor is it encouraged to learn important skills such as first-aid as well.
    </p>
    <h3>Solution:</h3>
    <p>
        An app to standardize emergency contacts and streamline communication
    </p>
    <ul>
        <li>Plan for the app focuses on making emergency services accessible, faster, for users by reducing delays due to call transfers and non-standardized emergency numbers</li>
        <li>Provide offline sources that users can follow during crises.</li>
        <li>This encourages users to be proactive and gives the confidence as they are able to act instead of idling.</li>
    </ul>
</div>

<div id="data_tab" class="tab-content">
    <h2>DP-900: Microsoft Certified: Azure Data Fundamentals - September 2025</h2>
    <p>
    Earned the DP-900 certification to build and validate a core foundation in Microsoft Azure’s cloud data ecosystem. Earning this credential equipped me with actionable knowledge to evaluate, select, and work with appropriate cloud database paradigms and analytics workflows based on enterprise requirements.
    </p>
    <ul>
        <li>Built a strong foundation in distinguishing relational vs. non-relational structures, transactional (OLTP) vs. analytical (OLAP) processing, and batch vs. real-time streaming architectures.</li>
        <li>Acquired clarity on selecting and configuring optimal cloud data stores across Azure SQL, managed open-source engines, and globally distributed NoSQL instances with Azure Cosmos DB.</li>
        <li>Developed an understanding of modern enterprise storage strategies, leveraging Azure Data Lake Storage Gen2 to structure unstructured data for scalable downstream pipelines.</li>
        <li>Gained fluency in data integration concepts, understanding how to orchestrate automated ETL/ELT pipelines with Azure Data Factory and unify enterprise analytics using Microsoft Fabric.</li>
    </ul>
    <p>
    Credential ID: 7D48289016043C24
    <br>
    Certification number: DFH425-F7145D
    </p>
    <h3>Course Link:</h3>
    <a href="https://learn.microsoft.com/en-us/credentials/certifications/azure-data-fundamentals/?practice-assessment-type=certification">https://learn.microsoft.com/en-us/credentials/certifications/azure-data-fundamentals/?practice-assessment-type=certification</a>
    <br><br>
    <img src="assets/images/DP-900 Cert.png" alt="DP-900 Cert" width="700" style="max-width: 100%; height: auto;" />
    <hr>
    <h2>IBM Data Engineering Professional Certificate | Coursera - May 2026</h2>
    <p>
    Completed a comprehensive 13-course program to build and demonstrate practical mastery across end-to-end data engineering infrastructure, pipeline automation, and distributed computing. Culminated the specialization by designing, deploying, and managing a complete, production-ready data engineering platform modeled after a real-world enterprise analytics scenario.
    </p>
        <ul>
        <li>Designed relational database schemas, executed advanced SQL queries, and implemented core database administration strategies and data warehousing models.</li>
        <li>Built end-to-end ETL/ELT data pipelines using Python and Shell scripting to extract, transform, and clean structured and unstructured datasets.</li>
        <li>Leveraged Apache Spark for large-scale distributed data processing and integrated NoSQL databases to handle non-relational workloads.</li>
    </ul>
    <p>
    Credential ID: RKZDHGITM033
    </p>
    <h3>Course Link:</h3>
    <a href="www.coursera.org/professional-certificates/ibm-data-engineer">www.coursera.org/professional-certificates/ibm-data-engineer</a>
    <br><br>
    <img src="assets/images/IBM Data Engineering Cert.png" alt="DP-900 Cert" width="700" style="max-width: 100%; height: auto;" />
</div>

<div id="others_tab" class="tab-content">
    <h2>Aswang Busters</h2>
    <p>
        Awang Busters was a small game project created to participate in Hackathon "Game-On: Game Developer's Gauntlet". It is also my first introduction into Python.
        <br><br>
        The premise of the game is simply to shoot as many Aswangs (A Filipino Ghost) in the given time, instead of a normal mouse and keyboard. The game uses a Nintendo Switch's Joycon for controls, leveraging and taking advantage of its built-in gyroscope module for aiming.
        <ul>
        <li>Won First Runner Up due to its unique controls</li>
        </ul>
    </p>
    <h3>Built with:</h3>
    <ul>
        <li>Python</li>
        <li>Tkinter for GUI</li>
        <li>joycon-python Library for Nintendo Switch Joy-Con Driver</li>
    </ul>
    <h3>Screenshots:</h3>
    <img src="assets/images/Aswang Busters.png" alt="Aswang Busters" width="600" height="337" style="max-width: 100%; height: auto;" />
    <img src="assets/images/FB_IMG_1789384698425.jpg" alt="FB_IMG_1789384698425" width="350" height="350" style="max-width: 100%; height: auto;" />
    <br>
    <h3>Repo Link:</h3>
    <a href="https://github.com/ZeekHoft/Nov_DevCon">https://github.com/ZeekHoft/Nov_DevCon</a>
</div>

<script>
function showTab(id) {
  document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(el => el.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  event.target.classList.add('active');
}
</script>