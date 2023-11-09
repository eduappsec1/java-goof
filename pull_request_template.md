Mudanças propostas nesse Pull Request:

Requisitos de seguranca - ASVS:
.

   - [ ] No codigo todas as inputs (campos de formulário HTML, solicitações REST, parâmetros de URL, cabeçalhos HTTP, cookies, arquivos em lote, feeds RSS, etc.) são validadas usando validação positiva (listas de permissão)
   - [ ] Não existe concatenação de strings nas queries do BD
   - [ ] Código não possui credenciais chumbadas (hardcoded)
   - [ ] A codificação de output é realizada de forma correta
