# Mugu Anna
### Junior Frontend Developer

# Contact Info:

* **E-mail:** [anika.22@mail.ru](anika.22@mail.ru)
* **GitHub:** [doublexkid](https://github.com/doublexkid)


# About Me
I am 25 years old, I work as a support engineer. I would like to change my career path because I'm passionate about web dev. it offers a ton of room for creativity. I also love the technical aspect, the fact that there is always something new to learn, and the ability to quickly share new projects. Oh, and knowing how the web works in a world that increasingly relies on it is pretty exciting.

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code, 
- Adobe Photoshop, Figma

# Code Example:

```javascript
function getLengthOfMissingArray(arrayOfArrays) {
  arrayOfArrays = (arrayOfArrays) ? arrayOfArrays.map(a=> a ? a.length : 0) : [0];
    let maxSize =  Math.max(...arrayOfArrays), minSize = Math.min(...arrayOfArrays);
    if(minSize === 0) { return 0; }
    for(let i = minSize; i < maxSize; i++) {
        if(arrayOfArrays.indexOf(i) === -1) {
            return i;
        }
    }
    return 0;
}

```


