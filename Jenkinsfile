
node {
      // Clone repo
	git branch: 'master', 
	credentialsId: 'github', 
	url: 'https://github.com/javahometech/myweb' 
   } 
	stage('compile-package')
	{
		def mvnhome = tool name: 'maven-3', type: 'maven'
		sh"${mvnhome}/bin/mvn package"
	}
  
   stage('Email Notification'){
		mail bcc: '', body: 'welcome to jenkins job mail notification', cc: '', from: '', replyTo: '', subject: 'jenkins jobs', to: 'skkings03@gmail.com'
		                         
   }
}

            
   }
}

