% Welcome to the simple Undergraduate Complexity Research CV-resume template!
% Please delete any sections that do not apply to your past experiences. We do not expect that applicants will have itmes for all of the sections included here. You can also rename or revise sections to best fit with your personal accomplishments.

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{multicol}
\input{glyphtounicode}

\usepackage{baskervillef}
\usepackage[T1]{fontenc}

\pagestyle{fancy}
\fancyhf{} 
\fancyfoot{}
\setlength{\footskip}{10pt}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{0.0in}
\addtolength{\evensidemargin}{0.0in}
\addtolength{\textwidth}{0.0in}
\addtolength{\topmargin}{0.2in}
\addtolength{\textheight}{0.0in}


\urlstyle{same}

%\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \it\vspace{3pt}
}{}{0em}{}[\color{black}\titlerule\vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{
  \item{
    {#1 \vspace{-4pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small #3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-10pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-3pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-2pt}}



%----------------------------------------------------------------------------------------
%	PACKAGES
%----------------------------------------------------------------------------------------
\usepackage{url}
\usepackage{parskip} 	

%other packages for formatting
\RequirePackage{color}
\RequirePackage{graphicx}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage[scale=0.9]{geometry}

%tabularx environment
\usepackage{tabularx}

%for lists within experience section
\usepackage{enumitem}

% centered version of 'X' col. type
\newcolumntype{C}{>{\centering\arraybackslash}X} 

%to prevent spillover of tabular into next pages
\usepackage{supertabular}
\usepackage{tabularx}
\newlength{\fullcollw}
\setlength{\fullcollw}{0.47\textwidth}

%custom \section
\usepackage{titlesec}				
\usepackage{multicol}
\usepackage{multirow}

%CV Sections inspired by: 
%http://stefano.italians.nl/archives/26
\titleformat{\section}{\Large\scshape\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{10pt}{10pt}

%for publications
\usepackage[style=authoryear,sorting=ynt, maxbibnames=2]{biblatex}

%Setup hyperref package, and colours for links
\usepackage[unicode, draft=false]{hyperref}
\definecolor{linkcolour}{rgb}{0,0.2,0.6}
\hypersetup{colorlinks,breaklinks,urlcolor=linkcolour,linkcolor=linkcolour}
\addbibresource{citations.bib}
\setlength\bibitemsep{1em}

%for social icons
\usepackage{fontawesome5}



\begin{document}


\begin{tabularx}{\linewidth}{@{} C @{}}
\Huge{Shun Zhang, MD, MPH} \\[7.5pt]
%\href{https://github.com/username}{\raisebox{-0.05\height}\faGithub\ username} \ $|$ \ 
\href{https://www.linkedin.com/in/shun-zhang-b3aaa026/}{\raisebox{-0.05\height}\faLinkedin\ Professional Profile} \ $|$ \ 
%\href{https://mysite.com}{\raisebox{-0.05\height}\faGlobe \ mysite.com} \ $|$ \ 
\href{https://scholar.google.com/citations?user=GwRcQyYAAAAJ}{\raisebox{-0.05\height}{\faGlobe} \ Google Scholar} $|$ 
\href{mailto:email@mysite.com}{\raisebox{-0.05\height}\faEnvelope \ Lonver126@hotmail.com} \ $|$ \ 
\href{tel:+000000000000}{\raisebox{-0.05\height}\faMobile \ (817)896-7968} \\
\end{tabularx}


\section{Summary}
\resumeItemListStart
\resumeItem{Enterprise AI Strategy and Platform Leadership: Led the design and execution of GenAI and agentic AI platforms, aligning AI capabilities with enterprise business objectives. Defined strategic roadmaps, integrated AI solutions into commercial and medical workflows, and ensured ethical AI adoption.}  
\resumeItem{Generative AI Innovation and Product Management: Spearheaded AI-driven product development, incorporating LLMs and AI agents into data ecosystems. Drove experimentation, optimization, and adoption of AI-powered solutions to enhance efficiency and decision-making across business units.}  
\resumeItem{Cross-Functional Leadership and AI Governance: Partnered with senior executives, legal, compliance, and analytics teams to establish AI governance frameworks, ensuring regulatory adherence and responsible AI deployment. Fostered collaboration between technical and business stakeholders to scale AI adoption.}  
\resumeItem{Data Science, ML, and Advanced Analytics Expertise: Applied machine learning, predictive modeling, and analytics to optimize commercial and medical strategies. Led AI-driven initiatives in customer engagement, diagnostics, and automation to drive measurable business impact.}  
\resumeItemListEnd

%-----------WORK EXPERIENCES-----------
\section{Work Experiences}
% if you have been employed, do volunteer activities, or have held other formal or informal jobs, you can list them here.   

\resumeSubHeadingListStart

    \resumeSubheading
      {Director of AI and Data Science}{Oct, 2023 -- Present}
      {AstraZeneca} {South San Francisco, CA}
     \resumeItemListStart
    \resumeItem{\textbf{Strategic Leadership in Generative \& Agentic AI:} Led the development and deployment of a multi-agent AI platform for enterprise-wide medical, commercial, and government affairs use cases. Defined the strategic roadmap, integrating generative AI capabilities with business intelligence, data science, and automation to drive measurable impact. Partnered with senior stakeholders to align AI-driven initiatives with organizational priorities.}

   \resumeItem{\textbf{Enterprise AI Platform Development \& Adoption:} Architected and scaled a robust agentic AI framework on enterprise data, combining knowledge graphs, retrieval-augmented generation (RAG), and real-time insights. Ensured seamless integration of AI solutions across diverse business functions, fostering adoption through structured change management and user engagement strategies.}

   \resumeItem{\textbf{Cross-Functional AI Innovation \& Governance:} Collaborated with legal, compliance, and medical affairs teams to establish governance frameworks for responsible AI deployment. Spearheaded AI literacy initiatives, empowering cross-functional teams with AI-driven decision-making capabilities while ensuring adherence to ethical AI standards and regulatory compliance.}

  \resumeItem{\textbf{People & Organizational Leadership in AI Transformation:} Built and led high-performing AI research and engineering teams, fostering a culture of innovation, accountability, and technical excellence. Designed scalable experimentation frameworks, optimized AI model lifecycles, and mentored teams in AI strategy, model interpretability, and impact-driven execution.}
\resumeItemListEnd






\resumeSubHeadingListStart
    \resumeSubheading
      {Sr. Director of Digital Health and Life Science}{Sept, 2021 -- June, 2023 (Affected by company layoff)}
      {Alibaba Cloud} {Bellevue, WA and Hangzhou, China}
      \resumeItemListStart
        \small\resumeItem{AI and Data Solutions for Advanced Marketplaces and Customer Success in Healthcare:Led strategic initiatives in developing large-scale AI-driven data platforms and intelligent models that enhance member engagement, patient outcomes, and marketplace solutions across pharmaceutical and healthcare providers. Designed comprehensive, scalable data foundations with a focus on metrics and predictive targeting dimensions, enabling deep insights for customer segmentation and revenue optimization across product portfolios. Implemented A/B testing frameworks to guide data-informed decisions, increase engagement, and optimize patient and provider alignment.}
        \resumeItem{High-Performance Data Platform Development for Real-Time Population Health:Directed the deployment of a comprehensive data platform for large-scale health data processing and marketplace analytics, supporting real-time data integration and resource optimization for population health management. Developed and managed a robust ETL infrastructure and applied advanced data warehousing techniques for fast, scalable data retrieval, directly enhancing customer support and operational efficiency.}
        \resumeItem{Federated Learning Platform for Liver Cancer Risk Prediction at Roche China: Led the design and implementation of a federated learning platform to securely aggregate data from multiple hospitals, enabling AI-driven insights while ensuring patient data privacy. Developed a liver cancer patient risk prediction model to identify high-risk individuals, optimize clinical trial patient enrollment, and enhance engagement strategies for both patients and healthcare providers. Established a scalable data infrastructure with advanced ETL processes and data quality frameworks, ensuring reliable analytics to support Roche China’s precision medicine and commercial initiatives.}
        \resumeItem{Technical Leadership and a Culture of Innovation:Built and led a high-performing team of data scientists and engineers, fostering a technology-first, innovation-driven culture that prioritizes customer value. Mentored and developed a strong bench of talent across analytics, machine learning, and engineering, aligning with modern data architectures and cross-functional goals. Established thought leadership within the organization, representing the team in industry forums, promoting best practices, and fostering collaborative relationships with executive teams in marketing, sales, and operations.}
        \resumeItemListEnd





    \resumeSubheading
      {Director of AI for Health}{Jan, 2020 -- Sept, 2021}
      {Microsoft}{Redmond,WA}
     \resumeItemListStart
     \small\resumeItem{Strategic Data Science and AI Leadership: Developed and led advanced data science initiatives across healthcare, life sciences, and tech sectors, driving transformative AI and data science solutions that deliver both member and customer value. Built high-impact data platforms, defined strategic data foundations, and applied machine learning to optimize product and service offerings, aligning with go-to-market strategies and maximizing user engagement.}
     \resumeItem{Key projects include:}
        \resumeItemListStart
        \resumeItem{Data Foundations and Strategic Insights for Scalable Impact Spearheaded the creation of scalable data infrastructures and AI-driven insights, leading projects that provided strategic alignment for business growth. Defined clear metrics and targeting frameworks to support marketplace optimization, A/B testing, and predictive analytics across diverse applications, from healthcare diagnostics to digital advertising solutions.}
        \resumeItem{Cross-Functional Collaboration and Leadership in Data Science Led large, diverse teams in delivering high-quality AI-driven solutions by fostering strong collaborations across technical and business functions, including Marketing and Sales. Enabled cross-team alignment by establishing data-informed decision-making practices and prioritizing impactful projects in close partnership with go-to-market teams, resulting in optimized member engagement and customer success.}
        \resumeItem{High-Performance Machine Learning Models and Deep Dive Analytics: Directed the deployment of machine learning models and deep-dive analyses for predictive and descriptive insights, driving measurable improvements in customer success and process optimization. Oversaw implementations ranging from real-time customer analytics and member engagement optimizations to healthcare applications supporting patient outcomes.}
        \resumeItem{Thought Leadership and Industry Advocacy: Acted as an industry thought leader and spokesperson, contributing insights and expertise in advanced analytics, machine learning, and data science best practices. Presented at industry forums, representing and elevating the value of data-driven solutions for strategic decision-making and long-term organizational impact.}
    \resumeItemListEnd

    \resumeItem{\textbf{Seleted Projects}:}
        \resumeItemListStart
        \resumeItem{Azure-Based Data Platform for Advanced Analytics: Designed and deployed an enterprise-grade Azure data platform, empowering users across healthcare and nonprofit sectors to leverage secure, scalable data solutions. Enabled access to advanced analytics and AI-driven business intelligence applications that maximized the power of structured and unstructured data.}
        \resumeItem{Machine Learning for Diagnostics and Predictive Analytics: Built and implemented machine learning models for clinical diagnostics, notably in COVID-19 response initiatives and cancer detection applications, demonstrating data’s role in actionable, high-impact public health insights and risk prediction.}
        \resumeItem{AI-Powered Business Intelligence and Workflow Optimization: Deployed AI solutions that streamlined workflows, enhanced user engagement, and provided actionable insights across industries. Worked with Looker and other BI tools to embed real-time data exploration capabilities, enabling dynamic reporting and empowering leadership with data-driven decision support.}
    \resumeItemListEnd
    \resumeItemListEnd

    \resumeSubheading
      {Sr. Director of Data Science}{Jul, 2016 -- Dec, 2019}
      {Health Care Services Corporation (Blue Cross Blue Shield, TX,IL,MT,OK,NM)}{Chicago, IL}
    \resumeItemListStart
    \small\resumeItem{Provider Quality Analytics  Decision Support}
    \resumeItemListStart
        \resumeItem{Quality Measurement  BI: Developed quality measurement frameworks using claims/EHR data and BI solutions that improved clinical operations and aligned with strategic goals, enhancing member engagement and Medicare ratings.}
        \resumeItem{Population Health Data Integration: Integrated population health data to improve organizational analytics quality and compliance, supporting data-driven decisions in member and provider engagement.}
        \resumeItemListEnd
    \resumeItemListEnd
    
   
    \resumeItemListStart
    \small\resumeItem{Provider and Network Decision Analysis (PANDA)}
        \resumeItemListStart
        \resumeItem{Predictive Models  Provider Insights: Built ML-driven models for risk adjustment, disease segmentation, and provider classification, enhancing decision-making for provider and network teams.}
        \resumeItem{Cross-Functional BI Strategy: Enhanced PANDA’s BI impact with collaborative visualizations that supported provider benchmarking and strategic network decisions.}
        \resumeItemListEnd
    \resumeItemListEnd
    
    \resumeItemListStart
    \resumeItem{Network Visualization and Optimization}
    \resumeItemListStart
        \resumeItem{Network Analysis Tool Development: Created a BI tool for visualizing provider networks, aiding in contracting and optimization decisions, with data visualizations that strengthened provider partnerships.}
        \resumeItemListEnd
    \resumeItemListEnd
        
    \resumeSubheading
      {Statistician III}{Nov, 2014 -- Jul, 2016}
      {NORC at The University of Chicago}{Chicago,IL}
      \resumeItemListStart
        \small\resumeItem{Academy Health and OPTUM(United Health Group) - Rheumatoid Arthritis Data Challenge (2016 Health Datapalooza):I crafted a comprehensive proposal, earning the opportunity to participate in the esteemed 2016 Health Datapalooza Data Challenge. Utilizing an amalgamation of data sources, including Electronic Medical Records (EMR), claims data, and free text provider notes, I developed a predictive model to estimate medication persistence in patients with Rheumatoid Arthritis. This innovative approach resulted in securing the first prize at the final competition. Subsequently, I presented the findings and proposed solutions to a distinguished committee, contributing to a broader understanding of treatment adherence in Rheumatoid Arthritis patients.}
        \resumeItem{Medicare and Medicaid Beneficiary Survey: I conducted a comprehensive assessment of disclosure risk associated with the release of public use data. Utilizing a hybrid data approach, I amalgamated claims data with survey data to generate insightful analytical reports for Medicare Fee-for-Service patients. Further, I managed the entire data delivery pipeline, overseeing multi-round data collections and maintaining rigorous quality control to ensure the accuracy, consistency, and reliability of the data assets.}
        \resumeItem{Multiple System Utilization for Tricare Beneficiaries Project: I managed an extensive longitudinal claims database, encompassing 9.6 million active-duty personnel, military retirees, and dependents. My responsibilities involved the meticulous examination and monitoring of migration behavior and payment patterns among Tricare beneficiaries transitioning between the direct care and purchased care systems. I conducted comparative analyses of the quality of care - measured through care processes and outcomes - between military facilities and civilian providers. For comprehensive payment comparisons, I utilized the sophisticated Medical Episode Group (MEG) tool, developed by Thomson Reuters.}
        \resumeItemListEnd
        
    \resumeSubheading
      {Biostatistician}{Jun, 2011 -- Nov, 2014}
      {National Center for Primary Care}{Atlanta, GA}
      \small\resumeItemListStart
        \resumeItem{Social Network Analysis: Breast Cancer Patient-Provider Network: Conducted social network analysis on the breast cancer patient-provider network to measure social network properties and identify important nodes in the healthcare network. Compared communities with different network properties to explain differences in health outcomes.}
        \resumeItem{Medical Model Simulation and Decision-making Project: Developed a systematic framework for medical decision-making using TreeAge software. Created Markov models, Monte Carlo simulations, and decision tree analyses to evaluate available options and develop strategies that maximize success while minimizing risk. Conducted cost-effectiveness analysis for adherence to long-term controller medications in children with asthma.}
        \resumeItemListEnd
\resumeSubHeadingListEnd



%-----------EDUCATION-----------
% Please list your current institution first and then past schools in reverse chronology. No need for GPA, etc. You do not need to include high school but may do so if there are accomplishments you would like to highlight.
\section{Education}
\resumeSubHeadingListStart

    \resumeSubheading
        {MASSACHUSETTS INSTITUTE OF TECHNOLOGY}{Jun, 2014 -- Jul, 2014}
        {Summer Courses}{Cambridge, MA}
      \resumeSubheading
        {UNIVERSITY OF NORTH TEXAS HEALTH SCIENCE CENTER}{Aug, 2009 -- May, 2011}
        {Master of Public Health with concentration in Biostatistics}{Fort Worth, TX}

      \resumeSubheading
        {ANHUI MEDICAL UNIVERSITY}{Sept, 2002 -- Jul, 2007}
        {MBBS}{Hefei, China}
\resumeSubHeadingListEnd






%-----------AWARDS & HONORS-----------
\section{Awards \& Honors} 
% This section can include academic achievements – things like scholarships, Dean's list, honors societies – as well as recognition in your community - community service, religious study, volunteerism, military service, or anything else. You can remove or add sections as needed.
\resumeSubHeadingListStart
    \resumeSubheading
    {Digital Edge 50 Award in US for Project of Provider Efficiency and Quality Measurement}{}
    {CIO magazine}{2018}
    \resumeSubheading
    {Outstanding Employee Award}{}
    {Health Care Services Corporation }{2016}
    \resumeSubheading
    {First Prize Winner of Health Datapalooza Data Challenge Competition}{}
    {Academy Health \& United Health Group(Optum)}{2016}
\resumeSubHeadingListEnd


%-----------Licensure & Certification-----------
\section{License \& Certification}
% Also an optional section, for any hobbies, sports, artistic and musical pursuits, etc. that you would like to include. You can include as many or as few as you like: delete or add as needed. 
\begin{itemize}[leftmargin=0.15in, label={}]
    \normalsize{\item{
     \textbf{Azure Data Fundamentals \& Azure AI Fundamentals \& Developing AI Application on Azure}{: {Microsoft} } \\
     \textbf{Machine Learning Specialization}{: {Coursera} } \\
     \textbf{Deep Learning Specialization}{: {Coursera} } \\
     \textbf{Certified Base Programmer for SAS®9}{: {(License BP000759v9)} } \\
     \textbf{Certified Advanced Programmer for SAS®9}{: {(License AP000202v9)} } \\
     \textbf{SAS Certified Clinical Trials Programmer Using SAS®9}{: {(License CTP000539v9)} } \\
     \textbf{Certified in Public Health for The National Board of Public Health Examiners }{: {(License 6622)} } \\
    }}    
 \end{itemize}

%-----------RESEARCH PRESENTATIONS-----------
\section{Research Presentations} 
% It is not expected that applicants will have items for this section, but if you have presented or published research findings at, for example, a student research conference, please list those here.
\begin{itemize}[leftmargin=0.15in, label={}]
    \normalsize{\item{
\begin{enumerate}
    \item Xin Hou, Yong He, Pan Fang, Shun Zhang, et al. \textit{Using artificial intelligence to document the hidden RNA virosphere}, Cell, Oct, 2024. \url{https://www.cell.com/cell/fulltext/S0092-8674(24)01085-7}
    \item Yong He, Cheng Wang, Shun Zhang, Nan Li, Zhaorong Li, Zhenyu Zeng. \textit{KG-MTT-BERT: Knowledge Graph Enhanced BERT for Multi-Type Medical Text Classification}, arXiv preprint arXiv:2210.03970.
    \item Yixi Xu, Raquel R Barbieri, Lucy Setian, Shun Zhang, et al. \textit{Reimagining leprosy elimination with AI analysis of a combination of skin lesion images with demographic and clinical data}, The Lancet Regional Health-Americas, 2022/5, (9).
    \item Shun Zhang, George Rust, Kathryn Cardarelli, Jesus Felizzola, Mesfin Fransua, Harold G. Stringer, Jr. \textit{Adherence to highly active antiretroviral therapy impact on clinical and economic outcomes for Medicaid enrollees with HIV and hepatitis C co-infection}, AIDS Care, 2015, 27 (7), 829-835.
    \item Shun Zhang, Shanell L. McGoy, Daniel Dawes, Mesfin Fransua, George Rust, David Satcher. \textit{The Potential for Elimination of Racial-Ethnic Disparities in HIV Treatment Initiation in the Medicaid Population among 14 Southern States}, PLOS One, Apr 25, 2014.
    \item Shun Zhang, Charles Senteio, Jesus Felizzola, Rust George. \textit{Disparities in Antiretroviral treatment among Medicaid HIV-infected pregnant women, 2005-2007}, American Journal of Public Health, December 2013, Vol. 103, No. 12, pp. e46-e53.
    \item Shun Zhang, Kathryn Cardarelli, Ruth Shim, Jiali Ye, Karla L. Booker, Rust George. \textit{Racial disparities in economic and clinical outcomes of pregnancy among Medicaid recipients}, Maternal and Child Health Journal, 2012; 15:45-54.
    \item Dominic Mack, Shun Zhang, Megan Douglas, Charles Sow, Harry Strothers, George Rust. \textit{Disparities in primary care Electronic Health Record (EHR) adoption rates}, Journal of health care for the poor and underserved, 27 (1), 327.
    \item RS Shim, MT Compton, S Zhang, K Roberts, G Rust, BG Druss. \textit{Predictors of Mental Health Treatment Seeking and Engagement in a Community Mental Health Center}, Community Mental Health Journal, 2017, 53 (5), 510-514.
    \item George Rust, Shun Zhang, Zhongyuan Yu, Lee Caplan, Sanjay Jain, Turgay Ayer, Luceta McRoy, Robert Levine. \textit{Counties eliminating racial disparities in colorectal cancer mortality}, Cancer, 2016, March.
    \item Dominic Mack, Shun Zhang, Megan Douglas, Charles Sow, Harry Strothers, George Rust. \textit{Disparities in Primary Care EHR Adoption Rates}, Journal of Health Care for the Poor and Underserved, Volume 27, Number 1, February 2016, pp. 327-338.
    \item Wonsuk Yoo, George Rust, Shun Zhang, James Lillard. \textit{Health disparity characteristics on growth patterns of breast cancer mortality trends among the US Counties, 1989-2010}, Cancer Research, 75 (15 Supplement), 3701-3701.
    \item George Rust, Shun Zhang, Khusdeep Malhotra, Leroy Reese, Luceta McRoy, Peter Baltrus, Lee Caplan, Robert S Levine. \textit{Paths to Health Equity – Local Area Variation in Progress Toward Eliminating Breast Cancer Mortality Disparities, 1990-2009}, Cancer, 2015, August, Volume 121, Issue 16, pp. 2765–2774.
    \item George Rust, Shun Zhang, Luceta McRoy, Maria Pisu. \textit{Potential Savings from Increasing Adherence to Inhaled Corticosteroid Therapy in Medicaid-enrolled Children}, The American Journal of Managed Care, 2015, March 21 (3), pp. 173-180.
    \item Abara, Winston E., Lerissa Smith, Shun Zhang, Amanda J. Fairchild, Harry J. Heiman, and George Rust. \textit{The Influence of Race and Comorbidity on the Timely Initiation of Antiretroviral Therapy Among Older Persons Living With HIV/AIDS}, American Journal of Public Health, 2014: e1-e7.
    \item George Rust, Shun Zhang, Kelvin Holloway, Yasmin Tyler-Hill. \textit{Timing of Emergency Department Visits for Childhood Asthma after Initial Inhaled Corticosteroid Use}, Population Health Management, July 2014.
    \item Khusdeep Malhotra, Peter Baltrus, Shun Zhang, Luceta McRoy, Lilly Cheng Immergluck, George Rust. \textit{Geographic and Racial Variation in Asthma Prevalence and Emergency Department Use among Medicaid-Enrolled Children, in Fourteen Southern States}, Journal of Asthma, June 2014, No. 10, pp. 1-24.
    \item Ruth S. Shim, Benjamin G. Druss, Shun Zhang, Giyeon Kim, Adesoji Oderinde, Sosunmolu Shoyinka, George Rust. \textit{Emergency Department Utilization among Medicaid Beneficiaries with Schizophrenia and Diabetes: The Consequences of Increasing Medical Complexity}, Schizophrenia Research, November 20, 2013.
    \item George Rust, Shun Zhang, Reynolds Joshua. \textit{Inhaled Corticosteroid Adherence and Emergency Department Utilization Among Medicaid-enrolled Children with Asthma}, Journal of Asthma, September 2013, Vol. 50, No. 7, pp. 769-775.
    \item Fang Fang Zhang, Roberto Cardarelli, Joan Carroll, Shun Zhang, Kimberly G. Fulda, Karina Gonzalez, Jamboor K. Vishwanatha, Alfredo Morabia, Regina M. Santella. \textit{Physical activity and global genomic DNA methylation in a cancer-free population}, Epigenetics, 6:3, pp. 293-9, March 2011.
    \item Charles Senteio, Summer Wright Collins, Rachael Jackson, Stacy Welk, Shun Zhang. \textit{Effective Resources Supporting Healthy Sexual Behavior in Formerly Incarcerated Persons}, American Journal of Sexuality Education, 2010, 5: pp. 362–376.
    \item Zhang Shun, Ding Xiaocang, Wang Haimin. \textit{The survey and analysis of impact on the financial crisis on the private medical services industry in Jing'an District, Shanghai}, Chinese Health Services Management, No.7, July 2009, pp. 475-476.
    \item Zhang Shun, Ding Xiaocang, et al. \textit{The dynamic monitoring survey of collected garbage spots in earthquake attacked area, Xuankou Township, Wenchuan County}, Chinese Primary Health Care, Vol.22, No.275, Nov. 2008, pp. 22-23.
    \item Zhang Shun, Zhu Xiaozhen. \textit{The survey on AIDS related knowledge among women who have work in the club of downtown Shanghai}, Chinese Journal of Public Health, Vol.24, Suppl., Aug. 2008, pp. 94-95.
    \item Zhang Shun, Zhu Xiaozhen, et al. \textit{Survey on attitude and behavior of sexual intercourse and knowledge of AIDS prevention among theatre academy students}, Chinese Journal of School Health, Vol. 29, No.7-B, 2008, pp. 15-16.
    \item Zhu Xiaozhen, Zhang Shun, et al. \textit{100 Questions on AIDS}, ISBN 978-7-5072-1333-1.
    \item Wang Liangfeng, Zhang Shun, et al. \textit{Current Status of self-esteem of middle school students and influential factors in the rural area of Anhui Province}, Modern Preventive Medicine, Vol.34, No.1, Jan. 2007, pp. 25-27,35.
    \item Zhang Shun, Wang Liangfeng, et al. \textit{Epidemiological survey on the current situation of social anxiety of left-behind children in primary school}, Modern Preventive Medicine, Vol.34, No.3, Feb. 2007, pp. 441-443.
    \item Zhang Shun, Wang Liangfeng, Sun Yehuan, et al. \textit{Current status and its influential factors of children’s feelings of loneliness in the rural area of Anhui province}, Chinese Journal of Disease Control and Prevention, Vol.11, Jan. 2007, pp. 61-64.
    \item Zhang Shun, Wang Liangfeng, Sun Yehuan, et al. \textit{Life Events and Self-esteem of Middle School Students in Rural Area of Anhui Province}, Chinese Mental Health Journal, Vol.20, No.11, November 2006, pp 730-732.
 \end{itemize}
\end{document}
