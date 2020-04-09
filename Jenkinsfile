node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'hanumantharao1986') {

        def customImage = docker.build("hanumantharao1986/dockerimageterform $BUILD_NUMBER")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
