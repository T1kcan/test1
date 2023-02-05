pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "TCH the first step"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
		echo "hiii"
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
    }
}
