# DP100-AgenteRAG-Pdf
Como estudante de Engenharia de dados, você cria um sistema com IA para analisar PDFs do TCC, extrair informações relevantes, conectar ideias entre artigos e responder perguntas de forma inteligente com base no conteúdo carregado.

#docx com o passo a passo feito na pasta Evidencias
1 – deploy do serviço do foundry
 <img width="694" height="578" alt="image" src="https://github.com/user-attachments/assets/42e4ccf2-de04-4807-bafb-d35baac5d88e" />


Proj-foundry-pdf
<img width="682" height="500" alt="image" src="https://github.com/user-attachments/assets/f89cbabe-0d27-4c37-a2ef-b632a3a2656b" />

 
Acessa recurso e criar modelo base:
<img width="886" height="910" alt="image" src="https://github.com/user-attachments/assets/915b045c-a1e9-4538-9bd0-b8fbaff87a7c" />
<img width="771" height="576" alt="image" src="https://github.com/user-attachments/assets/eed08b4c-4d03-400b-9141-063899a3ff3a" />
<img width="736" height="714" alt="image" src="https://github.com/user-attachments/assets/3e98967c-e1f9-41cc-9338-47884f40f2b1" />

Gerando modelo para nos ajudar com os embeddings: vetor para texto e vice versa
 <img width="839" height="638" alt="image" src="https://github.com/user-attachments/assets/aa687828-39bb-4458-b1ff-56bb2855fce0" />

Ir em playground e criar playground de chat:
 <img width="886" height="504" alt="image" src="https://github.com/user-attachments/assets/40888f15-3cc0-4a96-9b84-d489e462c91c" />

Setar o system prompt:
Você é um assistente de IA que ajuda as pessoas a encontrar informações sobre dados e ML.
<img width="886" height="557" alt="image" src="https://github.com/user-attachments/assets/b1a3225e-9842-436e-a3fa-f7a4827f58fd" />

 
Criar um azure AI Search para vetorizar os pdfs:
 <img width="886" height="898" alt="image" src="https://github.com/user-attachments/assets/28ec2fbf-d9c4-4b29-9466-45740ac05d5e" />

Aaisprojetopdf – não aceita traços	(não funciona no free)
<img width="886" height="674" alt="image" src="https://github.com/user-attachments/assets/0bfef162-efca-4f4c-b64e-94ec39e7aa0e" />
 

Adicionar dados:
 
 <img width="886" height="577" alt="image" src="https://github.com/user-attachments/assets/5c8e93fa-dcca-4cac-b12f-e6797c7a34c1" />
<img width="886" height="677" alt="image" src="https://github.com/user-attachments/assets/4c3c0b45-2b27-4219-b865-3dfb9e7fd136" />

Adicionar arquivos
 <img width="886" height="756" alt="image" src="https://github.com/user-attachments/assets/58683eac-6213-496b-b2bf-43ce4400aa71" />

Validando perguntas:
<img width="886" height="462" alt="image" src="https://github.com/user-attachments/assets/221ec847-aedd-4bf6-97e8-ddb59e5e690b" />
 

Fazer deploy do APP
 <img width="886" height="657" alt="image" src="https://github.com/user-attachments/assets/01325524-e0e1-4e93-ad29-b147f0018597" />

