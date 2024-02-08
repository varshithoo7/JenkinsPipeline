node {
    stage('Checkout') {
        // Checkout code from version control system (e.g., Git)
        git 'https://github.com/example/repository.git'
    }
    
    stage('Build') {
        // Build your project (e.g., Maven, Gradle)
        echo 'mvn clean package'
    }
    
    stage('Test') {
        // Run tests (e.g., unit tests, integration tests)
        echo 'mvn test'
    }
    
    stage('Deploy') {
        // Deploy your application (e.g., to a server)
        echo 'scp target/my-application.war user@server:/path/to/deploy'
    }

    // Post-build actions
    try {
        echo 'Pipeline succeeded! Application deployed successfully.'
    } catch (Exception e) {
        echo 'Pipeline failed! Application deployment failed.'
    }
}
