@Library('helpers') _

standardBuild {
    environment = 'maven'
    mainScript = '''
mvn clean install
'''
    postScript = '''
ls -l
./hello-world
'''
}
