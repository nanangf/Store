node {
    checkout scm

    docker.withRegistry('registry-1.docker.io', 'dockerhub') {

        def customImage = docker.build("hiyahiya/store")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
