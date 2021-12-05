node {
        stage('Clone') {
            git 'git@github.com:DECHACHETaousCHPS/jenkins.git'
        }
        stage('Build') {
            sh label: '', script: 'javac Main.java'
        }
        stage('Run') {
            sh label: '', script: 'java Main'
        }
}

