pipeline {
  agent any

  tools {
    nodejs 'node17' 
  }

  stages {
    stage('Installation des dépendances') {
      steps {
        bat 'npm install'
      }
    }

    stage('Build de l\'application') {
      steps {
        sh 'npm run build'
      }
    }

    stage('Fin') {
      steps {
        echo ' Build terminé avec succès !'
      }
    }
  }
}
