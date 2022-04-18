# Windows Subsystem for Linux

## Ajuda para comando wsl

$ wsl --list --help



## **Exibe uma lista de distribuições disponíveis para instalação com 'wsl --install'.**

`$ wsl --list --online`


|NAME  |FRIENDLY NAMEFRIENDLY NAME  |
|---------|---------|
|* Ubuntu       |Ubuntu        |
|  Debian       |Debian GNU/Linux        |
|  kali-linux   |Kali Linux Rolling         |
|  openSUSE-42  |openSUSE Leap 42         |
|  SLES-12      |SUSE Linux Enterprise Server v12         |
|  Ubuntu-16.04 |Ubuntu 16.04 LTS         |
|  Ubuntu-18.04 |Ubuntu 18.04 LTS         |
|  Ubuntu-20.04 |Ubuntu 20.04 LTS         |



Install a specific Linux distribution

`$ wsl --install --distribution <Distribution Name>`

`$ wsl --install --distribution Ubuntu-18.04`
Instalando: Plataforma de Máquina Virtual
Plataforma de Máquina Virtual foi instalado.
Instalando: Subsistema do Windows para Linux
Subsistema do Windows para Linux foi instalado.
Baixando: WSL Kernel
Instalando: WSL Kernel
WSL Kernel foi instalado.
Baixando: Ubuntu 18.04 LTS
Êxito na operação requisitada. As alterações só terão efeito depois que o sistema for reiniciado.

Executar como administrador do sistema


Set WSL version to 1 or 2

$ wsl --set-version "Ubuntu-18.04" "2"
$ wsl --set-version Ubuntu-18.04 2

$ wsl --set-default-version 2

$ sudo apt update

$ sudo apt upgrade



Ferramentas uteis:
Windows Terminal
