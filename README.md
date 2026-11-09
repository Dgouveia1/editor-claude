# Editor Claude

Editor de vídeos curtos (Reels, TikTok, Shorts) em que você conversa com o Claude e ele edita: corta silêncios,
legenda, reenquadra no rosto, aplica cor, transições, animações, narração com voz de IA e exporta em MP4.

## Baixar

**[⬇ Baixar para Windows (EditorClaudeSetup.exe)](https://github.com/Dgouveia1/editor-claude/releases/latest/download/EditorClaudeSetup.exe)**

Todas as versões: [Releases](https://github.com/Dgouveia1/editor-claude/releases)

## Instalar (Windows 10/11, 64 bits)

1. Abra o `EditorClaudeSetup.exe`. Se aparecer **"O Windows protegeu o computador"**, clique em
   **Mais informações** → **Executar assim mesmo** (o app ainda não tem assinatura de desenvolvedor).
2. O app se instala sozinho e cria o atalho **Editor Claude** na área de trabalho e no menu Iniciar.
3. Para conectar o Claude, instale o [Claude Code](https://claude.com/claude-code). No PowerShell:
   ```
   irm https://claude.ai/install.ps1 | iex
   claude
   ```
   O segundo comando abre o navegador para você entrar na sua conta. Também dá para usar uma chave de API
   da Anthropic em ⚙ Configurações.

Na primeira transcrição o app baixa o Whisper (~470 MB) e, na primeira exportação, o navegador de render (~100 MB).

## Atualizar

No app: ⚙ Configurações → **Baixar nova versão**. Baixe o `EditorClaudeSetup.exe` novo e abra por cima.
Seus projetos (em Documentos\EditorClaude) e configurações continuam.

## Desinstalar

Configurações do Windows → Aplicativos → Editor Claude → Desinstalar. A pasta Documentos\EditorClaude é mantida.
