# HowToScience
A knowledge engine for new students of bioinformatics.

##Installing

git clone https://github.com/Adamtaranto/HowToScience.git

cd HowToScience

sudo cp siri /usr/local/bin/

sudo cp ggl /usr/local/bin/

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

