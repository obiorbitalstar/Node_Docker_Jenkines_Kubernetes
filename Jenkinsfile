node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Docker Hub') {

        def customImage = docker.build("obiorbitalstar/node-web-app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
