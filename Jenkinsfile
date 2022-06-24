pipeline {
    agent any
    parameters {
        string(name: 'Greet', defaultValue: 'Sreekanth')
        string(name: 'Age', defaultValue: '100')
    }
    stages {
        stage('Greeting') {
            steps {
                echo "Welcome ${params.Greet}"
            }
        }
        stage('Age') {
            steps {
                echo "Your age is ${params.Age}"
            }
        }
    }
}
