📌 Descrição do Código

1️⃣ Leitura da planilha de clientes
O código abre a planilha dados_clientes.xlsx e lê os dados da aba principal.
Cada linha contém: Nome, Valor, CPF e Vencimento.

2️⃣ Configuração da planilha de fechamento
Tenta abrir a planilha_fechamento.xlsx.
Se a planilha não existir, cria uma nova e adiciona os cabeçalhos.

3️⃣ Automação do navegador com Selenium
Abre o navegador e acessa o site https://consultcpf-devaprender.netlify.app/.
Para cada CPF da planilha de clientes:
Insere o CPF no campo de pesquisa.
Clica no botão de consulta.
Aguarda a resposta do site.
Lê o status ("em dia" ou "pendente").
Se estiver "em dia", captura a data e o método de pagamento.

4️⃣ Registro na planilha de fechamento
Os dados são gravados na planilha_fechamento.xlsx:
Se o CPF estiver em dia → Registra a data e o método de pagamento.
Se o CPF estiver pendente → Apenas marca como "pendente".
A planilha é salva a cada iteração para evitar perda de dados.
5️⃣ Encerramento
O código aguarda uma entrada do usuário antes de fechar o navegador.
🔧 Tecnologias utilizadas
Python
Selenium (automação de navegador)
OpenPyXL (manipulação de planilhas Excel)

VEJA O RESULTADO CLICANDO NO LINK  
https://github.com/user-attachments/assets/cdc71bc3-9644-420d-85d3-e23f58a2a8a6



