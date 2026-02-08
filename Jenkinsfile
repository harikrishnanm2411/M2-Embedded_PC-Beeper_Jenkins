pipeline {
    agent any

    parameters {
        string(defaultValue: "TEST", description: "Which Environment?", name: "EnvironmentVarialbne")
    }

    stages {
        stage("foo") {
            steps {
                echo "flag: ${params.EnvironmentVarialbne}"
            }
        }
    }
}


