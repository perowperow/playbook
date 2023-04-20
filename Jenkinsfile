pipeline {
    agent any

    stages {
        stage('Syntax Check') {
            steps {
                sh 'ansible-playbook --syntax-check /path/to/your/install_nginx.yml'
            }
        }
        stage('Run Playbook') {
            steps {
                sh 'ansible-playbook /path/to/your/install_nginx.yml'
            }
        }
    }
}
