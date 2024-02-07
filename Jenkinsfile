node {
  stage('Checkout') {
    git ''
  }
  stage('Build') {
        sh 'mvn clean package'
    }

    stage('Echo') {
        echo 'Build finished successfully!'
    }
}
