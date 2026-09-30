# Neural IPTV OTA

## 7.0.18 / BLD-034 Canary
- OTA público alojado exclusivamente no GitHub.
- NeuralIPTVPlayer.nup cifrado.
- Sem token/PAT necessário na app para verificar ou descarregar atualizações.
- Validação do pacote cifrado por SHA-256 e tamanho.
- Desencriptação local e nova validação do NRO por SHA-256, tamanho e NRO0.
- Backup verificado e instalação transacional.
- Código-fonte permanece no repositório privado.
## 7.0.19 / BLD-035 Beta
- Reports DEV + Dev Eye passam para Google Drive.
- OTA continua público no GitHub com pacote cifrado.
- Sem token GitHub na app para atualizar.
## 7.0.20 / BLD-036 Beta
- Dev Eye Sentinela guarda capturas locais para análise UX/UI e design.
- Regista contexto de percurso, tempo entre ações e repetições.
- Capturas seguem no Report DEV para Google Drive.
- Contas IPTV e ecrãs sensíveis ficam fora das capturas automáticas.
- OTA continua público no GitHub com pacote cifrado.\n## 7.0.21 / BLD-037 Beta\n- Corrige loop de atualização em launchers/Sphaira.\n- Sincroniza executável ativo e caminho canónico Neural IPTV.\n- Valida envSetNextLoad em vez de sair silenciosamente.\n- Mantém Dev Eye Sentinela da BLD-036.\n- OTA público cifrado no GitHub.\n

## 7.0.22 / BLD-038 Beta
- Google Drive OAuth em 3 passos: credenciais, código Google, concluir ligação.
- Mantém fix de loop OTA BLD-037 e Dev Eye Sentinela.

## 1.0.1 / BLD-002 Beta
- Google OAuth: deteção automática de JSON válido por conteúdo, independentemente do nome.
- Pasta preferida: /switch/neural-iptv-player/google/.
- Também aceita JSON diretamente em /switch/neural-iptv-player/.
- Remove a introdução manual de Client ID e Client Secret na Switch.
- update_seq 2; update_epoch 1.

