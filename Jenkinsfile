def build = null
pipeline {
    agent any
    environment { AWS_DEFAULT_REGION = 'us-east-1' }
    stages {
        stage('done')   { steps { sh 'echo "done"' } }

    }
    post {
        // Clean after build
        always {
            cleanWs(cleanWhenNotBuilt: false,
                    deleteDirs: true,
                    disableDeferredWipeout: true,
                    notFailBuild: true,
                    patterns: [[pattern: '.gitignore', type: 'INCLUDE'],
                               [pattern: '.propsfile', type: 'EXCLUDE']])
        }
    }
}
