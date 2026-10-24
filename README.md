# Missão Clima — conceito público e protótipo 3D

Site estático em `dist/`. Fonte: PDF Missão Clima enviado pelo usuário em 23/10/2026. O PDF original não é distribuído pelo site.

## Execução
Sirva `dist` por HTTP. Three.js r170 é servido localmente. Navegadores sem WebGL usam um renderer de compatibilidade por projeção de triângulos em Canvas 2D sobre a mesma cena 3D.

## Entregue
- Apresentação do conceito e linha do tempo interativa.
- Artes conceituais de IA, explicitamente identificadas.
- Catálogo de oito pacotes Kenney CC0 com fontes e previews oficiais.
- Protótipo: corrida, salto, três faixas, ações contextuais, escolha de rota, pontos, resiliência, transformação e retorno automático.

## Limites
O protótipo usa geometria original simplificada, não os modelos pesquisados. Não há projeto Godot/exportação Windows nesta entrega. A arte conceitual é uma meta de direção, não promessa de equivalência geométrica ou screenshot real. Testar desempenho e input no hardware do evento.

## Conceito de produção no Xogot

O site documenta a ideia geral, o contrato da experiência de 40 segundos, a arquitetura modular de cenas e dois portões de aceitação: funcional e visual. As seis imagens fornecidas são critérios de comparação para câmera, luz, composição, interface e leitura das soluções climáticas. A produção proposta usa canvas base 1920 × 1080, aspecto `expand`, cenas salvas por elemento e validação no touch e no monitor do evento. O protótipo WebGL foi preservado sem alterações.

## Personagem aprovado · V1

O protagonista possui uma prancha de turnaround em T-pose e vistas frontal e traseira com transparência. A identidade aprovada combina pele morena, cabelo cacheado, camiseta turquesa, calça azul-marinho, tênis branco e mochila amarela. Os arquivos em `dist/assets/character/` servem como referência para modelagem, rig e animação no Xogot/Godot.

## Fontes de assets
https://kenney.nl/assets/city-kit-roads
https://kenney.nl/assets/city-kit-suburban
https://kenney.nl/assets/city-kit-commercial
https://kenney.nl/assets/nature-kit
https://kenney.nl/assets/car-kit
https://kenney.nl/assets/animated-characters-protagonists
https://kenney.nl/assets/particle-pack
https://kenney.nl/assets/smoke-particles

Os ZIPs oficiais foram examinados quanto a formatos e licença CC0. As imagens dos cards são previews oficiais; não são criações do autor do site.

## Imagens conceituais
Geradas com a ferramenta nativa imagegen. Prompt principal: cidade brasileira contemporânea low-poly, câmera traseira elevada, protagonista com jaqueta coral/calça azul/mochila teal, rua com calor e bifurcação alagada/verde, jardins de chuva e final resiliente; sem texto ou HUD.
Prompt storyboard: quatro painéis coerentes com calor/sombra, chuva e escolha de rota, brigada profissional em foco de incêndio distante da protagonista, transformação verde final. Arquivos: dist/assets/hero.png e dist/assets/story.png.

## Revisão visual — 23/10/2026
Catálogo revisado: Brazil House (Bohnen, CC BY 4.0), Quaternius Stylized Nature MegaKit Standard, Ultimate Modular Women e Downtown City MegaKit Standard. Materiais complementares Poly Haven CC0. Cards incluem links oficiais, limites das versões gratuitas e adaptações. Storyboard gerado com referências dessas seleções; não representa modelos já integrados. game.js e a seção jogável preservados.

## Referências fornecidas pelo usuário
As seis imagens enviadas agora compõem a abertura, galeria ampliável e etapas. Direção final: jovem de camiseta turquesa e mochila amarela, cidade contemporânea arborizada, UI azul/turquesa/verde. Catálogo de personagem alterado para Ultimate Modular Men (CC0), explicitamente uma base a adaptar, sem prometer personagem idêntico. Preservados game.js, Three.js e marcação da seção jogável. Verificados JavaScript, filtro do catálogo e ampliação de imagem.
