
# Teste Dev React Native Pl

## Qual o objetivo do teste?
Welcome dev! Esse teste tem o objetivo entender um pouco mais sobre a forma como você desenvolve, estilo de código e organizacão do projeto.

## Funcionalidades da aplicação

Na aplicação de teste faremos um simples visualizador de modelos de veículos exibindo algumas informações da tabela FIPE (orgão que define preços de veículos atualmente).

Na aplicação de teste você deverá criar uma aplicação em React Native chamada "FipeCar", utilizando o CLI `npx react-native init FipeCar`.

A aplicação deverá consumir a API de testes disponível em [https://deividfortuna.github.io/fipe/](https://deividfortuna.github.io/fipe/). Serão usados os endpoints:

- Listagem de marcas, ex: [https://parallelum.com.br/fipe/api/v1/carros/marcas](https://parallelum.com.br/fipe/api/v1/carros/marcas)
- Listagem de modelos, ex: [https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos](https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos)
- Listagem de anos para o modelo, ex: [https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos/5940/anos](https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos/5940/anos)
- Detalhes de um modelo com base no ano, ex: [https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos/5940/anos/2014-3](https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos/5940/anos/2014-3)

Como é uma API bastante simples e intuitiva, praticamente todos os atributos de cada recurso serão utilizados.

Você deverá seguir o layout disponível em [Link do layout no Figma](https://www.figma.com/file/QcRcGmlvWQOHPnLmjdWkvE/FipeCar---Teste-Dev-RN-pl?node-id=462%3A1241)

A navegação inicia com uma lista de marcas, quando uma marca é selecionada exibe os modelos da marca, quando seleciona um modelo é exibido um popup com os anos disponíveis daquele modelo e quando seleciona o ano é exibido os detalhes do veículo (A navegação está documentada no Figma).

Além da listagem de itens, a aplicação deverá ter a opção de favoritar veículos, onde o histórico de itens favoritados deve ser salvo localmente via Local Storage ou SQLite.

⚠️ &nbsp;Caso não consiga completar 100% do teste, envie-nos mesmo assim e comente no email quais foram as dificuldades e analisaremos seu teste ;)

## História do usuário

> **Como** revisor do teste 
> 
> **Quero** acessar o código e rodar o projeto em um
> simulador
> 
> **Para** poder entender melhor sobre seu código e te avaliar
> tecnicamente para a vaga que se candidatou

Ps. Essa é uma história de usuário ilustrativa, para te ajudar a entender melhor o resultado final.


## Sugestões/Considerações

- Utilize axios preferencialmente;
- Use React Navigation, please;
- Use TypeScript preferencialmente;
- Por favor, use componentes funcionais 🙏;
- Usando styled components conseguirá 5 pontos para Grifinória;
- Fique a vontade para adicionar funcionalidades ou melhorias que façam sentido no contexto da aplicação;

Caso escolha seguir usando ferramentas diferentes das sugestões, não tem problema, faça do seu jeito e explique o porque das decisões no email, submeta seu teste e avaliaremos com o mesmo cuidado e carinho.

## Avaliação

Além do seu código, avaliaremos também alguns outros pontos que podem ser mais subjetivos, como por exemplo:

- Organização do código
- Abstração e entendimento
- Documentação
- Reaproveitamento
- Usabilidade
- Lógica utilizada
- Criatividade

## Envio do teste

Ao finalizar o teste, envie um email com o assunto `[Teste Dev RN pl] Teste finalizado! Seu Nome`, no corpo do email adicione o **link de seu repositório com o resultado** e suas considerações para o email rh@nanoincub.com.br.

## Dúvidas

Se tiver qualquer dúvida sobre esse teste, envie um email com o assunto `[Teste Dev RN pl] O assunto da dúvida` para o email rh@nanoincub.com.br
