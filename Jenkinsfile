pipeline{
    agent {
        label 'ws'
    }
    stages{
        stage('lint checks'){
            steps{
                sh "echo ***********Starting Style Checks****************"
               // sh "mvn checkstyle:check || true"
            }
        }    
        stage('Static Code Analysis'){
            steps{
                sh "echo ******** Starting Static Code Analysis *******"
                sh "echo welcome all to sonarcube"
            }
        }
    }
    
}


//shipping