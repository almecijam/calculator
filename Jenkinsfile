pipeline {
    stage('Build'){
        steps {
            sh './gradlew compileJava'
        }
    }

    stage('Test'){
        steps {
            sh './gradlew test'
        }
    }
}