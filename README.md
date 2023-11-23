
##Aplicação de Lista de Tarefas
Este repositório contém o código para uma simples aplicação de Lista de Tarefas utilizando Flask para o backend, Bootstrap para o frontend, e Axios para realizar requisições assíncronas. A aplicação permite que os usuários adicionem, removam e editem tarefas.

#Arquivos e Estrutura
Arquivo HTML (index.html):

O arquivo HTML define a estrutura da página web, incluindo a barra de navegação, a área de conteúdo principal, e modais para adição e edição de tarefas.
#Arquivo CSS (style.css):

O arquivo CSS fornece estilos para os elementos da página web. Ele inclui alguns estilos básicos e importações de fontes.
#Arquivo JavaScript (script.js):

O arquivo JavaScript é responsável por realizar requisições assíncronas para o backend Flask usando o Axios. Ele também manipula a criação dinâmica de elementos HTML com base nos dados recebidos.
Backend Flask (app.py):

O backend Flask fornece endpoints de API para listar, adicionar, deletar e atualizar tarefas. Ele utiliza um arquivo CSV (Text.csv) para armazenar os dados das tarefas.
Como Executar
Instalar Dependências:

#Certifique-se de ter o Python e o Flask instalados. Instale os pacotes Python necessários com:
bash
Copy code
pip install Flask pandas
Executar a Aplicação Flask:

Execute a aplicação Flask rodando o seguinte comando no terminal:
bash
Copy code
python app.py
A aplicação será executada em http://127.0.0.1:5000/ por padrão.
Acessar a Aplicação:

Abra um navegador da web e acesse http://127.0.0.1:5000/ para usar a aplicação de Lista de Tarefas.
Funcionalidades
Adicionar Tarefa:

Clique no botão "+" na barra de navegação para abrir o modal "Adicionar Tarefa". Insira uma descrição da tarefa e clique em "Adicionar".
Remover Tarefa:

Cada tarefa possui um botão de remoção representado por um ícone de lixeira. Clicar neste botão solicitará confirmação antes de remover a tarefa.
Editar Tarefa:

Cada tarefa possui um botão de edição representado por um ícone de lápis. Clicar neste botão solicitará uma nova descrição para a tarefa, e a tarefa será atualizada de acordo.
Bibliotecas Externas
Bootstrap:

A aplicação utiliza o Bootstrap para estilização e componentes de interface. Os links CDN estão inclusos no arquivo HTML.
Axios:

O Axios é utilizado para realizar requisições assíncronas para o backend Flask. O link CDN está incluso no arquivo HTML.
Observações
Arquivo CSV (Text.csv):

Os dados das tarefas são armazenados em um arquivo CSV chamado Text.csv. O arquivo é criado se não existir, e as tarefas são adicionadas a ele conforme são inseridas.
Codificação de Caracteres:

A aplicação trata da codificação de caracteres ao ler e escrever no arquivo CSV para lidar com caracteres especiais.
