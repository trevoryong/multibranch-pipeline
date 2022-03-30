pipeline {
        agent   any

        stages{
                stage('echo-stage'){
                steps{
                 echo "Hello "
                }
                }
                stage('cat READ'){
                 when{
                  branch "fix-*"
                 }
                  steps{
                   sh ' cat README.md '
                  }
                }

        }
}

