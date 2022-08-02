pipeline {
    agent any
    stages {
        stage('stage1') {
           steps {
                echo "Hi This is vikram"
                sh 'mkdir firstdir4'
                sh 'pwd'
                sh 'ls -lrt'
               sh 'date'
               sh 'whoami'
            }
}
        stage('stage2') {
            steps{
            echo 'this is stage2'
}
}
        stage('stage3') {
        steps{
            echo 'this is step3'
    }
        }
    }
}
