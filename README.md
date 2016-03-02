# DEPENDENCIES #

### HERE IS THE LIST OF ALL DEPENDENCIES TO THE PROJECT ###

List of Required JAR Files and where they Can be found

# SLF4J <a href='http://www.slf4j.org/'>link</a>
  * slf4j-api-1.7.5.jar
  * slf4j-simple-1.7.5.jar

# Apache Commons Logging <a href='http://commons.apache.org/proper/commons-logging/download_logging.cgi'>link</a>
  * commons-logging.jar

# Apache POI - the Java API for Microsoft Documents <a href='http://poi.apache.org/download.html'>link</a>
  * poi-3.10.jar

# FREE TTS <a href='http://sourceforge.net/projects/freetts/files/'>link</a>
  * Get all Files

#Stanford NLP <a href='http://nlp.stanford.edu/'>link</a>
  * stanford-corenlp-2011-09-14-models.jar
  * stanford-corenlp-2011-09-14.jar
  * stanford-tregex.jar
  * xom.jar
  * joda-time.jar


# Illinois WordNet Similarity <a href='http://cogcomp.cs.illinois.edu/page/software_view/Illinois%20WNSim%20(Java)'>link</a>
  * WNSim.jar
  * jwnl.jar

### OTHER DEPENDENCIES ###

# WORDNET
The wordNet similarity Module Requires WordNet download and Provide the PATH to in wordnet.xml as a part of Illinois WordNet Similarity project.



## HOW TO ##


# You can Tweak Configuration Parameters in `edu.ncsu.csc.ase.dristi.configuration.Configuration.java`
  * The names of the parameters are self explanatory

# The entry method is `main` method in `edu.ncsu.csc.ase.dristi.Whyper.java`
  * Before that do set the variable "`Permission permission`" to required permission enum.
  * Finally only the first Sentence is considered so provide input sentence by sentence