node('master') {

    stage("Stage #1") {
        def d = new File("./")
        d.eachFile {
            println it
        }
        echo "testin"
        bat '''
            echo 'Multiline'
            echo 'Example'
            '''
    }
}

def printMessage(message) {
    echo "${message}"
}
