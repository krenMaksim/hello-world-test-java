$ java  -version

$ echo $JAVA_HOME

$ echo  $PATH

$ sudo update-alternatives --config java // to see all version java

with Program Manager find Java 8 jdk install OR unpack jdk-8uversion-linux-x64.tar.gz to  /usr/lib/jvm/
  
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
export PATH=$JAVA_HOME/bin:$PATH

// in ./hello-world-test-java
git clone https://github.com/krenMaksim/hello-world-test-java.git

$ javac ./testJavaTerminal/HelloWorld.java
$ java testJavaTerminal.HelloWorld
