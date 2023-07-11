<h2>Hi I'm Juan Ramirez 👋</h2>
<p><em>Fullstack Software Engineer at <a href="https://www.limberhealth.com/">Limber</a> </em></p>

```typescript
interface Developer {
    api: string[];
    architecture: string[];
    databases: string[];
    frameworks: string[];
    languages: string[];
    tools: string[];
    code: () => void;
}

class FullstackDeveloper implements Developer {
    api: string[];
    architecture: string[];
    cloud: string[];
    databases: string[];
    frameworks: string[];
    languages: string[];
    tools: string[];

    constructor(){
        this.api = ['REST', 'Graphql', 'GRPC']
        this.architecture = ['Microservice', 'Layer', 'Event-Driven]
        this.cloud = ['AWS', 'GCP'];
        this.databases = ['postgresql', 'mysql', 'sqlserver', 'dynamoDB', 'MongoDB'];
        this.frameworks = ['docker', 'k8s', 'vue', 'angular'];
        this.languages = ['javascript', 'ruby', 'golang', 'python', 'C#'];
        this.tools = ['react', 'node'];
    }

    code(){
        return "lets go 🧨";
    }
}

const punchtera = new FullstackDeveloper();
punchtera.code();

```

- Reach me through LinkedIn or Twitter 📫. 

[![Twitter: jsramirezc](https://img.shields.io/twitter/follow/jsramirezc?style=social)](https://twitter.com/jsramirezc)
[![Linkedin: juan-sebastian-ramirez-castañeda-8176a04b](https://img.shields.io/badge/-juan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/juan-sebastian-ramirez-castañeda-8176a04b/)](https://www.linkedin.com/in/juan-sebastian-ramirez-castañeda-8176a04b/)
[![GitHub: punchtera](https://img.shields.io/github/followers/thaiane?label=follow&style=social)](https://github.com/punchtera)
