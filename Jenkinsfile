pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                def list = [5, 6, 7, 8]
                println "Iterating over a list"
                list.each{
                    
                    println "Item: $it"
                }
                def map = [name: 'Gromit', likes: 'cheese', id: 1234]
                println "Iterating over a map"
                map.each{key, value ->
                    println "$key: #value"
                }
                    
            }
        }
    }
}
