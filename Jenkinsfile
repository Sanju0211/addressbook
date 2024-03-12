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
                        sh 'git pull origin develop /c/users/lenovo/ProjectY/addressbook/folder'
                  }
            }
      }
}
