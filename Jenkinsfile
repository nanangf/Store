node {
    checkout scm

    docker.withRegistry('', 'dockerhub') {

        def customImage = docker.build("ogya123/store")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
