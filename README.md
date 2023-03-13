# Yatsuu Profile
## 🚀 About Me
I am a developer with a passion for creating software and applications that improve people's lives. I have gained my development skills through years of professional experience, as well as through self-study and continuing education.

I am particularly proficient in web development technologies such as HTML, CSS, JavaScript, and popular frameworks such as React and Angular. I also have significant experience in backend development with languages such as Java, Python, and Node.js.

I am motivated by the opportunity to tackle complex technical challenges and solve practical problems for my clients and users. I believe that software development should be user-centered and I strive to create exceptional user experiences for all products I develop.

Outside of work, I enjoy exploring new technologies and participating in open-source projects. I am also a music lover and enjoy playing guitar in my free time.

I am always looking for new challenges and development opportunities. Don't hesitate to contact me if you are looking for a competent and passionate developer for your team or project.
## 🛠 Skills
I have advanced skills in several programming languages such as Python, Java and C++, as well as web technologies such as HTML, CSS, JavaScript and popular frameworks such as React and Angular.

I am also well versed in database development and data management, having worked with tools such as SQL, MongoDB and Firebase. I have a solid understanding of database design and data modeling principles, and am able to create efficient and effective data management systems.

I am also skilled in project management and collaboration. I have worked closely with teams of developers, designers, project managers, and clients to complete large-scale, complex software development projects.

I have the necessary problem solving skills and I have a great ability to understand the needs of users and customers.
## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express


## Additional informations
👩‍💻 I'm currently working a profesionnal portfolio.

🧠 I'm currently learning the language Assembler.

💬 Ask me about all areas related to computer technology....

📫 How to reach me : Mail" section on my website.

😄 Pronouns : He.


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://yatsuu.fr/)


## Example : Sprite Animation

```javascript
class Sprite {
  
    constructor(image, frames){
      const width = image.width, height = image.height
    
      let canvas = document.createElement("canvas")
      canvas.width = width
      canvas.height = height
      
      let context = canvas.getContext("2d")
      context.drawImage(image, 0, 0)
      
      this.canvas = canvas
      this.context = context
      this.frames = frames
    }
    
    drawFrame(ctx, frame, dx, dy, targetWidth, targetHeight){    
      const { x, y, width, height } = this.frames[frame]
      
      dx |= 0
      dy |= 0
      targetWidth |= width
      targetHeight |= height
      
      ctx.drawImage(this.canvas, x, y, width, height, dx, dy, targetWidth, targetHeight)
    } 
  }
  
  
  Sprite.GeometryHorizontalLinear = (width, height, count) => {
    let frames = [];
    
    for (var idx = 0; idx < count; idx += 1) {
      var frame = { x: (width * idx), y: 0, width: width, height: height }
      frames.push(frame)
    }
    
    return frames
  }
  
  export default Sprite
```


## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/Licenses/agpl-3.0)

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@Yatsuu](https://www.github.com/yatsuuw)


![Logo](https://i.pinimg.com/236x/7c/6e/23/7c6e23b51b5bfcc06c85451a00c86c02.jpg)

