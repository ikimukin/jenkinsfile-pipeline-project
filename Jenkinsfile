pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'using POLL SCM'
                echo 'Compiling the Java source code,'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled Java code.'
                sh 'java Hello'
            }
        }
    }
}
