pipeline {
    agent any
    stages {
        stage('Example Stage') {
            when {
                // Execute this stage only for Pull requests
                expression { return env.CHANGE_ID != null }
            }
            steps {
                echo "This is running on a Pull Request"
            }
        }
    }
}
