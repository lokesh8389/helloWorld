node{
    stage('helloWorld'){
        echo 'Hello World'
    }
    stage('SCM Checkout'){
        git 'https://github.com/lokesh8389/helloWorld'
    }
    stage('Compile-Package') {
        mvn 'clean package'
    }
}
