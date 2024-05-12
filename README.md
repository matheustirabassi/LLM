<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#about-the-project">Sobre</a>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## Sobre

Analisa e classifica o feedback do cliente considerando a satisfação e sentimento em relação ao
produto para retornar uma nota, lista de pontos positivos e negativos em JSON.

### Exemplo

Entrada:
```
O bolo de leite Ninho não agradou, a Palha Italiana pode melhorar e os preços idem, porém é só uma questão de ajuste.
Recomendo mesmo assim!!
```

Saída:
```
{
  "feedback_result": 3,
  "positive_points": [
    "O cliente recomenda o produto mesmo com os problemas.",
    "O cliente acredita que os problemas podem ser ajustados."
  ],
  "negative_points": [
    "O bolo de leite Ninho não agradou.",
    "A Palha Italiana pode melhorar.",
    "Os preços podem melhorar.
  ]
}
```

## Roadmap

- [x] Adicionar classificador de feedback
- [ ] Adicionar servidor REST para a API


## Contato

Matheus Tirabassi - [Linkedin](https://www.linkedin.com/in/matheus-henrique-tirabassi-466022201/) - matheustirabassi16@gmail.com

Link do projeto: [https://github.com/matheustirabassi/feedback-classifier](https://github.com/matheustirabassi/feedback-classifier)

<p align="right">(<a href="#top">voltar ao início</a>)</p>