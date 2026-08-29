# Avatar da organização i-9.ai

## Decisão

O avatar usa a mesma marca quadrada já publicada como favicon no site atual da
i-9.ai. Não há símbolo novo, recomposição ou exploração de identidade.

Fonte canônica:

- repositório: `I-9-AI/i-9.ai`;
- arquivo: `public/favicon.svg`;
- commit de origem: `6bac95405cc8363f07b1b3bce7284dddaf6b8b2a`;
- SHA-256 do SVG: `030e27ab36b00f0413ac9e4d3f49ce27e62df107108bb27ff10b9f8f40e29cd1`.

O arquivo `i9-organization-avatar.svg` é uma cópia byte a byte dessa fonte. O
PNG preparado para o GitHub foi rasterizado sem recorte ou alteração visual:

```sh
rsvg-convert -w 512 -h 512 i9-organization-avatar.svg \
  -o i9-organization-avatar.png
```

- dimensões: `512 × 512`;
- formato: PNG RGBA;
- SHA-256: `be727107097ec5ca28bd7562143435b5b49f8f90e4a1fe28052f13065dc04672`;
- redução inspecionada em `64`, `48`, `32`, `24` e `16` px;
- cores preservadas: `#111E67`, `#C63825` e `#FFFFFF`.

Esta autorização é específica para o avatar e o perfil da organização. Ela não
cria uma nova suíte de logos nem substitui o contrato visual do site.

## Estado anterior e rollback

O avatar em uso antes da alteração planejada foi capturado em 29 de agosto de
2026:

- origem pública: `https://avatars.githubusercontent.com/u/220147853?v=4`;
- arquivo: `organization-avatar-before.png`;
- dimensões: `460 × 460`;
- SHA-256: `1012f8c6b42811c2e1b46dbb4998178c3829c5ec83e83c099477f2f41469139f`.

Se a troca for aplicada, um owner da organização pode fazer rollback abrindo
**Settings**, selecionando **Upload new picture** e reenviando
`organization-avatar-before.png`. Depois, deve confirmar por consulta pública
que o avatar voltou a corresponder ao hash ou à inspeção visual registrada
acima.
