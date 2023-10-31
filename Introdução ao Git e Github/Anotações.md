# Git

### É um sistema de versionamento de código distribuído, é um software que ajuda a monitorar e utilizar as várias versões de um código.

### Objetos internos go Git

- Blobs: Objeto do Git onde ficam guardados arquivos

- Tree: As trees são usadas para armazenar blobs, elas também possuem seu próprio SHA1, que é referente a tudo armazenado dentro dela

- Commit: Ele compila todos os otros objetos, trazendo também o nome do autor e uma mensagem, os commits apontam também para seus parentes, ou seja, suas versões anteriores

### Primeiros comandos com o Git

- **Git ini**t: Inicia o versionamento do Git dentro de uma pasta específica  (cria a pasta .git)

- **Git add**: move nossos arquivos para área de standing (local onde ele espera para ser commitado)

- **Git commi**t: Adiciona nossos arquivos de standing para nosso repositório local

- **Git remote add origin (link)**: Indica para onde vamos empurrar nosso código

- **Git remote -v**: Indica o link cadastrado

- **Git push origin master**: Envia nosso código do repositório local para o repositório remoto

- **Git pull origin maste**r: Puxa o repositório remoto para nosso repositório local

- Git clone (URL): Clona qualquer repositório para dentro da nossa máquina



# Github

### É um sistema de armazenamento e exposição de código (repositório remoto)
