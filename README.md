
https://semaphoreci.com/community/tutorials/dockerizing-a-node-js-web-application

For Docker on Windows :

SET UP A NEW EXTERNAL NETWORK SWITCH:
First in Hyper-V Manager, create "Commutateur Virtuel"
https://docs.docker.com/machine/drivers/hyper-v/

(Replace virtualbox by hyperv)
docker-machine create dev2 --driver hyperv --hyperv-disk-size "5000" --hyperv-cpu-count 2 --hyperv-memory "4112"



https://www.digitalocean.com/community/tutorials/how-to-use-pm2-to-setup-a-node-js-production-environment-on-an-ubuntu-vps
