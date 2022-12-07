```ts
import { Profile, Language } from 'identity';

export const Naamloos : Profile = {
  name: "Ryan de Jonge",
  userName: "Naamloos",
  programmingLanguages: [
    { language: "C#", proficiency: "High" },
    { language: "TypeScript/JavaScript", proficiency: "High" },
    { language: "PHP", proficiency: "High" },
    { language: "Java", proficiency: "High" },
    { language: "Python", proficiency: "Intermediate" },
    { language: "Rust", proficiency: "Intermediate" },
    { language: "C++", proficiency: "Intermediate" }
  ],
  spokenLanguages: [
    Language.English, 
    Language.Dutch, 
    Language.German
  ],
  jobInfo: {
    role: "Software Developer",
    company: "Provrex B.V."
  },
  educationInfo: {
    university: "NHL Stenden University of Applied Sciences",
    type: "Bachelor Information Technology (Software Engineering)",
    completed: false,
  }
}
```
