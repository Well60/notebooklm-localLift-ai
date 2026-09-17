# NotebookLM — IA generativa aplicada à presença digital local

Projeto desenvolvido como parte de um desafio da [DIO](https://www.dio.me/) para criar um caderno temático no NotebookLM, selecionar fontes confiáveis e produzir conhecimento fundamentado nelas.

## Contexto e objetivos de estudo

O tema escolhido foi **“IA generativa aplicada à presença digital de negócios locais: o LocalLift AI como estudo de caso”**. A escolha une dois campos diretamente relacionados aos meus estudos e projetos: o uso responsável de inteligência artificial generativa e o desenvolvimento de soluções digitais voltadas a problemas reais de pequenos empreendedores.

Negócios locais dependem da Pesquisa e do Google Maps para serem encontrados por clientes, mas a gestão do Perfil da Empresa exige informações corretas, acompanhamento de avaliações, interpretação de métricas e respeito às diretrizes da plataforma. Para muitos empreendedores, esses processos são técnicos, dispersos e difíceis de transformar em ações práticas.

Nesse contexto, o LocalLift AI foi adotado como objeto de estudo por propor uma camada de interpretação entre os dados de presença digital e o gestor do negócio. O foco do caderno não foi promover o produto, mas analisar criticamente como a IA pode explicar diagnósticos, organizar prioridades e apoiar decisões sem substituir a revisão humana.

### Objetivo geral

Investigar como a IA generativa pode apoiar a gestão da presença digital de negócios locais, utilizando fontes confiáveis e o LocalLift AI como estudo de caso prático.

### Objetivos específicos

- compreender os conceitos fundamentais de IA generativa e modelos de linguagem;
- identificar os fatores que influenciam a classificação local no Google;
- analisar como dados técnicos podem ser convertidos em orientações acessíveis;
- diferenciar funcionalidades estruturadas, recursos em validação e integrações pendentes do LocalLift AI;
- avaliar riscos como alucinações, vieses, uso de dados insuficientes e recomendações incompatíveis com diretrizes oficiais;
- reforçar a importância da transparência, da privacidade e da revisão humana;
- testar a capacidade do NotebookLM de gerar respostas fundamentadas e rastreáveis;
- produzir um miniguia reutilizável com síntese, glossário, análise crítica e prompts de estudo.

## Caderno no NotebookLM

> **[Acessar o caderno completo no NotebookLM](https://notebook.google.com/notebook/1b1854c7-615a-4628-a8b4-de872ef1f15f)**  
> É necessário entrar em uma Conta Google para visualizar o notebook.

## Problema estudado

Pequenos empreendedores precisam manter informações comerciais corretas, acompanhar avaliações, interpretar métricas e obedecer às diretrizes do Google. A falta de tempo e de conhecimento técnico dificulta a identificação das ações mais importantes.

## Solução analisada

O **LocalLift AI** é um SaaS em desenvolvimento que propõe:

- diagnóstico da saúde do Perfil da Empresa;
- Health Score explicável;
- plano de ação priorizado;
- agente de IA para orientações;
- análise de concorrentes;
- apoio à otimização de conteúdo;
- relatório executivo.

O projeto está em preparação para um beta controlado. A interface e a estrutura dos módulos estão desenvolvidas, enquanto o Health Score, o agente de IA e a análise de concorrentes ainda precisam ser validados. Integrações reais com serviços do Google, provedor de IA, pagamentos e e-mails permanecem pendentes.

## LocalLift AI na prática

As telas abaixo apresentam o protótipo utilizado como estudo de caso. Os dados exibidos são demonstrativos e não representam resultados garantidos.

### Página inicial

Apresentação da proposta de valor do LocalLift AI para empresas locais.

![Landing page do LocalLift AI](assets/locallift/landing-page.png)

### Agente IA

Interface do consultor de SEO local, projetada para transformar diagnósticos em orientações acessíveis. O recurso permanece em validação.

![Agente IA do LocalLift AI](assets/locallift/agente-ia.png)

### Análise de concorrentes

Comparação regional demonstrativa para identificar diferenças e oportunidades. As pontuações e empresas exibidas são exemplos de teste.

![Análise de concorrentes do LocalLift AI](assets/locallift/analise-concorrentes.png)

## Conteúdos produzidos no caderno

- síntese central;
- teste de fundamentação nas fontes;
- glossário de conceitos;
- análise crítica;
- perguntas e respostas estratégicas;
- dois mapas mentais;
- resumo em áudio.

## Estrutura do repositório

- [Síntese do estudo](docs/sintese.md)
- [Análise crítica](docs/analise-critica.md)
- [Glossário](docs/glossario.md)
- [Perguntas estratégicas](docs/perguntas-estrategicas.md)
- [Teste de fundamentação](docs/teste-fundamentacao.md)
- [Prompts utilizados](prompts/prompts-utilizados.md)
- [Fontes consultadas](fontes/fontes-utilizadas.md)
- [Documento-base do estudo de caso](documentos/LocalLift_AI_Estudo_de_Caso.docx)
- [Resumo em áudio do NotebookLM](audio/resumo-audio-locallift-ai.mp3)

## Resumo em áudio

O NotebookLM também produziu uma conversa em áudio sobre como a IA pode traduzir informações do Google para pequenos lojistas.

**[Ouvir ou baixar o resumo em áudio](audio/resumo-audio-locallift-ai.mp3)** — duração aproximada de 21 minutos.

## Mapas mentais

### IA generativa e presença digital local

![Mapa mental sobre IA generativa, SEO e presença digital local](assets/mapa-mental-ia-seo-local.png)

### Estrutura e validação do LocalLift AI

![Mapa mental sobre arquitetura, estágio e validação do LocalLift AI](assets/mapa-mental-locallift-ai.png)

## Dificuldades, iterações e aprendizados

A construção do caderno foi um processo iterativo. As primeiras consultas mostraram que uma resposta bem escrita nem sempre apresenta automaticamente as citações da forma esperada. Como a conversa existente não podia ser reiniciada naquele momento, foi necessário reformular as instruções dentro do mesmo contexto, pedindo que o NotebookLM respondesse exclusivamente com base nas fontes selecionadas e informasse explicitamente quais documentos sustentavam cada resposta.

Também foi necessário melhorar progressivamente os prompts. Perguntas muito amplas geravam respostas corretas, porém genéricas. Os melhores resultados surgiram quando os comandos passaram a definir uma estrutura, separar fatos de possibilidades futuras e exigir distinção entre funcionalidades desenvolvidas, recursos em validação e integrações pendentes.

Outro cuidado importante foi evitar que o caderno apresentasse o LocalLift AI como um produto comercial finalizado. O protótipo possui interface e módulos estruturados, mas o Health Score, o agente de IA e a análise de concorrentes ainda dependem de validação com dados reais. As integrações de produção também permanecem pendentes. Essa distinção aumentou a precisão da análise e reduziu o risco de conclusões exageradas.

Durante o compartilhamento, foi identificada a diferença entre o link de visualização de uma conversa e o endereço do caderno completo. O link correto foi testado externamente e inserido no repositório com a observação de que o visitante precisa entrar em uma Conta Google.

Por fim, a organização no GitHub demonstrou que uma boa entrega não depende apenas do texto final. Foi necessário estruturar os documentos, nomear arquivos de forma clara, registrar as fontes, disponibilizar os prompts, incluir os mapas mentais, otimizar o áudio e apresentar evidências visuais do estudo de caso.

### Principais aprendizados

- prompts específicos produzem respostas mais verificáveis;
- citações e referências precisam ser solicitadas e conferidas;
- respostas de IA não devem ser aceitas sem revisão crítica;
- dados demonstrativos precisam ser claramente identificados;
- funcionalidades em validação não devem ser apresentadas como concluídas;
- a revisão humana continua necessária antes de qualquer decisão ou publicação;
- a organização dos artefatos facilita a reutilização e a avaliação do conhecimento produzido.

## Principais conclusões

A IA generativa pode reduzir a complexidade dos dados e apoiar a tomada de decisão, mas não garante melhor posicionamento, vendas ou resultados comerciais. O valor do LocalLift AI dependerá da qualidade dos dados, da validação com empresas reais, da conclusão das integrações e da revisão humana das recomendações.

## Tecnologias e ferramentas

- NotebookLM
- IA generativa e modelos de linguagem
- Lovable
- GitHub
- Perfil da Empresa no Google

## Autoria

Projeto acadêmico desenvolvido por **Well60** para o curso da DIO.
