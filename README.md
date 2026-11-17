# FINCORE — primeira versão

Aplicativo financeiro pessoal em português, com visual dark preto e verde.

## Recursos
- Entradas e despesas com data, categoria e descrição
- Dashboard com receitas, despesas e saldo
- Meta de faturamento configurável
- Resumo de despesas por categoria
- Histórico e exportação CSV
- Dados armazenados localmente no aparelho/navegador

## Gerar APK pelo celular
1. Crie uma conta no GitHub (se ainda não tiver).
2. Crie um repositório novo chamado `fincore`.
3. Envie todos os arquivos desta pasta para o repositório, mantendo a pasta `.github/workflows`.
4. Abra a aba **Actions** do repositório e execute **Build FINCORE APK** (ou aguarde o build após enviar para a branch `main`).
5. Quando terminar, abra a execução e baixe o artefato **FINCORE-debug-apk**.
6. Extraia o ZIP e instale `app-debug.apk` no Android. Talvez seja necessário permitir instalação pelo navegador/gerenciador de arquivos.

## Observações importantes
- Esta é uma versão inicial para uso pessoal, sem login e sem sincronização em nuvem.
- Os lançamentos ficam no armazenamento local do app. Desinstalar ou limpar os dados do app pode apagá-los; use Exportar backup (CSV).
- A meta nesta primeira versão compara o total de entradas registradas com a meta configurada; a meta diária/mensal será refinada na próxima versão.
- APK debug para teste, não é uma versão publicada na Play Store.
