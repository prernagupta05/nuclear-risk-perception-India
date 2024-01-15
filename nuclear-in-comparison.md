---
title: "nuclear energy in comparison"
output:
  pdf_document:
    toc: yes
    toc_depth: 2
    keep_tex: yes
    keep_md: yes
  header-includes:
  - \usepackage{dcolumn}
  - \usepackage{array}
  - \usepackage{pdflscape}
  - \newcommand{\blandscape}{\begin{landscape}}
  - \newcommand{\elandscape}{\end{landscape}}
  html_document:
    toc: yes
    toc_depth: '2'
    df_print: paged
---

# Abstract



















\newpage

# H1: Nuclear Energy will be seen as riskier than other energy technologies in India.  this paper explores nuclear energy in comparison with other technologies 

## Likert Responses (n= 2160)
The percentages are rounded off to whole numbers. 

![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-5-1.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-5-2.pdf)<!-- --> 

\newpage
## Introduction: Mean Perceived Risk and Mean Perceived Benefit for all energy technologies. 




![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-7-1.pdf)<!-- --> 


## Boxplot for perceived benefit and perceived risk by technology

![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-8-1.pdf)<!-- --> 




\newpage

## Pairwise T-test: Mean perceived risk and mean perceived benefit (all energy technologies)

The red and green pairs indicate that there is a statistically significant difference between the means of the two groups. 
White and grey indicate - no differences between the means of the two groups.

![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-9-1.pdf)<!-- --> 




\newpage 

## Benefit - Risk for each technology 
![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-10-1.pdf)<!-- --> 



\newpage

# Claim 1: Demographic variables: nuclear, solar, coal 






\blandscape

## Linear Regression with demographic variables (caste, religion, gender and age)

\begingroup\small\setlength{\tabcolsep}{1pt}\renewcommand{\arraystretch}{0.7}
% Table created by stargazer v.5.2.3 by Marek Hlavac, Social Policy Institute. E-mail: marek.hlavac at gmail.com
% Date and time: Wed, Jan 10, 2024 - 09:43:59
\begin{table}[!htbp] \centering 
  \caption{Linear Models: Perceived Risk and Net Perceived Benefit(Nuclear, Solar and Coal)} 
  \label{} 
\begin{tabular}{@{\extracolsep{5pt}}lcccccc} 
\\[-1.8ex]\hline 
\hline \\[-1.8ex] 
 & \multicolumn{6}{c}{\textit{Dependent variable:}} \\ 
\cline{2-7} 
\\[-1.8ex] & RiskNuclear & RiskSolar & RiskCoal & NetBenNuclear & NetBenSolar & NetBenCoal \\ 
\\[-1.8ex] & (1) & (2) & (3) & (4) & (5) & (6)\\ 
\hline \\[-1.8ex] 
 Uppercaste & 0.106 & $-$0.065 & 0.051 & $-$0.199$^{**}$ & $-$0.020 & $-$0.096 \\ 
  & (0.066) & (0.059) & (0.060) & (0.093) & (0.094) & (0.075) \\ 
  & & & & & & \\ 
 Male & 0.122$^{*}$ & $-$0.291$^{***}$ & 0.056 & $-$0.046 & 0.456$^{***}$ & $-$0.004 \\ 
  & (0.066) & (0.060) & (0.061) & (0.095) & (0.096) & (0.076) \\ 
  & & & & & & \\ 
 Hindu & $-$0.115 & $-$0.237$^{***}$ & 0.017 & 0.400$^{***}$ & 0.501$^{***}$ & 0.039 \\ 
  & (0.076) & (0.068) & (0.070) & (0.106) & (0.107) & (0.085) \\ 
  & & & & & & \\ 
 UrbanUrban & $-$0.099 & 0.521$^{***}$ & 0.110$^{*}$ & 0.390$^{***}$ & $-$0.711$^{***}$ & $-$0.015 \\ 
  & (0.065) & (0.058) & (0.059) & (0.092) & (0.093) & (0.073) \\ 
  & & & & & & \\ 
 age & 0.050$^{*}$ & $-$0.070$^{***}$ & 0.012 & $-$0.116$^{***}$ & 0.187$^{***}$ & $-$0.038 \\ 
  & (0.029) & (0.026) & (0.026) & (0.044) & (0.045) & (0.036) \\ 
  & & & & & & \\ 
 Constant & 3.309$^{***}$ & 2.325$^{***}$ & 3.005$^{***}$ & $-$0.355$^{**}$ & 0.835$^{***}$ & 0.059 \\ 
  & (0.108) & (0.097) & (0.099) & (0.154) & (0.156) & (0.124) \\ 
  & & & & & & \\ 
\hline \\[-1.8ex] 
Observations & 1,444 & 1,444 & 1,444 & 1,183 & 1,183 & 1,183 \\ 
R$^{2}$ & 0.012 & 0.100 & 0.003 & 0.041 & 0.122 & 0.003 \\ 
Adjusted R$^{2}$ & 0.009 & 0.097 & 0.00003 & 0.037 & 0.118 & $-$0.001 \\ 
Residual Std. Error & 1.176 (df = 1438) & 1.053 (df = 1438) & 1.080 (df = 1438) & 1.517 (df = 1177) & 1.533 (df = 1177) & 1.217 (df = 1177) \\ 
F Statistic & 3.552$^{***}$ (df = 5; 1438) & 31.870$^{***}$ (df = 5; 1438) & 1.010 (df = 5; 1438) & 10.122$^{***}$ (df = 5; 1177) & 32.725$^{***}$ (df = 5; 1177) & 0.705 (df = 5; 1177) \\ 
\hline 
\hline \\[-1.8ex] 
\textit{Note:}  & \multicolumn{6}{r}{$^{*}$p$<$0.1; $^{**}$p$<$0.05; $^{***}$p$<$0.01} \\ 
\end{tabular} 
\end{table} 
\endgroup

\elandscape



```
## 
## Regression Models Summary
## ================================================================================================================================================================
##                                                                                 Dependent variable:                                                             
##                     --------------------------------------------------------------------------------------------------------------------------------------------
##                           RiskNuclear              RiskSolar               RiskCoal            NetBenNuclear             NetBenSolar             NetBenCoal     
##                               (1)                     (2)                    (3)                    (4)                      (5)                    (6)         
## ----------------------------------------------------------------------------------------------------------------------------------------------------------------
## Uppercaste                   0.106                   -0.065                 0.051                 -0.199**                  -0.020                 -0.096       
##                             (0.066)                 (0.059)                (0.060)                (0.093)                  (0.094)                (0.075)       
##                                                                                                                                                                 
## Male                        0.122*                 -0.291***                0.056                  -0.046                  0.456***                -0.004       
##                             (0.066)                 (0.060)                (0.061)                (0.095)                  (0.096)                (0.076)       
##                                                                                                                                                                 
## Hindu                       -0.115                 -0.237***                0.017                 0.400***                 0.501***                0.039        
##                             (0.076)                 (0.068)                (0.070)                (0.106)                  (0.107)                (0.085)       
##                                                                                                                                                                 
## UrbanUrban                  -0.099                  0.521***                0.110*                0.390***                -0.711***                -0.015       
##                             (0.065)                 (0.058)                (0.059)                (0.092)                  (0.093)                (0.073)       
##                                                                                                                                                                 
## age                         0.050*                 -0.070***                0.012                -0.116***                 0.187***                -0.038       
##                             (0.029)                 (0.026)                (0.026)                (0.044)                  (0.045)                (0.036)       
##                                                                                                                                                                 
## Constant                   3.309***                 2.325***               3.005***               -0.355**                 0.835***                0.059        
##                             (0.108)                 (0.097)                (0.099)                (0.154)                  (0.156)                (0.124)       
##                                                                                                                                                                 
## ----------------------------------------------------------------------------------------------------------------------------------------------------------------
## Observations                 1,444                   1,444                  1,444                  1,183                    1,183                  1,183        
## R2                           0.012                   0.100                  0.003                  0.041                    0.122                  0.003        
## Adjusted R2                  0.009                   0.097                 0.00003                 0.037                    0.118                  -0.001       
## Residual Std. Error    1.176 (df = 1438)       1.053 (df = 1438)      1.080 (df = 1438)      1.517 (df = 1177)        1.533 (df = 1177)      1.217 (df = 1177)  
## F Statistic         3.552*** (df = 5; 1438) 31.870*** (df = 5; 1438) 1.010 (df = 5; 1438) 10.122*** (df = 5; 1177) 32.725*** (df = 5; 1177) 0.705 (df = 5; 1177)
## ================================================================================================================================================================
## Note:                                                                                                                                *p<0.1; **p<0.05; ***p<0.01
```


\newpage

# Claim 2: Regional differences 

We see huge differences for perceived risk and perceived benefit for each technology from state to state. These graphs explore that. The number of respondents from each state are also reported below. 

## Perceived risk by State



```
##   Maharashtra     Rajasthan    Tamil Nadu Uttar Pradesh   West Bengal 
##           653           677           320           125           386
```


\includegraphics[width=0.8\linewidth,height=0.8\textheight]{nuclear-in-comparison_files/figure-latex/unnamed-chunk-15-1} 





\newpage

## Perceived Benefit by State


```
##   Maharashtra     Rajasthan    Tamil Nadu Uttar Pradesh   West Bengal 
##           653           677           320           125           386
```


\includegraphics[width=1\linewidth,height=1\textheight]{nuclear-in-comparison_files/figure-latex/unnamed-chunk-16-1} 
## Radar chart - risk and benefit by state




![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-18-1.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-18-2.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-18-3.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-18-4.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-18-5.pdf)<!-- --> 

## Net benefit by state 




![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-20-1.pdf)<!-- --> 











\newpage 
## Mean Perceived Risk and Weighted Mean




\includegraphics[width=1\linewidth,height=1\textheight]{nuclear-in-comparison_files/figure-latex/unnamed-chunk-24-1} 

\newpage
## Mean Perceived risk and weighten means by Technologies- solar, coal and nuclear 












\includegraphics[width=1\linewidth,height=1\textheight]{nuclear-in-comparison_files/figure-latex/unnamed-chunk-28-1} 


## Zscores - 3 techs - solar, nuclear and coal 

![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-29-1.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-29-2.pdf)<!-- --> 




\newpage 

## Mean Perceived Benefit and Z-scores by State 





\includegraphics[width=1\linewidth,height=1\textheight]{nuclear-in-comparison_files/figure-latex/unnamed-chunk-32-1} 

\newpage 

## Mean Perceived Benefit and Z-scores by State - coal solar and nuclear 




![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-33-1.pdf)<!-- --> 



\newpage 








![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-35-1.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-35-2.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-35-3.pdf)<!-- --> ![](nuclear-in-comparison_files/figure-latex/unnamed-chunk-35-4.pdf)<!-- --> 






\blandscape
\newpage

## Linear Regression : Perceived Risk and Net Benefit- demographic variables including State

\begingroup\small\setlength{\tabcolsep}{1pt}\renewcommand{\arraystretch}{0.7}
% Table created by stargazer v.5.2.3 by Marek Hlavac, Social Policy Institute. E-mail: marek.hlavac at gmail.com
% Date and time: Wed, Jan 10, 2024 - 09:44:22
\begin{table}[!htbp] \centering 
  \caption{Linear Models: Perceived Risk and Net Perceived Benefit(Nuclear, Solar and Coal)} 
  \label{} 
\begin{tabular}{@{\extracolsep{5pt}}lcccccc} 
\\[-1.8ex]\hline 
\hline \\[-1.8ex] 
 & \multicolumn{6}{c}{\textit{Dependent variable:}} \\ 
\cline{2-7} 
\\[-1.8ex] & RiskNuclear & RiskSolar & RiskCoal & NetBenNuclear & NetBenSolar & NetBenCoal \\ 
\\[-1.8ex] & (1) & (2) & (3) & (4) & (5) & (6)\\ 
\hline \\[-1.8ex] 
 Uppercaste & $-$0.135$^{**}$ & $-$0.006 & $-$0.056 & 0.026 & $-$0.146$^{*}$ & $-$0.021 \\ 
  & (0.061) & (0.051) & (0.058) & (0.089) & (0.084) & (0.075) \\ 
  & & & & & & \\ 
 Male & 0.045 & $-$0.047 & 0.015 & 0.008 & 0.058 & $-$0.016 \\ 
  & (0.062) & (0.053) & (0.059) & (0.092) & (0.087) & (0.078) \\ 
  & & & & & & \\ 
 Hindu & $-$0.047 & $-$0.057 & 0.099 & 0.362$^{***}$ & 0.290$^{***}$ & $-$0.008 \\ 
  & (0.070) & (0.059) & (0.066) & (0.100) & (0.095) & (0.085) \\ 
  & & & & & & \\ 
 UrbanUrban & 0.052 & $-$0.076 & 0.055 & 0.172$^{*}$ & 0.143 & 0.014 \\ 
  & (0.067) & (0.056) & (0.063) & (0.099) & (0.093) & (0.084) \\ 
  & & & & & & \\ 
 age & $-$0.015 & 0.045$^{**}$ & 0.053$^{**}$ & $-$0.008 & 0.045 & $-$0.035 \\ 
  & (0.027) & (0.023) & (0.025) & (0.043) & (0.040) & (0.036) \\ 
  & & & & & & \\ 
 StateRajasthan & 0.222$^{**}$ & $-$1.285$^{***}$ & 0.234$^{***}$ & $-$0.014 & 1.957$^{***}$ & 0.077 \\ 
  & (0.094) & (0.080) & (0.090) & (0.135) & (0.128) & (0.115) \\ 
  & & & & & & \\ 
 StateTamil Nadu & $-$0.242$^{**}$ & $-$1.547$^{***}$ & $-$1.103$^{***}$ & $-$0.625$^{***}$ & 2.027$^{***}$ & 0.795$^{***}$ \\ 
  & (0.099) & (0.084) & (0.094) & (0.191) & (0.181) & (0.162) \\ 
  & & & & & & \\ 
 StateUttar Pradesh & $-$0.178 & $-$1.344$^{***}$ & $-$0.638$^{***}$ & $-$0.250 & 1.612$^{***}$ & 0.296$^{**}$ \\ 
  & (0.120) & (0.102) & (0.114) & (0.177) & (0.168) & (0.151) \\ 
  & & & & & & \\ 
 StateWest Bengal & 1.276$^{***}$ & $-$1.330$^{***}$ & 0.071 & $-$1.522$^{***}$ & 1.853$^{***}$ & $-$0.222$^{**}$ \\ 
  & (0.083) & (0.071) & (0.079) & (0.125) & (0.118) & (0.106) \\ 
  & & & & & & \\ 
 Constant & 3.208$^{***}$ & 2.752$^{***}$ & 3.053$^{***}$ & $-$0.240 & 0.323$^{**}$ & 0.022 \\ 
  & (0.100) & (0.084) & (0.095) & (0.147) & (0.139) & (0.124) \\ 
  & & & & & & \\ 
\hline \\[-1.8ex] 
Observations & 1,444 & 1,444 & 1,444 & 1,183 & 1,183 & 1,183 \\ 
R$^{2}$ & 0.204 & 0.353 & 0.141 & 0.171 & 0.338 & 0.035 \\ 
Adjusted R$^{2}$ & 0.199 & 0.349 & 0.136 & 0.165 & 0.333 & 0.028 \\ 
Residual Std. Error & 1.057 (df = 1434) & 0.894 (df = 1434) & 1.004 (df = 1434) & 1.413 (df = 1173) & 1.334 (df = 1173) & 1.199 (df = 1173) \\ 
F Statistic & 40.720$^{***}$ (df = 9; 1434) & 86.983$^{***}$ (df = 9; 1434) & 26.208$^{***}$ (df = 9; 1434) & 26.873$^{***}$ (df = 9; 1173) & 66.499$^{***}$ (df = 9; 1173) & 4.789$^{***}$ (df = 9; 1173) \\ 
\hline 
\hline \\[-1.8ex] 
\textit{Note:}  & \multicolumn{6}{r}{$^{*}$p$<$0.1; $^{**}$p$<$0.05; $^{***}$p$<$0.01} \\ 
\end{tabular} 
\end{table} 
\endgroup


<table style="text-align:center"><caption><strong>Linear Models: Perceived Risk and Net Perceived Benefit (Nuclear, Solar and Coal)</strong></caption>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="6"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="6" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td>RiskNuclear</td><td>RiskSolar</td><td>RiskCoal</td><td>NetBenNuclear</td><td>NetBenSolar</td><td>NetBenCoal</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td></tr>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Uppercaste</td><td>-0.135<sup>**</sup></td><td>-0.006</td><td>-0.056</td><td>0.026</td><td>-0.146<sup>*</sup></td><td>-0.021</td></tr>
<tr><td style="text-align:left"></td><td>(0.061)</td><td>(0.051)</td><td>(0.058)</td><td>(0.089)</td><td>(0.084)</td><td>(0.075)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Male</td><td>0.045</td><td>-0.047</td><td>0.015</td><td>0.008</td><td>0.058</td><td>-0.016</td></tr>
<tr><td style="text-align:left"></td><td>(0.062)</td><td>(0.053)</td><td>(0.059)</td><td>(0.092)</td><td>(0.087)</td><td>(0.078)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Hindu</td><td>-0.047</td><td>-0.057</td><td>0.099</td><td>0.362<sup>***</sup></td><td>0.290<sup>***</sup></td><td>-0.008</td></tr>
<tr><td style="text-align:left"></td><td>(0.070)</td><td>(0.059)</td><td>(0.066)</td><td>(0.100)</td><td>(0.095)</td><td>(0.085)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">UrbanUrban</td><td>0.052</td><td>-0.076</td><td>0.055</td><td>0.172<sup>*</sup></td><td>0.143</td><td>0.014</td></tr>
<tr><td style="text-align:left"></td><td>(0.067)</td><td>(0.056)</td><td>(0.063)</td><td>(0.099)</td><td>(0.093)</td><td>(0.084)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">age</td><td>-0.015</td><td>0.045<sup>**</sup></td><td>0.053<sup>**</sup></td><td>-0.008</td><td>0.045</td><td>-0.035</td></tr>
<tr><td style="text-align:left"></td><td>(0.027)</td><td>(0.023)</td><td>(0.025)</td><td>(0.043)</td><td>(0.040)</td><td>(0.036)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">StateRajasthan</td><td>0.222<sup>**</sup></td><td>-1.285<sup>***</sup></td><td>0.234<sup>***</sup></td><td>-0.014</td><td>1.957<sup>***</sup></td><td>0.077</td></tr>
<tr><td style="text-align:left"></td><td>(0.094)</td><td>(0.080)</td><td>(0.090)</td><td>(0.135)</td><td>(0.128)</td><td>(0.115)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">StateTamil Nadu</td><td>-0.242<sup>**</sup></td><td>-1.547<sup>***</sup></td><td>-1.103<sup>***</sup></td><td>-0.625<sup>***</sup></td><td>2.027<sup>***</sup></td><td>0.795<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.099)</td><td>(0.084)</td><td>(0.094)</td><td>(0.191)</td><td>(0.181)</td><td>(0.162)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">StateUttar Pradesh</td><td>-0.178</td><td>-1.344<sup>***</sup></td><td>-0.638<sup>***</sup></td><td>-0.250</td><td>1.612<sup>***</sup></td><td>0.296<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.120)</td><td>(0.102)</td><td>(0.114)</td><td>(0.177)</td><td>(0.168)</td><td>(0.151)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">StateWest Bengal</td><td>1.276<sup>***</sup></td><td>-1.330<sup>***</sup></td><td>0.071</td><td>-1.522<sup>***</sup></td><td>1.853<sup>***</sup></td><td>-0.222<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.083)</td><td>(0.071)</td><td>(0.079)</td><td>(0.125)</td><td>(0.118)</td><td>(0.106)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>3.208<sup>***</sup></td><td>2.752<sup>***</sup></td><td>3.053<sup>***</sup></td><td>-0.240</td><td>0.323<sup>**</sup></td><td>0.022</td></tr>
<tr><td style="text-align:left"></td><td>(0.100)</td><td>(0.084)</td><td>(0.095)</td><td>(0.147)</td><td>(0.139)</td><td>(0.124)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>1,444</td><td>1,444</td><td>1,444</td><td>1,183</td><td>1,183</td><td>1,183</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.204</td><td>0.353</td><td>0.141</td><td>0.171</td><td>0.338</td><td>0.035</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.199</td><td>0.349</td><td>0.136</td><td>0.165</td><td>0.333</td><td>0.028</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>1.057 (df = 1434)</td><td>0.894 (df = 1434)</td><td>1.004 (df = 1434)</td><td>1.413 (df = 1173)</td><td>1.334 (df = 1173)</td><td>1.199 (df = 1173)</td></tr>
<tr><td style="text-align:left">F Statistic</td><td>40.720<sup>***</sup> (df = 9; 1434)</td><td>86.983<sup>***</sup> (df = 9; 1434)</td><td>26.208<sup>***</sup> (df = 9; 1434)</td><td>26.873<sup>***</sup> (df = 9; 1173)</td><td>66.499<sup>***</sup> (df = 9; 1173)</td><td>4.789<sup>***</sup> (df = 9; 1173)</td></tr>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td colspan="6" style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>

\elandscape

\newpage

# Claim 3: Cultural, Political and Economic Values 







## CFA on eco-pol scale for Solar Energy













\begin{landscape}\begin{table}[!h]

\caption{\label{tab:unnamed-chunk-43}Confirmatory Factor Analysis(CFA) on newly developed eco-pol scale}
\centering
\resizebox{\linewidth}{!}{
\begin{tabular}[t]{l>{\raggedright\arraybackslash}p{4cm}rrrrrrrr}
\toprule
Scale & Items & Loadings & Standard Error & zvalue & pvalue & ci.lower & ci.upper & std.lv & std.all\\
\midrule
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Solar energy poses a great risk to the health of people living around it.} & \cellcolor{gray!6}{0.965} & \cellcolor{gray!6}{0.050} & \cellcolor{gray!6}{19.455} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{0.8678100} & \cellcolor{gray!6}{1.0622499} & \cellcolor{gray!6}{0.9650299} & \cellcolor{gray!6}{0.7747043}\\
People Centered Development & Solar energy spoils the natural beauty of the landscape. & 0.820 & 0.052 & 15.714 & 0e+00 & 0.7177752 & 0.9223481 & 0.8200617 & 0.6560430\\
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Solar energy is leading to displacement of people from their land.} & \cellcolor{gray!6}{0.692} & \cellcolor{gray!6}{0.050} & \cellcolor{gray!6}{13.800} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{0.5939852} & \cellcolor{gray!6}{0.7906393} & \cellcolor{gray!6}{0.6923123} & \cellcolor{gray!6}{0.5906886}\\
People Centered Development & Solar energy increases pollution of air/water/land. & 1.096 & 0.050 & 21.706 & 0e+00 & 0.9970923 & 1.1950355 & 1.0960639 & 0.8411179\\
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Large corporations are destroying the local industries in India and benefiting only a handful of people.} & \cellcolor{gray!6}{0.287} & \cellcolor{gray!6}{0.058} & \cellcolor{gray!6}{4.972} & \cellcolor{gray!6}{7e-07} & \cellcolor{gray!6}{0.1741052} & \cellcolor{gray!6}{0.4007040} & \cellcolor{gray!6}{0.2874046} & \cellcolor{gray!6}{0.2317296}\\
\addlinespace
People Centered Development & Regardless of ownership, the government should pass strong regulations and implement them. & 0.296 & 0.052 & 5.733 & 0e+00 & 0.1949541 & 0.3974941 & 0.2962241 & 0.2659785\\
\cellcolor{gray!6}{Nationalist Development} & \cellcolor{gray!6}{MECHANISATION} & \cellcolor{gray!6}{-0.445} & \cellcolor{gray!6}{0.052} & \cellcolor{gray!6}{-8.501} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{-0.5481301} & \cellcolor{gray!6}{-0.3427323} & \cellcolor{gray!6}{-0.4454312} & \cellcolor{gray!6}{-0.3859243}\\
Nationalist Development & Solar energy pushes forward the country's development. & 1.042 & 0.046 & 22.549 & 0e+00 & 0.9518805 & 1.1331082 & 1.0424943 & 0.8341064\\
\cellcolor{gray!6}{Nationalist Development} & \cellcolor{gray!6}{I would be proud if my community used solar energy} & \cellcolor{gray!6}{1.042} & \cellcolor{gray!6}{0.047} & \cellcolor{gray!6}{21.934} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{0.9485906} & \cellcolor{gray!6}{1.1347564} & \cellcolor{gray!6}{1.0416735} & \cellcolor{gray!6}{0.8187225}\\
Nationalist Development & Solar energy is a mark of pride for our nation. & 0.959 & 0.047 & 20.244 & 0e+00 & 0.8658229 & 1.0514501 & 0.9586365 & 0.7748161\\
\addlinespace
\cellcolor{gray!6}{Nationalist Development} & \cellcolor{gray!6}{Solar energy brings economic prosperity to the surrounding regions.} & \cellcolor{gray!6}{0.980} & \cellcolor{gray!6}{0.047} & \cellcolor{gray!6}{20.803} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{0.8876975} & \cellcolor{gray!6}{1.0723692} & \cellcolor{gray!6}{0.9800333} & \cellcolor{gray!6}{0.7896156}\\
NA & Solar energy will bring jobs to the local community. & 0.641 & 0.051 & 12.542 & 0e+00 & 0.5406190 & 0.7408777 & 0.6407483 & 0.5339818\\
\cellcolor{gray!6}{NA} & \cellcolor{gray!6}{Solar energy poses a great risk to the health of people living around it.} & \cellcolor{gray!6}{0.620} & \cellcolor{gray!6}{0.054} & \cellcolor{gray!6}{11.424} & \cellcolor{gray!6}{0e+00} & \cellcolor{gray!6}{0.5139817} & \cellcolor{gray!6}{0.7268665} & \cellcolor{gray!6}{0.6204241} & \cellcolor{gray!6}{0.3998333}\\
\bottomrule
\end{tabular}}
\end{table}
\end{landscape}



\newpage
## CFA on eco-pol scale for Coal










\begin{landscape}\begin{table}[!h]

\caption{\label{tab:unnamed-chunk-47}Confirmatory Factor Analysis(CFA) on newly developed eco-pol scale}
\centering
\resizebox{\linewidth}{!}{
\begin{tabular}[t]{l>{\raggedright\arraybackslash}p{4cm}rrrrrrrr}
\toprule
Scale & Items & Loadings & Standard Error & zvalue & pvalue & ci.lower & ci.upper & std.lv & std.all\\
\midrule
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Coal powered plants poses a great risk to the health of people living around it.} & \cellcolor{gray!6}{0.713} & \cellcolor{gray!6}{0.051} & \cellcolor{gray!6}{14.083} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.6140727} & \cellcolor{gray!6}{0.8126265} & \cellcolor{gray!6}{0.7133496} & \cellcolor{gray!6}{0.6482214}\\
People Centered Development & Coal powered plants spoils the natural beauty of the landscape. & 0.714 & 0.048 & 14.818 & 0.0e+00 & 0.6198092 & 0.8087672 & 0.7142882 & 0.6750268\\
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Coal powered plants is leading to displacement of people from their land.} & \cellcolor{gray!6}{0.628} & \cellcolor{gray!6}{0.055} & \cellcolor{gray!6}{11.376} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.5195755} & \cellcolor{gray!6}{0.7358706} & \cellcolor{gray!6}{0.6277231} & \cellcolor{gray!6}{0.5432527}\\
People Centered Development & Coal powered plants increases pollution of air/water/land. & 0.640 & 0.041 & 15.561 & 0.0e+00 & 0.5590262 & 0.7201432 & 0.6395847 & 0.7014985\\
\cellcolor{gray!6}{People Centered Development} & \cellcolor{gray!6}{Large corporations are destroying the local industries in India and benefiting only a handful of people.} & \cellcolor{gray!6}{-0.634} & \cellcolor{gray!6}{0.057} & \cellcolor{gray!6}{-11.174} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{-0.7449013} & \cellcolor{gray!6}{-0.5225822} & \cellcolor{gray!6}{-0.6337417} & \cellcolor{gray!6}{-0.5349921}\\
\addlinespace
People Centered Development & Regardless of ownership, the government should pass strong regulations and implement them. & -0.509 & 0.054 & -9.351 & 0.0e+00 & -0.6162708 & -0.4027047 & -0.5094877 & -0.4577641\\
\cellcolor{gray!6}{Nationalist Development} & \cellcolor{gray!6}{MECHANISATION} & \cellcolor{gray!6}{0.656} & \cellcolor{gray!6}{0.056} & \cellcolor{gray!6}{11.682} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.5460463} & \cellcolor{gray!6}{0.7662170} & \cellcolor{gray!6}{0.6561317} & \cellcolor{gray!6}{0.5556245}\\
Nationalist Development & Coal powered plants pushes forward the country's development. & 0.626 & 0.055 & 11.326 & 0.0e+00 & 0.5177592 & 0.7344596 & 0.6261094 & 0.6242574\\
\cellcolor{gray!6}{Nationalist Development} & \cellcolor{gray!6}{Coal powered plants brings economic prosperity to the surrounding regions.} & \cellcolor{gray!6}{0.547} & \cellcolor{gray!6}{0.054} & \cellcolor{gray!6}{10.086} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.4408772} & \cellcolor{gray!6}{0.6535573} & \cellcolor{gray!6}{0.5472172} & \cellcolor{gray!6}{0.5535687}\\
NA & Coal powered plants will bring jobs to the local community. & 0.472 & 0.054 & 8.776 & 0.0e+00 & 0.3667103 & 0.5776005 & 0.4721554 & 0.4834144\\
\addlinespace
\cellcolor{gray!6}{NA} & \cellcolor{gray!6}{PRIDECOAL} & \cellcolor{gray!6}{0.338} & \cellcolor{gray!6}{0.062} & \cellcolor{gray!6}{5.485} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.2173242} & \cellcolor{gray!6}{0.4590249} & \cellcolor{gray!6}{0.3381745} & \cellcolor{gray!6}{0.3081207}\\
NA & NPRIDECOAL & 0.284 & 0.061 & 4.667 & 3.1e-06 & 0.1645514 & 0.4027991 & 0.2836753 & 0.2634176\\
\cellcolor{gray!6}{NA} & \cellcolor{gray!6}{Coal powered plants poses a great risk to the health of people living around it.} & \cellcolor{gray!6}{0.702} & \cellcolor{gray!6}{0.056} & \cellcolor{gray!6}{12.572} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.5927046} & \cellcolor{gray!6}{0.8116380} & \cellcolor{gray!6}{0.7021713} & \cellcolor{gray!6}{0.5798090}\\
NA & Coal powered plants spoils the natural beauty of the landscape. & 0.610 & 0.050 & 12.173 & 0.0e+00 & 0.5113671 & 0.7076348 & 0.6095009 & 0.5443389\\
\cellcolor{gray!6}{NA} & \cellcolor{gray!6}{Coal powered plants is leading to displacement of people from their land.} & \cellcolor{gray!6}{0.941} & \cellcolor{gray!6}{0.069} & \cellcolor{gray!6}{13.656} & \cellcolor{gray!6}{0.0e+00} & \cellcolor{gray!6}{0.8060444} & \cellcolor{gray!6}{1.0761975} & \cellcolor{gray!6}{0.9411209} & \cellcolor{gray!6}{0.7048765}\\
\bottomrule
\end{tabular}}
\end{table}
\end{landscape}





