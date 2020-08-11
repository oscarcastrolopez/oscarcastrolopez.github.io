
notebook_covid19_esp.html : notebook_covid19.Rmd
	Rscript -e 'rmarkdown::render("notebook_covid19.Rmd")'
	mv notebook_covid19.html "notebook_covid19_esp_"`date +"%d-%m-%Y"`".html"