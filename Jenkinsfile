library "gcloud-pipeline-library"
def default_zone = 'europe-west1-b'
def project_id='workshop-gcp-195122'
node('ubuntu-test'){
  stage ('Unit Tests') {
    checkout scm
    sh './vendor/bin/simple-phpunit'
  }
}
