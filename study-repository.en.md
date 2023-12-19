<div align = "center">
  <p>This README is available in the following languages:</p>
  <br/>
  
  <a href = "#" target="_blank">
    <img src="https://img.shields.io/badge/Language-Portuguese-green"/>
  </a>
</div>

<div align="center">
  
  # Study repository - Nome do projeto
</div>

[Aqui entra um breve descrição do que é o projeto e porque ele foi desenvolvido].

## :gem: Used Gems

## :page_facing_up: Used design patterns

## :pushpin: Acquired knowledge

## :triangular_flag_on_post: Challenges encountered

## :rocket: Running the project

### 1. Cloning the repository

After the repository is on your machine, enter the newly cloned directory.

To run this project on your own machine, you can choose between the options:
   
* Run the project using Docker.
* Run the project by installing the dependencies.

### :whale2: Using Docker

#### :construction: Requirements

* Have Docker installed and configured on your machine.

#### 2. Build a project image using the following command:

```bash
docker build -t [nome_do_projeto] .
```

The created image will have the same name as the project.

#### 3. Create a container based on the newly created image using the command:

```bash
docker run -it --name [nome_do_projeto] [nome_do_projeto]
```

The above command will use the previously created image to create a container with the project name.

After running the above command, the container terminal should open automatically, already running the project code.

Para executar o projeto novamente, sem criar um novo contêiner, basta rodar o seguinte comando:

```bash
docker start -i ruby-caesar-cipher
```

### :link: Installing dependencies

#### :construction: Requirements

* Have Ruby installed on your machine.
* I recommend using tools like RVM or rbenv to allow the installation of Gems without administrator permission.

#### 2. Install project dependencies by running the command:

```bash
bundle install
```

#### 3. Run the project by executing the command:

```bash
ruby ./main.rb
```
