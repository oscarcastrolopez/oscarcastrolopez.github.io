
notebook_covid19_eng.html : notebook_covid19.Rmd
	Rscript -e 'rmarkdown::render("notebook_covid19.Rmd")'
	mv notebook_covid19.html "notebook_covid19_eng_"`date +"%m-%d-%Y"`".html"
