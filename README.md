<h1 align="center">CRUD React</h1>

<p align="center">
  <img width="170px" height="170px" src="https://user-images.githubusercontent.com/73148019/160190250-ec043f4a-09f5-4d2b-927c-e8f2cbce05fb.png" title="by Pixel perfect">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
</p>

<p align="center">
  <a href="https://github.com/arriaoedu123/boxshadow-generator/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge"/>
  </a>
</p>

***

<br>

## Sobre

Esse projeto é uma API de cadastro de pessoas referente ao desafio do processo seletivo da Compugraf, feito com NodeJS, ReactJS e MySQL.

<br>

***

<br>

## Como usar

Primeiramente, faça o seguinte comando SQL no banco de dados
```
CREATE TABLE `crudreact`.`pessoas`(
    `id` INT NOT NULL AUTO_INCREMENT,
    `nome` VARCHAR(120) NOT NULL,
    `sobrenome` VARCHAR(120) NOT NULL,
    `nacionalidade` VARCHAR(120) NOT NULL,
    `cep` VARCHAR(9) NOT NULL,
    `estado` VARCHAR(2) NOT NULL,
    `cidade` VARCHAR(120) NOT NULL,
    `logradouro` VARCHAR(120) NOT NULL,
    `email` VARCHAR(120) NOT NULL,
    `telefone` VARCHAR(14) NOT NULL,
    PRIMARY KEY(`id`)
) ENGINE = INNODB;
```

<br>

Dessa vez faça o seguinte comando no terminal em que o projeto está aberto
```
cd client/
yarn add axios react-hook-form react-icons react-ripples
```

<br>

Agora, vamos instalar as dependências do server-side
```
cd server/
yarn add express mysql cors
```

<br>

Pronto!! Todas as dependências foram instalar e agora é só iniciar o servidor
```
cd client/
yarn start

cd server/
node index.js
```

***
