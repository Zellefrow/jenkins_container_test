node("master"){
try {
	stage("CHECKOUT") {
		checkout scm
		echo "jenkins test"
		sh "ls"
	}
}
finally {
	echo "done"
}
}
