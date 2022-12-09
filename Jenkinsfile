pipeline{        
	agent any        
	tools{        
		maven "maven3"        
		jdk "jdk8"    
	}        
	
	stages{        
		stage('Fetch code') {          
			steps{              
				git branch: 'vp-rem', url:'https://github.com/devopshydclub/vprofile-repo.git'          
			}          
		}                
		
		stage('Build code') {          
			steps{              
			}          
		}    
	}
}
