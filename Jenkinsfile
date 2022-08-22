pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, this is Guy Fonkouop from devops'
                 }
                 }
                 stage('Two') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 stage('Three') {
                
                 steps {
                       echo "Hello 3 --> build completed Congrat!!!"
                 }
                
              }
         }
}
