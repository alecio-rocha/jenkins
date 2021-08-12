node {
    def git_arocha
        def git_rocha
        stage('Git Clone'){
            git 'https://github.com/alecio-rocha/jenkins'

        }
        stage('Test') { 
            'make test'
            junit '**/target/reports/TEST-*.bin'
        }
        stage('build') {
            ' go build -o  teste main.go'
        }
        stage('print') {
            echo 'Hello word'
        }
}

