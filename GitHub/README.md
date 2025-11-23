# GIT
- Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.
  - O funcionamento dessa ferramenta é semelhante aos sistemas de nuvens (Google Drive, Dropbox, Mega, etc), em que podemos compartilhar as edições de um script com uma equipe, além de retomar antigas versões de nossos arquivos.
  - É minicromático: Você escreve diretamente em um terminal white/black.

## PRINCIPAIS COMANDOS 

- A estrutura básica é : `git config <opções> chave valor`

- `Git init`: Inicializar um repositório Git dentro de um diretório do sistema.
- `Git clone`: Criar uma cópia de um repositório remoto em um diretório da máquina.
- `Git status`: Verificar o status de um repositório git.
- `Git add`: Adicionar arquivos ao pacote de alterações a serem feitas.
- `Git commit`:  Criar uma nova versão do projeto a partir de um pacote de alterações.
- `Git log`: Ver o histórico de alterações do projeto.
- `Git branch`: Criar novos ramos de desenvolvimento e visualizar quais são os ramos existentes.
- `Git checkout`: Navegar entre as versões do projeto e entre as diferentes ramificações criadas.
- `Git diff`: Visualizar modificações feitas entre commits.

## OBJTOS INTERNOS DO GIT

- `Blobs`: Armazena dados de arquivos, porém não guardam seus metadados.
- `Trees`: São objetos criados para armazenar dados de pastas, como blobs e até mesmo outras trees, podem ser entendidos como a representação de uma pasta dentro do git.
- `Commit`: São objetos que guardam o snapshot de um momento do projeto. Dentro de um commit são guardadas trees e blobs, que por sua vez identificam o estado dos arquivos e pastas no momento em que o commit é criado, assim como metadados como quando ele foi criado e por quem.

# GITHUB

- O Github é um dos maiores repositórios remotos que existem mundialmente, sendo ele uma plataforma que hospeda códigos fonte com auxílio do software de versionamento.
  - Tem uma interface gráfica. 

# Termos importantes
  
- `Commit`: Uma ação em que você faz uma alteração no projeto, se compromete e salva suas alterações no histórico do projeto. Cada commit é uma entrada no histórico que contém informações sobre as alterações feitas.
- `Pull`: Baixar versões de outros.
- `Merge/Fusões`: União de duas branch.
- `Push`: Enviar versões para repositório remoto.
- `Repositório`:É como uma pasta ou diretório que contém todos os arquivos e o histórico de um projeto.
- `Branch/Ramificações`: Existe a branch main/master que é o "tronco" e as branchs que são os "galhos". Os galhos crescem ser atrapalhar o tronco.
