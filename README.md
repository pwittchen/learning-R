# learning-R
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

Next, you can place the following contents in `hello.sh` file:

`Rscript ./hello.R`

You can also execute this command from terminal, if you want. In both cases, it will execute R script.

Resources
---------
- [Official website](http://www.r-project.org/)
- [Downloads, Manuals, Journal, FAQ, etc.](http://r.meteo.uni.wroc.pl/)
- [Manuals](http://r.meteo.uni.wroc.pl/manuals.html)
- [Tutorial at cyclismo.com](http://www.cyclismo.org/tutorial/R/)
- [Interactive tutorial on codeschool.com](http://tryr.codeschool.com/)
