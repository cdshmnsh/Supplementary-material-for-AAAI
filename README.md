# Supplementary material for Action Localization and Recognition using C3D and Localization Model (Student Abstract)
Table 1: Evaluation of Proposed Action Localization model with SOTA Tech-niques on Thumos14 database
\caption{Evaluation of Proposed Action Localization model with SOTA Techniques on Thumos14 database}
    
    \scalebox{0.8}{
    \begin{tabular}{|c||c|c|c||c|c|}
    \hline
   IoU $\rightarrow$ & 0.1  & 0.2  & 0.3 & 0.4  & 0.5   \\ 
   \hline \hline

    \hline
\multirow Saliency-Pool\cite{karaman2014fast} & 04.6 & 03.4 & 02.1 & 01.4 & 00.9 \\
         FV-DTF\cite{oneata2014lear} & 36.6 & 33.6 & 27.0 & 20.8 & 14.4 \\
         SLM-mgram\cite{richard2016temporal} & 39.7 & 35.7 & 30.0 & 23.2 & 15.2 \\
         S-CNN\cite{shou2016temporal} & 47.7 & 43.5 & 36.3 & 28.7 & 19.0 \\
         PSDF\cite{yuan2016temporal} & 51.4 & 42.6 & 33.6 & 26.1 & 18.8 \\
         R-C3D\cite{xu2017r} & 54.5 & 51.5 & 44.8 & 35.6 & 28.9 \\
         SSN\cite{zhao2017temporal} & \textbf{60.3} & \textbf{56.2} & \textbf{50.6} &\textbf{40.8}  & \textbf{29.1}\\
              
          \hline
          \hline
         
         \multirow HAS\cite{singh2017hide} & 36.4 & 27.8 & 19.5 & 12.7 & 6.8  \\
         UntrimmedNets\cite{wang2017untrimmednets} & 44.4 & 37.7 & 28.2 & 21.1 & 13.7 \\
         STPN (UNTF)\cite{nguyen2018weakly} & 45.3 & 38.8 & 31.1 & 23.5 & 16.2  \\
         STPN (I3DF)\cite{nguyen2018weakly} &  52.0 & 44.7 & 35.5 & 25.8 & 16.9  \\
         
         
         \hline
         Proposed Method & \textbf{55.55} & \textbf{50.95} & \textbf{39.81} & \textbf{30.29} & \textbf{22.54}  \\
          \hline
        
        
    \end{tabular}}

    \label{result}
\end{table}


\begin{table}[ht]
\centering
