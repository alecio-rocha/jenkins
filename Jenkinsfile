node {
        def git_rocha
        stage('Git Clone'){
            git 'https://github.com/alecio-rocha/jenkins'

        }
        stage('Test') { 
            'make test'
            junit '**/target/reports/TEST-*.bin'
        }
        stage('build') {
            ' go get gopkg.in/ns1/ns1-go.v2'
        }
        stage('print') {        stage('print') {
            echo 'Hello word'
        echo 'Hello word'
        }
}

