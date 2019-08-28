node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerlogin') {

        def customImage = docker.build("arun101/test-app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
