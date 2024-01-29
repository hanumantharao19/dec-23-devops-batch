pipeline {
    agent any 
    
    parameters {
        string(name: 'name', defaultValue: '', description: 'Please provide your name')
        choice(name: 'hometown', choices: ['hyd', 'guntur', 'vijayawada'], description: 'please select your homw town')
    }
    
     stages{
        stage('your name'){
           steps {
               sh 'echo ${name}'
         } 
      }
      
       stage('your home town'){
           steps {
               sh 'echo ${hometown}'
         } 
      }
    }
}
