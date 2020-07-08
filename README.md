
<h3 align="center"> 
	 NextLevelWeek 1.0 🚀 
</h3>

# ♻️ Ecoleta 

Ecoleta is a model of connecting companies and entities that collect organic and inorganic waste to people who need to dispose of their waste in an ecological way.

Companies or entities may register on the web platform by sending:

- An image of the collection point, name of the entity, email and whatsapp and the address so that it can appear on the map.
- In addition to selecting one or more collection items:
- Lamps
- Batteries
- Papers and cardboard
- Electronic waste
- Organic waste
- Kitchen oil

Users will have access to the mobile application, where they can:
- Browse the map to see the registered institutions.
- Contact the entity through E-mail or WhatsApp.

## 🛠 Technology

The following tools were used in the construction of the project:

- [Node.js](nodejs)
- [React](reactjs)
- [React Native](rn)
- [Expo](expo)
- [TypeScript](typescript)

### Starting the API

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

### Starting the Front-end

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

### Starting the Mobile

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
Project developed during **NLW - Next Level Week** offered by [Rocketseat](rocketseat.com.br).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
