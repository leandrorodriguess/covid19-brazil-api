<p align="center">
  <img src="/api/public/logo.svg" width="90px" float="center"/>
</p>
<h1 align="center">COVID-19 Brazil API</h1>
<p align="center">
  <strong>Notificação de casos de doença pelo coronavírus 2019 (COVID-19) no Brasil</strong>
</p>

**Chat: _[WhatsApp](https://chat.whatsapp.com/L7AY3Bpv12Y7JzjNTjbdBX), [Discord](https://discord.gg/fgs5v4)_**

## Translations

[English version](./README-US.md) 🇺🇸

## ⚠️ Atenção

O governo retirou a [página](http://plataforma.saude.gov.br/novocoronavirus/) com estatísticas oficiais. Os dados antigos tinham casos suspeitos e descartados. Na nova divulgação do governo, são divulgados apenas o número de casos e de mortes.
Portando os campos **suspects** e **refuses** não são consistentes, a partir do relatório de **18/02/2020** data que a plataforma do governo parou.

## [Site](https://covid19-brazil-api.now.sh/)

Página de divulção do projeto mostrando dados que são consumidos via api.

<div align="center">
  <br>
    <img src="static/screenshot.png" alt="Screenshot1" width="80%">
  <br>
</div>

## Motivo 🤔

Fornecer uma API JSON com dados atualizados sobre o avanço do coronavírus no Brasil, assim como em outros países.

## Datasource 💽

- [CSSEGISandData](https://github.com/CSSEGISandData/COVID-19)
- [Ministério da Saúde](http://saude.gov.br)
- [Coronavírus Brasil](https://covid.saude.gov.br/)

## Showcase 🎯

### Sites 💻

- [Levantelab](https://levantelab.com.br/mapa_coronavirus)
- [COVID19 Tracker](https://apex.oracle.com/pls/apex/f?p=82495)
- [SITE sitecovid19](https://sitecovid19.netlify.com/)
- [SITE Informecovid19](https://www.informecovid19.com.br/)

### Apps 📱

- [APP COVID-19 Estatísticas](https://github.com/robsonsilv4/covid19_statistics)

### Outros
- [CLI: alertcovid19](https://github.com/renanbastos93/alertcovid19)

## Servidor de desenvolvimento 🚀

Clonando o projeto:

```
git clone https://github.com/devarthurribeiro/covid19-brazil-api.git
```

Navegando até a pasta do projeto:

```
cd covid19-brazil-api/api
```

Baixando as dependências do projeto

```bash
yarn
```

Rodando o projeto

```bash
yarn dev
```

Visite [http://localhost:3000](http://localhost:3000) com o seu navegador para ver o resultado.

## Docs 📄

- [Site](https://covid19-brazil-api-docs.now.sh/)

## Bandeiras 🇧🇷

Para carregar a bandeira do estado:
```
https://devarthurribeiro.github.io/covid19-brazil-api/static/flags/{UF}.png
```
Onde o {UF} precisa ser a sigla do estado, Exemplo: SP, RJ ou RN.

## Base url 🔌

Todas chamadas devem usar a url base:
```
https://covid19-brazil-api.now.sh
```

## License 📝

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](LICENSE) file for details.

## Ajude o projeto 🤝

<a href="https://opencollective.com/covid19-brazil-api/donate" target="_blank">
  <img src="https://opencollective.com/corvid19-brazil-api/donate/button@2x.png?color=blue" width=300 />
</a>

[Paypal](https://www.paypal.com/donate/?token=1Ap7ElpjfDDlka5EIL6ddUbOnd1hvOmQPBO6wbFVGD7tOrQTOC7oa6yqyenGTQ9_edG70W&country.x=BR&locale.x=)

## Contribuidores

<table>
  <tr>
    <td align="center"><a href="https://github.com/Lukazovic"><img src="https://avatars0.githubusercontent.com/u/54550926?s=460&u=cdeeac652ce0597a986fbdcff6e249ad27a1f1da&v=4" width="100px;" alt=""/><br /><sub><b>Lucas Vieira</b></sub></a><br /><a href="https://github.com/devarthurribeiro/covid19-brazil-api/commits?author=Lukazovic" title="Code">💻</a></a></td>
  <tr>
</table>

## Autor

<table>
  <tr>
    <td align="center"><a href="https://github.com/devarthurribeiro"><img src="https://avatars1.githubusercontent.com/u/12974798?s=460&u=6a69934913c6f56d74fdf9c80793881d4cfb7bf6&v=4" width="100px;" alt=""/><br /><sub><b>Arthur Ribeiro</b></sub></a><br /><a href="https://github.com/devarthurribeiro/covid19-brazil-api/commits?author=devarthurribeiro" title="Code">💻</a> <a href="#devarthurribeiro" title="Design">🎨</a></td>
  <tr>
</table>
