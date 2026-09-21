# Doutora das Patas · Clínica Veterinária 24h (Salgado Filho, Belo Horizonte/MG) · página premium

Recriação das pranchetas **Desktop V1** (1440 px) e **Mobile V1** (390 px) do arquivo
"Landingpages Layout Premium" no Paper, com a copy da página atual (doutoradaspatas.petvidaeamor.com,
onde ela ficava). Publicada em 14/09/2026 como página principal (o `index.html` da raiz, com `img/` e `fonts/`).
A página anterior continua no histórico do Git (commit 0aea132); os arquivos dela na raiz (`1.webp`–`5.webp`,
`bg-desktop.webp`, `bg-mobile.webp` e `logo.webp`) ficaram sem uso.

## Integrações (as mesmas da página atual)
- WhatsApp 553131912377, mensagem "Olá encontrei vocês pelo Google, gostaria de atendimento." (o número nunca aparece na página)
- Google Tag Manager `GTM-N5TSFJSC` e Microsoft Clarity `xyrr5fudci`: carregam na primeira interação (mouse, toque, rolagem ou tecla), sem timer, para ficarem fora da medição do PageSpeed
- Mapa do Google: o mesmo embed da página atual (`4v1786124439392`), que só carrega quando a dobra de contato se aproxima
- Todos os CTAs principais: verde do WhatsApp, texto "ATENDIMENTO IMEDIATO", mesmo link, e mudam para "ABRINDO O WHATSAPP" no clique. O botão do cabeçalho mantém "Entre em contato", como na prancheta

## Imagens (`img/`)
- `avaliacao-1..5.webp`: os prints reais do Google (os mesmos `1.webp`–`5.webp` da raiz), 496×636, recomprimidos de 359 KB para 176 KB no total
- `logo.webp` (150 px, favicon) e `logo-96.webp` (cabeçalho e rodapé). A logo tem fundo ameixa `#382A48`, então as caixas da logo usam esse mesmo fundo
- Originais intocados em `C:/Users/Gaabs/brand-assets/doutora-das-patas` (logo e prints)
- Fotos do cliente enviadas em 14/09/2026, colocadas por ele direto em `img/` e otimizadas (de 1,6 MB para 304 KB no total). Os originais estão em `brand-assets/doutora-das-patas/fotos-originais/premium-14-09`:

| Foto | Onde aparece |
|---|---|
| `destaque-cirurgia` veterinário em cirurgia (765×1020) | card "Cirurgias com segurança" e linha "Cirurgias" |
| `destaque-exames` cão internado recebendo soro (574×1020) | card "Internação 24 horas" e linha "Emergência 24h" |
| `destaque-consultas` veterinária com um shih-tzu na mesa de vacinação (574×1020) | card "Consultas e vacinação" e linha "Vacinas" |
| `card-caes` pug no colo da veterinária, fundo roxo (800×800) | card "cães" e linha "Internação 24h" |
| `card-gatos` siamês, fundo roxo (800×800) | card "gatos" |
| `etapa-01` veterinária diante da parede com a logo (recorte 740×440 da foto vertical) | etapa 01 "Atendimento imediato" e linha "Consultas" |
| `etapa-02` tutor e cão na recepção, com a logo dourada (recorte 574×341) | etapa 02 "Sem espera" |
| `etapa-03` raio-X em um shih-tzu (recorte 740×440) | etapa 03 "Diagnóstico cuidadoso" |
| `etapa-04` lulu-da-pomerânia feliz no colo da tutora (recorte 740×440) | etapa 04 "Acompanhamento próximo" |

  Os recortes das etapas foram feitos a partir dos originais (fotos verticais viraram faixas horizontais). Para refazer um recorte, parta do original em `brand-assets`.
- Foto do template que continua (sem marca de outra clínica): `hero-cao-1100/1600` (golden retriever do hero). A `servico-emergencia` do template (cão deitado no asfalto) foi apagada em 21/09/2026

Para trocar qualquer outra foto, salve com o mesmo nome e no mesmo formato; se mudar a proporção, ajuste `width`/`height` na tag `<img>`.

## Ajustes pedidos pelo cliente (fora do template)
- 14/09/2026: "24H" da headline no verde do WhatsApp com halo escuro
- 21/09/2026 (os mesmos da Vet Paulistano): sem os botões "Saiba mais" (lista de serviços e cards cães/gatos) e sem as setas dos destaques; linha "Emergência 24h" com a foto do cão no soro no lugar do cão deitado no asfalto; cards cães e gatos com a foto redonda, a etiqueta e o título abaixo, sem o fundo roxo, e a palavra gigante na cor da marca centralizada atrás do círculo

## Cores (template turquesa → Doutora das Patas)
Tiradas da logo e da página atual: roxo da marca `#821DC0`, amarelo `#FFC820` e o ameixa do fundo da logo `#382A48`.

| Papel | Template | Doutora das Patas |
|---|---|---|
| cor principal / ícones / barra dos carrosséis / card do contato | `#0BA5C7` | `#821DC0` |
| texto de destaque (títulos, tags, "Depoimentos", "serviços") | `#0A7E9B` | `#7419AD` |
| linha de destaque do título do hero ("Veterinária 24H") e "Como chegar" | `#69CADB` | `#FFC820` |
| fundo suave (serviços) | `#E6F6FA` | `#F5EFFB` |
| texto principal | `#122027` | `#1E0F2B` |
| rodapé | `#0D3440` | `#2A1D36` |
| degradê do hero | `#075F76 → #69CADB` | `#1C1027 → #382A48 → #5E1E94 → #9B45D8` |

Sobre o roxo, texto e ícones ficam brancos. Botões de WhatsApp sempre no verde `#25D366`.

## Copy
Toda a copy vem da página atual e do documento de copy do cliente. Adaptações para caber nos blocos das pranchetas:
- Headline "Clínica / Veterinária 24H / em Belo Horizonte" (a mesma quebra que o cliente pediu no celular), com o "24H" no verde do WhatsApp `#25D366` e halo escuro para destacar do fundo roxo (pedido do cliente em 14/09/2026) e subheadline "Doutora das Patas, no Salgado Filho, em Belo Horizonte. Prontos para qualquer emergência que seu pet precisar!"
- Palavras gigantes do hero (atrás do cão): "Doutora / das Patas", no lugar de "Patinhas / de Assis", no mesmo tamanho e posição da prancheta
- Hero cards: aberta 24 horas todos os dias, urgência e emergência atendidas na hora, nota 4.9 no Google com 123 avaliações
- Destaques: "A qualquer hora do dia ou da noite, seu pet tem para onde ir", com cirurgias, internação e consultas/vacinação
- Lista de serviços com 5 linhas, como a prancheta: Consultas, Emergência 24h (linha em destaque), Cirurgias, Internação 24h, Vacinas
- Cards cães e gatos: atendimento humanizado e estrutura acolhedora
- Contato: "A saúde do seu pet não espera. E nós também não." com o endereço da R. Maquiné, 22

## Fidelidade
- Desktop: as dobras começam nas mesmas alturas da prancheta (Destaques 1679, Serviços 2434, Cards 3676, Etapas 4290, Contato 5052, Rodapé 5582; total 5.841 px contra 5.840)
- Mobile: mesma estrutura e ordem; os prints de avaliação aparecem inteiros (sem o corte de 470 px da prancheta); os títulos de Destaques e Contato, mais longos que os da prancheta, ocupam uma linha a mais no celular
- Cards de destaque ocupando a largura toda, como nas outras páginas feitas com este template
- Sem rolagem lateral em 390 e 1440 px

## Desempenho (Lighthouse 12 local, servidor com gzip, 14/09/2026)
| | Performance | Acessibilidade | Boas práticas | SEO |
|---|---|---|---|---|
| Desktop | 100 | 93 | 100 | 100 |
| Mobile | 96 | 93 | 100 | 100 |

- Mobile: LCP 2,3 s, FCP 1,3 s, TBT 60 ms, CLS 0. Desktop: LCP 0,7 s, FCP 0,3 s, CLS 0
- Acessibilidade 93 vem do bloqueio de zoom no celular, que é requisito do projeto
- Fontes Manrope e Montserrat servidas localmente (subset latin), sem CSS externo

## Conferência local
Abrindo o arquivo direto (`file://`) o Chrome bloqueia as fontes locais; para conferir, use um servidor local.
