pipeline{
	agent any
	stages{
		stage('Build'){
			when{
				tag 'release-*'
			}
			steps{
				echo "Building hello world Tags"
			}
		}
	}
}
