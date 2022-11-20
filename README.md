<p align="center">
  <img src="https://raw.githubusercontent.com/berkoca/berkoca/master/neo.gif" />
</p>

___

```js
import { SoftwareDeveloper } from 'berkoca';

class Bio extends SoftwareDeveloper {
  name     = 'Berk Koca';
  title    = 'Full Stack Developer';
  company  = 'Bolt Insight';
  location = 'Istanbul, Turkey';
}

class Skills extends SoftwareDeveloper {
  languages    = ['JavaScript', 'TypeScript'];
  databases    = ['MySQL', 'MongoDB', 'PostgreSQL', 'Redis'];
  orms         = ['Sequelize', 'Mongoose', 'Prisma'];
  frameworks   = ['Vue.js 2/3', 'React.js' 'Express.js', 'Socket.io'];
  technologies = ['GraphQL', 'REST', 'Websocket', 'RabbitMQ'];
}
```
___

```js
Promise.all([born, study, work, die]).then(life => process.exit());
```
