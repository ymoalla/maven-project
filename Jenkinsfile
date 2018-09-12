pipeline {
     agent any
environment {
    PATH = "/home/vagrant/apache-maven-3.5.3/bin:$PATH"
  }
     stages{
       stage('Build'){
         steps{
           sh 'mvn clean package'
            
            }
  }
}
}

