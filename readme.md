<div align="center">
  <p align="center">
    <img 
      alt="DIO Education" 
      src="https://raw.githubusercontent.com/digitalinnovationone/template-github-trilha/main/.github/assets/logo.webp" 
      width="100px" 
    />
    <h1>DIO</h1>
  </p>
</div>
<br/>

## Armazenamento de Dados de um E-Commerce na Nuvem

### 📌 Visão Geral

Nesta seção do bootcamp Microsoft Azure Cloud Native da DIO, explorei a implementação de um sistema de armazenamento para um E-Commerce utilizando serviços da Azure. O projeto combinou:

- **SQL Database** para a estruturação dos dados dos produtos
- **Blob Storage** para salvar as imagens dos produtos
- **Streamlit** para possibilitar o cadastro dos produtos a partir de uma interface visual com apenas algumas linhas de código

### 🔧 Processos Implementados

1. Criação de Resource Group e SQL Database
2. Configuração do Storage Account
3. Criação do Banco de Dados e Estruturação da Tabela Produto
4. Integração com o Streamlit

### 💡 Insights Adquiridos

1. Vantagens da Separação de Dados:
   - Armazenar imagens no Blob (ao invés de BD) pode melhorar a performance e reduzir os custos
   - As imagens podem ser facilmente recuperadas
2. Produtividade:
   - O Streamlit permite a prototipagem RÁPIDA de interfaces
   - O Portal da Azure unifica o gerenciamento de diversos recursos

<br/>

## Criando um Blog com Container Apps

### 📌 Visão Geral

Nesta seção do bootcamp Microsoft Azure Cloud Native da DIO, implementei uma aplicação web de blog utilizando containers na Azure. O projeto envolveu:

- **Docker** para containerizar a aplicação do blog
- **NGINX** como servidor web para servir os arquivos estáticos
- **Azure Container Registry (ACR)** para armazenar a imagem Docker
- **Azure Container Apps** para hospedar e executar a aplicação containerizada

### 🔧 Processos Implementados

1. Criação da estrutura básica do blog
2. Desenvolvimento do Dockerfile utilizando NGINX como base
3. Criação do Resource Group e Container Registry na Azure
4. Build e push da imagem Docker para o ACR
5. Implantação da aplicação como Container App e publicação

### 💡 Insights Adquiridos

1. Vantagens dos Containers:
   - Isolamento da aplicação e suas dependências
   - Portabilidade entre ambientes
   - Facilidade de escalabilidade
2. Performance:
   - O NGINX como servidor web oferece alta performance para conteúdo estático
   - Os Container Apps permitem dimensionamento automático conforme a demanda
4. Custos:
   - A abordagem serverless dos Container Apps pode reduzir custos para aplicações com tráfego variável
