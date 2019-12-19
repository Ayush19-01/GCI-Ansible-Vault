# GCI-Ansible-Vault
__1) Installation of Ansible on linux(Ubuntu):__

   _Entering the following commands in the terminal_

  1.1`$ sudo apt-add-repository ppa:ansible/ansible` 
    
   ![alt text](https://github.com/Ayush19-01/GCI-Ansible-Vault/blob/master/Screenshot%20from%202019-12-19%2017-31-20.png)
    
   _You should get the above screen and press enter_
    
    
   1.2`$ sudo apt update`
   
   Following this update, you can install the Ansible software with:
    
   1.3`$ sudo apt install ansible`
    
   _Installation of Ansible Vault is completed after this step._
    
__2) Encrypting the file:__
 
   Here i have used a dummy YML format file.
     
   _Command to encrypt:_
   
  `$ ansible-vault encrypt filename.yml`
        
   ![alt text](https://github.com/Ayush19-01/GCI-Ansible-Vault/blob/master/Screenshot%20from%202019-12-19%2017-49-38.png)
     
   _Above screen is achieved after the yml file is encrypted_
     
   _A password has to be set for the vault in order to decrypt it next time._
     
   _I have attached both encrypted and decrypted yml file_
     
   _Sample1.yml is encrypted while sample2.yml is decrypted_
   
   _Command to decrypt_
   
   `$ ansible-vault decrypt filename.yml`

   __3)Uses of Ansible Vault:__
    
   _Ansible Vault is a feature that allows users to encrypt values and data structures within Ansible 
    projects. This provides the ability to secure any sensitive data that is necessary to successfully 
    run Ansible plays but should not be publicly visible, like passwords or private keys. Ansible 
    automatically decrypts vault-encrypted content at runtime when the key is provided._
    
