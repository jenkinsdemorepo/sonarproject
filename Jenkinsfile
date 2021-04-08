                sh """
                echo "Running Code Analysis"
                """
            }
        }
        stage('Build Deploy Code') {
            when {
                branch 'dev'
            }
            steps {
                sh """
                echo "Building Artifact"
                """
                sh """
                echo "Deploying Code"
                """
            }
        }
    }   
}
