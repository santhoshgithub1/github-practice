pipeline {
    agent {label 'master'}
    stages{
        stage ('build and test'){
            parallel {
                stage ('build'){
                    steps {
                        sh 'echo "running build"'
                    }

                }
                stage ('test'){
                    steps {
                        sh 'echo "running test"'
                    }
                }
            }

        }

             
    }
    stage ('deploy'){
        steps {
            sh 'echo "deploy stage"'
        }
    }
}           