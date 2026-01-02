<p align="center">
  <img src="https://raw.githubusercontent.com/berkoca/berkoca/master/neo.gif" />
</p>

```js
import { Coffee } from "caffeine";
import { SoftwareDeveloper } from "universe";

class Berkoca extends SoftwareDeveloper {
  constructor() {
    super({ crashesWithoutCoffee: true });
    
    this.name = "Berk Koca";
    this.title = "Senior Backend Developer";
    this.location = "Istanbul, Turkey";
    this.company = "Pınar";
  }
  
  skills = {
    languages: ["JavaScript", "TypeScript", "Go"],
    databases: ["MongoDB", "MySQL", "PostgreSQL", "Redis"],
    frameworks: ["Vue.js", "React.js", "Nuxt.js", "Express.js", "Socket.io", "NestJS", "Retter.io"],
    technologies: ["GraphQL", "REST", "Websocket", "RabbitMQ", "Docker", "Kubernetes", "AWS"]
  };
  
  async workDay() {
    const coffee = new Coffee({ type: "Americano", sugar: false });
    
    while(this.isAwake()) {
      await this.drinkCoffee(coffee);
      await this.writeCode({ bugs: false }); // optimistic
      
      if (this.bugs.length) {
        await this.fixBugs();
        await this.drinkMoreCoffee(coffee);
      }
    }
  }
}
```

---

```js
Promise.all([born, study, work, learn])
  .then((life) => console.log("Enjoying the journey!"))
  .catch((error) => console.debug("Coffee needed:", error));
```
