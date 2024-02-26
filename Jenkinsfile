pipeline {
    agent any



    stages {
        stage('Git') {
            steps {
                git ' https://github.com/amrutha2607/amruthafeb26.git'
                sh 'java demo.java'
                sh 'python3 main.py'
            }
        }
    }
}
