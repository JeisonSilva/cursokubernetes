---
applyTo: '*Commits*'
---
Sempre que definir o texto do commit utilize a forma pt-br.
Indique sempre no commit o que foi feito, e não o que será feito.
Use o tempo verbal no passado, como se já tivesse sido feito.
Exemplo: "Corrigiu o bug de login" ao invés de "Corrigindo o bug de login" ou "Corrigirá o bug de login".
Evite usar palavras como "melhorias" ou "ajustes" sem especificar o que foi melhorado ou ajustado.
Use mensagens de commit claras e descritivas, que ajudem a entender o que foi alterado no código.
Evite mensagens genéricas como "Atualização" ou "Correção de bugs" sem detalhes adicionais.

Use semantic commits quando possível, seguindo o padrão:
- feat: para novas funcionalidades
- fix: para correções de bugs
- docs: para alterações na documentação
- style: para alterações de estilo que não afetam a lógica do código
- refactor: para alterações na estrutura do código que não adicionam funcionalidades nem corrigem bugs
- test: para adição ou modificação de testes
- chore: para tarefas de manutenção que não afetam o código-fonte (como atualizações de dependências)
Exemplo de mensagem de commit:
```