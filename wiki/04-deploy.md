# 4.1. Deploy to Heroku

##### Install Heroku Client

```bash
bash scripts/heroku.sh install-cli
```

##### First Deploy

Set Heroku app name in variable ```APP_NAME``` inside ```scripts/heroku.sh``` and execute:

```bash
bash scripts/heroku.sh first-deploy
```

##### Deploy

```bash
bash scripts/heroku.sh deploy
```

##### Commands

```scripts/heroku.sh```

Command      | Info
-------------|----------------------
install-cli  | Install Heroku client
first-deploy | First deploy
deploy       | Deploy
logs         | Show logs

# 4.2. Deploy to Virtual Machine

##### 4.2.1. Enter Terminal

```bash
bash scripts/dev.sh terminal
```

##### First Deploy

```bash
cap production deploy:init
```

##### Deploy

```bash
cap production deploy
```

##### Commands

```scripts/prd.sh```

Command | Info
--------|----------
logs    | Show logs

# 4.3. Stop Services

```bash
bash scripts/dev.sh stop
```# 1. Deploy to Heroku

##### Install Heroku Client

```bash
bash scripts/heroku.sh install-cli
```

##### First Deploy

Set Heroku app name in variable ```APP_NAME``` inside ```scripts/heroku.sh``` and execute:

```bash
bash scripts/heroku.sh first-deploy
```

##### Deploy

```bash
bash scripts/heroku.sh deploy
```

##### Commands

```scripts/heroku.sh```

Command      | Info
-------------|----------------------
install-cli  | Install Heroku client
first-deploy | First deploy
deploy       | Deploy
logs         | Show logs

# 4.2. Deploy to Virtual Machine

##### 4.2.1. Enter Terminal

```bash
bash scripts/dev.sh terminal
```

##### First Deploy

```bash
cap production deploy:init
```

##### Deploy

```bash
cap production deploy
```

##### Commands

```scripts/prd.sh```

Command | Info
--------|----------
logs    | Show logs

# 4.3. Stop Services

```bash
bash scripts/dev.sh stop
```
