pipeline {
    agent any
    stages {
        stage("cleanup"){
            steps {
                deleteDir()
            }
        }
        stage("clone repo"){
            steps {
                sh "git clone https://github.com/push005/practice.git"
            }
        }
        stage("build") {
            steps {
                dir("practice"){
                    echo "hello"
                }
            }
        }
        stage("test"){
            steps{
                dir("practice"){
                    echo "python"
                }
            }
        }
         stage("test"){
            steps{
                dir("practice"){
                    echo "GIT TEST"
                }
            }
        }
    }
}
