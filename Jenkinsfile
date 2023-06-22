pipeline {
    agent any
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
