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
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Shreyas Motupalli} \\ \vspace{1pt}
    \small (610)-412-6299 $|$ \href{mailto:motupalli.s@northeastern.edu}{\underline{motupalli.s@northeastern.edu}} $|$ 
    \href{mailto:smotupalli0307@gmail.com}{\underline{smotupalli0307@gmail.com}} $|$ 
    {West Chester, PA}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {The Hill School}{Pottstown, PA}
      {High School Diploma}{August 2021 -- June 2025}

   
      {Cumulative GPA (Weighted): 4.3}{}
    \resumeSubheading
      {Northeastern University}{Boston, MA}
      {Bachelor of Science in Computer Science}{August 2025 -- May 2029}

   
      {\textit{Expected Minor: Game Design}}{}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Engineering Volunteer Counselor}{March 2022 -- June 2025}
      {Ricketts Center}{Pottstown, PA}
      \resumeItemListStart
        \resumeItem{Lead board game activities for children as part of local outreach program}
        \resumeItem{Developed problem-solving, critical thinking, and teamwork skills by working with kids through engaging, and fun learning experiences}
 
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
%    \resumeSubSubheading
%     {Software Engineer I}{Oct 2014 - Sep 2016}
%     \resumeItemListStart
%        \resumeItem{Apache Beam}
%          {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
%     \resumeItemListEnd
%    \resumeSubHeadingListEnd
%-------------------------------------------


  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Computer Assembly}}{July 2021 -- September 2021}
          \resumeItemListStart
            \resumeItem{Researched components and many peripherals to build a custom desktop computer}
            \resumeItem{Gained hands-on experience working with PC hardware}
            \resumeItem{Expanded knowledge of computer component compatibility and functionality}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Keyboard Assembly}}{October 2024}
          \resumeItemListStart
            \resumeItem{Designed and put together a custom silent mechanical 75\% keyboard}
            \resumeItem{Acquired real-world experience handling keyboard components}
            \resumeItem{Enhanced understanding of keyboard architecture, sound-dampening techniques, and switch types}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Console Set-Up}}{November 2017 -- Present}
          \resumeItemListStart
            \resumeItem{Set up and used many consoles, including the Nintendo, multiple generations of PlayStation, and Xbox models}
            \resumeItem{Familiarized with the software and hardware of multiple main brand consoles}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Arcade Hardware Experience}}{May 2025 -- Present}
          \resumeItemListStart
            \resumeItem{Gained experience configuring arcade sticks and arcade machines}
            \resumeItem{Learned to reassemble arcade stick hardware, including buttons and gates}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Technology Student Association(TSA)}}{September 2024 -- April 2025}
          \resumeItemListStart
            \resumeItem{Reached state-level in the TSA Video Game Design competition as part of a team as a programmer, mainly focused on developing the game's unique card system}
            \resumeItem {A playable yet poor state version of the game found here: \href{https://ay28.itch.io/clipd}{\underline{https://ay28.itch.io/clipd}}}
            \resumeItem{Assisted The Hill School TSA board game team in the construction of their entry}
            \resumeItem{Developed priceless collaboration, communication, and marketing skills while working with teams on large-scale team projects}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Independent Game Development}}{May 2024 -- Present}
          \resumeItemListStart
            \resumeItem{Programmed a Snake game in Python, enhancing knowledge of the language and its libraries for use in game development}
            \resumeItem{Created a small parkour prototype, strengthening understanding of 3D development in Godot}
          \resumeItemListEnd
    \resumeSubHeadingListEnd



%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, Python, JavaScript, HTML/CSS, GDScript} \\
     \textbf{Frameworks}{: React} \\
     \textbf{Developer Tools}{: Godot, VS Code, Visual Studio} \\
     \textbf{Libraries}{: Pandas, NumPy, Matplotlib, sklearn, TensorFlow, pyngrok}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}
