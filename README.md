# English-to-Indian-Sign-Language
The project runs on jupyternotebook.
The main project file is a python file.
The code is present in code.docx rename it as code.py .

The dependencies for this project are:
First java needs to be installed from here https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
download the jdk for windows and set up the environment variable.
Add the java.exe part from progam files in the system environment variable named JAVA_HOME.

Now set up all the Stanford parser dependencis:
1.Download Stanford Named Entity Recognizer (NER) https://nlp.stanford.edu/software/stanford-ner-2018-10-16.zip and unzip
2.Downoad Stanford Part-Of-Speech Tagger https://nlp.stanford.edu/software/stanford-postagger-full-2018-10-16.zip
3.Download Stanford Parser Models https://nlp.stanford.edu/software/stanford-english-corenlp-2018-10-05-models.jar
4.Download Stanford Parser https://nlp.stanford.edu/software/stanford-parser-full-2018-10-17.zip and unzip
After downloading all this put all these downloads in a new folder.

Add these paths with the name CLASSPATH and STANFORD_MODELS in the system envirionment variables:

CLASSPATH = your_path\stanford-parser-full-2017-06-09; your_path\stanford-ner-2017-06-09; your_path\stanford-postagger-full-2017-06-09; your_path\stanford-parser-full-2017-06-09\stanford-parser.jar;

STANFORD_MODELS = your_path\stanford-postagger-full-2017-06-09\models; your_path\stanford-ner-2017-06-09\classifiers

the dates that are mentioned above depend on the time of download. The paths for CLASSPATH are from files 4,2,4 again with jar file also included.
The paths for STANFORD_MODELS are from files 1,2.
