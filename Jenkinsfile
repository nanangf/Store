node {
    checkout scm

    docker.withRegistry('https://index.docker.io', 'dockerhub') {

        def customImage = docker.build("hiyahiya/store")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
