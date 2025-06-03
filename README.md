# Desafio - Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

## 🎯 Objetivo

Este projeto faz parte de um desafio prático da plataforma DIO. O objetivo foi aplicar técnicas de organização, indexação e mineração de conhecimento utilizando os serviços de inteligência artificial do Azure. O laboratório foi baseado no guia "Explore an Azure AI Search index (UI)" e teve como cenário a análise de dados de avaliações de clientes de uma cafeteria fictícia, a Fourth Coffee.

### Principais etapas realizadas:

1. **Criação dos recursos no Azure**:

   * **Azure AI Search**: Serviço responsável por criar e consultar índices inteligentes.
   * **Azure AI Services**: Serviço que aplica habilidades de inteligência artificial para enriquecer os dados.
   * **Conta de Armazenamento**: Local utilizado para armazenar os documentos com as avaliações dos clientes, dentro de um contêiner chamado `coffee-reviews`.

2. **Ingestão e armazenamento dos dados**:

   * Os arquivos contendo as avaliações foram carregados no contêiner criado na conta de armazenamento.
   * Foi necessário permitir o acesso anônimo ao Blob para que os serviços do Azure pudessem acessar os dados.

3. **Indexação e enriquecimento dos dados**:

   * A indexação foi realizada com o **Azure AI Search**, que criou um **índice** a partir dos dados armazenados. O índice é uma estrutura que organiza e permite consultas rápidas e eficientes sobre os documentos.
   * O **enriquecimento de dados** consiste na aplicação de habilidades de IA para extrair automaticamente informações relevantes dos documentos, como:

     * Extração de nomes de locais.
     * Identificação de frases-chave.
     * Análise de sentimentos.
     * Geração de descrições e tags de imagens.
   * Esse processo transforma dados brutos em informações estruturadas, facilitando a mineração de conhecimento.

4. **Criação da Knowledge Store**:

   * Os dados enriquecidos foram armazenados em uma **Knowledge Store**, uma estrutura que permite visualizar e explorar as informações organizadas de forma mais prática.

5. **Consulta e exploração dos dados**:

   * Através do **Search Explorer**, foram realizadas consultas ao índice criado:

     * Exibição de todos os documentos.
     * Filtragem por localização ("Chicago").
     * Filtragem por sentimento ("negative").
   * As consultas demonstraram como a combinação entre indexação e enriquecimento de dados permite a exploração inteligente das informações.

---

### O que aprendi com a atividade:

* A **combinação entre diferentes serviços do Azure** permite criar soluções poderosas de mineração de conhecimento.
* A **conta de armazenamento** serve como repositório para os dados que serão processados.
* O **Azure AI Search** automatiza a criação de índices a partir de dados não estruturados, tornando possível realizar consultas eficientes.
* O **enriquecimento** é a etapa em que o Azure aplica algoritmos de IA para gerar novos atributos e metadados a partir dos dados originais, como sentimentos ou localização, facilitando a análise e interpretação.
* A **indexação** organiza os dados de forma que possam ser facilmente pesquisados e consultados através de filtros e buscas específicas.

---

### Reflexão final:

A prática demonstrou a importância da **integração entre armazenamento, indexação e inteligência artificial** para transformar grandes volumes de dados não estruturados em insights valiosos. Aprendi como o Azure pode ser utilizado para automatizar esse processo de ponta a ponta, facilitando tarefas complexas de mineração de conhecimento e visualização de dados.

## 🧑‍💻 Autor

**laisbastosbg**
Projeto realizado como parte do curso XP Inc. - Cloud com Inteligência Artificial pela plataforma DIO - Digital Innovation One.
[LinkedIn](https://www.linkedin.com/in/lais-godinho/)