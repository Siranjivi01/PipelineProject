pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Its Build From GitHub Repo"
          	start file1.txt
            }
        }
        stage('Test') { 
            steps {
                echo "Its Build From GitHub Repo"
          	start file2.txt
            }
        }
        stage('Deploy') { 
            steps {
                echo "This File Sends a Artifacts to the tomcat server"
            }
        }
    }
}
