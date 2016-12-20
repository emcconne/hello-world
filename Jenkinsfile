@Library('helpers') _

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
