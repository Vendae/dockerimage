node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'hanumantharao1986') {

        def customImage = docker.build("hanumantharao1986/dockerimageterform")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
