1. Ignorar certiicador SSL
git config --global http.sslVerify false


Configuração de nível local é aplicada no repositório do contexto em que o git config for invocado. Os  valores de configuração local são armazenados em um arquivo que pode ser encontrado no diretório .git do repositório: .git/config

git config --local user.email "you@example.com"
git config --local user.name "Your Name"

A configuração de nível global é específica do usuário, ou seja, ela é aplicada a usuários do sistema operacional. Os valores de configuração global são armazenados em um arquivo localizado no diretório de base do usuário. ~ /.gitconfig

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

A configuração de nível do sistema é aplicada em toda a máquina. Ela abrange todos os usuários do sistema operacional e todos os repositórios. O arquivo de configuração de nível do sistema está no arquivo gitconfig localizado fora do caminho raiz do sistema. $(prefix)/etc/gitconfig em sistemas Unix. No Windows, esse arquivo pode ser encontrado em C:\Documents and Settings\All Users\Application Data\Git\config no Windows XP e em C:\ProgramData\Git\config no Windows Vista e versões mais recentes.

git config --system user.email "you@example.com"
git config --system user.name "Your Name"
