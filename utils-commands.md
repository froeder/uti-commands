# My Usefull Commands

## GIT
---

 Para forçar um pull :

 ```
git fetch --all
git reset --hard origin/master
git pull origin master
 ```

## Terminal
---

 Procurar um comando no Histórico :

```
history grep | comandoAserPesquisado
```

## Composer - Windows

```
 php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
 - php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
 - php composer-setup.php
 -  php -r "unlink('composer-setup.php');"

```

## Others

To ad Ambient Variables without admin access in Windows

```
rundll32 sysdm.cpl,EditEnvironmentVariables
```

