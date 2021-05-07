![Image of Yaktocat](https://www.tribality.com/wp-content/uploads/2018/04/minotaur.jpg)

# MinioTaur
This repo help you auto-creating Minio username, bucket and policy via Ansible. Also you can keep these credentials and configs on Vault and Consul.

### Requirments:
- Vault 
- Consul
- mc (minio client) [Installation](https://docs.min.io/docs/minio-client-complete-guide)
- ansible

### User Manual:
Enter your input variables to vars/GlobalVars.yml file then just run
```bash
ansible-playbook ansible-playbook.yaml
```
