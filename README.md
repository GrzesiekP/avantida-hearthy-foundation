

## Instalacja

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'));


choco install vscode -y;
choco install nodejs -y;
choco install git -y;
choco install winscp -y;
```

## Może nie działać

`choco install brave -y;`
