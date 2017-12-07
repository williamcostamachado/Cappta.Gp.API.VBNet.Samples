**Configurando e usando:**

------------------------------------------------------------

- Instale e execute o CapptaGpPlus.exe com os dados forneceidos pela equipe;

- Execute o CapptaGpPlus;

- Extraia e abra o diretório Cappta.Gp.API.VBNet.Samples-master;

- Abra o arquivo Cappta.Gp.Api.Com.Sample.VB.exe.config (Binaries\VB.Net) em um editor de texto e configure os parametros "Cnpj" e "Pdv" com os dados fornecidos para instalação do CapptaGpPlus (não alterar a Chave de Autenticação); 

**Ex.:**
    add key="ChaveAutenticacao" value="795180024C04479982560F61B3C2C06E" /
    add key="Cnpj" value="00000000000000" /
    add key="Pdv" value="14" /

- Execute o Cappta.Gp.Api.Com.Sample.VB.exe ou use o código do projeto para fazer as transações de testes.
