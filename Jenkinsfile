pipeline {
  agent any


environment {
        def myString = "Hello World"
        def mynumber = 10
        def myBool = true
    }

    stages {
        stage("Demo") {
            steps {
                echo "string: ${myString}"
                echo "mynumber: ${mynumber}"
                echo "mybool: ${myBool} "
            }
        }
    }
}

