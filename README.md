<h1 align="center">Desafiando SQL com GitHub Copilot</h1>
<h5 align="center">Leve o GitHub Copilot ao limite em fluxos de trabalho complexos</h5>

- **Para quem é**: Qualquer profissional de tecnologia que deseja aprimorar técnicas básicas ao trabalhar com o GitHub Copilot. Engenheiros de Software, Engenheiros de Dados, Cientistas de Dados e qualquer pessoa que trabalhe com bases de código ou projetos de código desafiadores.
- **O que você aprenderá**: Técnicas avançadas do GitHub Copilot, especialmente úteis em problemas complexos. Essas técnicas e padrões podem ser aplicados em problemas difíceis ou quando o GitHub Copilot não fornecer a melhor solução.
- **O que você construirá**: Um banco de dados com dados altamente específicos e consultas avançadas, validadas e testadas unitariamente.

## Objetivos de Aprendizado

Neste workshop, você irá:

- Utilizar técnicas avançadas de interação com o GitHub Copilot para lidar com problemas complexos relacionados a consultas SQL.
- Iterar, validar e refinar respostas para obter sugestões melhores e mais precisas.
- Aplicar conceitos gerais que podem melhorar as sugestões e escolher estratégias diferentes para obter resultados mais eficazes.
- Compreender claramente técnicas ruins de criação de prompts (instruções iniciais) e como elas podem afetar drasticamente os resultados do GitHub Copilot.

## Pré Requisitos

Antes de participar do workshop, há apenas um pré-requisito: possuir uma conta pública no GitHub. Todos os recursos, dependências e dados fazem parte do próprio repositório. Certifique-se de ter a licença do GitHub Copilot, uma versão de teste ou a versão gratuita.

## Como executar

- Para criar o arquivo de ratings.db execute o setup.py na raiz.
- Utilize o máximo do poder do copilot para aprender sobre essa aplicação e como resolver o problema de otimizar a consulta de vinhos.
- Caso necessite pode remover o arquivo ratings.db e recria-lo a qualquer momento utilizando o setup.py

## Principais aprendizados

### 1. Defina objetivos e requisitos claros

*O que precisa ser alcançado?*

Comece entendendo claramente o objetivo final. No caso das consultas SQL, trata-se de agregação de dados, filtragem, junção, etc.? Sempre pergunte: o que preciso que esta consulta faça?

*Quais são as restrições?*

Identifique limitações ou exclusões. Por exemplo, em uma consulta SQL, talvez você precise excluir tipos específicos de lote ou dados. De forma mais ampla, as restrições podem incluir limitações de tempo, desempenho ou regras específicas a serem seguidas.

Seja preciso quanto ao escopo do problema. Se estiver inseguro, comece amplo e refine progressivamente os detalhes.

### 2. Divida o problema em componentes

Divida o problema em partes menores e gerenciáveis. Por exemplo, ao decompor uma consulta SQL complexa:
- Filtragem dos dados (ex: dados do dia atual).
- Exclusões específicas (ex: tipos "off-us" ou "offset").
- Agregação (ex: somar valores).

Garanta que cada condição seja aplicada passo a passo. Em programação, decompor uma função complexa em funções auxiliares menores facilita a escrita e a depuração.

Decomposição é uma ótima maneira de lidar com a complexidade, permitindo focar em pequenas tarefas por vez.

### 3. Aproveite vocabulário e contexto específicos do domínio

Use terminologia adequada ao domínio do problema. Seja escrevendo consultas SQL, código ou criando algoritmos, a familiaridade com o vocabulário técnico facilita a criação de instruções precisas para ferramentas como o Copilot ou na comunicação com outras pessoas.

Quanto mais preciso o vocabulário e o contexto, mais fácil será a compreensão e a geração de soluções por humanos e ferramentas.

### 4. Itere e refine a solução

Comece simples e depois refine. Em problemas complexos, as primeiras tentativas raramente são perfeitas. Comece com uma solução básica e construa sobre ela progressivamente.

Numa consulta SQL, comece selecionando todos os dados do dia e adicione filtros, exclusões e agregações em etapas.

Teste e valide cada iteração para garantir que o resultado esteja caminhando na direção certa.

### 5. Use exemplos para esclarecer requisitos

Ao criar prompts para modelos de IA ou explicar problemas, forneça exemplos. Exemplos ajudam a ilustrar expectativas, deixando claro o que precisa ser feito.

Por exemplo, nas consultas SQL, utilize dados de exemplo e explique como o resultado esperado deve aparecer.

Resolver problemas por exemplos ajuda a alinhar o entendimento, especialmente útil em tarefas ambíguas.

### 6. Identifique padrões e reutilize soluções

Reconheça padrões comuns no seu problema e reutilize soluções aplicáveis. Consultas SQL frequentemente apresentam padrões comuns (agregação, filtragem, agrupamento). Ao identificá-los, reutilize e modifique esses blocos de construção.

Reconhecer padrões é sinal de experiência. Ao enfrentar problemas semelhantes, você começará a notar similaridades que agilizam o processo.

### 7. Utilize restrições e casos limites para robustez

Considere casos extremos e exceções. Problemas complexos geralmente envolvem o tratamento de dados ideais e também casos-limite ou valores discrepantes que poderiam quebrar soluções ingênuas.

Em SQL, isso inclui garantir que datasets vazios, valores nulos ou tipos inesperados não causem erros.

Analisar casos-limite gera soluções mais resilientes e generalizadas.

### 8. Utilize ferramentas de forma eficaz

Seja GitHub Copilot ou outra automação, use ferramentas ao seu favor, guiando-as com o contexto correto. Ferramentas aceleram a criação, mas precisam de entradas estruturadas e validação.

Para o Copilot, forneça prompts detalhados e concisos.

Seja específico com as ferramentas, mas sempre valide resultados, pois nem sempre captam totalmente o contexto sem orientação adequada.

### 9. Busque feedback e colaboração

Em tarefas complexas, especialmente envolvendo código ou consultas, colaboração e feedback são cruciais. Não hesite em pedir insights ou revisões.

Ao criar uma consulta SQL complexa, colegas podem perceber problemas ou estratégias melhores que você não viu.

Colaboração traz novas perspectivas e reduz pontos cegos.

### 10. Teste e valide

Testar e validar são essenciais para garantir que a solução funciona corretamente. Teste consultas SQL com diversos casos-limite e compare os resultados com os esperados.

Inclua sempre uma etapa de validação no seu processo para detectar erros cedo.

## Recursos

Embora não obrigatório, algumas funcionalidades abordadas estão nos módulos da Microsoft Learning:

- [Code with GitHub Codespaces](https://learn.microsoft.com/training/modules/code-with-github-codespaces/)
- [Using advanced GitHub Copilot features](https://learn.microsoft.com/training/modules/advanced-github-copilot/)

## Contribuições

Este projeto aceita contribuições e sugestões. Para detalhes, visite https://cla.opensource.microsoft.com.

Este projeto adota o [Código de Conduta de Código Aberto da Microsoft](https://opensource.microsoft.com/codeofconduct/).

## Marcas registradas

Este projeto pode conter marcas registradas ou logotipos sujeitos às políticas de terceiros ou às [Diretrizes de Uso de Marca Registrada e Marca da Microsoft](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).