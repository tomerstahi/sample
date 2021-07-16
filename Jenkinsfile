pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {withEnv (props)
                {
                    echo 'Hello World'
                    echo 'env.havi'
                }
            def tomer=readYaml(file: "c:\\users\\tomer\\routes.yaml")
            def props =readProperties(file: "c:\\users\\tomer\\routes.properties")
            }
        }
    }
}
