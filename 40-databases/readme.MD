To increase volume size or space find the below commands to increase
```df -hT```
```lsbk```
```df -hT```
```sudo growpart /dev/nvme0n1 4```
```sudo lsbk```
```sudo lvextend -L +30G /dev/mapper/RootVG-homevol```
```sudo xfs_growfs /home```
```df -hT```
```terraform init```
```terraform apply -auto-approve```
