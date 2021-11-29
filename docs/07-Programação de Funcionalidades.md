# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Implementação do sistema descritas por meio dos requisitos funcionais e/ou não funcionais. Deve relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Para cada requisito funcional, pode ser entregue um artefato desse tipo

<h1> Tela – Escolha do carreto </h1>
Após realizar o login o usuário é redirecionado a tela onde ele irá escolher o tamanho do carreto, logo abaixo já informa o proprietário do caminho, telefone, cidade onde o motorista reside e avaliação do mesmo. Após o usuário aceitar o carreto ele é redirecionado para a tela de pagamento que veremos mais abaixo.

<img src="./img/escolhaMotorista.png">
Figura X – Escolha de carreto

<h1> Tela – Cadastre-se </h1>
No menu superior tem a opção de cadastrar-se o usuário é redirecionado para uma página onde ele irá preencher os campos com as seguintes informações: E-mail, nome, número de celular e senha.

<img src="./img/LoginCadastro.png">

Figura X – Cadastre-se

<h1> Tela – Aluguel de caixas 01 </h1>
A tela de aluguel de caixa apresenta, no bloco de conteúdo, as vantagens de se alugar caixas resistentes para realizar a mudança e o preço acessível.

<img src="./img/aluguelCaixas.png">

Figura X – Descrição de aluguel de caixa

<h1> Tela – Pagamento </h1>
Assim que o usuário informa o pacote ou o carreto, ele é redirecionado para uma tela de pagamento onde ele tem a opção de pagar com cartão ou boleto.

Figura X - Pagamento do aluguel das caixas e carreto
<img src="./img/meioPagamento.png">
Figura X - Pagamento do aluguel das caixas e carreto

Nesta seção é apresentada a tela de login. O respectivo endereço https://pucminasmude.herokuapp.com/ e outras orientações de acesso são apresentadas na sequência.

### Acesso para tela de login/cadastro (RF-01 e RF-02)

No cabeçalho da tela principal possui um botão de login e outro de cadastro, onde leva para uma página de login/cadastro após realizar o que é pedido vai para o perfil do usuário. As informações são armazenadas no Github com estruturas de dados baseada em JSON. Um exemplo das telas é apresentado nas Figuras abaixo.

<img src="../../../Downloads/a.png">
<img src="../../../Downloads/b.png">

Cabeçalho da Home

Login/Cadastro

### Requisitos atendidos

● RF-01 - Tela de Login/Cadastro

● RF-02 - Perfil do Usuário

### Artefatos da funcionalidade

● home.html
● login.html
● home.css
● home.js

Estrutura de Dados

{
"home": [
{
"id": 1,
"botão": "Login",
"titulo": "Seu Nome",
"titulo": "Sua Senha",
"marcador": "Manter-me logado",
"botão": "Logar"
"titulo": "Ainda não tem conta?"
“botão”: “Cadastre-se”
}
]
}

### Instruções de acesso

1. Abra um navegador de Internet e informe a seguinte URL: https://pucminasmude.herokuapp.com/

2. O login/cadastro é a primeira funcionalidade exibida pelo site.

### Perfil do Usuário (RF-05)

A tela de perfil permite ao usuário ter acesso ao mapa da sua região.

<img src="../../../Downloads/c.png">

Artefatos da funcionalidade
● login.html
● perfil.html
● perfil.css
● perfil.js

### Instruções de acesso

3. Faça o download do arquivo do projeto (ZIP) ou clone do projeto no GitHub; 4. Descompacte o arquivo em uma pasta específica; 5. Abra o Visual Studio Code e execute o Live Server; 6. Abra um navegador de Internet e informe a seguinte URL:
