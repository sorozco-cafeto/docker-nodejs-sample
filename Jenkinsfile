pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo "hello from jenkisnfile second try"
            }
        }
        stage('for the fix branch') {
            when {
                    branch "fix-"
            }
            steps {
                sh '''
                cat README.md
                '''
            }
        }
        stage('for the PR') {
            when  {
                branch 'PR.*'
            }
                
        }
    }
}

