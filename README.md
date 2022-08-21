# Welcome to my github profile

## About me
I`m a 26 years old Frontend Developer very passionate about my technologies and software Development.
I can use the following languages, libraries, frameworks or technologies.

![image](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![image](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![image](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![image](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![image](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![image](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![image](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![image](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![image](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![image](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![image](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)
![image](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![image](https://img.shields.io/badge/d3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)
![image](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![image](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)


## You can contact me through these links
[![image](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthurnassar@gmail..com?subject=Github%20contact)
[![image](https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white)](https://m.me/arthur.nassar.7)
[![image](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Kaozebra)
[![image](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/351920436456)
[![image](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthurnassar/)


```typescript
class FrontendDev {

  private name: string;
  private age: number;
  private technologies: string[]; // List of all Frameworks, languages, libraries and general knowledges
  private languages: { name: string, level: string }[]; // Languages that I speak
  private wishlist: string[]; 
 
  constructor(name: string, age: number, technologies: string[], languages: { name: string, level: string }[], wishlist: string[]) {
    this.name = name;
    this.age = age;
    this.technologies = technologies;
    this.languages = languages;
    this.wishlist = wishlist;
  }
 
  greet(): string {
    return `Hello, my name is ${ this.name } and I'm ${ this.age } years old`
  }
  
  
  myTechnologies(): string {   
    return `As a developer I have knowledge about those things: ${ this.technologies.join(', ') }`
  }
  
  myLanguages(): string {
    let answer: string[] = []
    this.languages.forEach((language: any) => {
      answer.push(`${ language.level } ${ language.name }`)
    })
    return `I can speak and write ${ answer.join(', ') }`
  }
  
  returnWishlist(): string {
    return `I wish to ${ this.wishlist.join(', ') }`
  }
}
 
let me = new FrontendDev(
  'Arthur Nassar',
  26,
  ['HTML', 'CSS', 'Bootstrap', 'SASS', 'Javascript', 'VueJS', 'Vue Router', 'Vuex', 'React', 'Redux', 'React Router', 'Typescript', 'MongoDB', 'NestJS', 'PHP'],
  [ { name: 'Portuguese', level: 'native' }, { name: 'English', level: 'advanced' }, { name: 'French', level: 'beginner' } ],
  [ 'Finish my ongoing React pathfinder project', 'Write an academic article about front-end technologies', 'Participate in a software development presencial event' ]
  );
  
  console.log(me.greet())
  // Hello, my name is Arthur Nassar and I`m 26 years old
  
  console.log(me.myTechnologies())
  // As a developer I have knowledge about those things: HTML, CSS, Bootstrap, SASS, Javascript, VueJS, Vue Router, Vuex, React, Redux, React Router, Typescript, MongoDB, NestJS, PHP
  
  console.log(me.myLanguages())
  // I can speak and write native Portuguese, advanced English, beginner French
  
  console.log(me.returnWishlist())
  // I wish to Finish my ongoing React pathfinder project, Write an academic article about front-end technologies, Participate in a software development presencial event
```

[![image](https://badgen.net/badge/See%20this%20code%20in%20action/snippet?icon=typescript)](https://www.typescriptlang.org/play?ssl=57&ssc=170&pln=1&pc=1#code/MYGwhgzhAEBiBOB7AdgFwKbICYBF0DdoBvAWAChzpoAHeAS3zA2mTAFt0AuaCVe5AOYBuSjXqNmYAVxYBXNgCN08EWSq0GTdNAzAAFskQhEAuugjde-AQG0AukOgB6J9AAydXtEQAzaGBAQOHh2dAB3RHgAawgAGmhwQVkpc3iQOgUQ+nN-bGhpZGUA6CjDMJB0LGkIUQ0JbUSBZOruIhZQyz46QTSCdBBO62gAX3tHF3cwJJSYVD0maABJHmp0MCja8S1oMM89dN5B7tsHaEpRYBQrWWBUSIAKVg4jnv9pbmR5JXh43QMjExmCw8LqCexpKZNGatdrPEHWXr4fovAQjcE7PYHVAo+wASmIoioc08ADontoALyw9CqKhEvSklLQKkpWl04kQEl-QzGUw5KncgF8iBs+mkxrNfkJSGSkWEnQMzm7CD7TyoZkYlVYtnDc5qfLwdDoVD3XEogn6qiG1CyeDIaAAAwAEv1jPE2ABPanQTzQAAkbQ5ZNCI1yWCWAHI2P7A4qSUzhtAPWt4DAjFgHaJdfrRKJPQAVdD6HmA8ym81tKjy622+0OgCCMDA0CwfWMq3gS2g8yRJTKFSq2jACkQsnVc0QEG0xMEwIDCtJgt5QJJACtEN17hH4hH8cNM-rs1X9Z63DKZuX4ccLXSEsbchAwsocXYNfZ5UGJTMST5IgBRMB9Hue4v3eXIPXxCkAD4b1vB8n3gElqFkFV7gdedQPQEkKiRIJEww89pGDDgRgdXF5WGcjLWgGs7UdZZgCmFY1iiMMdnoZh5ymR9lDXDdkC3Hc9wPKgjzOfVaOQAB1TE1UvKxr1IajJPozU9B0RAYwXJVZN4PjN23aBd1IrNyCPcgKnVEiqUKMJghQDBsDwfB7lECN63gOZbWgAA5SAIDAeBt1EAAmAA2WJRBsCMnXzABZNxDIjABhABlVKkoAIUQRBUCsMBqCS1L63SpKACkwEYCBgHoahUCSgA1WR0DKjKdya7QACVRwwIL2uagAPJLOrWW5hsqWQhp3EbAPVbqx2UJL8w9VZqtq+qdzilABEQHBMqSnzzFQVqkoABSdU6IzsSL9RsYhqW4CNTsiG0mnMdBDJw5EjNYVAGA+kZ4jaclHr-QQDj0T620esAsEYZBgEqCNAfukGjIQTB9Ch3DHqUUxkEKILQ2uqL0e6PZoE9bxBH41EZtuGgmD0HxulbTtaEQVciw2oypI4od7UA2H0DYOhgH8TyxYqfwRzHaAfCQNAAFpMHDJdSwgM7Ar+4A6GobZun8HhfFQMJAu0VtcMQagODQMR3oRuhij6NBkbsURcTZC4riMLDeXuDgSQEQ1jVNKiqAmF1AkQd0vXJH0YA8rzOz8qBArYxYHWjcKkxTNMQCwXN9UuZAIF97CTADrCCyLf5lzLXFw+cVxGyNy3+mt5Qux7bRSkQcpKmkGWeoVSdpwZWduFihL4jS1L4my3L8uoeJivS+IKqqmq9dQeIOtavfmugebesP9ABviend+PiaL5v2bj565R4mW1bt7q+Itppvb4kO3gD+gOdU6RcqAlzLhUCuAgq4klPIRBuTcJgMSYhAVY6w2JhH5u0P6vZnqeVkG9Kc8RYbw0RuGMGAgIbxDxt0QmwRMZ6BAdAMB5d-aB0kjJLUclG6iEQWpDScByYqkpl6batN74M31nMFm2Au4cy5rceIfM6CSEFoxVsotxbaylkOWW6oFYORVnkdWwp4inS0brSR2hDbNjLj4U25sWxtmtrbdUtAHa62dkiNAQA)


![image](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=arthurnassar&theme=vue)
![image](https://github-readme-stats.vercel.app/api/top-langs/?username=arthurnassar)
![image](https://github-readme-stats.vercel.app/api?username=arthurnassar)
![image](https://github-readme-streak-stats.herokuapp.com/?user=arthurnassar)






<!---
arthurnassar/arthurnassar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
