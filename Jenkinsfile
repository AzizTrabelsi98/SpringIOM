pipeline {
    agent any
    stages {
        stage('checkoutGIT') {
            steps {
                
                echo 'puling...';
                git branch : 'main',
                url:'https://github.com/AzizTrabelsi98/SpringIOM.git';
               
            }
        }
    }
}
