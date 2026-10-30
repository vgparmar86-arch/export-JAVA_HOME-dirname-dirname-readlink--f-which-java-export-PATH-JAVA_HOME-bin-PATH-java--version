# export-JAVA_HOME-dirname-dirname-readlink--f-which-java-export-PATH-JAVA_HOME-bin-PATH-java--version
export JAVA_HOME=$(dirname $(dirname $(readlink -f $(which java)))) export PATH=$JAVA_HOME/bin:$PATH java -version
