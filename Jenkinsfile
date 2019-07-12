node{
    checkout scm
    stage('Stage 1'){
        
        echo 'Hello World'
    }
    stage('Stage 2: Library Test'){
         def thing = load 'Thing.groovy'
         echo thing.doStuff()
    }
    
}