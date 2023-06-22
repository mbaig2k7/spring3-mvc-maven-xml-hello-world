pipeline {
    agent any
   environment {
        PATH = "/opt/apache-maven-3.9.2"
        }
    stages {
       /* stage("clone code") {
            steps {
                script {
                    // Let's clone the source
                    git 'https://github.com/alimelus/spring3-mvc-maven-xml-hello-world.git';
                }
            }
        }*/
         stage("mvn build") {
            steps {
                   sh 'mvn -v' 
                   sh 'mvn clean package'
                    
                }
        }
}
}
