pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                 bat 'C:\\Program Files\\Apache\\maven\\bin\\mvn -B -DskipTests clean package' 
            }
        }
    }
}
