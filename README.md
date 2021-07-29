# module3
The data I used was from https://public.tableau.com/app/profile/bo.mccready8742/viz/FilmGenrePopularity-1910-2018/GenreRelativePopularity
This data show film genre popularity from 1910 to 2018. The awk script stores each line of data into an array and prints the first 10 years of film genre popularity.
The awk script is in a file called "count.awk". 
Inside the shell script is a command to run the awk script
to create a shell script, type in the command vi *filename*.sh
Inside your shell script the very top should have #!/bin/sh
the command to run the shell script is awk -f *awkscript name* *path to csv file, or the name of the csvfile if you have it in your text editior*
for example my command is "awk -f count.awk Musicals_data.csv"
after exiting out of your shell script to run the actual shell script you type in the command 
./*filename*.sh
for me the command was ./demo.sh
Shell script, Vim and awk has to be installed to run the script if your text editior doesnt already have it installed.
