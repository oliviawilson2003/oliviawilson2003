<br />

```JS
class Oliviawilson {
  constructor() {
    this.name = "Olivia Wilson";
    this.profile = ["Software Engineer", "Javascript Developer"];
    this.tech = [
      "Javascript",
      "Typescript",
      `Python`,
      { "Framework/Library": ["React.js", "Next.js"] },
    ];
  }

  get informations() {
    const today = new Date();

    return (
      `My name is ${this.name} and I'm focusing on Full Stack development (sometimes also A.I.). \n` +
      `I have an ${this.profile[0]} and ${this.profile[1]} profile. \n` +
      `Technologies I use the most: ${this.tech[0]}, ${this.tech[1]} e ${this.tech[2]}. \n` +
      `My differential is in the creativity to solve problems in an innovative and efficient way. \n\n`      
    );
  }
}

const Me = new Oliviawilson();
console.log(Me.informations);
```
<br />

<div>

<br />

</div>
