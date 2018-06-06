library "gcloud-pipeline-library"
node('ubuntu'){
  stage ('Unit Tests') {
    checkout scm
    sh './vendor/bin/simple-phpunit'
  }
}
