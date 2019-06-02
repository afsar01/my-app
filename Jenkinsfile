
node {
      stage('SCM Checkout'){
    // Clone repo
	git branch: 'master', 
	credentialsId: 'github', 
	url: 'https://github.com/javahometech/myweb' 
   }      	
  
   stage('Email Notification'){
		mail bcc: '', body: 'welcome to jenkins job mail notification', cc: '', from: '', replyTo: '', subject: 'jenkins jobs', to: 'skkings03@gmail.com'
		                         
   }
}

