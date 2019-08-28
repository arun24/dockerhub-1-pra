node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("arun101/test-app-2")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
