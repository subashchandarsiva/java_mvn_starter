MAC-Only

$ tar -xvf apache-maven-3.4.5-bin.tar.gz

Add the M2_HOME environment variable. Edit your ~/.bash_profile 

open -e ~/.bash_profile

Add the following exports

export M2_HOME=/Applications/apache-maven-3.4.5
export PATH=$PATH:$M2_HOME/bin





-----------

JDK

/usr/libexec/java_home, just export $JAVA_HOME in file ~/. bash_profile or ~/.profile.

$ vim .bash_profile
export JAVA_HOME=$(/usr/libexec/java_home)

$ echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/1.7.0.jdk/Contents/Home
