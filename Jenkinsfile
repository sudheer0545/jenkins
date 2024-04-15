pipeline {
    agent any
    stages {
        stage {
            when('Build') {
                // execute this stage only for Pull requests
                expression { return env.CHANGE_ID != null }
            }
            steps {
                echo " this is running on PR"
            }
        }
    }
}
