PRF QUEST — PRIMEIRA VERSÃO FUNCIONAL
=====================================

O que já funciona:
- Interface responsiva em tema escuro.
- Navegação entre início, disciplinas, caderno de erros e desempenho.
- Quiz de múltipla escolha com feedback.
- Desafio de palavra-chave (estilo Wordle).
- Jogo da forca.
- Verdadeiro ou falso.
- XP, nível, sequência diária, acertos e erros.
- Salvamento local do progresso.
- PWA com cache para abrir offline após o primeiro carregamento.

IMPORTANTE SOBRE O CONTEÚDO:
Esta versão é um protótipo técnico. As questões incluídas são exemplos autorais de fundamentos gerais para testar o funcionamento. Elas NÃO são questões oficiais de provas anteriores e NÃO representam um edital vigente. A grade de disciplinas também é provisória. Antes de publicar o banco definitivo, será necessário validar o edital específico do cargo administrativo da PRF e vincular cada questão à sua fonte oficial.

Como testar no computador:
1. Extraia a pasta.
2. Abra um terminal dentro dela.
3. Execute: python -m http.server 8000
4. Acesse http://localhost:8000

Como instalar no Android:
1. Hospede a pasta em um serviço HTTPS (por exemplo, GitHub Pages).
2. Abra o endereço no Chrome Android.
3. Use o menu do Chrome > Instalar app / Adicionar à tela inicial.
4. Abra uma vez com internet; depois o cache permite uso offline.

O progresso fica salvo no armazenamento local do navegador/aplicativo. Limpar os dados do navegador pode apagar o progresso.
