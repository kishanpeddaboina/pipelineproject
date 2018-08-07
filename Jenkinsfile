pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
pipeline {
agent any

    stages {
    stage("install_apache2")
       steps {
         sh "chmod 777 apache2.sh"
         sh "apache2.sh"
       }
}
}
