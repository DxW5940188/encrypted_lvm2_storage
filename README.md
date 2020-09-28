# encrypted_lvm2_storage  
> 實作者: Wan Pei Chih 
> last edit date of 13 Jun, 2018  
## Description  
Manage your encrypted lvm storage
> first, you need to create a lvm-disk (pv->vg->Lv).  
> second, use `cryptsetup` to encrypt the lvm-disk, about the information can be to [reference](https://www.cyberciti.biz/hardware/howto-linux-hard-disk-encryption-with-luks-cryptsetup-command/)  
## Deployment  
- Will be deploy to /usr/local/bin
> ansible-playbook deploy.yml  
## How to Start  
> `encryptedstorage {start|stop|exportstorage|importstorage}`  
