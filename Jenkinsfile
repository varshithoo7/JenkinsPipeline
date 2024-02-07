node {
  stage('Checkout') {
    git 'https://github.com/varshithoo7/JenkinsPipeline.git'
    echo 'Checkout Successful .................'
  }
  stage('Build') {
        echo 'mvn clean package'
    }

    stage('Echo') {
        echo 'Build finished successfully.......'
    }
}
