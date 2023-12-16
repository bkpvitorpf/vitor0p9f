<div align = "center">
  <p>This README is available in the following languages:</p>
  <br/>
  
  <a href = "#" target="_blank">
    <img src="https://img.shields.io/badge/Language-English-blue"/>
  </a>
</div>

<div align="center">
  
  # Repositório de estudo - Nome do projeto
</div>

[Aqui entra um breve descrição do que é o projeto e porque ele foi desenvolvido].

## :gem: Gems utilizadas

## :page_facing_up: Padrões de projeto utilizados

## :pushpin: Conhecimentos adquiridos

## :triangular_flag_on_post: Desafios encontrados

## :rocket: Executando o projeto 

### 1. Clonando o repositório

Clone este repositório em sua máquina utilizando o seguinte comando no terminal:

```bash
git clone 
```

Após o repositório estar em sua máquina, entre no diretório recém clonado.

Para executar este projeto em sua própria máquina, você pode escolher entre as opções:

* Executar o projeto usando Docker.
* Executar o projeto instalando as dependências.

### :whale2: Utilizando o Docker

#### :construction: Requisitos

* Ter o Docker instalado e configurado em sua máquina.

#### 2. Monte uma imagem do projeto utilizando o seguinte comando:

```bash
docker build -t [nome_do_projeto] .
```

A imagem criada terá o mesmo nome do projeto.

#### 3. Crie um container com base na imagem recém criada utilizando o comando:

```bash
docker run -it --name [nome_do_projeto] [nome_do_projeto]
```

O comando acima utilizará a imagem criada anteriormente para criar um container com o nome do projeto.

Após rodar o comando acima, o terminal do container deve abrir automaticamente, já executando o código do projeto.

### :link: Instalando as dependências

#### :construction: Requisitos

* Ter o Ruby instalado em sua máquina
* Aconselho a utilizar ferramentas como RVM ou rbenv para permitir a instalação de Gems sem permissão de administrador.

#### 2. Instale as dependências do projeto rodando o comando:

```bash
bundle install
```

#### 3. Execute o projeto rodando o comando:

```bash
ruby ./main.rb
```


