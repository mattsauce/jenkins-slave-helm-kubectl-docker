# jnlp-slave-helm-kubectl-docker
This image is using jenkins/jnlp-slave:alpine as a base then add:

- docker: version 18.06.1-ce
- kubectl: version 1.12
- helm: version 2.9.1 + init --client-only
- Incubator repo for helm
- s3 plugin for helm
