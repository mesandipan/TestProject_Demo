def workspace;
node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '007196d0-1a23-4f2e-9815-a6db6bc677b8', url: 'https://github.com/mesandipan/TestProject_Demo.git']]])
        workspace=pwd()
    }
    stage('static code analysis')
    {
        echo "static code analysis"
    }
    stage('Build')
    {
        echo "Build the code"
    }
    stage('Unit Testing')
    {
        echo "Unit Testing"
    }
    stage('Delivery')
    {
        echo "Delivery the code"
    }
}
