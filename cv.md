# Brizhevskaya Diana

## Contacts
- **Location:** Minsk, Belarus
- **Phone:** +375 (33) 689-40-75
- **E-mail:** dianabrizh@gmail.com
- **GitHub:** [brizhd](https://github.com/brizhd)

## About me
My goal is to become a good and demanded developer. I am capale of self-education and love to do it, because I want to always develop new skills. I am attentive to details and I am an excellent team worker!

## My skills
- HTML5
- CSS3
- JavaScript (Basic)
- Git
- Figma
- Photoshop
- VS Code

## Code example
```
function numberOfPairs(gloves) {
  let glovesMap = new Map();
  for (let i=0; i<=gloves.length-1; i++) {
    if (glovesMap.has(gloves[i])) {
      glovesMap.set(gloves[i], glovesMap.get(gloves[i])+1);
    } else {
      glovesMap.set(gloves[i], 1);
    }
  }

  let result = 0;
  for (let amount of glovesMap.values()) {
    result += Math.trunc(amount/2);
  }
   
  return  result;
}
```

## Education
RS Schools course "JavaScript/Front-end. Stage 0"

## Languages
- Russian - Native
- English - Pre-intermediate
