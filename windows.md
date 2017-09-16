# Windows
## License
- Digital License
unavailable to use Prodoct Key to install Windows
- Others
available to use Product Key to install Windows

## what to do after install Windows
### disable hybernate
```
# run as Admin
powercfg /H off
```

### install choco and packages
```
# run as Admin
Set-ExecutionPolicy AllSigned; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
restart powershell. then
```
# run as Admin
choco install -y visualstudiocode jde8 jdk8 git python python2 ruby winrar nodejs sysinternals wireshark golang poshgit yarn
```

### enable developper mode

### (option)
- scala
- office
- msys2
- mpc-be
- ubuntu
- (enable openssh module)
    - cannot read `~/.ssh/config`
    - `ssh -i \.ssh\id_ed25519.pub -p PORT user@host