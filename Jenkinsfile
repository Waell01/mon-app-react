pipeline {
  agent any

  stages {
   

    stage('Installation des dépendances') {
      steps {
        sh 'npm install'
      }
    }

    stage('Build de l\'application') {
      steps {
        sh 'npm run build'
      }
    }

    stage('Fin') {
      steps {
        echo 'Build terminé avec succès '
      }
    }
  }
}
