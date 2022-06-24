pipeline {
    agent any
    parameters {
        string(name: 'Greet', defaultValue: 'Sreekanth')
        string(name: 'Age', defaultValue: '30')
        string(name: 'SalaryPerMonth', defaultValue: '40000')
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
        stage('Salary Per Month') {
            steps {
                echo "Your Monthly Salary is ${params.SalaryPerMonth}"
            }
        }
    }
}
