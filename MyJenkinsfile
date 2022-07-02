pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                print "Hello This is a test pipeline"
            }
        }
            stage('DevBuild') {
            steps {
                print "Hello This is a Dev build stage"
                git branch: 'main', credentialsId: 'IDForGithubCredential', url: 'https://github.com/Tusarprogrammer/GroovyTrainingDay6'
            }
        }
        
        stage('SitBuild') {
            steps {
                print "Hello This is a Dev build stage"
            }
        }
        stage('UatBuild') {
            steps {
                print "Hello This is a Dev build stage"
            }
        }
        stage('ProdBuild') {
            steps {
                print "Hello This is a Dev build stage"
            }
        }
        stage('ProdDeployment') {
            steps {
                print "Hello This is a Dev build stage"
            }
        }
        
    }
}
