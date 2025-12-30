# Buscador Carros Na Web

Ferramenta para montar URLs de busca avançada no site [Carros Na Web](https://www.carrosnaweb.com.br/).

![Screenshot do Buscador](screenshot.png)
<!-- Substitua screenshot.png pelo nome do arquivo de imagem -->

## Por que isso existe?

O Carros Na Web tem um catálogo excelente, mas o formulário de busca avançada limita os valores a faixas pré-definidas. Por exemplo: peso/torque só aceita de 20 a 100 em intervalos de 5, porta-malas vai de 50 a 600 em incrementos de 50, e por aí vai.

Felizmente, o site expõe os parâmetros na URL. Isso me permitiu documentar os filtros e criar essa ferramenta que dá controle total sobre cada valor — sem as limitações do formulário original.

## Como usar

1. Abra o arquivo `index.html` no navegador (ou acesse online)
2. Preencha os campos que desejar com os valores exatos
3. A URL é gerada automaticamente conforme você preenche
4. Clique em **Abrir Busca** ou escaneie o **QR Code** pelo celular

## Estrutura

- `index.html` — a ferramenta em si (HTML + CSS + JS em arquivo único)
- `parametros_de_busca.md` — documentação dos parâmetros disponíveis
- `buscador-tema-neon.html` — tema alternativo (backup)

## Roadmap

- [ ] Documentar mais parâmetros do site
- [ ] Adicionar listas de sugestões para fabricantes, modelos, etc.
- [ ] Salvar buscas favoritas no navegador (localStorage)
- [ ] Histórico das últimas buscas
- [ ] Presets de configurações comuns (econômico, esportivo, familiar)
- [ ] Contador de filtros ativos
- [ ] Melhorias de acessibilidade
- [ ] Toggle de tema claro/escuro

## Observações

- Projeto pessoal para uso próprio, compartilhado caso seja útil para alguém
- Os parâmetros documentados são os que mais me interessam; o site pode ter outros
- O site Carros Na Web pode mudar sua estrutura a qualquer momento, o que quebraria a ferramenta

