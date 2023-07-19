def build = null
pipeline {
    agent any
    environment { AWS_DEFAULT_REGION = 'us-east-1' }
    // post { always { script { build.postScript() } } }
    // stages {
    //     stage('Load Library')   { steps { script { build=load 'jenkins/build.groovy' } } }
    //     stage('Build Deps')     { steps { script { build.installDeps()               } } }
    //     stage('Build Assets')   { steps { script { build.buildAssets()               } } }
    //     stage('Run Tests')      { steps { script { build.runTests()                  } } }
    //     // stage('Cypress Tests')  { steps { script { build.runCypress()                } } }
    //     // stage('Lacework Scan')  { steps { script { build.scanImage()                 } } }
    //     stage('Extract Assets') { steps { script { build.extractAssets()             } } }
    //     stage('Upload to S3')   { steps { script { build.uploadToS3()                } } }
    // }
}
