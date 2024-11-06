# Cifra de César e Cifra por Transposição

- **César**
  - **Descriptografar:**
    - **Força Bruta:**
      - Viável para o problema, pois o maior deslocamento é de 26 casas, letras do alfabeto.
      - Mais demorado, percorre o texto 26 vezes.
      - Resposta sempre certa.
      - Ótimo para mensagens curtas.
    - **Análise de Frequência:**
      - Viável.
      - Menos demorado do que a força bruta, percorre o texto 2 vezes.
      - Resposta incerta.
      - Péssimo para mensagens curtas.
      - Quanto maior o texto, maior a chance de uma resposta correta.

- **Transposição**
  - **Descriptografar:**
    - **Força Bruta:**
      - Inviável, pois o problema é n!.
      - Resposta sempre certa.
      - Quanto maior a chave utilizada, mais difícil será de descriptografar por meio da força bruta.

## Referência
- [Análise de Frequência](https://www.gta.ufrj.br/grad/06_2/alexandre/criptoanalise.html)

