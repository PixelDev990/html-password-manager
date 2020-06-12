# HTML Password Manager

Adaptado de [Helpful Sheep - HTML password manager](https://helpfulsheep.com/2012-01-20-html-password-manager/)

Utiliza a [Stanford Javascript Crypto Library](http://bitwiseshiftleft.github.io/sjcl/) 

Para Salvar as alterações clique no botão Salvar, não tente usar a opção de menu **Arquivo / Salvar** do navegador para salvar as alterações(não funciona)

Para refazer o logon tecle **F5**

Para Resetar a senha Mestra, Digite no lugar da senha: **reset**

Os campos **Mensagem Secreta** e **Dado de Autenticação** são opcionais, são utilizados como chaves adicionais para encriptar as senhas

ATENÇÃO: Se a senha Mestra for resetada, todas as senhas serão perdidas e deverão ser recadastradas. Tenha sempre uma cópia de **backup** deste arquivo.

## CHANGELOG

### [Unreleased]
* Mobile device detection
* Allow to save only the master password

### [hpm_0.5] - 2020-06-10
* Search feature improved
* Save button
* Other interface improvements

### [hpm_0.4] - 2019-07-13
* Unified release V0.4: fields for optional settings: salt and adata

### [en_0.3] - 2019-07-12
* Improved master password screen, hiding password by default and button to show password | Visibility of statusIndicator

### [pt-br_0.3] - 2019-07-12
* Melhorada tela da senha mestra, ocultando a senha por padrão e botão para mostrar senha | Visibilidade do statusIndicator

### [en_0.2] - 2019-03-13
* Version adapted for english that uses an "input type password" to receive the master password, hiding it during typing

### [pt-br_0.2] - 2019-03-13
* Versão adaptada para pt-br que usa um "input type password" para receber a senha mestra ocultando-a durante a digitação

### [en_0.1] - 2019-03-12
* Version adapted for english that uses "prompt" to receive the master password

### [pt-br_0.1] - 2019-03-12
* Versão adaptada para pt-br que usa "prompt" para receber a senha mestra

