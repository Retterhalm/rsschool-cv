# **Denis Kuznetsov**
## Junior Frontend Developer

*****

### **CONTACTS**

Phone: +381611728103

E-mail: [kuznetsovd@hotmail.com](kuznetsovd@hotmail.com)

github: [https://github.com/Retterhalm](https://github.com/Retterhalm)

Linkedin: [https://www.linkedin.com/in/denis-kuznetsov235/](https://www.linkedin.com/in/denis-kuznetsov235/)

*****

### **ABOUT ME**

I've just finished JS/frontend Pre-School course and I'm really love it! I'm full of enthusiasm about my future education.

I know that now it won't be so easy, but I'm ready for the challenge.

For the last three months I've learned a lot of stuff and look straight forward to discover new horizons.

I grateful for all creators, mentors, activists and all of my colleagues-students for this opportunity, support and amazing experience!

*****


### **SKILLS**

- HTML

- CSS

- Java-Script

- Json(In progress)

- Python (Basic level)

- Java (Basic level)

- C (Basic level)

- Git and Github

- PowerShell

- Visual Studio Code, Notepad++

*****
### CODE SAMPLES
#### PYTHON
##### A DICE ROLLER
```
import random
dice_qty = int(input('How many dices do you want to roll ?')) # getting amount of dices
dices= {}
for i in range (1, (dice_qty  + 1)):                          # finding out how many side each dice is
    if i == 1:
        message = 'How many sides is your first dice ?'
    elif i == dice_qty:
        message = 'How many sides is your last dice ?'
    else:
        message = 'How many sides is your next dice ?'
    sides = int(input(message))
    dices[i] = sides                                          # forming a dictionary, where key is an index number of a dice and a value is a number of sides
dice_index = 1
while dice_index < dice_qty + 1:
     roll = random.randint(1, dices[dice_index])
     print(' Your  {} dice ( {}  sides ) has rolled {} !'.format(dice_index, dices[dice_index], roll))# printing out results
     dice_index += 1
```

#### JAVA-SCRIPT
##### CODEWARS 16 + 18 = 214

```
function add(num1, num2) {
  num1 = intToArray(num1).reverse();
  num2 = intToArray(num2).reverse();
  
  let maxLength = Math.max(num1.length, num2.length);
  let sum = [];
  
  for(let i = maxLength - 1; i >= 0 ; i--){
    sum.push(Number(num1[i] || 0) + Number(num2[i] || 0));
  }
  
  function intToArray(num){
  return num = String(num).split('');
  }
  return sum.reduce((acc, ell) => Number(String(acc) + String(ell)));
}
```
*****

### **WORK EXPERIENCE** 

**SIMPLE BATTLE SIMULATOR**

[Code on the github](https://github.com/Retterhalm/Simple_Battle_Simulator)

**PLANTS**

[Code on the RS App](https://rolling-scopes-school.github.io/retterhalm-JSFEPRESCHOOL2022Q4/plants/)

**MOMENTUM**

[Code on the RS App](https://rolling-scopes-school.github.io/retterhalm-JSFEPRESCHOOL2022Q4/momentum/)

*****

### **EDUCATION**

- [RS School JS/Front-end Pre school](https://rs.school/js-stage0/)

- My profile at [SoloLearn](https://www.sololearn.com/Profile/3666766#)

- My profile at [Stepik.org](https://stepik.org/users/48925680)

- My profile at [freecodecamp.org](https://www.freecodecamp.org/retterhalm)

- [https://www.edx.org/course/introduction-computer-science-harvardx-cs50x](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)

*****

### **LANGUAGES**

- English (C2) [EF Certificate](https://www.efset.org/cert/jwsXxK)
- Polish (B1)
- Serbian (A2 - B1)
- Spanish (Basic level)