to push changes to OCF (and reflect them onto the prod website):

```shell
# ssh into uic's ocf server
ssh uic@ssh.ocf.berkeley.edu #pw=dri%NqpzbPxv@RS5Vpu13p8p@~puci5X

# pull changes from git repo
cd public_html && git pull origin master
```

changes may take a couple minutes to be reflected in the prod deployment.
