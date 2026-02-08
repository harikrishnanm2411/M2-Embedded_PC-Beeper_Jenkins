pipeline {
    agent any

    parameters {
        choice(choices: ["TEST", "DEV", "PROD"], description: "Which Environment?", name: "EnvironmentVarialbne")
    }

    stages {
        stage("foo") {
            steps {
                echo "string: ${params.EnvironmentVarialbne}"
            }
        }
    }
}


