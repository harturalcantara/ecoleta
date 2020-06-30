
<h3 align="center"> 
	 NextLevelWeek 1.0 🚀 
</h3>

# ♻️ Ecoleta 

O Ecoleta é um modelo de conectar empresas e entidades de coleta de resíduos orgânicos e inorgânicos as pessoas que precisam descartar seus resíduos de maneira ecológica.

As empresas ou entidades poderão se cadastrar na plataforma web enviando:
- Uma imagem do ponto de coleta, nome da entidade, email e whatsapp e o endereço para que ele possa aparecer no mapa.
- Além de selecionar um ou mais ítens de coleta: 
  - Lâmpadas
  - Pilhas e baterias
  - Papéis e papelão
  - Resíduos eletrônicos
  - Resíduos orgânicos
  - Óleo de cozinha

Os usuários terão acesso ao aplicativo móvel, onde poderão:
- Navegar pelo mapa para ver as instituições cadastradas
- Entrar em contato com a entidade através do E-mail ou WhatsApp.

Projeto desenvolvido durante a **NLW - Next Level Week** oferecida pela [Rocketseat](rocketseat.com.br).

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](nodejs)
- [React](reactjs)
- [React Native](rn)
- [Expo](expo)
- [TypeScript](typescript)

### Iniciando a API

```bash
# Clone this repository
$ git clone https://github.com/danilods/e-coleta

# Go into the repository
$ cd ecoleta/backend

# Install dependencies
$ yarn install

# Run Migrates
$ yarn knex:migrate

# Run Seeds
$ yarn knex:seed

# Start server
$ yarn dev

# running on port 3333
```

### Iniciando o Front-end

```bash
# Clone this repository
$ git clone https://github.com/danilods/e-coleta

# Go into the repository
$ cd ecoleta/frontent

# Install dependencies
$ yarn install

# Run
$ yarn start

# running on port 3000
```

### Iniciando o Mobile

```bash
# Clone this repository
$ git clone https://github.com/danilods/e-coleta

# Go into the repository
$ cd ecoleta/mobile

# Install dependencies
$ yarn install

# Run
$ yarn start

# Expo will open, just scan the qrcode on terminal or expo page

# If some problem with fonts, execute:
$ expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto

```


## 📝 Licença

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
