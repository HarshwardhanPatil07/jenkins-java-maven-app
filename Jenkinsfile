// CODE_CHANGES = getGitChanges()

pipeline {
    agent any
    stages {
        stage("build") {
            // when{
            //     expression{
            //         BRANCH_NAME == 'dev' && CODE_CHANGES == true
            //     }
                
            }
            steps {
                script {
                    echo "building the application"
                }
            }
        }
        stage("Test") {
            steps {
                script {
                    echo "Testing the application"
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying the application"
                }
            }
        }
    }   
}
