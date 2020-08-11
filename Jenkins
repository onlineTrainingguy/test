node
{
    stage('git')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/onlineTrainingguy/test.git']]])
        def workspace=pwd()
    }
    stage('1')
    {
        echo "1"
    }
    stage('2')
    {
        echo "2"
    }
    
}
