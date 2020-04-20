node{
		stage ('Checkout Code') {
			
			git 'https://github.com/iamratnesh/DemoGitRepo/tree/master/springjpaexample'
		}
		stage ('Compile Package') {
			
			sh 'mvn package'
		}
}
