# Projeto de automação com Postman

Projeto de automação com Postman desenvolvido pela Squad LockeKey no Qa.Coders Academy

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

## Projeto Desenvolvido por: 

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/73588768?v=4" width=90><br/><sub>Amanda Oliveira</sub>](https://github.com/amandatec)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/amandaoliveira--/)](https://www.linkedin.com/in/amandaoliveira--/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/33519484?v=4" width=90><br/><sub>Amauri Almeida</sub>](https://github.com/amaurialmeida)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/amauri-almeida26/)](https://www.linkedin.com/in/amauri-almeida26/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/109545654?v=4" width=90><br/><sub>Andreza Oliveira</sub>](https://github.com/Andreza0593)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andreza-oliveira-02a7ab163)](https://www.linkedin.com/in/andreza-oliveira-02a7ab163) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/148631954?v=4" width=90><br/><sub>Patricia Vitoriano</sub>](https://github.com/PatriciaVitoriano)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/patricia-castro-vitoriano)](https://www.linkedin.com/in/patricia-castro-vitoriano) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/116967975?v=4" width=90><br/><sub>Thaís Marchetti</sub>](https://github.com/thaisconto)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thaismarchetticonto/)](https://www.linkedin.com/in/thaismarchetticonto/)
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
