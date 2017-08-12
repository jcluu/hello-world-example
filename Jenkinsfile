node('master') {
    checkout scm
    stage('build') {
        // some block
        withMaven(jdk: 'Default JDK 8u144', maven: 'Default Maven') {
            // some block
            sh "mvn clean install"
        }
    }
}
