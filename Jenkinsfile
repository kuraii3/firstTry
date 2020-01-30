node {
    stage('clone') {
        git 'https://github.com/kuraii3/firstTry.git'
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('run') {
        sh label: '', script: 'java Main'
    }
}
