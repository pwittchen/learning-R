# learning R
Repository created in order to learn basics of R language

Overview
--------
R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS.

Installation on Linux
---------------------

```
sudo apt-get update
sudo apt-get install r-base
```

After installation, just type: `R` in terminal and you should be able to use R language from command line.

Executing R file from a shell script
------------------------------------

You can define the `hello.R` file contents as follows:

```R
#!/usr/bin/Rscript
"Hello World in R!"
```

Now you can run the following command in terminal to execute the script:

`./hello.R`

IDE
---

[R Studio](http://www.rstudio.com/)

### Installation of R Studio on Linux

```
wget http://download1.rstudio.org/rstudio-0.98.1062-amd64.deb
sudo dpkg -i *.deb
sudo rm *.deb
```

R in the web
------------

[Shiny - a web application framework for R](http://shiny.rstudio.com/)

Resources
---------
- [Official website](http://www.r-project.org/)
- [Downloads, Manuals, Journal, FAQ, etc.](http://r.meteo.uni.wroc.pl/)
- [Manuals](http://r.meteo.uni.wroc.pl/manuals.html)
- [Tutorial at cyclismo.com](http://www.cyclismo.org/tutorial/R/)
- [Interactive tutorial at codeschool.com](http://tryr.codeschool.com/)
- [Data Camp](https://www.datacamp.com/)
- [Introduction to Programming in R](https://www.teamleada.com/tutorials/introduction-to-statistical-programming-in-r)
- [Beginner's guide to R](http://www.computerworld.com/article/2497143/business-intelligence/business-intelligence-beginner-s-guide-to-r-introduction.html)
- [Advanced R](http://adv-r.had.co.nz/)
- [Programowanie w języku R - książka PWN [PL]](http://rksiazka.rexamine.com/)
- [Programowanie w języku R - materiały uzupełniające [PL]](https://github.com/gagolews/Programowanie_w_jezyku_R)
