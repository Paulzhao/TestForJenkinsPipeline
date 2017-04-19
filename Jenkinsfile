node {
    stage "gitSCM"
    	checkout([$class: 'GitSCM', branches: [[name: '*/dev']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'e02fa7ef-2d72-4e57-8089-556a9e7a6d58', url: 'git@github.com:Paulzhao/TestForJenkinsPipeline.git']]])
    stage "build"
    	pwd()
    stage "content"
    	sh 'cat README.MD'
}
