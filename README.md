# command and jobs for run ansible

```
step1:
    create user ansible in machin local and target:
        useradd ansible
        passwd ansible
    change user:
        su - ansible
    add user ansible to sudo:
        sudo visudo
        root    ALL=(ALL:ALL) ALL
***
step2:
    create ssh:
        ssh-keygen
        ssh-copy-id <user>@<ip>
***
step3:
    create ansible and install ansible:
        python -m venv vnv
        source venv/bin/activate
        pip install ansible
***
```