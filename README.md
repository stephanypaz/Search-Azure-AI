# 🚀 Configurando seu Azure AI Search

O **Azure AI Search** permite criar buscas inteligentes para diversos tipos de dados, como produtos, documentos e registros.

## 🖥️ 1. Criar o AI Search

- **Acesse o Portal Azure:** Vá para [portal.azure.com](https://portal.azure.com).
- **Crie um novo recurso:** Pesquise por **"Azure AI Search"** e clique em **"Criar"**.
- **Configure os detalhes básicos:**  
  - Escolha a **assinatura** e um **grupo de recursos**.  
  - Defina um **nome único** para o serviço.  
  - Escolha uma **região** próxima dos seus usuários.  
  - Selecione um **tipo de preço** (Free, Basic, Standard ou Storage Optimized). Importante: Se estiver testando, procure por Basic.  
- **Finalize a criação:** Clique em **"Revisar + Criar"** e aguarde a implantação.

---

## 🖥️ 2. Criar o AI Services

- **Crie um novo recurso:** Na página inicial do Azure, clique em **"Criar um recurso"**, procure por **"IA + Machine Learning"** e clique em **"Azure AI Services"**.
- **Configure os detalhes básicos:**  
  - Escolha a **assinatura** e um **grupo de recursos**.  
  - Defina um **nome único** para o serviço.  
  - Escolha uma **região** próxima dos seus usuários.  
  - Selecione um **tipo de preço** (Free, Basic, Standard ou Storage Optimized). Importante: Se estiver testando, procure por Standard S0.  
- **Finalize a criação:** Clique em **"Revisar + Criar"** e aguarde a implantação.

---

## 📊 3. Criar o Armazenamento de Dados

- **Criação de Contas de Armazenamento:** Na página inicial do Azure, procure e clique em **"Contas de Armazenamento"** e selecione **"Criar"**.
- **Configure os detalhes básicos:**  
  - Escolha a **assinatura** e um **grupo de recursos**.  
  - Defina um **nome único** para o serviço.  
  - Escolha uma **região** próxima dos seus usuários.  
  - Selecione um **desempenho** (Standard ou Premium). Importante: Se estiver testando, procure por Standard.
  - Selecione uma **redundância** (LRS, GRS, ZRS ou GZRS). Importante: Se estiver testando, procure por LRS. 
- **Finalize a criação:** Clique em **"Revisar + Criar"** e aguarde a implantação.

---

## 🔑 4. Liberar Acessos Anônimos

- **Encontrar Conta de Armazenamento:** Clique em **"Contas de Armazenamento"**, procure **a conta de armazenamento criada anteriormente** e clique nela.
- **Liberar Acesso Anônimo:** Vá na aba **"Configurações"** > **"Configurações"**.
  - Altere o campo **"Permitir Acesso Anônimo ao Blob"** para **"Habilitado"**.
- **Finalize a alteração:** Clique em **"Salvar"**.

## 📂 5. Criar um Contêiner de Armazenamento de Dados

- **Crie um Contêiner:** Vá na aba **"Armazenamento de Dados"** > **"Contêineres"**.
   - Clique em **Contêiner +"**.
- **Configure os detalhes básicos:**
   - Defina um **nome único** para o serviço.
   - Selecione o **nível de acesso anônimo (Privado, Blob, Contêiner). Importante: Se estiver testando, procure por Contêiner. 
- **Finalize a criação:** Clique em **"Criar"**.
- **Importar os dados:** Importe os dados em **"Carregar"**

---

## 🔍 6. Testar e Consultar Dados

- **Importar Dados"**: Na página inicial do Azure, selecione **"AI Services"**.
   - Selecione **o mecanismo de busca criado anteriormente**.
   - Clique em **"Importar Dados"**.
   - Selecione **o recurso de armazenamento de dados criado anteriormente**.
- **Finalize a importação:** Clique em **"Próximo"**.
- **Efetue a pesquisa:** Selecione **"Importar e Vetorizar Dados"**.
- **Exemplo de pesquisa:** Preencha com **"search=locations:'Chicago'"** e clique em **"Procurar"**.

---

## 🎯 7. Aplicações na Vida Real

O **Azure AI Search** pode ser usado para:

- ✅ **E-commerces** – Oferece uma busca inteligente que melhora a experiência do usuário, com filtros avançados e recomendações personalizadas.
- ✅ **Atendimento ao Cliente** – Acelera o suporte ao permitir buscas instantâneas em bases de conhecimento, reduzindo o tempo de resposta.
- ✅ **Saúde** – Facilita o acesso a prontuários médicos e registros clínicos, auxiliando profissionais na tomada de decisão rápida e eficiente.
- ✅ **Gestão Documental** – Otimiza a organização de documentos corporativos, garantindo buscas rápidas e seguras em arquivos internos e sistemas de compliance.

Agora seu **Azure AI Search** está pronto para uso! 🚀
