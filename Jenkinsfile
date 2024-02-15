pipeline {
    agent any

    stages {
        stage('Récupération du code source') {
            steps {
                // Cette étape clone le référentiel Git
                git 'https://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@github.com/Eya-Haffar/jenkinsProject.git'
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
#