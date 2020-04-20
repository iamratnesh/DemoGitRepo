node{
		stage ('Checkout Code') {
			
			git 'https://github.com/iamratnesh/DemoGitRepo'
		}
		stage ('Compile Package') {
			
			sh 'mvn package'
		}
}
