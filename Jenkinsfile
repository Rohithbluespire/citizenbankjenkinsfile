pipeline {
    agent any
    stages {
        stage('Bitbucket') {
            steps {
                script {
                    echo "Code Successfully Updated..."
                }
            }
        }
        stage('Maven') {
            steps {
                script {
                    echo "Packaging Code: Successfull..."
                }
            }
        }
        stage('SonarQube') {
            steps {
                script {
                    echo "Code quality Check: Successfull..."
                }
            }
        }
        stage('Docker') {
            steps {
                script {
                    echo "Docker image Build: Successfull..."
                }
            }
        }
        stage('Nexus') {
            steps {
                script {
                    echo "Image Push sucessfully into Nexus Repo: Successfull..."
                }
            }
        }
        stage('Openshift cluster') {
            steps {
                script {
                    echo "Succesfully Deployed into Cluster..."
                }
            }
        }
        stage('Openshift') {
            steps {
                script {
                    echo "Pod and Services are running..."
                }
            }
        }
        stage('Datadog') {
            steps {
                script {
                    echo "Log and Metrics created: succesfully..."
                }
            }
        }
    }
}
