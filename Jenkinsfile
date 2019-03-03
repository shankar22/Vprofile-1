pipeline{
    agenet any
    stages{
        stage('SCM Checkout'){
           steps{
              sh "https://github.com/mendeshiva/Vprofile-1.git"
           }
      }     
        stage('Buile code'){
           steps{
             sh "mvn package"
        }
      }
    }
}
