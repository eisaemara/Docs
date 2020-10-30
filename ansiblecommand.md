# My Ansible Commands 
to run with defined host using command `-i <hosts-file>`
to list all hosts 
` ansible -i <file-name> --list-hosts [all|target]`
to run simple command to test machine you could use
`ansible -i <file-name> -m ping  [all|target]`

to run play books 
`ansible-playbook -i <file-name>  [play-book file]`