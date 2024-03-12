pipeline {
      agent any
      stages {
            stage('Checkout') {
                  steps {
                        git branch: 'develop', url: 'https://github.com/Sanju0211/addressbook.git'
                  }
            }
            stage('Pull to Folder') {
                  steps {
                        sh 'mkdir folder'
                        sh 'cp README.md folder'
                  }
            }
      }
}
