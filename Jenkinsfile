node{
    stage('helloWorld'){
        echo 'Hello World'
    }
    stage('SCM Checkout'){
        git 'https://github.com/lokesh8389/helloWorld'
    }
    stage('hello World'){
        echo 'Check Out Done'
    }
    stage('Compile-Package'){
        mvn package
    }
}
