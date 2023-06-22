# Check Cisco ASA config

Repository for the blog post [Automating Network Device Configuration Parsing with Ansible: Tips and Tricks for Network Engineers](https://medium.com/p/99790909c384)

## Run

Provide a config file as an Ansible extra variable with the command line using the --extra-vars (or -e) argument.

```
$ ansible-navigator run main.yml -e config=base.txt
```


## Resources
- [Understanding the Ansible CLI parser](https://docs.ansible.com/ansible/latest/network/user_guide/cli_parsing.html#understanding-the-cli-parser)
- [Creating ACL entries in a Cisco ASA device](https://subscription.packtpub.com/book/cloud-and-networking/9781803235417/8/ch08lvl1sec50/creating-acl-entries-in-a-cisco-asa-device)
- [Ansible playbooks examples to provision a Cisco ASAv](https://github.com/berndonline/asa-lab-provision/tree/master)
- [Python re](https://docs.python.org/3/library/re.html#module-re)