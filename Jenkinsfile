node('UBUNUTU'){
    stage('GIT'){
        https://github.com/harikumar430/jenkinsbuildpractice.git
    }
    stage('package'){
        sh 'mvn package'
    }
    stage('archiveartifact'){
        archive 'gameoflife-web/target/*.war'
    }
}