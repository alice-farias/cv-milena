\documentclass[a4paper,10pt]{article}
\usepackage[margin=0.5in,nofoot]{geometry}
\usepackage{fontawesome5}
\usepackage{hyperref}
\usepackage{titlesec}
\usepackage{xcolor}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=blue,
    urlcolor=blue,
    citecolor=blue
}

\titleformat{\section}{\large\bfseries}{\thesection}{1em}{}[\titlerule]
\titlespacing*{\section}{0pt}{*1}{*1}

\newcommand{\entry}[4]{
  \noindent\textbf{#1} \hfill #2 \\
  \noindent\textit{#3} \hfill \textit{#4} \\
  \vspace{2pt}
}

\newcommand{\project}[2]{
  \noindent\textbf{#1} \hfill #2 \\
  \vspace{2pt}
}

\begin{document}

\pagenumbering{gobble}

\noindent
\begin{minipage}[t]{0.5\textwidth}
\textbf{\Large MILENA DE BARROS}

\vspace{0.4em}

\noindent \faMapMarker ~ Vila Isabel, Rio de Janeiro ~ \\
\faIdCard ~ Brasileira
\end{minipage}%
\begin{minipage}[t]{0.5\textwidth}
\raggedleft
{\color{blue}} \href{https://example.com}{\faPhone \space (21) 96520-9695} \quad
{\color{blue}} \href{mailto:milenabarros2011@gmail.com}{\faEnvelope \space milenabarros2011@gmail.com}

\vspace{0.2em}

{\color{blue}} \href{https://www.linkedin.com/in/milena-barross/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app}{\faLinkedin \space LinkedIn} \\
\end{minipage}

\vspace{0.5em}

\section*{Competências Profissionais}
\vspace{0.6em}

Estudante de Psicologia com vivência em mediação de conflitos, atendimento psicossocial e elaboração de relatórios. Desenvolve habilidades em comunicação interpessoal, escuta ativa e promoção da diversidade e inclusão em ambientes acadêmicos e sociais. Interesse em aplicar conhecimentos de psicologia organizacional, desenvolvimento humano e justiça restaurativa para contribuir com equipes multidisciplinares. Experiência com Microsoft Office e redes sociais para divulgação e engajamento.



\section*{Experiência Profissional}
\vspace{0.6em}

\entry{Secretaria Municipal da Pessoa com Deficiência (SMPD)}{\faCalendar \space Abril 2025 -- atual }{Estagiária Voluntária}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Apoio a políticas públicas de inclusão e acessibilidade no ambiente urbano e institucional.
\item Condução de atendimentos psicossociais com foco em escuta ativa, mapeamento de necessidades e encaminhamentos.
\item Participação em iniciativas interdisciplinares com foco na promoção da equidade no mercado de trabalho.
\end{itemize}

\entry{UFRJ – Instituto de Psicologia – Disciplina de Psicologia Jurídica}{\faCalendar \space Abril 2025 -- atual }{Monitora Voluntária}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Apoio na organização didática e pedagógica da disciplina de Psicologia Jurídica.
\item Mediação de discussões sobre temas como avaliação psicológica forense, laudos técnicos e atuação em contextos legais.
\item Suporte aos alunos em atividades teóricas e práticas, incluindo análise de casos reais e jurisprudência.
\end{itemize}

\entry{Fórum Regional da Ilha do Governador – Vara de Família}{\faCalendar \space Janeiro 2024 -- Março 2025 }{Estagiária Bolsista}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Realização de entrevistas e elaboração de relatórios sociais e psicossociais para decisões judiciais.
\item Apoio na triagem e organização de processos junto à equipe técnica (Psicologia e Serviço Social).
\item Participação em supervisões semanais sobre ética, violência doméstica, guarda e parentalidade.
\end{itemize}

\entry{Escola Nacional de Saúde Pública (ENSP – Fiocruz)}{\faCalendar \space Janeiro 2024 -- Agosto 2024 }{Estagiária Voluntária}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Condução de atividades lúdico-terapêuticas com crianças com demandas de saúde mental e aprendizagem.
\item Desenvolvimento de estratégias de intervenção psicossocial em grupo.
\item Relato de evolução dos atendimentos para equipe multiprofissional.
\end{itemize}

\entry{UFRJ – Laboratório de Informática Rolf Preuss (LIRP)}{\faCalendar \space Abril 2023 -- Abril 2025}{Monitora Bolsista}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Manutenção e suporte técnico de computadores e rede do Instituto de Psicologia.
\item Gestão de comunicação institucional via site e redes sociais (Instagram), ampliando o alcance de eventos em +60\%.
\item Divulgação de oportunidades acadêmicas e institucionais, com foco em inclusão e diversidade.
\end{itemize}

\entry{Novo DEGASE – NUAF e ASSEGRE}{\faCalendar \space Junho 2023 -- Dezembro 2023 }{Estagiária Voluntária}{\faMapMarker \space Rio de Janeiro, RJ}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Atuação junto ao Núcleo de Acolhimento à Família (NUAF), promovendo apoio emocional e orientação psicossocial.
\item Apoio à reinserção socioeconômica de adolescentes egressos, com foco em empregabilidade e ressocialização.
\item Participação em projetos intersetoriais voltados à justiça restaurativa e prevenção à reincidência.
\end{itemize}

\section*{Formação Acadêmica}
\vspace{0.6em}

\entry{Universidade Federal do Rio de Janeiro (UFRJ)}%
       {\faCalendar \space 2º semestre de 2020 -- atual (previsão: Dez. 2026)}%
       {Bacharelado em Psicologia}%
       {\faMapMarker \space Rio de Janeiro, RJ}



\vspace{-0.6em}





\section*{Projetos Acadêmicos}
\vspace{0.6em}

\project{Desconstruindo Estereótipos | \normalfont{\textit{Extensão Universitária – UFRJ}}}{\textbf{Agosto 2022 -- Junho 2023}}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Criação de conteúdo educativo digital voltado a saúde mental, diversidade de gênero e raça, viés implícito e opressões estruturais.
\item Gestão de mídias sociais (Instagram), promovendo engajamento e conscientização com base em evidências científicas.
\item Estímulo ao pensamento crítico e à desconstrução de estereótipos por meio da psicologia social e comunitária.
\end{itemize}

\project{Atenção Compartilhada e Produção Coletiva de Sentidos no Meio Pedagógico | \normalfont{\textit{Iniciação Científica – UFRJ}}}{\textbf{Agosto 2022 -- Agosto 2023}}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Pesquisa sobre cognição social e aprendizagem com base na abordagem enativa e construtivista da psicologia.
\item Estudo teórico e análise qualitativa das relações afetivas e da construção de sentidos em contextos escolares.
\item Revisão e diálogo com autores nacionais e internacionais para fundamentação epistemológica e crítica.
\end{itemize}

\project{Responsabilidade da Universidade Pública na Qualificação da Assistência em Saúde Mental | \normalfont{\textit{Extensão Universitária – IPUB/UFRJ}}}{\textbf{Abril 2023 -- Fevereiro 2024}}
\vspace{-1.6em}
\begin{itemize}
\setlength\itemsep{-0.3em}
\item Atuação como acompanhante terapêutica de usuários em hospital psiquiátrico vinculado ao IPUB/UFRJ.
\item Integração ao Trabalho Coletivo multiprofissional, com médicos, residentes, especializandos e graduandos.
\item Co-criação e execução de oficinas terapêuticas focadas em autonomia, expressão simbólica e reabilitação psicossocial.
\end{itemize}

\section*{Atividades Complementares}
\vspace{0.4em}

\noindent
\textbf{UFRJ} --- Curso “Clínica Sartriana: da teoria à prática” (Mai 2024 -- Jul 2024) \\
Aprendizado sobre o método clínico sartriano, com enfoque crítico e implicado socialmente. \\

\noindent
\textbf{UNICAMP} --- Curso Livre de Educação em Redução de Danos (Mai 2024 -- Jun 2024) \\
Estudo sobre estratégias de Redução de Danos em diversos contextos. Participação em aulas com referências da área, como Luís Fernando Tófoli e Sandro Rodrigues. \\

\noindent
\textbf{UERJ} --- Curso “Racializando as Artes Visuais” (Set 2022 -- Dez 2022) \\
Aprendizado sobre artes visuais a partir de uma perspectiva crítica, com ênfase nas relações raciais no campo artístico.

\section*{Idiomas}
\vspace{0.4em}

\noindent
\textbf{Inglês} --- Curso Wizard (Intermediário, 2013--2016); Curso Cultura Inglesa (Avançado, 2017--2019) \\
\textbf{Libras} --- CLAC UFRJ (Básico, 2021)

\vspace{1em}





\end{document}
