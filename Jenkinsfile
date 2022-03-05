pipeline {
    agent {label ''}
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
}           