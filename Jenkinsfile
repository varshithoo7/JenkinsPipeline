node {
  stage('Checkout') {
    git 'https://github.com/varshithoo7/JenkinsPipeline.git'
  }
  stage('Build') {
        sh 'mvn clean package'
    }

    stage('Echo') {
        echo 'Build finished successfully!'
    }
}
