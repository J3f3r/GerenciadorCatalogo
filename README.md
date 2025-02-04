# Simulação de Base de Banco de Dados da Netflix com Azure Functions

## Descrição do Projeto
Este projeto simula o funcionamento da base de um banco de dados da Netflix utilizando **Azure Functions** com **HTTP Trigger**. O objetivo é armazenar e gerenciar arquivos de mídia (imagens e vídeos), bem como manipular registros no banco de dados **CosmosDB**.

## Tecnologias Utilizadas
- **Azure Functions**
- **Azure CosmosDB**
- **Azure Storage Account**
- **Azure API Manager**
- **Visual Studio**
- **Postman**

## Recursos Criados no Azure
- **CosmosDB**: Para armazenar metadados e informações dos arquivos.
- **Storage Account**: Para armazenar os arquivos de mídia (imagens e vídeos) dentro de contêineres.
- **API Manager**: Para facilitar o gerenciamento e a exposição das APIs.

## Azure Functions Criadas
1. **Upload de Arquivos**: Salva imagens e vídeos no **Storage Account**.
2. **Salvar Metadados**: Registra informações dos arquivos no **CosmosDB**.
3. **Filtrar Registros**: Realiza buscas específicas no **CosmosDB**.
4. **Listar Registros**: Retorna todos os registros armazenados no **CosmosDB**.

## Funcionalidades Implementadas
- Manipulação do código das **Azure Functions** para:
  - Salvar arquivos no **Storage Account**.
  - Salvar metadados no **CosmosDB**.
  - Filtrar registros no **CosmosDB**.
  - Listar registros do **CosmosDB**.
- Testes realizados com **Postman** para validar as APIs.

## Como Executar o Projeto
1. **Configurar o Ambiente**:
   - Instale o **Visual Studio** e configure o **Azure Functions Tools**.
   - Configure o **Azure Storage Emulator** ou utilize um **Storage Account** real.
   - Crie um **CosmosDB** no portal do Azure.

2. **Executar as Azure Functions**:
   - Utilize o **Visual Studio** para rodar as functions localmente.
   - Utilize o **Postman** para fazer requisições HTTP e testar as APIs.

## Testes com Postman
- **Upload de Arquivos**: Enviar uma requisição HTTP POST com um arquivo para a API correspondente.
- **Salvar Metadados**: Enviar um JSON com informações do arquivo para o CosmosDB.
- **Filtrar Registros**: Realizar uma requisição GET com filtros específicos.
- **Listar Registros**: Requisição GET para obter todos os registros armazenados.

## Considerações Finais
Este projeto é um exemplo prático de como utilizar **Azure Functions** para construir um sistema de armazenamento e gerenciamento de mídia na nuvem, simulando uma base de dados da Netflix. Com a integração entre **Storage Account** e **CosmosDB**, conseguimos garantir escalabilidade e eficiência no processamento e na consulta de dados.

---

## Referências
AZ 204
DIO
Henrique Souza
