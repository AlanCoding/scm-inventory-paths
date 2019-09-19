# Ansible Tower SCM inventory search paths

This shows a totally-not-crazy way to manage a large swath of inventory
plugins inside of a repo used inside of Ansible Tower.

Test locally:

```
ansible-doc -t inventory -l
```

Now parse a particular inventory:

```
ansible-inventory -i inventories/cow.yaml --list --export
ansible-inventory -i inventories/fox.yaml --list --export
```
