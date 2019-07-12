node ('master')
{
    stage('contous download')
    {
        git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('contous build')
    {
        sh label: '', script: 'mvn package'
    }
    
    
}

