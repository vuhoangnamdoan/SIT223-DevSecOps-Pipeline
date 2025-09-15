pipeline {
    // The 'agent any' line tells Jenkins that this pipeline can run on any available agent.
    agent any

    // The 'stages' block contains all the individual stages of the pipeline.
    stages {
        stage('Git Info') {
            steps {
                echo 'Getting commit information...'
                // The following command will print the most recent commit log.
                sh 'git log -1'
            }
        }
    }
}
