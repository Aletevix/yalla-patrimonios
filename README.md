# Yalla — Controle de Equipamentos

Sistema web de controle de patrimônios e equipamentos da Yalla Car.

## Acesso
- **Time (visualização + PDF):** abra o link do sistema. Não precisa de login.
- **Edição (designar, cadastrar, desligar):** clique em **Ativar edição** e cole um token do GitHub com permissão *Contents: Read and write* neste repositório. O token fica salvo apenas no seu navegador.

## Como funciona
- Os dados ficam em `dados.json` neste repositório.
- O sistema lê os dados sempre atualizados e, no modo editor, grava as alterações de volta via API do GitHub.
- O relatório em PDF é gerado no próprio navegador.

## Arquivos
- `index.html` — o sistema
- `dados.json` — base de patrimônios e colaboradores
- `vendor/` — bibliotecas de geração de PDF (jsPDF)
