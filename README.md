Consulta de CEP (API ViaCEP)
Um projeto simples em Java para consultar endereços brasileiros de forma automatizada, utilizando a API ViaCEP. A aplicação recebe um número de CEP, busca os dados e gera um arquivo .json formatado com as informações do endereço.

🛠️ Tecnologias Utilizadas
Java 17+ (ou a versão que você estiver usando)

Gson: Biblioteca do Google para conversão de objetos Java em JSON e vice-versa.

HttpClient: Para realizar as requisições HTTP de forma nativa.

🚀 Funcionalidades
Consulta de endereços em tempo real.

Tratamento de exceções para CEPs inválidos ou erros de conexão.

Geração automática de arquivo JSON nomeado com o CEP consultado.

Uso de Records para representação de dados imutáveis.

📁 Estrutura do Projeto
Main.java: Ponto de entrada da aplicação e interação com o usuário.

ConsultaCep.java: Responsável pela comunicação com a API ViaCEP.

Endereco.java: Modelo de dados (Record) que representa o endereço.

GeradorDeArquivo.java: Lógica para salvar os dados recebidos em um arquivo físico.

🚧 Próximos Passos
Este projeto ainda está em desenvolvimento. Algumas implementações futuras previstas são:

[ ] Interface gráfica ou melhoria na interação via console.

[ ] Opção de listar múltiplos CEPs.

[ ] Validação avançada de formato de CEP (Regex).