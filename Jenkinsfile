pipeline {
    agent any

    stages {

        stage('git checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/dvsp-projects/1.mrdevops_java_app.git'
                }
            }
        }
    }
}