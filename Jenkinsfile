pipeline{
	agent any
	stages{
		stage('build'){
			steps{
				echo 'building gradle'
				withGradle(){
					bat './gradlew -v'
				}
			}
		}
	}
}
