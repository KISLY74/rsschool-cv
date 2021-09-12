# Nikita Kisly
# Contact information
* **_Phone-number:_** +375336618051
* **_E-mail:_** kisly.nikita@mail.ru
* **_GitHub:_** [KISLY74](https://github.com/KISLY74)

# About me
I am 19 years old. I am studying at university. I have the desire and ability to learn something new and I think this is the most important thing. My best 3 qualities are punctuality, responsibility and independence. Of weak qualities I am not very well-read: at school I did not like to read. But now I read different articles about programming, documentation, book about algorithms. I like to solve problems, to look for other ways to solve problems. For me, my interest has become closer to frontend development. I was and am always interested in how sites are developed, specifically the client side: what the user sees, how elements are arranged, animation using js. That's why I want to learn all the necessary skills in a company to work there. The most important thing is the desire.

# Skills
* **_Javascript(Medium)_** 
* **_HTML(above medium)_**
* **_CSS(above medium)_**
* **_SCSS,SASS_**
* **_NodeJs(Basic)_**
* **_Git(Basic)_**
* **_SQL(Medium)_**
* **_C++(Medium)_**

# Example code
```javascript
function isIsogram(str) {
    var bool
    str = str.toLowerCase()
    var str_new = []
    if (str.length === 0) {
       bool = true
    }
    for (var i in str) {
       str_new.push(str[i])
    }
      str = str.split("")
       let result = []
    for (var i of str) {
       if (!result.includes(i)) {
          result.push(i);
       }
    } str_new = str_new.join("")
    for (var i in str_new) {
       if (result[i] === str_new[i]) {
          bool = true
          console.log(result[i])
          console.log(str_new[i])
      }
       else {
          bool = false
      }
    }
    result = result.join("")
    console.log(bool)
 }
 ```

 # Experience
 
