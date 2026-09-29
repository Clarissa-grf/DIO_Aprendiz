# DIO_Aprendiz
Desafios da DIO
# Contexto e Objetivo:
  O tema escolhido para o caderno foi a "Criação de um organizador e revisor para verificação a lógica, o texto e realizar o cruzamento de referências e citações de um trabalho de conclusão de curso". <br>
  
  O Notebook nasce da necessidade de apoiar na verificação da conformidade principalmente das referências e citações em minha tese de doutorado. <br>
  Explorar a capacidade do NotebookLM de realizar cruzamentos lógicos em textos longos. <br>
  Criar uma base de conhecimento sólida com regras atualizadas da ABNT para guiar a análise da ferramenta.<br>
# Curadoria de fontes:
  https://www.youtube.com/watch?v=MpNWft8-9mA <br>
  https://www.youtube.com/watch?v=Ps8UhU9vXfQ <br>
  https://tcctranquilo.com.br/formato-abnt-como-utilizar-no-tcc/ <br>
  https://portal.ifce.edu.br/documents/18124/Manual_de_normalizacao_de_trabalhos_acad%C3%AAmicos.pdf <br>
  https://www.gov.br/inpe/pt-br/area-conhecimento/posgraduacao/repositorio-de-arquivos/formato_de_dissertacoes_e_teses-inpe.pdf/@@download/file/Formato_de_dissertacoes_e_teses-INPE.pdf <br>
  https://www.overleaf.com/latex/templates/modeloinpe-2022/bytpkdzvmyqk <br>
  http://urlib.net/ibi/8JMKD3MGP8W/SFA8LH <br>
  https://www.gov.br/inpe/pt-br/area-conhecimento/biblioteca/editoracao <br>
  Modelo de Tese do INPE <br>
  Livro: Science without laws <br>
  Livro: Craft of Reasearch <br>
  Livro: Scientific writing thinking <br>
  
# Engenharia de Prompts e "Cicatrizes"
Exemplos de prompts: <br>

    Com base no modelo de tese enviado, converta o arquivo para formato word e crie uma estrutura básica de parágrafos, uma estrutura básica para se empregar na descrição de tabelas, imagens e mapas. Crie ainda dentro da estrutura dos parágrafos uma base padronizada para o desenvolvimento das ideias, sua análise e conclusão. <br>
    
    Com base no documento da tese enviado, realize a referenciação das imagens, siglas e tabelas em sumário especifico. <br>
    
    Avalie se as referências bibliográficas foram apresentadas corretamente e realize a conferência destas referências no GoogleScholar.[Modelo tese.pdf](https://github.com/user-attachments/files/32778808/Modelo.tese.pdf) <br>
    
    Atue como um revisor acadêmico rigoroso. Com base no (documento 01) e nas (ABNT N.xxx ), leia o documento (documento a ser analisado). Cruze todas as citações feitas no corpo do texto com a lista de referências ao final do documento. Gere uma tabela com duas colunas: 1. Autores citados no texto mas que faltam na referência; 2. Referências listadas ao final mas que não foram citadas no texto. <br>
    
  O Notebook LM não irá analisar a parte visual do documento, e sim a parte textual. É importante ter conhecimento das potencialidades e capacidades da ferramenta a ser utilizada, logo as conformidades de espaçamentos, recuos, tipo de fonte, a formatação de forma geral não será verificada. Outro ponto relevante é a elaboração do comando dado a IA, este deve ser claro, especifico e objetivo, evitar textos genéricos ou que induzam a IA a uma resposta. <br>

# Miniguia de estudos
Resumo estruturado do assunto: <br>
    O que a IA PODE revisar: Cruzamento de dados (citação vs. referência); presença de elementos obrigatórios na string de texto da referência (Autor, Título, Ano, Cidade); coerência textual, ortografia e fluidez; transição de parágrafos. <br>
    O que a IA NÃO PODE revisar: Margens (3cm/2cm), espaçamento entrelinhas, recuo de parágrafo (1,25cm), fontes (Arial/Times), paginação exata. <br>
    
Glossário: <br>
    Citação Direta: Transcrição literal de parte da obra do autor consultado. (Pode ser curta, até 3 linhas, ou longa, com recuo de 4cm). <br>
    Citação Indireta: Texto baseado na obra do autor consultado, escrito com as palavras do pesquisador (paráfrase). <br>
    Referência Bibliográfica: Conjunto padronizado de elementos descritivos retirados de um documento, que permite sua identificação individual ao final do trabalho. <br>
    Alucinação de IA: Quando o modelo gera informações incorretas ou sem sentido devido à falta de contexto ou restrição técnica (como pedir para ler metadados visuais de um PDF). <br>
    Engenharia de prompt: Como criar ou descrever o que se pede para IA de forma a gerar respostas assertivas e satisfatórias. <br>
    <br>
    
Prompts reutilizáveis:<br>
  <br>  Para Validação de Referências (Conferência de Estrutura): <br>
        "Análise a seção 'Referências' do meu documento. Com base no Manual da ABNT anexado, verifique a estrutura de texto de cada referência. Liste aquelas que estão com a formatação de texto incorreta (ex: ausência de cidade ou editora) e sugira a correção." <br>
    Para Cruzamento de Dados (O mais útil): <br>
        "Cruze as citações do corpo do texto com a bibliografia final. Liste: 1. Quem foi citado mas não referenciado; 2. Quem foi referenciado mas não foi citado no texto." <br>
    Para Clareza e Coesão: <br>
        "Leia o Capítulo 2. Identifique frases que estejam excessivamente longas (mais de 4 linhas) ou parágrafos confusos. Sugira reescritas para tornar a linguagem mais acadêmica, formal e direta, mantendo o sentido original."
