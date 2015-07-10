# Bac à sable autour de l'ecosystème de Docker
## Terminologie
* **[Vagrant](https://www.vagrantup.com/)**: C'est un wrapper autour de **VirtualBox** qui permet d'automatiser la mise-en-place de machines virtuelles (grâce au `Vagrantfile`, et à l'utilitaire `vagrant` etc.).
 * **[Box](http://docs.vagrantup.com/v2/boxes.html)**: Pratiquement parlant, une **Box** est un template de machine virtuelle qui va être instanciée lorsque le `Vagrantfile` y fait référence. Pour créer une **Box**: (https://blog.engineyard.com/2014/building-a-vagrant-box).
 * **[Packer](https://www.packer.io/)**: C'est est un outil pour créer des templates (pour **Vagrant**, mais aussi pour **Amazon**, par exemple). 
* **[CoreOS](https://coreos.com/)**: **CoreOS** est une distribution Linux orientée serveur, très légère (pas de package manager), destinée à ne lancer que des instances **Docker** en utilisant des `Unit` pour `systemd`. 
* [Docker](about:blank):
* [Flannel](about:blank): Un moyen d'avoir la même table d'IP pour des instances Docker sur des machines différentes. 
