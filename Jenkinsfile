pipeline {
    agent any
    stages {
        stage('stage1') {
           steps {
                 sh 'date'
                 sh 'ls -lrt'
                 sh 'rm -rf fir* '
                 sh 'pwd'
                 sh 'ls -lrt'
                echo "Hi This is vikram"
                echo "hello vikram how are you "
                sh 'mkdir firstdir99'
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
      stage('stage4') {
         steps{
           echo 'this is step4'
}
}
       stage('stage5') { 
         steps{
       echo 'thisis stage 3'
       echo 'hi hello'
        sh 'date'
}
}
    }
}




