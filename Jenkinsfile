pipeline 
{
    agent any
    stages
    {
        stage ('from git')
        {
            steps {
                git "https://github.com/yuvamanoj/Devops.git"
            }
        }
            
        
        stage ('package')
        {
            steps
            {
                sh 'mvn package'
            }
            
        }
        stage ('tet')
        {
            steps
            {
                   sh 'mvn test'
            }
         
        }
        
        
    }
}
