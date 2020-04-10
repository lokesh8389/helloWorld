node{
    stage('SCM Checkout'){
        git 'https://github.com/lokesh8389/helloWorld'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
