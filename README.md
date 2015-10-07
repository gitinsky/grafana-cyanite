```bash
git clone http://10.40.0.10/hryamzik/grafana-vagrant.git
cd grafana-vagrant/
git submodule update --init
cd roles/cyanite/vagrant/
git submodule update --init
vagrant up
ansible-playbook cyanite.yml
```