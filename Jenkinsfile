pipeline {
    agent any
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting} World!"
            }
        }
        stage('Next_Stage') {
            steps {
                echo "Step 1"
            }
            steps {
                echo "Step 2"
            }
        }
    }
}
