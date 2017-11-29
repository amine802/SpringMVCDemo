node ("master") {
	stage('Provision'){
		echo 'Checkout source code from GitHub ...'
		git branch: 'developer', credentialsID: 'GitHub', url: 'git@github.com:amine802/SpringMVCDemo.git'
	}
}
