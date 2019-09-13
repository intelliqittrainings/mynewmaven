node('master')
{
    stage('ContinuousDownloadi:Master') 
    {
       git 'https://github.com/intelliqittrainings/maven.git'
    }
    stage('ContinuousBuild:Master')
    {
        sh label: '', script: 'mvn package'
    }
    }
