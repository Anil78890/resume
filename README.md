# LATEX FORM RESUME
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
  {\LARGE \scshape Anil Parida} \\ \vspace{1pt}
  Bhubaneswar, India \\
  \href{mailto:paridaanil848@gmail.com}{paridaanil848@gmail.com} $|$
  \link{https://www.linkedin.com/in/anil-parida}{linkedin.com/in/anil-parida} $|$
  \link{https://github.com/Anil78890}{github.com/Anil78890}
\end{center}

%-------------------- Summary --------------------
\section*{Summary}
Aspiring software developer and frontend engineer with strong problem-solving skills. Proficient in web technologies like JavaScript, TypeScript, and Node.js, and experienced in Java and Data Structures. Passionate about creating user-friendly interfaces and continuously learning new tools.

%-------------------- Education --------------------
\section*{Education}
\resumeHeading
{B.Tech in Computer Science}{2022 -- Present}
{GITA Autonomous College, Bhubaneswar}{}

\resumeHeading
{Class XII (ICSE)}{2022}
{Percentage: 60\%}{}

\resumeHeading
{Class X (ICSE)}{2020}
{Percentage: 72\%}{}

%-------------------- Technical Skills --------------------
\section*{Technical Skills}
\begin{tabularx}{\textwidth}{X X}
\textbf{Languages:} Java, JavaScript, TypeScript & \textbf{Frontend:} HTML, CSS \\
\textbf{Backend:} Node.js, MongoDB & \textbf{Tools:} Git, GitHub, VS Code \\
\end{tabularx}

%-------------------- Experience --------------------
\section*{Experience}
\resumeSubheading
{Web Development Training -- GDSC}{GITA College, 2024}
\begin{itemize}
  \resumeItem{1-2 month extracurricular by Google Developer Student Club.}
  \resumeItem{Focused on HTML/CSS, GitHub, and project collaboration.}
\end{itemize}

%-------------------- Projects --------------------
\section*{Projects}
\resumeSubheading
{Portfolio Website}{}
\begin{itemize}
  \resumeItem{Built a personal portfolio site showcasing projects and contact info.}
  \resumeItem{Technologies: HTML, CSS, JavaScript}
  \resumeItem{GitHub: \link{https://github.com/Anil78890/portfolio}{github.com/Anil78890/portfolio}}
\end{itemize}

\vspace{2pt}

\resumeSubheading
{Online Book Store Web App}{}
\begin{itemize}
  \resumeItem{Full-stack app to browse and manage book listings.}
  \resumeItem{Technologies: Node.js, Express, MongoDB, HTML/CSS, JavaScript}
\end{itemize}

%-------------------- Certifications --------------------
\section*{Certifications}
\begin{itemize}
  \resumeItem{Build Your Own Generative AI}
  \resumeItem{Web Development by GDSC}
\end{itemize}

%-------------------- Languages Known --------------------
\section*{Languages Known}
\begin{itemize}
  \resumeItem{English – Intermediate}
  \resumeItem{Hindi – Intermediate}
  \resumeItem{Odia – Intermediate}
  \resumeItem{Bengali – Intermediate}
\end{itemize}

%-------------------- Soft Skills --------------------
\section*{Soft Skills}
Fast Learner, Good Communication, Self-Motivated

%-------------------- Hobbies --------------------
\section*{Hobbies}
Reading, Teaching, Exploring New Technologies

\end{document}
