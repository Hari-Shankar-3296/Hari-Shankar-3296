# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Hari-Shankar-3296)
[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


```javascript
'use-strict'

class WhoAmI {
    constructor(){
        this.name = 'Harishankar Devaraj';
        this.role = 'Senior Frontend Developer';
        this.previousEmployer = '/thoughtworks';
        this.languageSpoken = ['ta_IN', 'en_US'];
        this.native = "India 🇮🇳"
        this.livesIn = "Australia 🇦🇺"
    }

    greet(){
        console.log("Thanks for dropping by, hope you find some of my work interesting.")
    }
    
    skills(){
      const mySkills = {
        code: [
            Javascript,
            Typescript,
            HTML,
            CSS,
            Python
        ],
        tools: [ 
            React, 
            Redux,
            ReactNative,
            Styled-Components,
            Jest,
            testing-library
        ],
        architecture: ['dynamic-data-driven', 'design system pattern', 'mobile-first-approach'],
        techCommunities: {
          organiser: 'Brogrammers',
          member: ['UI Community', 'Silligong Valley'],
        },
        funChallenge: "I am doing the #CSSBattles challenge focused on CSS Fun"
      };
      
      return mySkills;
    }
}

me = new WhoAmI()
me.greet()
```
