======================================================================
           ACADEMIC PULSE PRO v1.0.5 | SYSTEM DOCUMENTATION
                    VNR VJIET - DEPT. OF CSE
======================================================================

Academic Pulse Pro is an advanced, multi-threaded analytical engine 
designed to extract, resolve, and synchronize academic faculty 
profiles across the world's leading research databases.

----------------------------------------------------------------------
1. SYSTEM ARCHITECTURE: THE 7-STAGE PIPELINE
----------------------------------------------------------------------
Unlike standard scrapers, this system utilizes a sequential 7-stage 
processing pipeline for every faculty member:

Stage 1: Node Initialization (Targeting Scholar/Scopus/WoS)
Stage 2: Deep Extraction & Metadata Parsing
Stage 3: Identity Resolution (Master UUID Assignment)
Stage 4: Cross-Platform Record Linking
Stage 5: Multi-Source Deduplication
Stage 6: Intelligent Refinement (Golden Record Creation)
Stage 7: Supabase Cloud Synchronization

----------------------------------------------------------------------
2. HOW TO OPERATE
----------------------------------------------------------------------
1. Launch 'AcademicPulsePro.exe'.
2. Monitor the 'Live Pipeline Audit Feed' on the Dashboard.
3. Use the Sidebar to navigate between engines:

   [SCHOLAR ENGINE]
   - Enter First Name, Last Name, and Affiliation.
   - Solve the Google Captcha in the browser if prompted.

   [SCOPUS ENGINE]
   - Enter Author details.
   - REQUIREMENT: Manually log in via Institutional Credentials 
     when the browser window appears.

   [WOS GHOSTING]
   - Launch the 'Ghosting' protocol to bypass Cloudflare detection.
   - Manually navigate to the search results as prompted by the logs.

4. POST-PROCESSING:
   - Click 'VIEW OUTPUTS' on the Dashboard to access local Excels.
   - Click 'VIEW LOGS' to see the detailed UTF-8 technical audit.
   - Click 'SYSTEM INFO' (ⓘ) to view the Architecture Diagram.

----------------------------------------------------------------------
3. GENERATED ASSETS (THE AUDIT TRAIL)
----------------------------------------------------------------------
The system generates 6 specialized Excel files for every sync:
- Scholar_Profile / Scholar_Exhaustive
- Scopus_Profile  / Scopus_Publications
- WoS_Profile     / WoS_Publications

Master records are simultaneously pushed to the Supabase Cloud.

----------------------------------------------------------------------
4. SYSTEM REQUIREMENTS
----------------------------------------------------------------------
- OS: Windows 10 / 11 (64-bit)
- Browser: Google Chrome (Latest Version)
- Network: Active Internet Connection (Required for Supabase Sync)
- Resolution: 1400x900 or higher recommended

----------------------------------------------------------------------
5. PROJECT CREDITS
----------------------------------------------------------------------
INSTITUTION: VNR Vignana Jyothi Institute of Engineering & Technology
DEPARTMENT: Computer Science & Engineering (CSE)

PROJECT GUIDE: 
Dr. V. Baby, HoD & Assoc. Professor

DEVELOPMENT TEAM:
- Tirupate Aniketh
- Daripelly Vinay
- Talasila Sri Krishna Chaitanya
- Seeramreddy Sai Teja Akhil

© 2026 | Major Project Phase-II Build
======================================================================