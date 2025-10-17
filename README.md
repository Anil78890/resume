\documentclass[a4paper,9pt]{article}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{tabularx}
\usepackage{xcolor}
\usepackage{fontawesome5}
\usepackage{parskip}

\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Section formatting
\titleformat{\section}{\scshape\small\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{4pt}{4pt}

% List formatting
\setlist[itemize]{noitemsep, topsep=2pt, left=0.15in}

% Custom commands
\newcommand{\resumeItem}[1]{\item\small{#1}}
\newcommand{\resumeSubheading}[2]{\textbf{#1} \hfill \textit{#2}\\}
\newcommand{\resumeHeading}[4]{
  \textbf{#1} \hfill \textit{#2} \\
  \textit{#3} \hfill \textit{#4} \\
}
\newcommand{\link}[2]{\href{#1}{\texttt{#2}}}

\setlength{\tabcolsep}{0in}
\begin{document}

%-------------------- Header --------------------
\begin{center}
  {\LARGE \scshape Anil Parida — Frontend Developer \textbar{} Software Engineer} \\ \vspace{1pt}
  Bhubaneswar, India \\
  \href{mailto:paridaanil848@gmail.com}{paridaanil848@gmail.com} $|$
  \link{https://www.linkedin.com/in/anil-parida}{linkedin.com/in/anil-parida} $|$
  \link{https://github.com/Anil78890}{github.com/Anil78890}
\end{center}

%-------------------- Professional Summary --------------------
\section*{Professional Summary}
\begin{itemize}
  \item Passionate Frontend Developer with experience in building responsive and user-friendly web applications.
  \item Skilled in React.js, JavaScript, TypeScript, REST APIs, and UI/UX principles.
  \item Strong foundation in Java and Data Structures for efficient problem-solving.
\end{itemize}

%-------------------- Education --------------------
\section*{Education}
\resumeHeading
{B.Tech in Computer Science}{2022 -- Present}
{GITA Autonomous College, Bhubaneswar}{}

\resumeHeading
{Class XII (ICSE)}{2022}
{Orient Day School \textbar{} Percentage: 60\%}{}

\resumeHeading
{Class X (ICSE)}{2020}
{Orient Day School \textbar{} Percentage: 72\%}{}


%-------------------- Technical Skills --------------------
\section*{Technical Skills}
\begin{tabularx}{\textwidth}{X X}
\textbf{AI/ML:} Generative AI, Prompt Engineering, LLMs & \textbf{Frontend:} HTML, CSS, React.js \\
\textbf{App Development:} Android Development, 
Cross-Platform Basics & \textbf{Languages:} Java, JavaScript \\
\textbf{Backend:} Node.js, MongoDB & \textbf{Concepts:} REST APIs, CRUD \\
\textbf{Tools:} Git, GitHub, VS Code & \textbf{Others:} Responsive Design, UI/UX \\
\end{tabularx}


%-------------------- Experience --------------------
\section*{Experience}
\resumeSubheading
{Web Development Training — GDSC}{GITA College, 2024}
\begin{itemize}
  \resumeItem{Participated in a 2-month Google Developer Student Club activity focused on real-world frontend dev.}
  \resumeItem{Worked in collaborative projects using GitHub and modern UI design tools.}
  \resumeItem{Applied responsive design principles and REST API integration.}
\end{itemize}

\resumeSubheading
{Freelance Web Developer}{Remote, 2023}
\begin{itemize}
  \resumeItem{Built static websites for local businesses using HTML, CSS, and JavaScript.}
  \resumeItem{Delivered projects with clean, responsive layouts and SEO basics.}
\end{itemize}

%-------------------- Projects --------------------
\section*{Projects}

\resumeSubheading
{Portfolio Website}{}
\begin{itemize}
  \resumeItem{Built a fully responsive portfolio website to showcase skills and projects.}
  \resumeItem{Increased profile visits by 40\% using SEO practices and mobile-first design.}
  \resumeItem{\textbf{Technologies:} HTML, CSS, JavaScript}
  \resumeItem{\textbf{GitHub:} \link{https://github.com/Anil78890/portfolio}{github.com/Anil78890/portfolio}}
\end{itemize}

\vspace{2pt}

\resumeSubheading
{Online Book Store Web App}{}
\begin{itemize}
  \resumeItem{Full-stack web app to browse, search, and manage book listings.}
  \resumeItem{Implemented CRUD operations with user-friendly UI and RESTful backend.}
  \resumeItem{\textbf{Technologies:} Node.js, Express.js, MongoDB, JavaScript}
\end{itemize}

%-------------------- Certifications --------------------
\section*{Certifications}
\begin{itemize}
  \resumeItem{Certificate of Generative AI Mastermind}
  \resumeItem{Build Your Own Generative AI}
  \resumeItem{Certificate of Completion – Data Structures and Algorithms (DSA)}
  \resumeItem{Web Development by GDSC}
\end{itemize}

%-------------------- Languages Known --------------------
\section*{Languages Known}
\begin{itemize}
  \resumeItem{English – Intermediate}
  \resumeItem{Hindi – Intermediate}
  \resumeItem{Bengali – Intermediate}
\end{itemize}

%-------------------- Soft Skills --------------------
\section*{Soft Skills}
Fast Learner, Good Communication, Self-Motivated

%-------------------- Hobbies --------------------
\section*{Hobbies}
Reading, Teaching, Exploring New Technologies

\end{document}
