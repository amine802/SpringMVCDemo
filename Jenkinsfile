node ("master") {

	// Change the project version
	env.BN = VersionNumber([
			versionNumberString : '$(BUILD_MONTH).$(BUILD_TODAY).$(BUILD_NUMBER)',
			projectStartDate : '2017-11-29',
			versionPrefix : 'v1.'
		])

	stage('Provision'){
		echo 'Checkout source code from GitHub ...'
		git branch: 'developer', credentialsID: 'GitHub', url: 'git@github.com:amine802/SpringMVCDemo.git'
	}
}
