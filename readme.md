# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos
para utilização de git e Github

## Configuração inicial
Rode os comandos abaixo no terminal (cmd) do seu computador.
```bash 

git config --global user.name "Diogo Guilherme dos Santos"

git config --global user.email diogo.santos67@fatec.sp.gov.br
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init
**IMPORTANTE:** Só é executado 1 vez.
```bash
git init
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no 
Github e seguir a segunda opção da lista de comandos que aparece no site
**IMPORTANTE** Depois do remote devem ser executados os outros 2 comandos da página.
```bash
git remote add origin < url_repositorio_github >
```

Para verificar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Para adicionar os arquivos modificados
```bash
git add (nome do arquivo ou . para todos os arquivos no local)
```

Para salvar as modificações 
```bash
git commit -m "Mensagem desejada"
```

Para baixar as alterações que estão apenas no Github utilizamos o pull <br>
**IMPORTANTE:** Sempre deve baixar a útlima versão da nuvem antes de enviar a atual do computador
``` bash
git pull
```

Para baixar o repositório do Github em um novo computador utilizamos o git clone
``` bash
git clone < url-do-repositorio-github >
```
Para enviar os commits do pc para o Github utilizamos o push
``` bash
git push
```
