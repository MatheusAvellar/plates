# Plates

Possibilita ao usuário verificar se uma palavra pode ser transformada em uma placa de carro do novo modelo do Mercosul (e.g. BANANAS -> BAN4N45). Além disso, também possui abaixo uma lista com todas as palavras do [Dicionário Aberto](http://dicionario-aberto.net) que encaixam no novo modelo de placa (e.g. CORAÇÃO -> COR4C40).

Você pode conferir a [demo online](https://matheusavellar.github.io/plates/index) ou ver os prints abaixo:

<p align="center">
  <img src="https://i.imgur.com/4OjcQ7o.png">
</p>

---

Exemplo de palavra inválida (i.e. que não pode ser transformada em placa):

<p align="center">
  <img src="https://i.imgur.com/2gbCFbb.png">
</p>

O problema está no fato de que "R" não tem uma representação numérica como "A" (4) ou "O" (0).


## TODO

- [ ] Indicar *onde* na palavra está o erro (7 `<input>`'s?)
- [ ] Design: separar a funcionalidade principal das palavras do dicionário
- [ ] Colocar uma bandeirinha fofa do Brasil no topo direito da placa
