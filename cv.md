# Denis Bondarenko

#### Junior Front-End Developer

---

## Contact info

> **Gdansk, Poland**

> Denis.Bondarenko.pl@gmail.com

> [LinkedIn](linkedin.com/in/denis-bondarenko-pl)

> [Github](https://github.com/ExIxIxS)

## Briefly About Myself

I began my career after university in the railways branch in 2011, where I took initial skills of working with technical documentation and a stack of plenty of technology. The last 2 years I have been working in an International Company as lead technical writer,  where the main point of my work was development and management technical documentation with different types of content. Also I have a DSLR-camera for my hobby - photography and essential skills of graphic editing. 
I believe that my background  and passion for learning will make me a proficient Frontend Developer.

## Skills and Proficiency

### Hard Skills

+ MS Office, Schema ST4 (CMS), XMetal Author
+ Smarteam (cPLM), AutoCAD
+ Adobe PS & LR, Corel Draw
+ HTML5, CSS3, Python3
+ VS Code, PyCharm

### Soft Skills

+ Analytical thinking
+ Detail oriented
+ Communication
+ Self-organization and responsibility
+ Creativity and flexibility
+ Blind typing

## Code examples

    import xml.etree.ElementTree as xmlET

    """
    Output three numbers separated by a space: the values of RGB.
    
    The top cube corresponding to the root of the XML document has a value of 1.
    The cubes directly below it have a value of 2.
    The cubes directly below it have a value of 3. etc.
    The value of a color is the sum of the values of all the cubes of that color. Output three numbers separated by a space: the values of Red, Green and Blue.
    """
    
        input_data = input()
        root = xmlET.fromstring(input_data)
        result = {'red': 0, 'green': 0, 'blue': 0}
    
    def diving(parent, i=1):
        color = parent.attrib['color']
        result[color] += i
        for child in parent:
            diving(child, i+1)
    
    diving(root)
    print(*result.values())

## Education

Belarusian State University of Transport, Belarus – Bachelor of Engineering - BE, Railroad and Railway Transportation / Electrician Engineer
*__2006 – 2011__*


### Courses

- ["Поколение Python"](https://stepik.org/cert/1382667)
- ["Python: Основы и применение"](https://stepik.org/cert/1527393)
- RS School UpSkill Me (in progress)

## LANGUAGES
+ English (Professional working proficiency, CEFR B2)
+ Russian (Native)
+ Belarusian (Native)
+ Polish (Beginner)