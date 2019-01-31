pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, This is Aditi'
            
                }
        }
        stage('Two') {
                steps {
                        sh 'cd /home/delhivery/Desktop/project-hq/caas/'
                        sh 'source ../.environments/caas_env/bin/activate'
                        sh 'python manage.py runserver'
                        sh 'python test_runserver.py'
            
                }
        }

    }
}
    