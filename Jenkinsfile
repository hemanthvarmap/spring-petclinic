node {
    stage('scm'){
    // git clone
    git 'https://github.com/hemanthvarmap/spring-petclinic.git'

    }
    stage('build the package'){
    // mvn package
    sh label: '', script: 'mvn package'

    }
    stage('archival'){
    // archiving the artifacts
    archiveArtifacts 'target/*.jar'

    }
}