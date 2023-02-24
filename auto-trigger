pipeline {
			agent any
			
			stages {
						stage ('shutdown'){
						
							steps {
							
								build 'shutdown'
											
							}
						}
						
						stage ('build'){
						
							steps {
							
									build 'Compile-code'
											
							}
						}
						
						stage ('copy'){
						
							steps {
											build 'copy-war'
'
							}
						}
						
						stage ('dev-deploy'){
						
							steps {
											build 'deploy-dev'
							}
						}
						
						stage ('qa-deploy'){
						
							steps {
											build 'deploy-qa'
							}
						}
			}
}

