# Projeto de automação com Postman

Projeto de automação com Postman e emissão de Relatório Newman

## Tecnologias utilizadas

- Postman web version

- node v16.18.0

- newman v6.0.0

- newman reporter-htmlextra

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)

- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)

```bash
npm install -g newman
```

- Terceiro: realize a instalação da dependência dos relatórios (opcional) 
 [baixe aqui](https://www.npmjs.com/package/newman-reporter-htmlextra)

```bash
npm install -g newman-reporter-htmlextra
```

## Como rodar os testes

### Pelo Postman web ou desktop

- Importe a collection e as variáveis de ambiente e globals

- Execute a seguinte linha de comando para rodar os testes

 ```bash
    newman run Amanda-ApiLockekey.json -e env-automacao.json -g env-global.json -r cli
  ```

## Execução com Report html-extra (opcional)

```bash
newman run Amanda-ApiLockekey.json -e env-automacao.json -g env-global.json -r htmlextra
```

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos teses e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato

  <a href="https://www.linkedin.com/in/amandaoliveira--/" style="margin-right: 1vw" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="http://discordapp.com/users/Amandatec#4699" style="margin-right: 1vw"  target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/amanda_almajor/" style="margin-right: 1vw"  target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:amandatec.oliveira@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

 Made by [**Amandatec**](https://www.linkedin.com/in/amandaoliveira--/)
