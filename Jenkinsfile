pipeline {
agent any


stages {

    stage('Checkout Code') {
        steps {
            // Pull code from GitHub
            git branch: 'master', url: 'https://github.com/harikrishnanm2411/M2-Embedded_PC-Beeper_Jenkins.git'
        }
    }

    stage('Build') {
        steps {
            echo "Building project..."
            
            // Example build commands (change as per project)

            
        }
    }

    stage('Test') {
        steps {
            echo "Running tests..."
            
            
        }
    }

    stage('Deploy') {
        steps {
            echo "Deploy step..."
            // Add deploy script if needed
        }
    }
}

post {
    success {
        echo 'Build Successful!'
    }
    failure {
        echo 'Build Failed!'
    }
}


}
