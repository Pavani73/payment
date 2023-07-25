pipeline {
  agent {
     node { label 'workstation' }
    }

   stages {

      stage('code Checkout') {
        steps {
          echo 'code checkout'
           }
      }

 /*build no need for python*/

    stage('UNIT TESTS') {
        steps {
           echo 'UNIT TEST'
           //sh 'python -m unittest'
            }
        }

    stage('CODE ANALYSIS') {
        steps {
          echo 'CODE ANALYSIS'
           }
        }

    stage('SECURITY SCAN') {
       steps {
          echo 'SECURITY SCAN'
          }
       }
    stage('PUBLISH A ARTIFACT WITH VERSION') {
       steps {
          echo 'PUBLISH A ARTIFACT WITH VERSION'
          }
      }

   }

}


