# Projeto de Login com Firebase

Este é um projeto Android que implementa um sistema de login simples utilizando o Firebase Authentication. O projeto permite que usuários se registrem e façam login utilizando e-mail e senha. Após o login bem-sucedido, o usuário é redirecionado para uma tela de boas-vindas, onde pode se deslogar.

## Funcionalidades

- **Registro de usuário**: O usuário pode se registrar utilizando um e-mail e uma senha.
- **Login de usuário**: O usuário pode fazer login com um e-mail e senha previamente registrados.
- **Tela de boas-vindas**: Após o login, o usuário é redirecionado para uma tela de boas-vindas com a opção de deslogar.
- **Deslogar**: O usuário pode deslogar da conta e voltar para a tela de login.

## Tecnologias Utilizadas

- **Firebase Authentication**: Para autenticação de usuários com e-mail e senha.
- **Android**: Para desenvolvimento da interface do usuário e navegação entre telas.
- **Kotlin**: Linguagem utilizada para desenvolvimento do aplicativo Android.

## Estrutura do Projeto

O projeto é composto por duas atividades principais:

1. **MainActivity**: Tela inicial onde o usuário pode se registrar ou fazer login.
2. **WelcomeActivity**: Tela de boas-vindas que é exibida após um login bem-sucedido, com a opção de deslogar.

### Estrutura de Pacotes

- `com.login`: Pacote principal contendo as atividades `MainActivity` e `WelcomeActivity`.

### Layouts

- **activity_main.xml**: Layout da tela de login e registro.
- **activity_welcome.xml**: Layout da tela de boas-vindas.

## Como Rodar o Projeto

### Requisitos

- **Android Studio**: IDE recomendada para abrir e rodar o projeto.
- **Conta no Firebase**: Crie um projeto no [Firebase](https://firebase.google.com/) e configure a autenticação via e-mail e senha.

### Passos

1. Clone este repositório para sua máquina local.
2. Abra o projeto no Android Studio.
4. Sincronize o projeto com o Firebase.
5. Construa e execute o aplicativo no emulador ou dispositivo Android.

## Como Funciona

1. **Tela de Login e Registro**:
   - O usuário pode registrar uma nova conta com um e-mail e senha.
   - O usuário pode também fazer login com um e-mail e senha já cadastrados.

2. **Tela de Boas-vindas**:
   - Após o login bem-sucedido, o usuário é direcionado para a `WelcomeActivity`.
   - Na `WelcomeActivity`, o usuário pode clicar no botão de "Logout" para deslogar e voltar para a tela de login.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Se você tiver algum problema ou dúvida, sinta-se à vontade para abrir uma *issue* neste repositório!
