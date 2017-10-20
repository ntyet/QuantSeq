.PHONY : DataAnalysis.nb.html
DataAnalysis.nb.html: DataAnalysis.Rmd ../data/dat_4.rds  ../data/dat_7.rds  ../data/dat_11.rds ../data/dat_14.rds ../data/dat_28.rds ../data/dat_32.rds ../data/dat_35.rds ../data/dat_39.rds ../data/dat_42.rds ../data/dat_56.rds
	R -e "rmarkdown::render('DataAnalysis.Rmd', 'html_notebook', 'DataAnalysis.nb.html')"

DataPrep.nb.html ../data/dat_4.rds  ../data/dat_7.rds  ../data/dat_11.rds ../data/dat_14.rds ../data/dat_28.rds ../data/dat_32.rds ../data/dat_35.rds ../data/dat_39.rds ../data/dat_42.rds ../data/dat_56.rds: DataPrep.Rmd
	R -e "rmarkdown::render('DataPrep.Rmd')"