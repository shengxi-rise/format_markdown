**one**
===
  * one
  * two
  * three

# one
## two
### three
#### four
##### five
###### six


two
===
hello **one** word

[two](#mermaid)

_one_

```c++
#include <iostream>
using namespace std;
int main(){
    cout << "hello Markdown" << endl;
    return 0;
}
```

The url
---

The url
===
**[two](#two)**
>* this is the two tile
>* hello world
>* hi world

> Hello Markdown

<div align=center><img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.jj20.com%2Fup%2Fallimg%2Ftp09%2F210F2130512J47-0-lp.jpg&refer=http%3A%2F%2Fimg.jj20.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1661785454&t=d8d1eeb7d0eebca198009c977ac817a4"/> </div>

---
| one | two | three |
|:---:|:---:| :---: |
|nihao|hello|   hi  |

- [x] one
- [ ] `two`
- [x] three



Mermaid
===
* PIE
  ```mermaid
  pie
  title Learning_plan
  "English": 30
  "Mathes":30
  "Programming":40
  ```
---
* graph
  ```mermaid
  graph TB
  A(OPEN)--YES---B[ON]
  A(OPEN)--NO---C{OFF}
  B(ON)---D(END)
  C(OFF)-->D(END)
  ```
---
* ClassDiagram
  ```mermaid
  classDiagram
  Animal <|-- fish
  Animal <|-- cat
  Animal <|-- pig
  Animal <|-- mokey
  Animal : +one
  Animal : two()
  class fish{
    one
    two()
    three
  }
  class cat{
    +one
    -two
    +three()
  }
  class pig{
    null
  }
  class mokey{
    nothing()
  }
  ```
---
* mermaid
  ```mermaid
  gantt
  dateFormat DD
  title work_project

  section First
  one:done,do1,01,04
  two:done,do2,07,10
  three:active,do3,after do2,5d

  section Second
  four:active,do4,after do1,3d
  five:done,do5,09,18

  section Third
  six:crit,31
  seven:done,do6,09,14
  
  ```
<iframe src="https://jx.bozrc.com:4433/player/?url=https://www.bilibili.com/video/BV1Pg41197un?share_source=copy_web&vd_source=c08b74410ee9d09897502544e8bcec4b" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="100%" height="500px"> </iframe>
