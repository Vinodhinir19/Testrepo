node{
	stage('SCM Checkout'){
            
	    git 'https://github.com/Vinodhinir19/Testrepo'
		}
	stage('Compile-Package'){
		def mvnHome = tool name: 'Maven1', type: 'maven'
		sh "${mvnHome}/bin/mvn package"		
	}
	}
