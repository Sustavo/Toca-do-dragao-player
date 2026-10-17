# Player Toca do Dragão

Distribuição dos instaladores do Player para Computador. O código-fonte permanece em um repositório privado.

## Windows 0.3.3 experimental

[Baixar o instalador Windows x64](https://github.com/Sustavo/Toca-do-dragao-player/releases/download/player-windows-v0.3.3-experimental/Toca-do-Dragao-Player-Setup-x64.exe) · [Notas e SHA-256](https://github.com/Sustavo/Toca-do-dragao-player/releases/tag/player-windows-v0.3.3-experimental)

Inclui importação de playlists Spotify por link, seleção da música no computador local e correção do encerramento da captura. Autorize novamente o Spotify para permitir controle da reprodução e leitura dos dispositivos.

No Windows 10, o modo opcional `--legacy-output-capture` transmite toda a saída de áudio, incluindo sons de outros aplicativos e notificações. Esse modo é identificado na interface e foi testado em Windows 10 Pro build 19045 com áudio chegando à sala web, pausa/retomada, busca e importação de 48 músicas.

O modo padrão captura apenas o processo Spotify. Sua validação física no Windows 11 e sessões longas continuam pendentes. O instalador não possui assinatura digital de editor.

## Linux 0.2.0 beta

[Baixar para Ubuntu 24.04 amd64](https://github.com/Sustavo/Toca-do-dragao-player/releases/download/player-v0.2.0-beta/Toca-do-Dragao-Player-amd64.deb). Requer Spotify oficial e PipeWire/PulseAudio.

Use Conexões → Exportar diagnóstico no Player para obter informações técnicas sem incluir senhas ou tokens.