1. Criar arquivo .bachrc caso não exista
touch ~/.bachrc

2. Instalar nvm
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash

3. Atualizar novas variáveis de ambiente criadas
source ~/.bachrc

4. Instalar ultima versão lts
nvm install --lts

6. Instalar versão específica
nvm install 14

7. Informar qual versão usar
nvm use v14.19.1

8. Verificar versão disponível
node --version
npm --version

9. Desistalar uma versão já instalada
nvm uninstall v16.14.2

10. Configurar uma versão default para o sistema
nvm alias default v14.19.1



