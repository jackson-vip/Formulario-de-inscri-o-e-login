# Formulário de Registro, Login e Recuperação de Senha usando html, CSS e JavaScript

Este é um exemplo de código HTML, JavaScript e CSS que demonstra um conjunto de formulários de registro, login e recuperação de senha em uma única página. Cada seção é estilizada com classes de CSS e validada com funções JavaScript. O código também inclui o uso de ícones da Font Awesome para melhorar a experiência do usuário.

### Estrutura do HTML

O código HTML é dividido em três seções principais, cada uma representando um tipo de formulário: Registro, Login e Recuperação de Senha. Cada formulário é acompanhado de campos específicos, rótulos, mensagens de erro e botões de ação.

### Formulário de Registro

- [ ] Título: "Register"
- [ ] Campos: Nome completo, Nome de usuário, Endereço de e-mail, Senha, Confirmação de senha, Gênero, Captcha e Aceitação dos Termos de Uso.
- [ ] Botão "Register" para enviar o formulário.

### Formulário de Login

    Título: "Log in"
    Campos: Nome de usuário, Senha, Captcha.
    Botão "Log in" para enviar o formulário.

### Formulário de Recuperação de Senha

- [ ] Título: "Recover password"
- [ ] Campo: Endereço de e-mail.
- [ ] Botão "Reset password" para enviar o formulário.

### Estilo (CSS)

O código CSS é usado para estilizar os elementos dos formulários, incluindo rótulos, campos de entrada, mensagens de erro e ícones de verificação e erro. Classes CSS são aplicadas dinamicamente para indicar sucesso ou erro na validação dos campos.

### Utilização de Font Awesome

O código inclui a biblioteca Font Awesome para a renderização dos ícones usados na interface do usuário. Certifique-se de que o script do Font Awesome esteja corretamente referenciado no seu projeto para que os ícones sejam exibidos corretamente.

### Funções JavaScript

O código JavaScript define várias funções que são chamadas para validar os campos dos formulários, processar a lógica de visualização dos campos de senha, gerar e validar o Captcha e verificar se os campos foram marcados corretamente.

As funções incluem validações para campos como nome completo, nome de usuário, endereço de e-mail, senha e confirmação de senha, bem como a lógica para mostrar ou ocultar senhas. Além disso, a função Captcha gera uma sequência alfanumérica aleatória e verifica se o valor inserido pelo usuário corresponde a essa sequência.

### Validação dos Formulários

- Registro: Os campos de nome completo, nome de usuário, endereço de e-mail, senha, confirmação de senha, Captcha, aceitação dos Termos de Uso e a seleção de gênero são validados. Mensagens de erro são exibidas se houver problemas de validação.

- Login: Os campos de nome de usuário, senha e Captcha são validados. Mensagens de erro são exibidas conforme necessário.

- Recuperação de Senha: A validação é aplicada ao campo de endereço de e-mail, e mensagens de erro são exibidas quando necessário.

### Observações

- O atributo action nos formulários está vazio, o que significa que os formulários não enviam dados para nenhum destino específico. Você deve atualizá-los com a ação desejada, como a URL de processamento do servidor.
- Os formulários de registro e login incluem a funcionalidade Captcha, que ajuda a verificar se o usuário é um humano, não um robô. Os valores do Captcha são gerados dinamicamente e recarregados com um botão de recarga.
- Certifique-se de que o código do formulário funcione adequadamente com as regras de validação no lado do servidor para garantir a segurança.
- Este código pode servir como ponto de partida para criar um sistema de registro, login e recuperação de senha em seu projeto. Certifique-se de adicionar a lógica de servidor e as funcionalidades necessárias para que esses formulários funcionem corretamente em seu aplicativo.

Este README fornece uma visão geral do código e de suas funcionalidades. Certifique-se de entender a estrutura e a lógica para personalizar e integrar esses formulários em seu projeto conforme necessário.