# Document_generator

# Olá!
Este projeto tem como objetivo a construção de um gerador de documentos automatico, para seus outros projetos de programação e desenvolvimento.
Confira abaixo a estrutura do projeto.

# Arquitetura do Projeto

- Analisador de Código:

Um módulo que percorre o código-fonte, identifica comentários/docstrings e extrai informações importantes.
Pode suportar múltiplas linguagens, começando com uma (Python, JavaScript) e expandindo para outras.

- Gerador de Documentação:

Com base nos comentários extraídos, gerar a documentação.
Suporte a diferentes formatos de saída (Markdown, HTML).

- Interface do Usuário:

Uma interface de linha de comando (CLI) simples que permita aos desenvolvedores configurar e rodar o gerador de documentação.
Suporte para personalização, como especificar o formato de saída, selecionar arquivos, etc.
