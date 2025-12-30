# Buscador Carros Na Web

O [Carros Na Web] é um excelente portal de busca online para aqueles que estão procurando informações sobre carros, com dados detalhadas e imparciais de cada modelo. Embora poderosa, a pesquisa do site limita o usuário em alguns aspectos, como por exemplo criando faixas pré-definidas de valores para alguns parâmetros. Felizmente, o site expõe esses parâmetros na URL, o que permite documentar os filtros e fazer buscas personalizadas com controle total sobre cada valor, sem as limitações do formulário original do site. Esse site tem como objetivo facilitar a criação dessas buscas personalizadas.

## Como usar

1. Acesse o [site do projeto]
2. Preencha os campos com os valores desejados
3. A URL é gerada automaticamente conforme você preenche
4. Clique em **Abrir Busca** ou escaneie o **QR Code** para abrir pelo celular

## Estrutura do repositório

- `index.html` — a ferramenta em si (HTML + CSS + JS em arquivo único)
- `parametros_de_busca.md` — documentação dos parâmetros disponíveis

## Roadmap

- [ ] Documentar e incluir mais parâmetros do site
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
- O site Carros Na Web pode mudar sua estrutura a qualquer momento, o que pode quebrar a ferramenta

[Carros Na Web]: https://www.carrosnaweb.com.br/
[site do projeto]: http://busca-carros.hdmj.fastmail.org