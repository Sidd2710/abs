node('master')
{
    stage('ContinuousDownload in master') 
    {
         git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('ContinuousBuild in master') 
    {
         sh label: '', script: 'mvn package'
    }
    
    
    
}

