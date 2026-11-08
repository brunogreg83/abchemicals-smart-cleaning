# AB Chemicals Smart Cleaning

Aplicativo web independente para apoiar a identificação de sujidades e a seleção tecnicamente validada de produtos do portfólio AB Chemicals.

## Estado atual — MVP de interface (0.1)

- Interface responsiva para celular e desktop.
- Captura de foto pela câmera ou seleção da galeria.
- Campos de ambiente, material/superfície, tipo percebido de sujidade e observações.
- Pré-visualização da imagem e resumo dos dados informados.
- Aviso explícito de que o motor de IA ainda não está conectado.

## Próximas etapas

1. Conectar um serviço de visão computacional/IA por meio de backend seguro (chaves nunca devem ficar no navegador).
2. Construir e validar a base técnica do catálogo: aplicações permitidas, materiais compatíveis, restrições, diluições, modo de uso e fichas técnicas.
3. Implementar análise com hipóteses, nível de confiança e perguntas complementares quando a imagem não for suficiente.
4. Recomendar apenas produtos cuja aplicação e compatibilidade estejam documentadas e aprovadas.
5. Adicionar histórico de análises e controles de privacidade para imagens.

## Executar localmente

Abra `index.html` em um navegador moderno. Para publicar, habilite GitHub Pages ou conecte o repositório a um serviço de hospedagem estática.

## Segurança

A imagem, isoladamente, não determina a composição química de uma mancha. O aplicativo não deve incentivar misturas de produtos nem sugerir aplicações sem confirmação de compatibilidade. Rótulo, FDS e ficha técnica aprovados são a fonte para instruções de uso.