node('master')
{
    stage('ContinuousDownload in branch') 
    {
         git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('ContinuousBuild in branch') 
    {
         sh label: '', script: 'mvn package'
    }
    
    
    
}

