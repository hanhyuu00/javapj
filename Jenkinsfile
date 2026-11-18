
pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                bat '"C:\\Program Files\\Eclipse Adoptium\\jdk-21.0.13.9-hotspot\\bin\\javac.exe" HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running...'
                bat '"C:\\Program Files\\Eclipse Adoptium\\jdk-21.0.13.9-hotspot\\bin\\java.exe" HelloWorld'
            }
        }
    }
}
