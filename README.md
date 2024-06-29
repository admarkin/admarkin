admarkin%-------------------------
% Resume in Latex
% Author : Aditya Kumar, 1410adityakumar@gmail.com
% License : MIT
%MIT License

%Copyright (c) 2023 Aditya Kumar

%Permission is hereby granted, free of charge, to any person obtaining a copy
%of this software and associated documentation files (the "Software"), to deal
%in the Software without restriction, including without limitation the rights
%to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
%copies of the Software, and to permit persons to whom the Software is
%furnished to do so, subject to the following conditions:

%The above copyright notice and this permission notice shall be included in all
%copies or substantial portions of the Software.

%THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
%IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
%FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
%AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
%LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
%OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
%SOFTWARE.
%------------------------

%---- Required Packages and Functions ----

\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\usepackage[russian]{babel}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=0.6cm, top=0.5cm, right=0.6cm, bottom=0.5cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{:\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1},\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{Маркин Александр Дмитриевич} % Your Name
\newcommand{\course}{Физтех-школа прикладной математики и информатики, 

Информатика и Вычислительная техника} % Your Course
\newcommand{\phone}{+79379123005} % Your Phone Number
\newcommand{\emaila}{markin.ad@phystech.edu} %Email 1
\newcommand{\emailb}{your email} %Email 2
\newcommand{\github}{https://github.com/admarkin} %Github
%\newcommand{\website}{https://www.yourwebsite.com} %Website
\newcommand{\linkedin}{your linkedIn link} %linkedin




\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------
\parbox{3cm}{%

\includegraphics[width=2cm]{emblema_mfti.png}

}\parbox{\dimexpr\linewidth-2.8cm\relax}{
\begin{tabularx}{\linewidth}{L r}
  \textbf{\LARGE \name} & \phone\\
  \roll & markin.ad@phystech.edu\\
  {Московский физико-технический институт, Долгопрудный } & \\
  \course  &  \href{https://github.com/admarkin}{GitHub} \\ %$|$ 
  
\end{tabularx}
}

\vspace{-2mm}

%-----------EDUCATION-----------------
\section{\textbf{Образование}}
\setlength{\tabcolsep}{5pt} % Default value: 6pt
% \renewcommand{\arraystretch}{1.1} % Default value: 1
\resumeProject
      {МБОУ гимназия № 44} %Project Name
      {Математика и физика} %Project Name, Location Name
      {2019-2023} %Event Dates
    
      \resumeItemListEnd
     \vspace{-1mm}
\vspace{3mm}

\resumeProject
      {Московский физико-технический институт} %Project Name
      {Физтех-школа прикладной математики и информатики, Информатика и вычислительная техника} %Project Name, Location Name
      {2023-2027} %Event Dates
    
      \resumeItemListEnd
     \vspace{-1mm}
\vspace{1mm}

%-----------PROJECTS-----------------
\section{\textbf{Проекты}}
\resumeSubHeadingListStart
    
    \resumeProject
      {Текстовый редактор} %Project Name
      {ФПМИ, ИВТф, практикум Python} %Project Name, Location Name
      {Октябрь 2023} %Event Dates
      {\href{https://github.com/admarkin/editor_of_text}{\textbf{Github}}} %Website
      \resumeItemListStart
        \item {Проект текстовый редактор представляет собой окно для ввода текста с полосой прокрутки. В меню взаимодействия с файлом можно создать новый документ, открыть документ, сохранить и выйти из текстового редактора. Меню инструментов предоставляет возможность копировать, вырезать и вставлять строки. Кроме того можно осуществить поиск первого вхождения элемента, либо всех введеных пользователем элементов и их замену на другие. Меню шрифт позволяет менять виды шрифта, их размер, цвет шрифта и цвет фона редактора.}
      \resumeItemListEnd
    
     \vspace{-1mm}
     
    \resumeProject
      {Телеграм бот для заметок} %Project Name
      {ФПМИ, ИВТф, практикум Python} %Project Name, Location Name
      {Ноябрь - Декабрь 2023} %Event Dates
      {\href{https://github.com/admarkin/notes_bot}{\textbf{Github}}} %Website
      \resumeItemListStart
        \item  {Телеграмм бот для создания заметок с использованием базы данных (временно приостановлен). Пользователь может зарегестрироваться и сохранять различные заметки, получающие уникальные номера. Функционал предоставляет возможность просматривать все заметки созданные пользователем и при желании их удалять. Также можно воспользоваться поиском в Википедии для нахождения полезной информации.}
      \resumeItemListEnd

    \resumeProject
      {Морской бой} %Project Name
      {ФПМИ, ИВТф, Технологии программирования, C++} %Project Name, Location Name
      {февраль - май 2024} %Event Dates
      {\href{https://gitlab.com/}{\textbf{GitLab}}} %Website
      \resumeItemListStart
        \item {Данный проект является учебным. В нём продемонстрированы навыки создания uml и usecase диаграмм, применения паттернов программирования, разделение внутренней логики работы приложения и frontend, а также примение некоторых инструментов разработки, таких как  Cmake и Docker. Также ожидается что для данного проекта будут написаны тесты.}
      \resumeItemListEnd
         
   
      
\resumeSubHeadingListEnd
\vspace{-7.5mm}

\section{\textbf{Технический навыки}}
 \resumeHeadingSkillStart
  \resumeSubItem{Языки программировнаия} % Category
    {C++, Python}
    
    %\vspace{-0.5mm}

 \resumeSubItem{Полезные практики} {Использование паттернов программирования, Тестирование (unit\&mock в том числе), SOLID}
 \resumeSubItem{Инструменты} % Category
    {GIT, Docker, Bash, CMake, Latex, Markdown} % Skills
    
    %\vspace{-0.5mm}
    
 \resumeSubItem{Операционные системы} % Category
    {Windows, Linux \& MacOS} % Skills
    
    %\vspace{-0.5mm}
    
 
 \resumeHeadingSkillEnd

\vspace{-1.5mm}

\section{\textbf{Изучаемые и пройденные курсы}}
\resumeHeadingSkillStart
 \resumeSubItem{Компьютерные науки} % Category
    {Объектно-ориентированное программирование на C++, Алгоритмы и структуры данных, программирование на Python, Технологии программирования}

\resumeSubItem{Математика} % Category
    {Математический анализ, Линейная алгебра, Аналитическая геометрия, Алгебра логики, комбинаторика и теория графов,
    Основы высшей алгебры и Теория кодирования}
    %\vspace{-0.5mm}

\resumeHeadingSkillEnd

\vspace{-1mm}

\end{document}
admarkin
