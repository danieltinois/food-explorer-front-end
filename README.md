## 👨‍💻 Diferenciais - Página do cliente

## Consulta automática do Cep via Api externa:

<p>Ao digitar um cep na página atualizar perfil, o sistema efetua uma busca do cep do cliente e preenche os campos respectivos automaticamente através da Api: <a href="https://viacep.com.br/"> https://viacep.com.br/</a> </p>

---

## Carrinho de compras interativo:

<p>Nessa versão do food Explorer o cliente tem acesso ao carrinho de compras interativo, onde o mesmo tem a liberdade de alterar a quantidade de itens, excluir o produto, além de poder verificar o endereço de entrega ou atualizar. No resumo do pedido o cliente pode verificar todos os valores. E na forma de envio o mesmo pode escolher entre frete grátis ou econômico. Assim facilitando sua experiência de compra.</p>

---

## Checkout de compras completo:

<p>Ao finalizar a compra do seu pedido o cliente pode executar de forma rápida em 4 passos, assim maximizando seu tempo e diminuindo toda a burocracia de uma compra. No 1º passo ele verifica seus dados pessoais. no 2º passo confirma seu endereço de entrega. No 3º passo confirma a opção de frete escolhida no carrinho de compras e os valores e no 4º e último passo o cliente tem a opção de escolher a forma de pagamento, cartão de crédito ou pix, aqui ele finaliza sua compra e é redirecionado para a página de confirmação do pedido finalizado. E em resumo do pedido o mesmo tem a opção de adicionar observações em seu pedido assim diminuindo o risco de ser enviado um produto fora do que o cliente deseja, mais também aumentando sua experiência direta com a loja.</p>

---

## 👨‍💻 Diferenciais - Página do administrador

---

## Top produtos favoritos:

<p>O administrador do site ao acessar a página de favoritos, terá acesso a todos os produtos favoritados por ordem de relevância, assim podendo criar ações de marketing para os produtos específicos, ao clicar no produto favorito especifico, é redirecionado para a página do prato, podendo editar, mudando a descrição, preço, etc. Essa funcionalidade tem como objetivo de aumentar as vendas com promoções direcionadas para os produtos mais visualizados, aumentando a escalabilidade das vendas.</p>

---

## Processamento de pedidos eficiente:

<p>Na página de pedidos acessado pelo administrador, o acesso dinâmico as informações facilita o processamento dos pedidos, assim ganhando tempo em todo o processo. Todos os pedidos dos clientes são exibidos nessas página, separado por blocos, onde o administrador após processar, enviar e confirmar o pedido entregue e todas as outras informações, pode mudar o status do pedido para finalizado, caso tenha alguma dúvida sobre o pedido especifico, o administrador pode clicar em ver detalhes, assim tendo um acesso mais completo a todos os dados do pedido. </p>

---

## 📄 Tecnologias

As seguintes tecnologias foram empregadas na criação deste projeto:

- [Splide (v0.7.12)](): Criação de sliders ou carrosséis responsivos e personalizáveis em páginas da web.
- [Axios (v1.6.2) ](): Simplifica e facilita a realização de solicitações HTTP em navegadores e ambientes Node.js.
- [React (v18.2.0) ](): Construção de interfaces de usuário (UI) interativas e reativas em aplicações web.
- [React-dom (v18.2.0) ](): Extensão específica do React projetada para lidar com a manipulação do DOM (Document Object Model).
- [React-icons (v4.11.0) ](): Biblioteca que fornece ícones populares e amplamente utilizados para serem incorporados em projetos React.
- [react-router-dom (v6.17.0) ](): Biblioteca React, projetada para facilitar a navegação entre diferentes componentes.
- [styled-components (v6.1.0) ](): Permite que você escreva estilos diretamente em seus componentes React usando uma sintaxe de template literal do JavaScript.

---

## 🔖 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/community/file/1196874589259687769). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

---

## 🚀 Como utilizar

Clone o projeto para o local desejado em seu computador.

```bash
$ git clone https://github.com/danieltinois/food-explorer-front-end.git
```

---

## 🚧 Executando o front-end

Entre na pasta raiz do repositório

```bash
cd food_explorer_front_end
```

Instale as dependências necessárias

```bash
$ npm install
```

Acesse a pasta src/services/index.js e insira a sua baseURL

```bash
import axios from "axios"

export const api = axios.create({
  baseURL: "INSIRA_AQUI_SUA_BASE_URL",
})
```

Execute a aplicação localmente:

```bash
$ npm run dev
```

Clique no link apresentado no terminal segurando ctrl
Exemplo:

```bash
  VITE v4.5.0  ready in 396 ms

  ➜  Local:   http://127.0.0.1:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

---

## 🛠️ Código Api back-end

<p>Você pode acessar a API back-end desse projeto através do link: 
<a href= "https://github.com/danieltinois/food-explorer-back-end" target="_blank"> Clique aqui ⏯ </a>
</p>

---

<p align="center"> created by Daniel Tinois  - © 2024 - Todos os direitos reservados.<p align="center">
 <a href="https://www.linkedin.com/in/daniel-tinois-7338a2244/" target="_blank"><img src="https://static.licdn.com/sc/h/5bukxbhy9xsil5mb7c2wulfbx" height="25" width="25" alt="Linked" />
</p></p>

---
