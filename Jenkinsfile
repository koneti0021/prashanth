pipeline {
    agent none
    
    stages{
        stage('codecheckout'){
            agent { label 'master'}
            steps {
                script{
                    sh "echo hello "
                }
            }
        }
        stage('build'){
            agent { label 'master'}
            steps {
                script{
                    sh "echo build "
                }
            }
        }
		stage('Test'){
            agent { label 'master'}
            steps {
                script{
                    sh "echo Test "
                }
            }
        }
        stage('Deploy'){
            agent { label 'master'}
            steps {
                script{
                    sh "echo Test "
                }
            }
        }
        stage('Release'){
            agent { label 'master'}
            steps {
                script{
                    sh "echo Test "
                }
            }
        }
    }
}
