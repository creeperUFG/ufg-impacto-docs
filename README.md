<h1 align="center">SAD
</h1>
<h3 align="center">
Projeto UFG Impacto
</h3>

## Tabela de conteúdos

 * [Sobre o projeto](#-sobre-o-projeto)
 * [Layout](#-layout)
 * [Arquitetura](#arquitetura)
 * [Pré-requisitos](#pré-requisitos)
 * [Rodando o Projeto](#rodando-o-projeto)
 * [Como contribuir](#-como-contribuir)
 * [Autores](#-autores)

## 💻 Sobre o projeto

A UFG é uma instituição que preza pela formação de profissionais comprometidos com a transformação e desenvolvimento da sociedade. Está entre seus objetivos, se desenvolver cada vez mais para melhorar sua qualidade de ensino, pesquisa e extensão.
Levando esses objetivos em consideração, chegamos a conclusão de que é de extrema importância um sistema que apresente os indicadores de impacto social e econômico da UFG na sociedade.
O sistema UFG Impacto dispobilizará indicadores tais como os tipos de projetos desenvolvidos por cada unidade acadêmica (Ensino, Pesquisa e Extensão), uma word cloud por tipo de projeto com o conteúdo do resumo do projeto, empresas criadas e/ou mantidas por egressos da UFG, Quantidade de empregos gerados por essas empresas e quantidade de egressos em relação às vagas oferecidas por cotas e vagas no geral.


## 🎨 Layout

O layout do projeto está disponível em:
- [Web](https://www.figma.com/file/ikPCY9V3rPmLrtL0EWox2F/Untitled?node-id=0%3A1).
- [Mobile](https://www.figma.com/file/Wl3U6RMNMo0CTJd2ehJ0hV/UFGImpactoMobile?node-id=0%3A1).

### Arquitetura

- [ ] Diagrama Arquitetural


### Pré-requisitos

Antes de dar início, certifique-se que tenha em sua máquina:
- [ ] Node versão 12.16.3 ou superior
- [ ] Yarn versão 1.22.4 ou superior


### Rodando o projeto

```bash
1. Clone este repositório
$ git clone https://github.com/creeperUFG/ufg-impacto-server.git

2. Acesse a pasta do projeto no seu terminal/cmd
$ cd ufg-impacto-server

3. Instale as dependências
$ yarn

5. Configure o .env em ./ufg-impacto-server com as seguintes variáveis de ambiente
SERVER_URL = ip da maquina onde será executado o servidor
SERVER_PORT = porta onde será executado o servidor
DB_HOST = IP para o servidor do banco de dados
DB_USER = seu usuario do banco de dados
DB_PASS = sua senha do banco de dados
DB = ufgimpacto

6. Execute a aplicação
$ yarn start

```

## 💡 Como contribuir

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`

## 👨‍💻 Autores

* [Alan Brito Barros](https://github.com/alanbbarros)
* [Amanda Lobo Gomes](https://github.com/amandalobo)
* [Fernando Severino Almeida](https://github.com/fernandosev)
* [Michelly Silva Lima](https://github.com/MichellyLima)