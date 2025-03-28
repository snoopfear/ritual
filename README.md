# ritual

wget https://raw.githubusercontent.com/snoopfear/ritual/refs/heads/main/rit_ins.sh && chmod +x rit_ins.sh && ./rit_ins.sh

docker logs -f --tail 50 infernet-node

Sleep 3
Starting sub id 230000
Batch size 800
Sync period 30

sudo systemctl restart ritual-network.service

nano ~/infernet-container-starter/deploy/config.json
nano ~/infernet-container-starter/projects/hello-world/container/config.json
