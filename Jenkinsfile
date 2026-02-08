pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
    }

    stages {
        stage("foo") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
    }
}


docker exec b1a1e372723c cat /var/jenkins_home/secrets/initialAdminPassword
