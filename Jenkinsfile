pipeline {
    agent any
    stages {
        stage('checkout from GIT'){
            steps{
                git branch: 'prod', url: 'https://github.com/bkrrajmali/enahanced-petclinc-springboot.git'
            }
        }
        stage('Test'){
            steps {
                echo"test"
            }
        }
        stage('Deploy') {
            steps {
               echo "deploy"
            }
        }
    }
}
