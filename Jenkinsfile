pipeline {

	agent jenkinsagent
	
	stages {
  		stage("build") {
  			steps {
				    println "gem build command"	
      			sh "gem build hwgem.gemspec"
      		}
		  }	
	}
    
}
