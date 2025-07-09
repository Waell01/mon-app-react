pipeline {
  agent any

  stages {
    stage('Clonage du code') {
      steps {
        git 'https://github.com/Waell01/mon-app-react.git'
      }
    }

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
