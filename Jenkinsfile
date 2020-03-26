pipeline {
    agent any
    stages {
	stage('run-parallel-branches') {
	    steps {
		parallel(
		    a: {
			echo "Tests on Linux"
		    },
		    b: {
			echo "Tests on Windows"
		    }
		)
	    }
	}	
    }
}
