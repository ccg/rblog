* rename the remote repo
* figure out what to do with deploy.sh
  - ~/.ssh/config
  - Might not want to checkin personal details in the public repo (username, server location, etc.)
* do something to save the knowledge in the old s3.sh
* improve build automation?
  - Use `R/build.R`?
  - automate image stuff?
  - https://github.com/rstudio/blogdown/issues/51

### ~/.ssh/config

https://unix.stackexchange.com/questions/94421/how-to-use-ssh-config-setting-for-each-server-by-rsync

```
Host ?
  HostName ???
  User ???
  Port ???
```

Maybe use `IdentityFile`:

https://unix.stackexchange.com/questions/127352/specify-identity-file-id-rsa-with-rsync
