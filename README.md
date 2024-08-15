# ativ2tdd
Atividade da aula de TDD 14/08/2024


## Inicialização do Projeto (Página HOME)

Para que o projeto funcione, execute o arquivo index.html

```bash
cd ativ2tdd/index.html
```

## Configuração do Git

Para acessar o projeto é necessário realizar o clone:

```bash
git clone https://github.com/VilarimLucas/ativ2tdd.git
```

## Criação e uso de Ramificações
Cada página foi criado uma branch

#### Página HOME
criando a branch:

```bash
git checkout -b desenvolvimento/home
git add .
git commit -m "criação da branch home"
git push origin desenvolvimento/home
```
* LUCAS: contribuiu com o desenvovimento da Home, foi interessante realizar a mesclagem para a main antes de enviar o repositório para o Github. Fiz um teste de estilo colocando os código internos, depois foi transcrito no arquivo styles.css .

##### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/home
git add .
git commit -m "mesclagem da branch home com a main"
git push origin main
```

#### Página SOBRE
criando a branch:

```bash
git checkout -b desenvolvimento/sobre
git add .
git commit -m "criação da branch sobre"
git push origin desenvolvimento/sobre
```
##### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/sobre
git add .
git commit -m "mesclagem da branch sobre com a main"
git push origin main
```
#### Página PORTIFÓLIO
criando a branch:

```bash
git checkout -b desenvolvimento/portifolio
git add .
git commit -m "criação da branch portifólio"
git push origin desenvolvimento/portifolio
```
##### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/portifolio
git add .
git commit -m "mesclagem da branch portifolio com a main"
git push origin main
```
#### Página CONTATO
criando a branch:

```bash
git checkout -b desenvolvimento/contato
git add .
git commit -m "criação da branch contato"
git push origin desenvolvimento/contato
```
##### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/contato
git add .
git commit -m "mesclagem da branch contato com a main"
git push origin main
```
## Envio para o GitHub
É necessário estar na branch main:
```bash
git checkout main
```
Execute os seguintes comandos:
```bash
git remote add origin https://github.com/VilarimLucas/ativ2tdd.git
git push -u origin main
```
