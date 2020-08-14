pipeline {
    agent any

    stages {
  
	stage('BUILD') {
            steps {
		    envVarsForTool() {
			    ANDROID_SDK_ROOT=/home/ubuntu/snap/androidsdk/current/AndroidSDK/
		    
		    
                sh 'flutter build apk'
		    }
            }
        }
    }
}

