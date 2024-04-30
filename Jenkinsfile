pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the Git repository
                git branch: 'main', url: 'https://github.com/SnehaSSP/amazingApril.git'
            }
        }
        
        stage('Run Python Scripts') {
            steps {
                // Run the first Python script
                sh 'Mytest_lab.py'
                
                // Run the second Python script
                sh 'lab3.py'
            }
        }
    }
}
