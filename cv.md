# Umar Rustamov
_My Discord nickname: Umar (@Umar2505)_

### About me:

Hello my name is Umar and I'm from Uzbekistan. I'm 16 years old.I study at school at 10th grade.I like to learn programming and go in for sports. I started to study HTML/CSS from 14 years from internet.But I'm still not so sure of my knowledge. So I restart to study HTML/CSS/JS in RS-SCHOOL.I will try to finish my studies at RS School. Thank you for your attention.

## My Skills at programming

As I said at the age of 14, I studied HTML and CSS, but in the last year I have spent more time learning Golang. I looked through all the resources available to me on the Internet about Golang and now I train my skills on the Codewars website, solving tasks for 7-8kyu. Below I will present examples of my work.

__7kyu Task(Shortest Word):__
```golang
package kata

import (
  "strings"
)

func FindShort(s string) int {
  res := strings.Split(s, " ")
  result := res[0]
  for _, str := range res {
    if len(str) < len(result) {
      result = str
    }
  }
  return len(result)
}
```

__8kyu Task(Convert boolean values to strings 'Yes' or 'No'.):__
```golang
package kata

func BoolToWord(word bool) string {
  if word {
    return "Yes"
  }
  return "No"
}
```