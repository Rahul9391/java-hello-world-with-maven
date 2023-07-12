node {
    stage('source code management'){
        //Getting code from git
        git branch: 'sprint1', url: 'https://github.com/Rahul9391/java-hello-world-with-maven.git'
    }
    stage('build package'){
        //building package
        sh 'mvn clean package'
    }
}
