/* declarative pipeline is relatively new to jenkins
  it offers a pipeline by code technique without requiring
  the groovy learning curve */
pipeline {
  // the agent we wish to choose
  agent { label 'java-docker-worker' }
  // a step lives inside of a stage
  stages {
    // our first (only) stage is "build"
    stage('build') {
        steps {
            sh 'python3 --version'  // determine version of python avail
            }
        }
    }
}
