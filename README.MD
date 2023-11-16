# Firebase CRUD com Javascript 🚀

Este é um projeto didático de CRUD (Create, Read, Update, Delete) utilizando o Firebase e JavaScript para gerenciar clientes. O sistema inclui funcionalidades básicas como inserir, consultar, alterar e excluir registros de clientes.

## Pré-requisitos

Certifique-se de ter uma conta no [Firebase](https://firebase.google.com/) e crie um projeto para obter as credenciais necessárias.

## Configuração do Firebase

Substitua as credenciais do Firebase no bloco de código abaixo com as informações do seu projeto:

```javascript
const firebaseConfig = {
    apiKey: "SuaAPIKey",
    authDomain: "SeuDominio.firebaseapp.com",
    projectId: "SeuProjetoID",
    storageBucket: "SeuProjeto.appspot.com",
    messagingSenderId: "SeuID",
    appId: "SeuAppID"
};

// Inicializa o Firebase
const app = initializeApp(firebaseConfig);
const db = getFirestore(app);
```
## Estrutura do Projeto
O projeto é estruturado em páginas HTML separadas para fornecedor (Fornecedor.html), produtos (produtos.html), e clientes (index.html). Cada página contém uma tabela para exibir os registros e modais para interações como inserção, consulta, alteração e exclusão.

## Dependências
- Bootstrap: Utilizado para o estilo e layout responsivo do sistema.
- DataTables: Biblioteca para manipulação de tabelas HTML, facilitando a exibição e interação com os dados.
- Firebase: Utilizado para armazenamento e manipulação dos dados.

## Como Usar
- Clone o repositório ou faça o download dos arquivos.
- Substitua as credenciais do Firebase no código.
- Abra os arquivos HTML em um navegador da web.
- Lembre-se de adaptar o código conforme necessário para atender aos requisitos específicos do seu projeto didático.

## Demonstração 🎥



Observação: Este projeto é voltado para fins educacionais, e a segurança não foi a principal preocupação. Em um ambiente de produção, medidas adicionais de segurança devem ser implementadas.

