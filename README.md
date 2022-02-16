<p align="center">
  <img src="https://raw.githubusercontent.com/berkoca/berkoca/master/neo.gif" />
</p>

___

```js
import { SoftwareDeveloper } from 'berkoca';

class Bio extends SoftwareDeveloper {
  name     = 'Berk Koca';
  title    = 'Software Developer';
  company  = '-';
  location = 'Istanbul, Turkey';
}

class Skills extends SoftwareDeveloper {
  languages    = ['JavaScript', 'TypeScript'];
  databases    = ['MySQL', 'MongoDB', 'PostgreSQL', 'Redis'];
  orms         = ['Sequelize', 'Mongoose', 'TypeORM'];
  frameworks   = ['Vue.js 2/3', 'Express.js', 'Socket.io'];
  technologies = ['GraphQL', 'REST', 'Websocket'];
}
```
___

```js
Promise.all([born, study, work, die]).then(life => process.exit());
```
