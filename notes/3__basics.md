# BASICS

```yaml
person:
  name: "Randy"
  occupation: 'programmer'
  age: 37
  gpa: 3.8
  fav_num: 1e+10
  male: true
  birthday: 1983-02-26T05:36:58+0000  # ISO-8601
  flaws: null

  # array
  hobbies:
    - videogames
    - movies
    - lego building
  movies: ["The Matrix", "There's Something About Mary"]

  # map
  friends:
    - name: "Marshall"
    - age: 47
    - {name: "Adam", age: 38}
    -
      name: "Jane"
      age: 30

  # rendered as single long line
  description: >
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
    Mauris vel luctus orci. Proin in fermentum lectus. 
    Morbi molestie finibus ultrices. In vel dapibus metus, 
    vel molestie est. Fusce ac est vel ipsum luctus accumsan.

  # rendered with formatting preserved
  signature: |
    Randy
    iOS, Swift, React Native, JavaScript
    email - randy.hsiao@myemailhost.com
```
