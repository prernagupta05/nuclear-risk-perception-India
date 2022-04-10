---
pdf_document:
  toc: yes
  number_sections: yes
  toc_depth: 2
  fig_width: 9
  fig_height: 6
  fig_caption: yes
output:
  html_document:
    fig_width: 9
    fig_height: 6
    fig_caption: yes
    keep_md: yes
    theme: paper
    df_print: paged
  pdf_document: default
title: "Dependent Variable Graphs"
---





















## Q1. Below is a list of various centrally managed sources of energy. How risky are each of these energy technologies according to you?  Please tell me whether you see each technology as: not at all risky(1), slightly risky(2), moderately risky(3), very risky(4), or extremely risky(5)

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":["technology"],"name":[1],"type":["chr"],"align":["left"]},{"label":["perceivedrisk.mean"],"name":[2],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.median"],"name":[3],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.n"],"name":[4],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.sd"],"name":[5],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.var"],"name":[6],"type":["dbl"],"align":["right"]}],"data":[{"1":"Solar","2":"1.766405","3":"1","4":"2161","5":"1.050320","6":"1.103173"},{"1":"Wind","2":"2.124489","3":"2","4":"2161","5":"1.122467","6":"1.259932"},{"1":"Hydro","2":"2.267981","3":"2","4":"2161","5":"1.216492","6":"1.479854"},{"1":"Oil","2":"2.847921","3":"3","4":"2161","5":"1.196538","6":"1.431703"},{"1":"Coal","2":"3.076267","3":"3","4":"2161","5":"1.088431","6":"1.184682"},{"1":"Gas","2":"3.193782","3":"3","4":"2161","5":"1.145126","6":"1.311314"},{"1":"Nuclear","2":"3.397428","3":"4","4":"2161","5":"1.188856","6":"1.413378"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div>




![](DVgraphs_files/figure-html/unnamed-chunk-7-1.png)<!-- -->



## Q2. Following is a list of various individually or community-owned and managed sources of energy. How risky are each of these energy technologies according to you? Please tell me whether you see each technology as: not at all risky(1), slightly risky(2), moderately risky(3), very risky(4), or extremely risky(5). 

prefix IND stands for individually or community-owned and managed. 

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":["technology"],"name":[1],"type":["chr"],"align":["left"]},{"label":["perceivedrisk.mean"],"name":[2],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.median"],"name":[3],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.n"],"name":[4],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.sd"],"name":[5],"type":["dbl"],"align":["right"]},{"label":["perceivedrisk.var"],"name":[6],"type":["dbl"],"align":["right"]}],"data":[{"1":"INDSolar","2":"1.819959","3":"1","4":"2161","5":"1.081112","6":"1.168804"},{"1":"INDFirewoodetc","2":"2.094537","3":"2","4":"2161","5":"1.098778","6":"1.207313"},{"1":"INDWind","2":"2.258124","3":"2","4":"2161","5":"1.148039","6":"1.317994"},{"1":"INDHydro","2":"2.276632","3":"2","4":"2161","5":"1.088462","6":"1.184749"},{"1":"INDDiesel","2":"2.366071","3":"2","4":"2161","5":"1.213819","6":"1.473357"},{"1":"INDKerosene","2":"2.478199","3":"2","4":"2161","5":"1.192774","6":"1.422711"},{"1":"INDBiogas","2":"2.741223","3":"3","4":"2161","5":"1.133757","6":"1.285405"},{"1":"INDLPG","2":"3.278972","3":"3","4":"2161","5":"1.147889","6":"1.317650"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div>

![](DVgraphs_files/figure-html/unnamed-chunk-9-1.png)<!-- -->


## Q3. Following is a list of centrally managed sources of energy. How beneficial are each of these according to you? Please tell me whether you see each technology as: not at all beneficial(1), slightly beneficial(2), moderately beneficial(3), very beneficial(4), or extremely beneficial(5)?

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":["technology"],"name":[1],"type":["chr"],"align":["left"]},{"label":["perceivedbenefit.mean"],"name":[2],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.median"],"name":[3],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.n"],"name":[4],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.sd"],"name":[5],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.var"],"name":[6],"type":["dbl"],"align":["right"]}],"data":[{"1":"Oil","2":"3.271498","3":"3","4":"2161","5":"1.0339758","6":"1.0691060"},{"1":"Nuclear","2":"3.317229","3":"3","4":"2161","5":"1.1729106","6":"1.3757193"},{"1":"Coal","2":"3.331386","3":"3","4":"2161","5":"1.0475454","6":"1.0973513"},{"1":"Gas","2":"3.433804","3":"3","4":"2161","5":"1.0179993","6":"1.0363226"},{"1":"Hydro","2":"3.520575","3":"4","4":"2161","5":"1.0209599","6":"1.0423592"},{"1":"Wind","2":"3.580811","3":"4","4":"2161","5":"0.9677877","6":"0.9366131"},{"1":"Solar","2":"3.832779","3":"4","4":"2161","5":"0.9049763","6":"0.8189821"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div>


![](DVgraphs_files/figure-html/unnamed-chunk-11-1.png)<!-- -->


## Q4. Following is a list of various individually or community owned and managed sources of energy. How beneficial are each of these according to you? Please tell me whether you see each technology as: not at all beneficial(1), slightly beneficial(2), moderately beneficial(3), very beneficial(4) or extremely beneficial(5) ?

prefix IND stands for individually or community-owned and managed. 

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":["technology"],"name":[1],"type":["chr"],"align":["left"]},{"label":["perceivedbenefit.mean"],"name":[2],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.median"],"name":[3],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.n"],"name":[4],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.sd"],"name":[5],"type":["dbl"],"align":["right"]},{"label":["perceivedbenefit.var"],"name":[6],"type":["dbl"],"align":["right"]}],"data":[{"1":"INDKerosene","2":"3.180961","3":"3","4":"2161","5":"1.0341894","6":"1.0695478"},{"1":"INDFirewoodetc","2":"3.195673","3":"3","4":"2161","5":"1.1401961","6":"1.3000471"},{"1":"INDHydro","2":"3.286170","3":"4","4":"2161","5":"0.9981463","6":"0.9962961"},{"1":"INDDiesel","2":"3.286670","3":"3","4":"2161","5":"0.9899923","6":"0.9800848"},{"1":"INDWind","2":"3.362756","3":"4","4":"2161","5":"0.9607465","6":"0.9230338"},{"1":"INDBiogas","2":"3.390879","3":"3","4":"2161","5":"0.9900556","6":"0.9802101"},{"1":"INDLPG","2":"3.574889","3":"4","4":"2161","5":"1.0288625","6":"1.0585580"},{"1":"INDSolar","2":"3.772055","3":"4","4":"2161","5":"0.9376231","6":"0.8791371"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div>

![](DVgraphs_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

![](DVgraphs_files/figure-html/unnamed-chunk-14-1.png)<!-- -->

Prefix IND stands for individually or community-owned and managed. 


![](DVgraphs_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

