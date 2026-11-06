# Jeitaki Android — 3 APKs

Este repositório contém o fluxo automático **Jeitaki — Compilar 3 APKs** do GitHub Actions.

## Para iniciar (uma única vez)

1. Baixe o arquivo **Jeitaki_3_Apps_Android_Projeto_Compilacao.zip** fornecido pelo ChatGPT.
2. No GitHub, abra **Add file → Upload files**, em https://github.com/ianmatheus1599-coder/jeitaki-android/upload/main
3. Envie o arquivo ZIP **sem descompactar nem renomear**. Clique **Commit changes**.
4. O GitHub Actions iniciará 3 compilações automaticamente: cliente, profissional, admin.
5. Abra https://github.com/ianmatheus1599-coder/jeitaki-android/actions → execução mais recente → Artifacts e baixe os APKs.

Cada artefato inclui um APK Android de **teste (debug)**. O app precisa de Firebase Authentication/Firestore configurados e regras de segurança auditadas para utilização pública. APK debug não é a versão de produção.

O fluxo também pode ser executado manualmente em Actions → Jeitaki — Compilar 3 APKs → Run workflow depois que o ZIP estiver presente.

**Atenção:** este repositório está público. Evite enviar chaves privadas, senhas e arquivos de credenciais de serviços. A configuração Firebase web usa identificadores públicos, mas o banco continua dependendo de regras Firestore corretas.
