node {
    checkout scm

    docker.withRegistry('https://hub.docker.com/repository/docker/ogya123/store', 'dockerhub') {

        def customImage = docker.build("hiyahiya/store")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
