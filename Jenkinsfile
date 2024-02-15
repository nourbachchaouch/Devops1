pipeline {
    agent any

    stages {
        stage('Récupération du code source') {
            steps {
                // Cette étape clone le référentiel Git
                git clone 'git@github.com:Eya-Haffar/jenkinsProject.git'
            }
        }

        stage('Affichage de la date système') {
            steps {
                // Cette étape affiche la date système
                script {
                    def date = sh(script: 'date', returnStdout: true).trim()
                    echo "La date système est : ${date}"
                }
            }
        }
    }
}
