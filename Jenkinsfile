node{
		stage ('Checkout Code') {
			
			git clone https://github.com/iamratnesh/DemoGitRepo.git
		}
		stage ('Compile Package') {
			
			sh 'mvn package'
		}
}
