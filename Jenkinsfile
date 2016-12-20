@Library('helpers') _

node {
	standardBuild {
	    tool = 'M3'
	    mainScript = '''
	mvn clean install
	'''
	    postScript = '''
	ls -l
	./hello-world
	'''
	}
}
