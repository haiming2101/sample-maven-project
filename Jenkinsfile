pipeline {
  agent any
stages {
  stage('maven install') {
    steps {
      // One or more steps need to be included within the steps block.
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
    // some block
      sh 'mvn clean install'
           }
    }
  }

}

}
