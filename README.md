# Bac à sable autour de l'ecosystème de Docker
## Terminologie
* **[Vagrant](https://www.vagrantup.com/)**: C'est un wrapper autour de **VirtualBox** qui permet d'automatiser la mise-en-place de machines virtuelles (grâce au `Vagrantfile`, et à l'utilitaire `vagrant` etc.).
 * **[Box](http://docs.vagrantup.com/v2/boxes.html)**: Pratiquement parlant, une **Box** est un template de machine virtuelle qui va être instanciée lorsque le `Vagrantfile` y fait référence. Pour créer une **Box**: (https://blog.engineyard.com/2014/building-a-vagrant-box).
 * **[Packer](https://www.packer.io/)**: C'est est un outil pour créer des templates (pour **Vagrant**, mais aussi pour **Amazon**, par exemple). 
* **[CoreOS](https://coreos.com/)**: **CoreOS** est une distribution Linux orientée serveur, très légère (pas de package manager), destinée à ne lancer que des instances **Docker** en utilisant des `Unit` pour `systemd`. 
* [Docker](about:blank):
* [Flannel](about:blank): Un moyen d'avoir la même table d'IP pour des instances Docker sur des machines différentes. 

## Liens
* [Tutorial pour **Ansible**](https://github.com/leucos/ansible-tuto)
* [**Playbook** pour **Ansible** avec pleins de commentaires](https://gist.github.com/marktheunissen/2979474)
* [**Weave** et **Ansible** sur **AWS**](http://weave.works/guides/weave-ansible-docker-haproxy-aws.html)*
* [**Kubernetes** avec **Vagrant**](http://lollyrock.com/articles/kubernetes-vagrant/)
* [**CoreOS** et **Flannel**](https://sreeninet.wordpress.com/2015/01/18/docker-networking-coreos-flannel/)
* [Construire une **Box** pour **Vagrant**](https://blog.engineyard.com/2014/building-a-vagrant-box)
* [**Kubernetes** sur **CoreOS** avec **Ansible**](https://github.com/erikdejonge/coreos-kubernetes-vagrant-ansible-demo)
* [Data-only Pattern pour **Docker**](http://container42.com/2013/12/16/persistent-volumes-with-docker-container-as-volume-pattern/)
* [**Kubernetes** sur **CoreOS** avec **Fleet** et **Flannel**](https://github.com/kelseyhightower/kubernetes-fleet-tutorial)
