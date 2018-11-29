node
{
    stage('checkout')
    {
        
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '4ee87f13-d4b5-476c-8437-ccc1b693e95d', url: 'https://github.com/VikramME/Jenkins.git']]])
        def workspace=pwd();
    }
    stage('static code analysis')
    {
        
        echo"Static code analaysis";
    }
    stage('testing')
    {
        echo"testing"
    }
    stage('deploy')
    {
        echo"deploy"
    }
}
