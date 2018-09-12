pipeline {
     agent any
environment {
    PATH = "/home/vagrant/apache-maven-3.5.3/bin"
  }
     stages{
       stage('Build'){
         steps{
		withEnv(['PATH+EXTRA=/usr/sbin:/usr/bin:/sbin:/bin']){
           sh '$PATH/mvn clean package'
}
            
            }
  }
}
}

