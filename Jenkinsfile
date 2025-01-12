pipeline{
    
    agent any
    
    stages{
        
        stage('Try catch'){
            steps{
                
                script{
                    
                    try{
                        sh 'exit 1'
                    }
                    
                    catch(Exception e){
                        echo 'error happens'
                    }
                }
            }
        }
    }
