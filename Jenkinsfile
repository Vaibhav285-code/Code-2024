pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/Vaibhav285-code/Code-2024.git' 
		echo 'This is Build Stage.'
                echo 'This is Jenkins Job'
                sh '''echo "this is shell script step"
                cd /var/lib/jenkins/workspace'''
            }
        }
        stage('Test') {
            steps {
                echo 'This is Test Stage.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is Deploy Stage.'
            }
        }
    }
}
