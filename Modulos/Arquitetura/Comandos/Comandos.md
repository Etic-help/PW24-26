# 📜 Resumo de Comandos Aprendidos

## 🐧 Comandos de Terminal Linux
### Navegação e Gestão de Arquivos
- `ls`: Lista os arquivos e diretórios do diretório atual.  
- `cd <diretório>`: Acessa o diretório especificado.
- `cd ..`: Acessa o diretório anterior.
- `cd /`: Acessa o diretório home/root vai a raiz.  
- `pwd`: Mostra o diretório atual desde a /.  
- `mkdir <nome>`: Cria um novo diretório.  
- `rm <arquivo>`: Remove um arquivo.
- `cat <arquivo>`: Consegue ver o contéudo do arquivo.  
- `rm -r <diretório>`: Remove um diretório e seu conteúdo.  
- `cp <origem> <destino>`: Copia arquivos ou diretórios.  
- `mv <origem> <destino>`: Move ou renomeia arquivos/diretórios.

### Variáveis de Ambiente
- `export VARIAVEL="valor"`: Define uma variável temporária.
- `printenv VARIAVEL - ou apenas env`: Mostra o valor da variável.  
- `unset VARIAVEL`: Remove uma variável de ambiente.  
- `echo $VARIAVEL`: Exibe o valor de uma variável.

---

## 🖥 Comandos de Terminal Windows (CMD)
### Navegação e Gestão de Arquivos
- `dir`: Lista os arquivos e diretórios do diretório atual.  
- `cd <diretório>`: Acessa o diretório especificado.  
- `mkdir <nome>`: Cria um novo diretório.  
- `del <arquivo>`: Remove um arquivo.  
- `rmdir <diretório> /s`: Remove um diretório e seu conteúdo.  
- `copy <origem> <destino>`: Copia arquivos.  
- `move <origem> <destino>`: Move ou renomeia arquivos/diretórios.

---

## 🐳 Comandos Docker
### Gestão de Contêineres
- `docker ps`: Lista os contêineres em execução.
- `docker ps -a`: Lista todos os contêineres (incluindo parados).    
- `docker rm <ID>`: Remove um contêiner.  

### Listagem
- `docker image ls -a` Lista todas imagens criadas no docker.
- `docker container ls -a` Lista todos containers criados no docker.

### Construção e Imagens
- `docker build -t <nome>:<tag> .`: Cria uma imagem a partir de um Dockerfile.  
- `docker images ls`: Lista todas as imagens locais.  
- `docker rmi <ID>`: Remove uma imagem.  

### Manipulação de Arquivos
- `docker cp <caminho_local> <ID_DO_CONTAINER>:<caminho_destino>`: Copia arquivos da máquina para o contêiner.  
- `docker cp <ID_DO_CONTAINER>:<caminho_container> <caminho_local>`: Copia arquivos do contêiner para a máquina.

---

Este arquivo resume os comandos essenciais que estão a ser aprendidos durante o curso. 📂✨