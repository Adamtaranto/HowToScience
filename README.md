# HowToScience
A knowledge engine for new students of bioinformatics.

##Installing

git clone https://github.com/Adamtaranto/HowToScience.git

sudo ln -s HowToScience/siri /usr/local/bin/siri

sudo ln -s HowToScience/ggl /usr/local/bin/ggl

##Updating

From 'HowToScience' directory..

git pull origin master

##Usage 
###Be asked a question:

siri

ggl

###Ask a question:

siri Should I annotate my genome in MS Word?

ggl how to science?

###Use stdin to pass question strings:

(actually useful for piping error messages to google)

cat pipeme.txt | ggl

