--- 
title: "Lab Handbook"
subtitle: "Our R Computing Lab"
author: 
- S. Mason Garrison
date: "2022-12-24"
knit: "bookdown::render_book"
site: bookdown::bookdown_site
url: 'https\://r-computing-lab.github.io/handbook/'
github-repo: R-Computing-Lab/handbook
twitter-handle: smasongarrison
cover-image: assets/logo.png
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "Handbook for the R Computing Lab"
favicon: assets/favicon.ico

---


# (PART\*) Front Matter {-}

# Preamble  {-}



The R Computing Lab is directed by Prof. Mason Garrison. Our lab houses scientists who conduct biometrically-informed research in R. Our research addresses a mixture of substantive and methodological questions. We're part of the MegaLab with Prof. Veronica Cole!



[web]: https://r-computing-lab.github.io/handbook
[git]: https://github.com/r-computing-lab/handbook/
[commits]: https://github.com/r-computing-lab/handbook/commits/main
[git_lab]: https://github.com/R-Computing-Lab
[stat545]: https://stat545.com





```{=html}
<div class="vembedr" align="center">
<div>
<iframe src="https://www.youtube.com/embed/yPr-Vm6Ji0E" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```


## How to use this handbook  {-}


This handbook is broken down into multiple section and chapters. Use the table of contents on the left side of the screen to navigate, and use the hamburger icon (horizontal bars) at the top of the document to open or close the table of contents. At the top of the document, you'll see additional icons which you can click to search the document, change the size, font or color scheme of the page. This lab handbook is constantly changing and in active development. Some sections may be empty. I encourage you to contribute to the [lab github][git_lab]. If you catch typos or errors, please issue a pull request with the fixes. 


<!--chapter:end:index.Rmd-->






[web]: https://r-computing-lab.github.io/handbook
[git]: https://github.com/r-computing-lab/handbook/
[commits]: https://github.com/r-computing-lab/handbook/commits/main
[git_lab]: https://github.com/R-Computing-Lab
[stat545]: https://stat545.com


# Attributions {-}
I have heavily adapted pieces from other lab manuals/handbooks. I will do my best to properly attribute sources. However, I strongly suspect that as this document grows and develops attributions will be harder and harder to keep track of. 

This document leans heavily on other peoples' materials and ideas. I have done my best to document the origin of the materials and ideas. In particular, I have noted those people whose work has been a major contribution as well as those who have additional contributions. You can see specific changes by examining the [edit history on the git repo][commits]

## Major Attributions  {-}

* Jenny Bryan's ([jennybryan.org](https://jennybryan.org)) [STAT 545][stat545]
* [Candice Morey's lab handbook](https://github.com/CCMorey/labHandbook)
* [Jonathan Peelle's lab manual](http://jpeelle.net/peellelab_manual.pdf)
* [Joshua Hartshorne's Language Learning Lab Manual](http://l3atbc.org/L3Manual.pdf)


# License {-#license}

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

<center>
<i class="fab fa-creative-commons fa-2x"></i><i class="fab fa-creative-commons-by fa-2x"></i><i class="fab fa-creative-commons-sa fa-2x"></i>
</center>

*This information is a human-readable summary of (and not a substitute for) the license.
Please see <https://creativecommons.org/licenses/by-sa/4.0/legalcode> for the full legal text.*

**You are free to:**

- **Share**---copy and redistribute the material in any medium or
  format

- **Remix**---remix, transform, and build upon the material for any
  purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the
license terms.

**Under the following terms:**

- **Attribution**---You must give appropriate credit, provide a link
  to the license, and indicate if changes were made. You may do so in
  any reasonable manner, but not in any way that suggests the licensor
  endorses you or your use.
  
- **ShareAlike**---If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original. 

- **No additional restrictions**---You may not apply legal terms or
  technological measures that legally restrict others from doing
  anything the license permits.

**Notices:**

You do not have to comply with the license for elements of the
material in the public domain or where your use is permitted by an
applicable exception or limitation.

No warranties are given. The license may not give you all of the
permissions necessary for your intended use. For example, other rights
such as publicity, privacy, or moral rights may limit how you use the
material.






# Colophon {-}

These notes was written in [bookdown](http://bookdown.org/) inside [RStudio](http://www.rstudio.com/ide/). The [website][web] is hosted with [github](https://www.github.com), The complete source is available from [github][git].

The book style adapted from designs by [Desirée De Leon](https://desiree.rbind.io/).

This version of the notes was built with:


```
#> Finding R package dependencies ... Done!
#>  setting  value
#>  version  R version 4.2.2 (2022-10-31 ucrt)
#>  os       Windows 10 x64 (build 22623)
#>  system   x86_64, mingw32
#>  ui       RTerm
#>  language (EN)
#>  collate  English_United States.utf8
#>  ctype    English_United States.utf8
#>  tz       America/New_York
#>  date     2022-12-24
#>  pandoc   2.19.2 @ C:/Program Files/RStudio/resources/app/bin/quarto/bin/tools/ (via rmarkdown)
```

Along with these packages:


```{=html}
<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-95b063857a85b7a146ee" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-95b063857a85b7a146ee">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["askpass","assertthat","backports","base64enc","bigD","bit","bit64","bitops","blob","bookdown","brew","brio","broom","bslib","cachem","callr","cellranger","cli","clipr","colorspace","commonmark","conflicted","cpp11","crayon","credentials","crosstalk","curl","data.table","DBI","dbplyr","desc","devtools","dichromat","diffobj","digest","downlit","dplyr","DT","dtplyr","ellipsis","evaluate","fansi","farver","fastmap","fontawesome","forcats","fs","gapminder","gargle","gender","genderdata","generics","geonames","gert","ggplot2","gh","gitcreds","glue","googledrive","googlesheets4","gridExtra","gt","gtable","haven","highr","hms","htmltools","htmlwidgets","httpuv","httr","ids","ini","isoband","jquerylib","jsonlite","juicyjuice","knitr","labeling","later","lattice","lazyeval","lifecycle","lubridate","magrittr","MASS","Matrix","memoise","mgcv","mime","miniUI","modelr","munsell","nlme","openssl","pillar","pkgbuild","pkgconfig","pkgdown","pkgload","praise","prettyunits","processx","profvis","progress","promises","ps","purrr","R6","ragg","rappdirs","rcmdcheck","RColorBrewer","Rcpp","readr","readxl","rebird","rematch","rematch2","remotes","reprex","rlang","rmarkdown","roxygen2","rplos","rprojroot","rstudioapi","rversions","rvest","sass","scales","selectr","sessioninfo","shiny","sourcetools","stringi","stringr","sys","systemfonts","testthat","textshaping","tibble","tidyr","tidyselect","tidyverse","timechange","tinytex","tzdb","urlchecker","usethis","utf8","uuid","V8","vctrs","viridis","viridisLite","vroom","waldo","whisker","withr","xfun","xml2","xopen","xtable","yaml","zip"],[null,"0.2.1","1.4.1",null,null,null,null,null,null,"0.31",null,null,"1.0.2","0.4.2","1.0.6","3.7.3","1.1.0","3.5.0",null,"2.0-3",null,null,null,"1.5.2",null,null,null,null,"1.1.3","2.2.1",null,"2.4.5",null,null,"0.6.31",null,"1.0.10","0.26",null,"0.3.2","0.19","1.0.3",null,"1.1.0",null,"0.5.2","1.5.2",null,"1.2.1",null,null,"0.1.3",null,null,"3.4.0",null,null,"1.6.2","2.0.0","1.0.1",null,null,"0.3.1","2.5.1",null,"1.1.2","0.5.4","1.6.0","1.6.7","1.4.4",null,null,null,"0.1.4","1.8.4",null,"1.41",null,"1.3.0",null,null,"1.0.3","1.9.0","2.0.3",null,null,"2.0.1",null,"0.12","0.1.1.1","0.1.10","0.5.0",null,null,"1.8.1","1.4.0","2.0.3",null,"1.3.2",null,"1.1.1","3.8.0","0.3.7",null,"1.2.0.1","1.7.2","1.0.0","2.5.1",null,null,null,null,"1.0.9","2.1.3","1.4.1",null,null,null,"2.4.2","2.0.2","1.0.6","2.19",null,null,null,"0.14",null,"1.0.3","0.4.4","1.2.1",null,"1.2.2","1.7.4",null,"1.7.8","1.5.0",null,null,null,null,"3.1.8","1.2.1","1.2.0","1.3.2","0.1.1",null,"0.3.0","1.0.1","2.1.6","1.2.2",null,null,"0.5.1",null,null,null,null,null,"2.5.0","0.36","1.3.3",null,"1.8-4","2.3.6",null],["2019-01-13","2019-03-21","2021-12-13","2015-07-28","2022-09-05","2022-11-15","2020-08-30","2021-04-24","2022-04-10","2022-12-13","2022-09-29","2021-11-30","2022-12-15","2022-12-16","2021-08-19","2022-11-02","2016-07-27","2022-12-20","2022-02-22","2022-02-21","2022-10-14","2021-11-26","2022-10-12","2022-09-29","2021-11-29","2021-11-04","2022-10-06","2022-11-16","2022-06-18","2022-06-27","2022-09-08","2022-10-11",null,"2021-10-05","2022-12-11","2022-07-05","2022-09-01","2022-10-19","2022-08-20","2021-04-29","2022-12-13","2022-03-24","2022-07-06","2021-01-25","2022-10-25","2022-08-19","2021-12-08","2017-10-31","2022-09-08",null,null,"2022-07-05",null,"2022-12-05","2022-11-04","2022-09-08","2022-09-08","2022-02-24","2021-07-08","2022-08-13","2017-09-09","2022-11-16","2022-09-01","2022-08-22","2022-12-22","2022-08-19","2022-12-07","2022-12-15","2022-12-14","2022-08-17","2017-05-31","2018-05-20","2022-12-20","2021-04-26","2022-12-06","2022-11-10","2022-11-18","2020-10-20","2021-08-18","2021-09-22","2019-03-15","2022-10-07","2022-11-06","2022-03-30","2022-08-03","2022-09-13","2021-11-26","2022-10-21","2021-09-28","2018-05-18","2022-11-11","2018-06-12","2022-10-10","2022-12-06","2022-08-19","2022-11-27","2019-09-22","2022-12-14","2022-11-16","2015-08-11","2020-01-24","2022-10-26","2020-11-02","2019-05-16","2021-02-11","2022-10-26","2022-12-20","2021-08-19","2022-10-24","2021-01-31","2021-09-27","2022-04-03","2022-07-08","2022-10-01","2022-08-17",null,"2016-04-21","2020-05-01","2021-11-30","2022-08-17","2022-09-24","2022-12-15","2022-12-08",null,"2022-04-02","2022-08-22","2022-08-31","2022-08-19","2022-11-24","2022-08-20","2019-11-20","2021-12-06","2022-12-15","2018-04-25","2022-07-11","2022-12-02","2022-10-18","2022-02-11","2022-12-09","2021-10-13","2022-07-22","2022-09-08","2022-10-10","2022-07-18","2022-11-04","2022-12-13","2022-03-28","2021-11-30","2022-05-25","2021-07-24","2022-04-19","2022-11-03","2022-11-16","2021-10-13","2022-08-22","2022-09-30","2022-03-16","2022-12-05","2022-03-03","2022-12-21","2021-11-30","2018-09-17","2019-04-21","2022-10-18","2022-10-26"],["CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.0)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)",null,"CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)",null,null,"CRAN (R 4.2.2)",null,"CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.1)","CRAN (R 4.2.2)","CRAN (R 4.2.2)",null,"CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)",null,"CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.1)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.0)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.2)","CRAN (R 4.2.1)","CRAN (R 4.2.2)"]],"container":"<table class=\"cell-border stripe\">\n  <thead>\n    <tr>\n      <th>package<\/th>\n      <th>loadedversion<\/th>\n      <th>date<\/th>\n      <th>source<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":165,"autoWidth":true,"bInfo":false,"paging":false,"columnDefs":[],"order":[],"orderClasses":false,"orderCellsTop":true,"lengthMenu":[10,25,50,100,165]}},"evals":[],"jsHooks":[]}</script>
```


<!--chapter:end:0000_front.Rmd-->

# (PART) Introductions {-}




# Who R we?


The R Computing Lab is directed by Prof. Mason Garrison. Our lab houses scientists who conduct biometrically-informed research in R. Our research addresses a mixture of substantive and methodological questions. We're part of the MegaLab with Prof. Veronica Cole!

Our substantive work focuses understanding the relationships between socioeconomic status, health & well-being, and individual differences (personality, intelligence). Our methodological work focuses on developing and improving biometrically-informed designs, such as behavior genetic and discordant kin models. Much of the research in my lab is student-driven, so the specific content questions will meander within that broad topic. :)

Students in the laboratory work on projects covering a wide range of topics, including inter-generational consequences of divorce, vaccination willingness, R package development.


My goal is to foster an inclusive, equitable, welcoming, and accessible lab environment, where EVERY member of the lab can thrive. I am convinced that supportive labs produce better science and scientists. I want you to feel welcomed, supported, valued, and respected. I want you to thrive. 


Members are listed by seniority (in the order they joined the lab).

## Investigators

### Principal Investigator

* S. Mason Garrison

### Affiliated Principal Investigator
* Veronica Cole


## Current Students

### Graduate Students
#### Primary Lab

* Yoo Ri Hwang
* Xuanyu Lyu


#### Affiliated (Primary Lab)

* Jonathan Trattner (Kishida)
* Emma Sims (Jayawickreme)




### Undergraduate Students

* Hannah Robertson
* Rachel Good
* Morgan Milhollen
* Laura McKinzie
* Sarah Thompson
* Emma Webster
* Mary King


### Sidekicks
* Tukey
* Archie & Annie


## Prior Members

#### Graduate Students
##### Affiliated (Primary Lab)

* Lindley Slipetz (Cole)

### Undergraduate Students
* Nora Clancy
* Sherry Mao
* Kennon Later
* Jonathan Trattner



<!--chapter:end:0001_who.Rmd-->





# (PART) Being in the lab {-}



# Being in the lab

Ok, so what does it mean to be part of the R computing lab? Well, let's start with my goals and expectations.


My goal is to foster an inclusive, equitable, welcoming, and accessible lab environment, where EVERY member of the lab can thrive. I am convinced that supportive labs produce better science and scientists. I want you to feel welcomed, supported, valued, and respected. I want you to thrive. 

This handbook is a first point of reference for current lab members as we strive to achieve these goals, and serves as a general introduction for prospective members. 


## Everyone

Generally, don't be an asshole. 

### You won't know everything

Ask questions! It is ok to not know something. I don't know everything. It is the sign of a good scholar to ask questions and it is the sign of a confident scholar to be willing to say that they don't know.

### Work-Life Balance

We value work-life balance.


## Mason
You can expect me to:

- Have a vision of where the lab is going.
- Care about your happiness, health, and well-being.
- Obtain the funding to support the science and the people in the lab.
- Track down interesting sources of data.
- Support you in your career development (regardless of whether you plan to stay in research), including: 
    - writing letters of recommendation,
    - introductions to other scientists, 
    - subsidizing conference travel, and 
    - promoting your work as often and as shamelessly as possible.

- Support you in your personal growth, including (but not limited to):
    - giving you flexibility in working hours and environment, and 
    - encouraging you to do things other than science.

- Treat you to coffee and keep the snack drawer filled.

- Make the time to meet with you regularly, read through your manuscripts, and talk about science.



## Graduate Students

I expect graduate students to:
- Know the literature related to their topic.
- Seek out and apply for fellowships and awards (including travel awards, etc.).
- Realize there are (extraordinarily rare) times for pulling all nighters, and times for leaving early to go to the park and enjoy the sunshine.

By the time you're done, you will have to know how to do statistics and plots in R, share your work with me using Rmarkdown, use mplus for latent variable modeling and use github for version control analyses.

The learning curve can be a little steep on these but it's well worth it. (If these learning outcomes aren't compatible with your goals or interests, my lab is probably not a good fit for you!)




## Undergraduate Students

I expect undergraduates to be utterly reliable and willing to help with whatever projects need it. At a bare minimum, reliability includes showing up on time and making sure that all of your work is accurate (double-check everything). If you find yourself without a specific project:

- Ask around to see if you can help with anything.
- Look on the wiki under "Essential lab skills" and spend some time learning something new.
- Look on the giant lab todo list for either a wiki page that needs creating/updating, or other miscellaneous lab tasks that need to be done.

There is enough to do that you should not be bored!

Your first semester in the lab is an opportunity to see whether continuing in the lab is a good fit; after your first semester we will meet and discuss whether you will continue.



### Honors Students

### Independent study




## University Policies
### Employee guidelines
### Sexual harassment



<!--chapter:end:0100_lab.Rmd-->


# Communication 
## Communication within the lab


### My doors

### Ways to get ahold of Mason

Here are my secret [Calendly links](https://calendly.com/smasongarrison/).




###  Lab Meetings

Lab members participate in both regular and ad hoc meetings. These meetings may involve everyone or just subgroups. If you have been asked to participate in a meeting, it is because you are a vital part of that project group. If you cannot attend, you should tell the group leader in advance. Remember, however, that the group may no longer be able to carry out the intended work without your presence, so skip meetings sparingly. 

If you do not appear at a meeting as expected and have not informed anyone in advance, it will be assumed that you have been abducted by aliens, and a search-and-rescue mission will be organized. I will draw [inspiration](https://www.nbcnews.com/news/world/how-swedish-professor-helped-rescue-grad-student-isis-controlled-iraq-n947866) from Prof. Charlotta Turner of Lund University.

All meetings begin and end on time, if not earlier. Don't be afraid to remind me of this if/when I am the offending party. It is important that we all respect each other's time.




### Wiki

The lab wiki is our shared collection of knowledge about how to get things done in the lab. The lab handbook you are reading now is "top down", in that I am writing the whole thing myself. By contrast the wiki is a shared resource to which everyone can—and should—contribute. A good rule of thumb is that if you need to figure out how to do something, someone else in the lab may someday need to do the same thing. Whenever possible please document what you figure out on the wiki, including updating old sections which may no longer be relevant. Please encourage each other (and those working with you) to do the same! (And me, please remind me!)



### Email

### Calendars


## Communication outside the lab

This section concerns general suggests and wisdom in communication. In the practical science section, I've included rmarkdown templates and practical advice.

### Social Media
### Presentations
#### Talks
#### Posters

### Manuscripts

## Conferences

Conferences are excellent opportunities to present your research, make connections, and learn about new research and methods from others. If possible, I recommend attending two or more conferences while you are a graduate student at Wake Forest and presenting your research at one or more of the conferences you attend.  



```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">Demystifying conference attendance was a motivation we had to write this article! We hope it helps broaden participation and improves mentoring of first-time attendees <a href="https://t.co/2TnCbinYX3">https://t.co/2TnCbinYX3</a> <a href="https://t.co/nEUM98xrH6">https://t.co/nEUM98xrH6</a></p>&mdash; Dr. Liz Leininger (she/her) (@ec_leininger) <a href="https://twitter.com/ec_leininger/status/1462603702670344192?ref_src=twsrc%5Etfw">November 22, 2021</a></blockquote>

```


Here are some conferences that are worth considering

https://psychology.ucmerced.edu/graduate-program/resources-current-students/conferences-psychological-sciences


### ARP

Association for Research in Personality ( https://www.personality-arp.org/ )



### BGA

Annual Meeting of Behavior Genetics Association (BGA)

Behavior Genetics Association ( http://bga.org/ )

Submission Deadline General: Submissions are typically due in March

- Prior Specific Deadlines

Conference Date General: Conference is generally in June

- Specific Example

Typical Costs


### Dev Methods

Developmental Methods ( http://www.developmentalmethods.org/ )

Submission Deadline General

- Prior Specific Deadlines

Conference Date General

- Specific Example

Typical Costs


### ISIR

International Society for Intelligence Research ( https://isironline.org/ )

Submission Deadline General

- Prior Specific Deadlines

Conference Date General

- Specific Example

Typical Costs

### SMEP

Society for Multivariate Experimental Psychology ( https://smep.org/ )

Submission Deadline General

- Prior Specific Deadlines

Conference Date General

- Specific Example

Typical Costs

### SPSP

Name: Annual Meeting of the Society for Personality and Social Psychology (SPSP)

Sponsoring Organization: Society for Personality and Social Psychology ( http://meeting.spsp.org/ )

Submission Deadline General: Submissions are typically due in July

- Prior Specific Deadlines

Conference Date General: Conference is generally in Winter (Ranges from Late Jan to Early Feb)

- Specific Example

Typical Costs:

### SSSP

Society for Southeastern Social Psychology ( http://southeast.spsp.org/upcoming-and-past-meetings )

Submission Deadline General

- Prior Specific Deadlines

Conference Date General

- Specific Example

Typical Costs


###  Abbreviation

Name ( Abbreviation )

Sponsoring Organization ( URL )

Submission Deadline General

- Prior Specific Deadlines

Conference Date General

- Specific Example

Typical Costs

<!--chapter:end:0101_communication.Rmd-->






[web]: https://r-computing-lab.github.io/handbook
[git]: https://github.com/r-computing-lab/handbook/
[commits]: https://github.com/r-computing-lab/handbook/commits/main
[git_lab]: https://github.com/R-Computing-Lab
[stat545]: https://stat545.com



# Science
## Big picture science
### Scientific integrity


You have a responsibility to me, the institutions that support our work, and the broader scientific community to uphold the highest standards of scientific accuracy and integrity. By being in the lab you agree to adhere to professional ethical standards. There is never an excuse for fabricating or misrepresenting data. If you have any questions, or in the unlikely event that you have concerns about a research practice you have seen in the lab, please talk to me immediately. It is also important that you prioritize the accuracy of your work while in the lab. Unintentional errors due to inattentiveness or rushing can be extremely damaging and produce results that turn out to be incorrect. Although there is always a pressure for a high quantity of research, it is critical that everything we do is of the highest quality. Please double-check your work frequently. In many cases multiple people will double-check a data set to ensure no mistakes have crept in along the way.


### Open, accurate, and reproducible science
#### Open science
#### Accurate science


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">I just completed a formal paper correction on my first first-authored publication. This was rough as a trainee, but the experience drastically changed how I approach science &amp; I&#39;m taking this as a good (albeit painful) lesson learned early on. 🧵(/7): <a href="https://t.co/96BIjx2vTI">https://t.co/96BIjx2vTI</a></p>&mdash; Meriah DeJoseph (@meriahdejoseph) <a href="https://twitter.com/meriahdejoseph/status/1461484970074152960?ref_src=twsrc%5Etfw">November 19, 2021</a></blockquote>

```

## Practical science

### Writing

#### Abstracts


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">Abstract writing template by Nature <a href="https://twitter.com/PhDVoice?ref_src=twsrc%5Etfw">@PhDVoice</a> <a href="https://twitter.com/PhDfriendSana?ref_src=twsrc%5Etfw">@PhDfriendSana</a> <a href="https://twitter.com/PhD_Genie?ref_src=twsrc%5Etfw">@PhD_Genie</a> <a href="https://twitter.com/OpenAcademics?ref_src=twsrc%5Etfw">@OpenAcademics</a> <a href="https://twitter.com/yourPhDpal?ref_src=twsrc%5Etfw">@yourPhDpal</a> <a href="https://twitter.com/hashtag/AcademicTwitter?src=hash&amp;ref_src=twsrc%5Etfw">#AcademicTwitter</a> <a href="https://twitter.com/hashtag/phdchat?src=hash&amp;ref_src=twsrc%5Etfw">#phdchat</a> <a href="https://twitter.com/hashtag/AcademicChatter?src=hash&amp;ref_src=twsrc%5Etfw">#AcademicChatter</a> <a href="https://t.co/MtzsLD5oNA">pic.twitter.com/MtzsLD5oNA</a></p>&mdash; Dr Asma Jabeen (@DrasmaJabeen1) <a href="https://twitter.com/DrasmaJabeen1/status/1459448488048140294?ref_src=twsrc%5Etfw">November 13, 2021</a></blockquote>

```
### Computers and data
### Authorship

My general philosophy is to be generous and provide ample opportunity for members of the lab to earn authorship. Authorship on an academic work is a ["public acknowledgment of scientific or professional contribution"](https://www.apa.org/science/leadership/students/authorship-paper). Although the criteria for authorship differ slightly across fields, the general question asked is whether this individual made a meaningful contribution to the work. I tend to ask myself had this potential author not been involved in the project, would the final product differed substantially? If the answer to that counter-factual is yes, then I believe that person has earned authorship.

#### Order of Authors

In psychology, the order of authors reflects their relative contribution. Other fields have different conventions, such as economics tends to alphabetize authors. However, psychology and other lab-based fields don't merely rank authors. Instead the authorship order resembles a 'U' where first and last authors indicate the most substantial contributions and authors in the middle reflect relatively smaller contributions. Practically speaking, this ordering means that I (Mason) will probably be last author, and any project that you, dear reader, lead are first author.

<!--chapter:end:0102_science.Rmd-->

# (PART) Lab Documents {-}





# Lab Documents and Resources



## Course Materials

### Data Science for Psychologists

https://datascience4psych.github.io/DataScience4Psych/

### Behavior Genetics
https://bga.org/training-materials/



<!--chapter:end:0200_labdocs.Rmd-->







[web]: https://r-computing-lab.github.io/handbook
[git]: https://github.com/r-computing-lab/handbook/
[commits]: https://github.com/r-computing-lab/handbook/commits/main
[git_lab]: https://github.com/R-Computing-Lab
[stat545]: https://stat545.com




# Onboarding

## Things You'll Need
 

 
## Github
 
- Github Membership
- Added to the lab repo
- Added to the DS class
 
## Google Group
 
 Primarily, this google group serves as an easy way for me to transmit information/opportunities to the lab. You can opt opt of the emails or consolidate them as a digest.

https://groups.google.com/g/rcomputinglab 
 
## R


<!--chapter:end:0201_onboarding.Rmd-->


# Data


This lab doesn't collect fresh data. We use archival data that others have collected. 

## Sources in general

### Publicly Available Data

I have a sampling listed here. The main list is in the [Secondary Dataset Repositories][https://osf.io/ra8yg/wiki/home/]

#### University Archives
- [Harvard Dataverse][http://dataverse.harvard.edu/]
- [Inter-university Consortium for Political and Social Research (ICPSR)][https://www.icpsr.umich.edu/icpsrweb]



#### Government Data


##### NLSY

[National Longitudinal Surveys of Youth (NLSY)] contains 4 generations of data and a replication sample that is nationally representative of the united states. It's got tons of good stuff in it. And is a staple data set in the lab for sibling comparison designs.  

The [NLSY79 topical guide](https://www.nlsinfo.org/content/cohorts/nlsy79/topical-guide) is a good place to get started.




### Limited Access Data

- Kelly/Connolly Longitudinal Study (KCLS)

## Genetically Informed Data

https://vipbg.vcu.edu/research/datasets-projects/

<!--chapter:end:0203_data.rmd-->

# (PART) Projects {-}



# Active Projects

For the most current list... navigate to the lab github.... https://github.com/R-Computing-Lab


# Showcase

<!--chapter:end:0300_projects.Rmd-->

# (PART) Wake Forest Timelines {-}

# Graduate Students

## General Timeline

The timeline below is intended to help you structure your time during the WFU graduate program -- to stay on track with: 
- non-coursework program requirements, 
- professional development opportunities (conferences), and 
- PhD applications, if you plan to apply. 

It likely not comprehensive for your unique situation, and it is expected that you will personalize it. This timeline was originally written by [The AMAZING Shannon Brady](https://psychology.wfu.edu/about-the-department/faculty-and-staff/shannon-brady/). I've tweaked it and added to it. But she really deserves credit for it.

### Year 1

August

- Match with Advisor
- Consider Submitting to SSSP


September

- Acclimate! Get lab key
- Discuss interests and goals with advisor; personalize timeline


October

- Read relevant literature
- Review Grad Handbook sections for Year 1 
- Begin to develop First Year Project (FYP)
- Consider attending SSSP 


November

- Read relevant literature
- Present FYP to peers; get feedback


December

- Read relevant literature
- Refine plan for FYP
- If needed: Secure IRB approval for FYP 
    - (In my lab needing IRB approval is rare)


January

- Begin data collection OR begin data cleaning/analysis


February

- Collect data and/or clean and analyze data


March

- Collect data and/or clean and analyze data
- Discuss initial ideas for MAP w/ advisor
- Find template for FYP poster; 
    -  discuss w/ advisor
- Consider submitting FYP to BGA

April

- Create and revise FYP poster
- Present FYP Poster


May

- Review Grad Handbook sections for Year 2 
- Discuss initial ideas for MAP w/ advisor
- Generate initial list of PhD topics/advisors; 
    - discuss w/ mentors 
- Consider submitting to a conference (like SPSP)



June

- Identify articles to be "mentor texts"
- Draft Methods section of MAP; get feedback
- Read papers by prospective advisors

July

- Draft Results section of MAP; get feedback
- Read papers by prospective advisors
- Create/update CV
- Consider submitting to SPSP


### Year 2

August

- Review Grad Handbook expectations for MAP
- Create complete outline of MAP
    - get feedback
- Submit MAP outline and annotated biblio
- Refine list of PhD advisors; 
    - reach out
- Write crappy first draft of SOP
- Consider submitting to SSSP


September

- Schedule MAP feedback meeting
- Send MAP to all committee members
- Contact letter writers
- Discuss SOP with mentors/peers/friends

October

- Have MAP feedback meeting
    - If needed: revise MAP
- Review Grad Handbook expectations for thesis
- Finalize thesis idea
- Review and revise SOP;
- draft any other materials needed for applications
- Send materials to letter writers
- Consider attending SSSP


November

- Draft thesis prospectus; get feedback; revise
- Schedule thesis prospectus mtg 
- If needed, identify new “mentor texts” 
- Get feedback on other materials; finalize
- Submit applications (if due this early)



December

- Have thesis prospectus mtg 
- If needed: Secure IRB approval for thesis
- Draft/refine thesis timeline
- Submit applications



January

- File intent to graduate
- At latest: Begin data collection OR begin data cleaning/analysis
- Find, contact, and confirm outside member for thesis committee
- Maybe: interview(s)



February

- Collect data and/or clean and analyze data 


March

- If needed: revise thesis timeline
- Collect data and/or clean and analyze data 
- Schedule thesis defense
- Revise prospectus into thesis draft
- Submit format thesis to Grad Office
- Maybe: interview(s)



April

- Write, write, write!
- Get feedback and revise
- Defend thesis 
- Submit thesis 
- Complete graduation logistics
- Hopefully: Choose PhD program; inform all programs of decision 


May

- Graduate!
- Organize and annotate all research files
- Make sure advisor has copy of all research files (materials, data, code, notes, etc.) 



June

- Write/revise projects for publication

July

- Write/revise projects for publication; submit


### Graduation Requirement Checklist

https://graduate.wfu.edu/graduation-requirement-checklist-reynolda-campus/

<!--chapter:end:0400_graddev.Rmd-->

# Undergraduate Student

## Psychology Resources

[Undergraduate Information & Resources for Psychology Majors (and Minors)](https://sites.google.com/a/wfu.edu/psych/home)


<!--chapter:end:0401_undergraddev.Rmd-->

# (PART) Style Guides {-}



# APA

## Bias-Free Language

> The American Psychological Association emphasizes the need to talk about all people with inclusivity and respect. Writers using APA Style must strive to use language that is free of bias and avoid perpetuating prejudicial beliefs or demeaning attitudes in their writing. Just as you have learned to check what you write for spelling, grammar, and wordiness, practice reading your work for bias.
> 
> The guidelines for bias-free language contain both general guidelines for writing about people without bias across a range of topics and specific guidelines that address the individual characteristics of age, disability, gender, participation in research, racial and ethnic identity, sexual orientation, socioeconomic status, and intersectionality. These guidelines and recommendations were crafted by panels of experts on APA’s bias-free language committees.
Inclusive and bias free-language. 

[Source](https://apastyle.apa.org/style-grammar-guidelines/bias-free-language)


## Inclusive Writing

See this recent document from the APA about using [inclusive](https://www.apa.org/about/apa/equity-diversity-inclusion/language-guidelines.pdf) and [bias-free](https://apastyle.apa.org/style-grammar-guidelines/bias-free-language/general-principles) language. The APA recently added an entire section on the [disability-community](https://apastyle.apa.org/style-grammar-guidelines/bias-free-language/disability). Also, the National Center on Disability and Journalism has an inclusive [style guide](https://ncdj.org/style-guide/).

# Useful Copy-editing Resources

These resources are useful for copyediting, readability, and academic phrasing. Often these use NLP.

## Software and Widgets
- Grammarly
- [Writefull](https://www.writefull.com/)
- [Writefull's Title Generator](https://x.writefull.com/title-generator/index.html)
- [Writefull's Academic Paraphraser](https://x.writefull.com/paraphraser/index.html)
- [Hemingway App](https://hemingwayapp.com/)



# R Style Guide

The goal of this Programming Style Guide is to make the lab's R code more consistent and easier to work with. This guide is based on the Tidyverse Style Guide by Hadley Wickham [license](https://creativecommons.org/licenses/by-sa/2.0/). It differs in a few ways, and provides much more detail on variables names for the NLSY.

## NLSY Variable Names

Please use the variable renamer function

### Armed Services Vocational Apptitude Battery

( WORD_KNOWLEDGE | WORDKNOW ) = WK

( ARITHMETIC_REASONING | ARITHREASON ) = AR

( WORD_KNOWLEDGE | WORDKNOW ) = WK

( PARACOMP | PARAGRAPH_COMPREHENSION ) = PC

<!--chapter:end:0500_styleguide.Rmd-->

# (PART) Useful Things {-}





[web]: https://r-computing-lab.github.io/handbook
[git]: https://github.com/r-computing-lab/handbook/
[commits]: https://github.com/r-computing-lab/handbook/commits/main
[git_lab]: https://github.com/R-Computing-Lab
[stat545]: https://stat545.com

# Software

This wikipage contains the collective lab knowledge about software and coding. Sections are kind of organized logically.



## R & Rstudio

There are tons more stuff about R in my [Data Science for Psychologists class.](https://datascience4psych.github.io/DataScience4Psych/)



### Base R

### R studio

### R Code

This subsection contains R code that I have googled more than once.

#### How do I export a dataframe?

Description: export a dataframe to specific data type?

Source: [Quick-R](https://www.statmethods.net/input/exportingdata.html)


 - dat

> write.table(mydata, "mydata.dat", sep="\t")
    
 - csv
 
> write.csv(mydata,"mydata.csv", row.names = FALSE)



#### How do I merge a list of dataframes?

Description: Merges list of dataframes into a single dataframe

Source: [stackoverflow]( https://stackoverflow.com/questions/2851327/convert-a-list-of-data-frames-into-one-data-frame/38509685)


> bind_rows(list_of_dataframes, .id = "column_label")

Note: .id = "column_label" adds the unique row names based on the list element names


#### How do I produce all combinations of list elements?

Description: produce all combinations of list elements

Source: [rdrr.io](https://rdrr.io/r/base/expand.grid.html)


```r
require(utils)

expand.grid(height = seq(60, 80, 5), 
            weight = seq(100, 300, 50), 
            type = c("Cat","Dog"))
#>    height weight type
#> 1      60    100  Cat
#> 2      65    100  Cat
#> 3      70    100  Cat
#> 4      75    100  Cat
#> 5      80    100  Cat
#> 6      60    150  Cat
#> 7      65    150  Cat
#> 8      70    150  Cat
#> 9      75    150  Cat
#> 10     80    150  Cat
#> 11     60    200  Cat
#> 12     65    200  Cat
#> 13     70    200  Cat
#> 14     75    200  Cat
#> 15     80    200  Cat
#> 16     60    250  Cat
#> 17     65    250  Cat
#> 18     70    250  Cat
#> 19     75    250  Cat
#> 20     80    250  Cat
#> 21     60    300  Cat
#> 22     65    300  Cat
#> 23     70    300  Cat
#> 24     75    300  Cat
#> 25     80    300  Cat
#> 26     60    100  Dog
#> 27     65    100  Dog
#> 28     70    100  Dog
#> 29     75    100  Dog
#> 30     80    100  Dog
#> 31     60    150  Dog
#> 32     65    150  Dog
#> 33     70    150  Dog
#> 34     75    150  Dog
#> 35     80    150  Dog
#> 36     60    200  Dog
#> 37     65    200  Dog
#> 38     70    200  Dog
#> 39     75    200  Dog
#> 40     80    200  Dog
#> 41     60    250  Dog
#> 42     65    250  Dog
#> 43     70    250  Dog
#> 44     75    250  Dog
#> 45     80    250  Dog
#> 46     60    300  Dog
#> 47     65    300  Dog
#> 48     70    300  Dog
#> 49     75    300  Dog
#> 50     80    300  Dog
```

#### How to remove scientific notation?

Description: Stop R from printing tiny decimals as strings

Source: [stackoverflow](https://stackoverflow.com/questions/5352099/how-to-disable-scientific-notation)


```r

options(scipen = 999)
```


# Browsers/Internet

## Google
This section contains google-related code that I have googled more than once

### Search Operators
[Source]( https://ahrefs.com/blog/google-advanced-search-operators/)


#### cache

Description: Returns the most recent cached version of a web page 
 
> cache:


#### filetype

Description: Restrict results to those of a certain filetype. e.g., PDF, DOCX, TXT, PPT, etc.

> filetype:
 
#### site    
Description: Limit results to those from a specific website.

> site:
    
#### related
Description: Find sites related to a given domain.

> related:


#### intitle
Description: Find pages with a certain word (or words) in the title. 

> intitle:


#### Proximity
Description: Proximity search. Find pages containing two words or phrases within X words of each other.

> AROUND(X)



## Javascript Bookmarklets

A bookmarklet is a bookmark stored in a web browser that contains JavaScript commands that add new features to the browser. 
(Source: [Wikipedia](https://en.wikipedia.org/wiki/Bookmarklet))

### WFU Related

Description: Redirects you to the WFU proxied version of the website

> javascript:void(location.href="http://go.libproxy.wakehealth.edu/login?url="+location.href)
    
Source: Mason

### Google Related



#### Switch google accounts


Description: If you have multiple google accounts, you can add "?authuser=1" to switch to your 2nd account.

> javascript:window.location.href=window.location.href+'?authuser=1'

Source: Mason

#### Google Cache 

Description: Text-only version of google Cache


> javascript:(function(){var loc=window.location;if (window.location.protocol != "https:"){loc=window.location.toString().replace(/^http:\/\//,'http://webcache.googleusercontent.com/search?q=cache:');}else{loc=window.location.toString().replace(/^https:\/\//,'https://webcache.googleusercontent.com/search?q=cache:');}window.location.replace(loc + '&num=1&strip=1&vwsrc=0')})()

Source: [Online Techtips](https://www.online-tech-tips.com/cool-websites/the-12-best-bookmarklets-every-browser-should-have/)

### Google Translate 

Description: Autodetect language and translate into English


> javascript:var t=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection &&document.selection.createRange&&document.selection.createRange().text));var e=(document.charset||document.characterSet);if(t!=''){location.href='http://translate.google.com/translate_t?text=' t '&hl=en&langpair=auto|en&tbb=1&ie=' e;}else{location.href='http://translate.google.com/translate?u=' escape(location.href) '&hl=en&langpair=auto|en&tbb=1&ie=' e;};

Source: [Online Techtips](https://www.online-tech-tips.com/cool-websites/the-12-best-bookmarklets-every-browser-should-have/)

### Not Otherwise Specified

#### Waybackmachine

Description: "If the webpage you're wanting to read is no longer available, is throwing an error, or the website as a whole has been taken down, you might still have luck finding it on Wayback Machine." 


> javascript:location.href='https://web.archive.org/web/*/'+location.href

Source: [Online Techtips](https://www.online-tech-tips.com/cool-websites/the-12-best-bookmarklets-every-browser-should-have/)





## Userscripts

What are user scripts?

User scripts put you in control of your browsing experience. Once installed, they automatically make the sites you visit better by adding features, making them easier to use, or taking out the annoying bits. The user scripts on Greasy Fork were written by other users and posted to share with the world. They're free to install and easy to use. 

(Source: [GreasyFork](https://greasyfork.org/en/help/installing-user-scripts))


<!--
# Template

## Name

Description: 

> CODE

Note: Additional comments

Source: [URL](https://google.com)

-->

<!--chapter:end:0600_usefulthings.Rmd-->


# Remote Access




## Steps

1. You will need to be sure you have the WFU VPN Client software (Cisco Anyconnect Mobility) installed - if you don't already have it, you can install it from software.wfu.edu (and probably this specific link: https://software.wfu.edu/download/wfu-vpn/). 


2. You will also need to have the Microsoft Remote Desktop software installed. You should already have this as part of MS Office. If on a Mac, you won't have it probably, but can get it free through the app store. 



3. You will sign into VPN (using the client software mentioned above). 


4. To sign in, you should enter your ID and password. For example, if your email address is " Gravity21@wfu.edu" and your password is "11111111" you should key in "Gravity21" and "11111111"


5. Once connected through VPN, you need to open the Microsoft Remote Desktop software and key in the IP address that you already received.

## Troubleshooting

In case Cisco Anyconnect isn't working, try these resources. 

- https://is.wfu.edu/services/vpn/

- https://help.wfu.edu/support/solutions/articles/13000033253

<!--chapter:end:0601_remoteaccess.Rmd-->

# (PART) Professional Development {-}




# Future Directions!

This section gathers together some professional development resources I've gathered throughout my career. The collections are currently divided into Graduate School Applications and Academic Job Search. Clearly, there's much to add in between those two stages. 

<!--chapter:end:0900_development.Rmd-->



# Graduate School Admissions Advice

## Motivation

Here are an incomplete collection of resources for students interested in applying to graduate school in psychology. I've included my application materials that I used for the PhD program I enrolled in. NOTE: I really feel that I was accepted in spite of my application essay. However, in the spirit of transparency, I've included it anyway.



## General Advice


### Should you go?

- The Economist on [Why doing a PhD is often a waste of time](https://medium.economist.com/why-doing-a-phd-is-often-a-waste-of-time-349206f9addb)
- Richard Z on [Why Would You Want to Do a PhD?: Student perspectives on the value of a graduate degree](https://gradadmissions.mit.edu/blog/why-would-you-want-do-phd)


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">A big part of my job is mentoring undergraduate students in research programs in the humanities, arts, and social sciences and so I have conversations with students who are thinking about getting PhDs every single week of my life. Here is what I tell them.</p>&mdash; Jacquelyn Ardam (@jaxwendy) <a href="https://twitter.com/jaxwendy/status/1492553462302707714?ref_src=twsrc%5Etfw">February 12, 2022</a></blockquote>

```


## Application

- [Appleby, D. C., & Appleby, K. M. (2006). Kisses of death in the graduate school application process. Teaching of Psychology, 33(1), 19-24.](https://psychology.unl.edu/psichi/Graduate_School_Application_Kisses_of_Death.pdf)

- [Philip Guo's](http://www.pgbovine.net/index.html) [A Five-Minute Guide to Ph.D. Program Applications](http://www.pgbovine.net/PhD-application-tips.htm)


### Personal Statements


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">With PhD applications due soon, thousands of young people are currently beginning their statements of purpose with the same cliché story, or the same anodyne statement<br><br>Stop right now!<br><br>Here are 10 thoughts for doing this right. Helps you, and helps admissions committees.👇</p>&mdash; Chris Blattman (@cblatts) <a href="https://twitter.com/cblatts/status/1593606505340801024?ref_src=twsrc%5Etfw">November 18, 2022</a></blockquote>

```



### Resumes and CVs


```{=html}
<div class="vembedr" align="center">
<div>
<iframe src="https://www.youtube.com/embed/42ifhBbyu8A" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```


### Recommendation Letters


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">It&#39;s rec letter season! A few tips: (1) include all materials in one batch and one email thread, (2) include a table of due dates/instructions, and keep up-to-date in most recent email; (3) send reminders; (4) let us know if you are now NOT submitting. What did I miss? Good luck!</p>&mdash; Dr. Bridgette Kelleher (@DrBKelleher) <a href="https://twitter.com/DrBKelleher/status/1455202559988273155?ref_src=twsrc%5Etfw">November 1, 2021</a></blockquote>

```


```{=html}
<div class="vembedr" align="center">
<div>
<iframe src="https://www.youtube.com/embed/PJZwQZsoqE0" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```

### Contacting Professors


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">I just got 5 emails from prospective PhD students and there is a definite right and wrong way of approaching a potential supervisor/PI. This is not innate knowledge so here goes a thread. Starting from worst examples (1/n) <a href="https://twitter.com/hashtag/AcademicChatter?src=hash&amp;ref_src=twsrc%5Etfw">#AcademicChatter</a> <a href="https://twitter.com/hashtag/phdchat?src=hash&amp;ref_src=twsrc%5Etfw">#phdchat</a></p>&mdash; Cristina Banks-Leite (@crisbanksleite) <a href="https://twitter.com/crisbanksleite/status/1453753435594047494?ref_src=twsrc%5Etfw">October 28, 2021</a></blockquote>

```

```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">How to write to a potential PI?<br><br>1-Dear [correct] title and name<br>2-Brief parag., who you are and what you want <br>3-Long parag., explaining your BSc, MSc, title of dissertation, previous experience and skills<br>4-Mid/long parag, explain in detail why work with PI<br>5-Funding (5/n)</p>&mdash; Cristina Banks-Leite (@crisbanksleite) <a href="https://twitter.com/crisbanksleite/status/1453753463494610952?ref_src=twsrc%5Etfw">October 28, 2021</a></blockquote>

```

### My Materials

I've included my materials for my application to quantitative psychology graduate programs. You can find them in the [source code for the handbook](https://github.com/R-Computing-Lab/handbook/tree/main/admin/masonmaterials/gradapps). Specifically, here is my CV when I applied (file: [docx](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/gradapps/SMGarrisonCVNOV.docx); [pdf](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/gradapps/SMGarrisonCVNOV.pdf));  and statement of purpose (file: [docx](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/gradapps/VanderbiltStatementofPurpose.docx); [pdf](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/gradapps/VanderbiltStatementofPurpose.pdf)).

## Interviews


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">Just submitted psychology graduate school applications? Time to start prepping for interviews! Here’s a list of sample questions that may be helpful when preparing. Feel free to distribute or add! <a href="https://twitter.com/AcademicChatter?ref_src=twsrc%5Etfw">@AcademicChatter</a> <a href="https://twitter.com/PsychChatter?ref_src=twsrc%5Etfw">@PsychChatter</a> <a href="https://t.co/CnirQ6nCbu">pic.twitter.com/CnirQ6nCbu</a></p>&mdash; Julie Cristello (@julie_cristello) <a href="https://twitter.com/julie_cristello/status/1466047527518679043?ref_src=twsrc%5Etfw">December 1, 2021</a></blockquote>

```

This collection of questions comes from [this reddit post]( https://www.reddit.com/r/gradadmissions/comments/rxizvp/master_list_of_interview_questions/)

### Motivations

- What motivated you to apply to grad school?
- Why do you feel prepared to start graduate school?
- What areas of research interest you?
- Why do you want to pursue a PhD in your area of interest?
- Do you have any reservations/worries about entering a PhD program?
- What are you looking to gain from your graduate school experience?
- Why do you need a PhD to achieve your career goal?
- Where do you see your field going in the next 5-10 years?
- Where do you see yourself in 15 years?
- What is unique about you that gives you a competitive edge over other applicants?

### The Program/Institution

- Why are you specifically drawn to this program?
- Why do you think this program would be a good fit for you?
- What specific resources does this institution offer to enhance your scientific trajectory?
- How do you think your interests will fit in with the program?
- What do you think you will contribute to the program?
- Which faculty members’ work particularly interests you and why?
- Have you established a relationship with one or more faculty members within the program?
- What interests you about the city the institution is in?
- What would make you choose this institution over other programs?

### Previous Research

- Please list the different research experiences you have had.
- How many total years of research experience do you have?
- How has your research experience prepared you for graduate school?
- What questions did your research help answer?
- What was your role in developing research ideas?
- How did you manage your research project?
- What was innovative about your research?
- What was your favorite technique that you used in your undergraduate research?
- What was the biggest challenge you encountered in your undergraduate research, and how did you deal with it?
- How is your work distinct from your supervisor’s/principal investigator’s?
- What do you think are your most significant research accomplishments?
- What do you consider to be your best paper/work and why?
- What has been the impact of your research?
- Do you expect to publish before starting graduate school?
- If you were starting your project again today, what would you do differently?

### Current/Future Research

- What are your research interests?
- What are the big picture questions you want to investigate?
- What are the biggest challenges/questions in your field of research?
- How do you plan to approach your questions?
- How do you see this work impacting the field?
- How does the work you propose follow on from what you are already doing?
- What skills do you want to develop at this institution?
- Do you plan to apply for additional funding?
- What funding opportunities are you aware of, or what would you like to apply for?
- How would you convince a funding body that they should fund your research?
- How would you fit with the existing activities in the department?
- If we gave you unlimited resources, what would you do with them?
- Who do would you expect to collaborate with in the institution?
	- Why do you want to collaborate with them?
- What is an interesting paper you have read lately?

### If you have a specific project in mind...

- What is the overall importance of this project?
- Can you see any of your research proposal failing?
- What will you do if your hypothesis is proved wrong?
- What resources will you need?
- What opportunities for multi-disciplinary work does your research offer?
- 
### Potential Advisors

- What do you want to work on in my lab?
- What interests you about my research?
- What do you know about my research?
- Who are you interested in working with?
- What techniques have you learned that you could use in my lab?


### Teaching

- Do you have any teaching experience?
- How do you feel about teaching?
- How do you feel about mentoring undergrads?
- How would you deal with any conflict/disagreement within the research group?
- Do you have an example of when you have had to deal with a disagreement?
- 
### Personal

- What do you do in your free time (not in the lab)?
- What motivates you?
- What drives you as a scientist?
- Who has influenced you the most?
- How do you work best – independently, or with a team, at home?
- How do your interests fit with the strengths and goals of the program?
- What do you expect to be challenging about graduate school? What are your plans for managing those challenges?
- Graduate school often involves a combination of intense days, long nights, and high expectations. What strategies will you use to manage this combination of demands?
- What are your strengths and weaknesses?
- Tell us about a time when things didn’t go the way you wanted. How did you handle it, and what did you learn from the experience?
- Tell us about your most successful or interesting research experience in a lab environment. Which of your qualities helped facilitate this success?
- Describe a time that you encountered a significant personal obstacle? How did you handle it?
- Is there any information pertinent to your application that you would like to add?
- In what ways, other than research and teaching could you contribute to this department?
- What are your long term career goals


### Questions for you to ask current grad students

- Does the environment feel more collaborative or competitive?
- What is the funding structure/guarantee for students?
- Is it an inclusive environment?
- Where do you (and students in general) live?
- What is the area around campus like?
- Do you think the stipend reflects the cost of living?
- Is the university helpful with finding housing?
- How easy/difficult was the process of joining a lab?
- Do most people join their first choice lab?
- How much time are you expected to spend in the lab?
- How would you describe your PI's advising style?
- How do you maintain a successful relationship with your advisor?
- How regularly/quickly does your advisor publish?
- What research are you working on?
- How quickly were you able to start your research?
- Is the project you're working on what you thought you'd be doing, or has the project you're working on gone in any unexpected directions?
- Who is on your committee and why?
- Would you choose this advisor if you were doing it over?
- Do you get to attend conferences?
- What do you think of the courses - useful content, well taught, relevant to your research/goals?
- How easy/hard is it to customize the program?
- What would you change about the program?
- What kind of schedule do you work?
- What do grad students do in their free time?
- Do most students have a good work/life balance?
- Do grad students in this program hang out with each other?
- Do you know many people in grad school who regret starting it?
- Do you know people who have left the graduate program?
- What kind of resources does the program offer (e.g. for mental health, career development, learning new skills, etc.)?
- Is there anything you wish you had taken into consideration when making your decision about where to attend?

### Questions for you to to ask potential PI’s

- I read your paper/book X. Can you tell me about your future research goals related to X? What are your current projects?
- What research projects do you have that would be looking for graduate students?
- What advice would you give to a student who wants to be successful in your program? Are there any specific pitfalls to be avoided?
- What are the expectations for a graduate student in your lab?
- Do students create their own projects or work on something already developed/in progress?
- How is your lab organized? Do you have a lab manager, or do other members of the lab take on this role?
- Do you have lab/group meetings, and what is the format of those meetings?
- How much collaboration is there within the lab?
- How much do your students publish?
- How often do you sent students to conferences?
- How long do students in your lab take to complete their degree?
- What do students from your lab typically do after graduation?
- What is the big picture/goal/focus/priority of the department?

### Questions for you to ask other interviewers

(like program or admissions directors)

- What are the responsibilities of grad students in this program?
- What is the workload/time commitment?
- Do grad students have to TA? How many terms do you TA?
- Are students generally collaborative or competitive?
- How big is the program?
- What's the biggest strength of the program?
- What professional development services are available?
- How/when are students paired with advisors?
- What does the program do if someone doesn't find a lab to join by the deadline?
- What percentage of students complete the degree? Pass quals?
- How would you compare this program to X and Y?
- Is there funding available for attending things like conferences or summer schools?
- What are the career outcomes for students in this program?


## Field Specific Things

### Clinical Psychology

- [Mitch Prinstein](http://mitch.web.unc.edu/info-for-phd-applicants/)'s collection of info for Clinical Psychology PHD applicants including:
    - [Mitch's Uncensored Advice for Applying to Graduate School in Clinical Psychology](http://mitch.web.unc.edu/files/2017/02/MitchGradSchoolAdvice.pdf) 
    - [Tips on Applying to Graduate School](http://mitch.web.unc.edu/files/2013/10/TipsForApplyingToGradSchool.pdf) by Sophie Choukas-Bradley
    - [Before You Apply](http://mitch.web.unc.edu/files/2013/10/BeforeYouApply.pdf) by Casey Calhoun
- [Craig Rodriguez-Seijas's](https://sites.lsa.umich.edu/splat-lab/) [FAQ](https://sites.lsa.umich.edu/splat-lab/faqs/)

- [American Psychological Association](https://www.apa.org/index)'s [List of APA-Accredited Programs](https://www.apa.org/ed/accreditation/programs/)


### Individual Differences (Personality, Intelligence, etc)

- [Bill Revelle](https://www.personality-project.org)'s [Website has a collection of info](https://www.personality-project.org/org.html#howtoapply) 

- [Bill Revelle](https://www.personality-project.org)'s List of [Graduate Departments of Psychology with Personality Programs](https://www.personality-project.org/org.html#gradpsych)


### Social Psychology

- [Social Psychology Network Ranked List](https://www.socialpsychology.org/gsocial.htm)
- [SPSP's Social and Personality Graduate Program Directory](http://spsp.org/resources/student/grad-directory)

### Quantitative Psychology

- [List of schools for quantitative psychology](https://en.wikipedia.org/wiki/List_of_schools_for_quantitative_psychology)
- [2022 Grad Programs in Quant Methods Descriptions](https://drive.google.com/file/d/1bZKlZOzz2gvvJbhAt1CmgLfzTthwUudR/view?usp=share_link)
- [Matrix Algebra Prep](ttps://docs.google.com/document/d/1zJppucbjjIw38PyGbdlVY457xJ2fJFgT/edit?usp=share_link&ouid=116013359694141653434&rtpof=true&sd=true)
	
## Bonus Stuff
 

### Funded Terminal Master's Programs (Incomplete List)

- [College of William and Mary](https://www.wm.edu/as/psych-sciences/gradprogram/financial-support/index.php)
- [Villanova University](https://www1.villanova.edu/villanova/artsci/psychology/AcademicPrograms/graduate/current/assistantships.html)
- [Wake Forest University](http://psychology.wfu.edu/graduate-program/graduate-financial-aid-2/)


## Subreddits
- [/r/Gradadmissions](https://www.reddit.com/r/gradadmissions/)
- [/r/GradSchool](https://www.reddit.com/r/GradSchool/)
- [/r/AskAcademia](https://www.reddit.com/r/AskAcademia)

## Grad Cafe

- [gradcafe admission results](https://www.thegradcafe.com/survey/index.php)
- [Data Visualization of Timelines](https://www.reddit.com/r/gradadmissions/comments/7srxxy/decision_timelines_for_particular_universities/)

<!--chapter:end:0901_gradadmission.Rmd-->



# Sources of Funding


## Internal Wake Forest

https://ureca.wfu.edu/student-resources/starr-travel-grant



## External

### General Advise

https://twitter.com/RohacsTibor/status/1468678482897084426


### International Alliance for Ability in Science

https://iafais.org/scholarships

## Behavior Genetics Association

Travel Awards

## Council of Graduate Departments of Psychology (COGDOP) 

https://www.cogdop.org/scholarships/
<!--
### SMEP
 https://smep.org/resources/underrepresented-fellowships Support for Students from Underrepresented Groups to Attend Methodological Workshop
-->
### SPSP

SPSP has travel awards

# Sample Materials

## NSFGRFP

I've included my National Science Foundation Graduate Fellowship materials. You can find them in the [source code for the handbook](https://github.com/R-Computing-Lab/handbook/tree/main/admin/masonmaterials/nsfgrfp). I applied twice. Here's my personal statement [(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/unsuccessful/MG_NOWIN_personal_submitted.pdf), research proposal[(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/unsuccessful/MG_NOWIN_research.pdf), and reviewer feedback [(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/unsuccessful/MG_NOTWIN_ViewApplReview.pdf) for my unsuccessful first attempt . And here are those same things (personal statement [(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/successful/mg.personal_2014.pdf), research proposal[(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/successful/mg.research.pdf), and reviewer feedback [(pdf)](https://github.com/R-Computing-Lab/handbook/blob/main/admin/masonmaterials/nsfgrfp/successful/mg.ViewApplReview.pdf)) for my successful 2nd attempt. 

<!--chapter:end:0902_funding.Rmd-->






# Career Resources

## Motivation

I had a tough time finding examples of job materials for quantitatively-inclined candidates. Here are representative examples from my own materials. Hopefully, they'll be able to help inspire your own materials. In addition, I've added some of the other resources and information that I found helpful. Although this collection has focused on academic jobs, I also considered industry jobs in my search.


## Academic Jobs

### General Advice

- The Professor Is In: [Blog](http://theprofessorisin.com/) and [Book](https://smile.amazon.com/gp/product/0553419420)

- American Psychological Association [APA Career Resources](https://www.apa.org/careers/resources/academic/)

- [Pennycook, G. & Thompson, V. A. (2018). An analysis of the Canadian cognitive psychology job market (2006-2016). Canadian Journal of Experimental Psychology, 72, 71-80.](https://psyarxiv.com/mxa35)
- Jaremka, L. M., Ackerman, J. M., Gawronski, B., Rule, N. O., Sweeny, K., Tropp, L. R., Metz, M. A., Molina, L., Ryan, W. S., & Vick, S. B. (2020). Common Academic Experiences No One Talks About: Repeated Rejection, Impostor Syndrome, and Burnout. Perspectives on psychological science : a journal of the Association for Psychological Science, 15(3), 519–543. https://doi-org.go.libproxy.wakehealth.edu/10.1177/1745691619898848
- [Boysen, G. A., Morton, J., & Nieves, T. (2019). Kisses of Death in the Psychology Faculty Hiring Process. Teaching of Psychology, 46(3), 260–266. ](https://journals.sagepub.com/doi/abs/10.1177/0098628319853942)

- Bureau of Labor Statistics on [STEM crisis or STEM surplus? Yes and yes](https://www.bls.gov/opub/mlr/2015/article/stem-crisis-or-stem-surplus-yes-and-yes.htm)
- [What are the chances of becoming a Psychology Professor?](http://geekpsychologist.com/what-are-the-chances-of-becoming-a-psychology-professor/stem-surplus-yes-and-yes.htm)
    - [(archived link)](http://webcache.googleusercontent.com/search?q=cache:M-P4L1Xj8XoJ:geekpsychologist.com/what-are-the-chances-of-becoming-a-psychology-professor/&hl=en&gl=us&strip=0&vwsrc=0)

- Washington Post on [The academic job market is a nightmare](https://www.washingtonpost.com/outlook/2019/04/15/job-market-academics-is-nightmare-heres-one-way-fix-it/)
- Jeremy Yoder on [I Found a Tenure-Track Job. Here's What it Took](https://chroniclevitae.com/news/1775-i-found-a-tenure-track-job-here-s-what-it-took)

### Materials

#### Cover letter
- [How To Write Academic Job Cover Letters from The Professor Is In](https://theprofessorisin.com/category/how-to-write-academic-job-cover-letters/)

#### Teaching Statements
- [Vanderbilt Center for Teaching on Teaching Statements]( https://cft.vanderbilt.edu/guides-sub-pages/teaching-statements/)
- [Writing a Teaching Philosophy Statement by Helen G. Grundman](http://www.ams.org/notices/200611/comm-grundman.pdf)
- [University of Arizona on Writing Diversity Statements](https://postdoc.arizona.edu/content/writing-diversity-statements)

#### Research Statements

#### Diversity Statements
- [The Effective Diversity Statement from InsideHigherEd](https://www.insidehighered.com/advice/2016/06/10/how-write-effective-diversity-statement-essay)
- [Beck, S. L., (2018). Developing and writing a diversity statement. Vanderbilt University Center for Teaching](https://cft.vanderbilt.edu/guides-sub-pages/developing-and-writing-a-diversity-statement/)

#### Example Materials

- UCSF [Samples for Academic Positions](https://career.ucsf.edu/grad-students-postdocs/career-planning/academic-jobs/applying/academic-samples)
- [Plasticity in Neurodevelopment Lab](https://www.plasticityinneurodevelopmentlab.com/for-academics)
- [Mine](https://github.com/R-Computing-Lab/handbook/tree/main/admin/masonmaterials)


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/Psychology?src=hash&amp;ref_src=twsrc%5Etfw">#Psychology</a> folks on the <a href="https://twitter.com/hashtag/jobmarket?src=hash&amp;ref_src=twsrc%5Etfw">#jobmarket</a> -- I&#39;ve uploaded all my job search materials including teaching, research and diversity statements to my <a href="https://twitter.com/OSFramework?ref_src=twsrc%5Etfw">@OSFramework</a> page. I hope that they might be helpful <a href="https://t.co/uuieRolpq8">https://t.co/uuieRolpq8</a> in these weird times. <a href="https://twitter.com/AcademicChatter?ref_src=twsrc%5Etfw">@AcademicChatter</a></p>&mdash; Prof. Mason Garrison 🌈💫✨ (@SMasonGarrison) <a href="https://twitter.com/SMasonGarrison/status/1311458554101063683?ref_src=twsrc%5Etfw">October 1, 2020</a></blockquote>

```

### Interviews

-  UConn's Common Academic Interview Questions (https://career.uconn.edu/wp-content/uploads/sites/7/2014/12/common-academic-inteview-questions.pdf)
- https://www.vitae.ac.uk/researcher-careers/pursuing-an-academic-career/applying-for-academic-jobs/commonly-asked-questions-in-academic-interviews#general-research-questions
- 
### Job Talk

- [Boysen, G. A., Jones, C., Kaltwasser, R., & Thompson, E. (2018). Keys to a successful job talk: Perceptions of psychology faculty. Teaching of Psychology, 45(3), 270-277.](https://journals.sagepub.com/doi/full/10.1177/0098628318779277)


### Negotiating


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">1. People are interviewing for jobs, which means that soon people will be negotiating offers. Here is a thread about some of my experiences doing so:</p>&mdash; Dr. Larisa, Assistant (to the) Regional Professor (@samclab) <a href="https://twitter.com/samclab/status/1460959264936239108?ref_src=twsrc%5Etfw">November 17, 2021</a></blockquote>

```



## Industry



```
#> Error in tweet_blockquote(tweet_url = tweet_url, maxwidth = maxwidth,  : 
#>   Forbidden (HTTP 403).
```

## Finding Jobs

### Academic
- [APA PsychCareers](https://www.psyccareers.com/search)
- [APS Employment Network](https://jobs.psychologicalscience.org/)
- [HigherEd Jobs](https://www.higheredjobs.com/faculty/search.cfm?JobCat=91)
- [Psych Jobs Wiki](http://psychjobsearch.wikidot.com/)
- [SMEP Job Postings](https://smep.org/resources/positions-available)
- [Society for Math Psych](http://www.mathpsych.org/index.php?option=com_content&view=category&layout=blog&id=34&Itemid=62)
- [SPSP](https://my.spsp.org/Careers/Job-Search)
- [Times Higher Education](https://www.timeshighereducation.com/unijobs/en-us/listings/psychology/)



### Industry
Most data-savvy companies have a careers page. I've included some of those pages here of companies I applied to, were recruited by, or would be interested in working for. There are also job boards, which companies post positions on. There's some overlap, but not 100%.

#### Specific Companies
- [23andMe](https://www.23andme.com/careers/)
- [ACT](https://careers-act.icims.com/jobs/)
- [Amazon](https://www.amazon.jobs/en/job_categories/data-science)
- [Ancestry](https://careers.ancestry.com/us/en)
- [ETS](https://www.ets.org/careers)
- [Facebook](https://www.facebook.com/careers/jobs)
- [Google](https://careers.google.com/)
- [Houghton Mifflin Harcourt](https://careers.hmhco.com/key/educational-measurement-jobs.html)
- [ITHAKA (JSTOR, Ithaka S+R, Portico)](https://www.ithaka.org/career-opportunities)
- [New York Times](https://www.nytco.com/careers/)
- [Pearson](https://pearson.jobs/)
- [Pew Research Center](https://jobs-prc.icims.com/jobs/)
- [RAND](https://www.rand.org/jobs.html)
- [SSRS](https://ssrs.com/careers/)
- [W. W. Norton & Company](https://wwnorton.com/careers/current-openings)

#### Job Postings
- [Glassdoor](https://www.glassdoor.com)
- [Indeed](https://www.indeed.com/)
- [USA Jobs (US Government Jobs)](https://www.usajobs.gov/)


## Random Wisdom


```{=html}
<blockquote class="twitter-tweet" data-width="550" data-lang="en" data-dnt="true" data-theme="light"><p lang="en" dir="ltr">Interesting discussion over on <a href="https://twitter.com/rOpenSci?ref_src=twsrc%5Etfw">@rOpenSci</a> forum 🍿<br><br>&quot;Workflow best practices&quot; 🧰 <a href="https://twitter.com/hashtag/RStats?src=hash&amp;ref_src=twsrc%5Etfw">#RStats</a><a href="https://t.co/60QeCwiYsC">https://t.co/60QeCwiYsC</a><br><br>With insights by <a href="https://twitter.com/noamross?ref_src=twsrc%5Etfw">@noamross</a> <a href="https://twitter.com/MilesMcBain?ref_src=twsrc%5Etfw">@MilesMcBain</a> <a href="https://twitter.com/benmarwick?ref_src=twsrc%5Etfw">@benmarwick</a></p>&mdash; Maëlle Salmon (@ma_salmon) <a href="https://twitter.com/ma_salmon/status/1471375120941916161?ref_src=twsrc%5Etfw">December 16, 2021</a></blockquote>

```

<!--chapter:end:0903_career.Rmd-->

# (PART) Back Matter {-}



# References {-}


<!--chapter:end:9999_references.Rmd-->

