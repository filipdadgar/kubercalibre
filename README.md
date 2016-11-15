# kubercalibre
Kubernetes deployment of Calibre

The Calibre E-book management system http://calibre-ebook.com/ run in a docker container with Kuberenetes orchestration.
Image is https://github.com/aptalca/docker-rdp-calibre

The POD in Kuberentes uses a NFS share for saving the ebooks.
