pipeline {
    agent any

    stages {
        stage("Clone Repository") {
            steps {
                git "https://github.com/Aditya-1422/Git-Jenkins-Pipepline.git"
            }
        }

        stage("Build") {
            steps {
                sh "./hello.sh"
            }
        }
    }
}