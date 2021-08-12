node {
<<<<<<< HEAD
    def git_arocha
=======
        def git_rocha
>>>>>>> 3320db147c61616bc633c5d1f8e9e553dad05df4
        stage('Git Clone'){
            git 'https://github.com/alecio-rocha/jenkins'

        }
        stage('Test') { 
            'make test'
            junit '**/target/reports/TEST-*.bin'
        }
        stage('build') {
<<<<<<< HEAD
            ' go build -o  teste main.go'
=======
            ' go get gopkg.in/ns1/ns1-go.v2'
>>>>>>> 3320db147c61616bc633c5d1f8e9e553dad05df4
        }
        stage('print') {
            echo 'Hello word'
        }
}

