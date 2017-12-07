properties([[$class: 'GithubProjectProperty',
             displayName: '',
             projectUrlStr: 'https://github.com/naveenreddy5568/multibranchpipeline_repo.git/'],
             pipelineTriggers([githubPush()])])



pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo " This is Buildnnnnnnnnnnn Stage"
            }
        }
        stage('Test'){
            steps {
                echo "This is a Test Stage" 
            }
        }
        stage('Deploy') {
            steps {
                echo "This is a Deploy Stage"
            }
        }
    }
}
