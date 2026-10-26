# AudensCut: instaladores

Aqui ficam só os instaladores do **AudensCut**, o editor de vídeo da Audens. O código-fonte é privado.

## Instalar

1. Abra a [versão mais recente](https://github.com/audenscompanyprojects-beep/AudensCut-releases/releases/latest).
2. Baixe o `AudensCut-Setup-<versão>.exe` e rode.
3. O instalador não tem assinatura digital. Se aparecer "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo**.

Depois de instalado, o AudensCut **se atualiza sozinho**: ao abrir, ele confere se tem versão nova, baixa em segundo plano e pergunta se quer reiniciar pra atualizar. Os projetos são mantidos.

Requisitos: Windows 10 ou 11, 64 bits.

## Como as versões são geradas

O workflow [`build.yml`](.github/workflows/build.yml) compila o AudensCut a partir de uma tag do repositório privado (lido com uma chave só de leitura) e publica o instalador como release aqui. Ele roda manualmente: **Actions → Build installer → Run workflow**.

## Licença

O AudensCut é distribuído sob a licença MIT e é baseado no [OpenCut](https://github.com/OpenCut-app/OpenCut) e no [OpenCut Classic](https://github.com/OpenCut-app/opencut-classic) (MIT). Os avisos de licença, incluindo os de bibliotecas de terceiros, vão junto com o programa instalado (`LICENSE` e `NOTICE.md`, na pasta `resources`). O AudensCut não é afiliado ao projeto OpenCut.
