pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "*world.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}