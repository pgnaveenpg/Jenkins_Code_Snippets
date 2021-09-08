pipeline { 
agent any
    stages {
        stage('Clone git') {
            steps {
                git 'https://github.com/pgnaveenpg/Jenkins_Code_Snippets.git'
            }
        }
        stage('Build Code') {
            steps {
                sh "chmod u+x Prog1.py"
                sh "./Prog1.py"
            }
        }
     stage('Test Code') {
            steps {
                sh "chmod u+x Test.py"
                sh "./Test.py"
            }
        }
    } 
}
