pipeline{
    agent {
        label 'debian-agent1'
    }
    tools{
        maven 'maven3'
        jdk 'jdk-11'
    }
    stages{
        stage('Clean Workspace'){
            steps{
                cleanWs(    )
            }
        }
    }
    stages{
        stage('Checkout  from scm'){
            steps{
                git branch: 'main', url: 'https://github.com/kuzi23/complete-prodcution-e2e-pipeline'
            }
        }

    }
}