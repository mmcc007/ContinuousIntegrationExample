pipeline {
  agent { label 'master' } 
  /*
    slsSetEnv('go', '1.8.1')
  environment {
        CC = 'clang'
	// Install the desired Go version
    	def root = tool name: 'Go 1.8.1', type: 'go'
    	// Export environment variables pointing to the directory where Go was installed
    	GOROOT=${root}
	PATH='${root}/bin'
	GO='${root}/bin'
    }
    */
  stages {
    stage('build') {
      steps {
        sh "echo build"
      }
    }
  }
}
