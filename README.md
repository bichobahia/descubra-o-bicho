# Descubra o Bicho pela Milhar

Ferramenta online gratuita: digite uma milhar e veja na hora a **centena**, a **dezena**, o **grupo** e o **bicho** correspondente.

🔗 **Usar online:** https://bichobahia.github.io/descubra-o-bicho/

## Recursos

- Conversão instantânea milhar → centena → dezena → grupo → bicho
- Tabela dos 25 bichos com destaque do grupo encontrado
- Funciona no celular, sem cadastro e sem anúncios
- Um único arquivo `index.html`, sem dependências

## Como o cálculo funciona

```
grupo = ceil(dezena / 4)   // a dezena 00 conta como 100
```

Exemplo: milhar 3462 → dezena 62 → 62 / 4 = 15,5 → grupo 16 (Leão).

## Rodar localmente

Basta abrir o `index.html` no navegador.

## Sobre

Projeto open source mantido pelo Bicho Bahia (https://bichobahia.com.br/). Licença MIT.

Conteúdo apenas informativo. A ferramenta não prevê resultados e não aceitamos apostas.
