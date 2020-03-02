node {
    stage('clone') {
        git 'https://github.com/buba4r/HelloWorld.git'
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('run') {
        sh label: '', script: 'java Main'
    }
}
