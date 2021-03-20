echo "--build start--"

stage('Checkout Stage') {
	echo "--Checkout--"
}

stage('Build Stage') {
	echo "--Build Stage--"
}

stage('npm') {
	nodejs(nodeJSInstallationName: 'Node.js') {
        sh 'npm install && npm run build'
    }
}

stage('Push Stage') {
	echo "--Push Stage--"
}
