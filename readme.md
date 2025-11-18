# Setup

1. Spin up Digital ocean Ubuntu droplet. (ClickOps or CLI up to you)

2. SSH into instance

```shell
ssh use_your_username@203.0.113.0 -i ~/.ssh/digital_ocean_rsa
```

3. Do cloud magic

```shell
git clone https://github.com/seanjin97/firecracker-67.git

./setup.sh


# In screen 1
screen -S firecracker
./start.sh

# In screen 2
# Spin up microVMs and do shenanigans


```

# Cool stuff

https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md

https://github.com/firecracker-microvm/firecracker-containerd/blob/main/docs/getting-started.md

https://kruzenshtern.org/writings/2021-02-24-run-firecracker-on-digitalocean

https://d1.awsstatic.com/events/reinvent/2019/REPEAT_1_Deep_dive_into_firecracker-containerd_CON408-R1.pdf
