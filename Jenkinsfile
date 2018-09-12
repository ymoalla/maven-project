pipeline {
     agent any
environment {
    PATH = "/home/vagrant/apache-maven-3.5.3"
  }
     stages{
       stage('Build'){
         steps{
           /bin/sh '$PATH/mvn clean package'
            
            }
  }
}
}

