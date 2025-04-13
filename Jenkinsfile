pipeline {
    agent any 
    environment {
        PROJECT_NAME= "project neptun"
        OWNER_NAME= "Elik Idrisov"
    }
    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing......."
                echo "End of Stage Build"
                echo "Hello ${PROJECT_NAME}"
                echo "Owner: ${OWNER_NAME}"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Deploying......."
                sh '''
                    echo "lein1"
                    echo "lein2"
                '''
                echo "End of Stage Build"
            }
        }
        stage('4-Celebrate') {
            steps {
                echo "CONGRATULYACIYA!"
            }
        }    
    }
}
