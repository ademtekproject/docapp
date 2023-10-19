pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''sudo docker login -u sandeep5a6 -p "dckr_pat_FiYpyD4aFYkFIH2tMEVDMed0U0U"
sudo docker build -t sandeep5a6/myrepo2:$BUILD_NUMBER .
sudo docker push sandeep5a6/myrepo2:$BUILD_NUMBER'''
      }
    }

  }
}