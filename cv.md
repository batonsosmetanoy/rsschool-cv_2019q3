# CV for RSSchool
Mukhammadali Madraimov
## Contact Info
E-mail: [madraimovmsh@gmail.com](mailto:someone@example.com)
Telegram: [@nicknameForTelegram](t.me/nicknameForTelegram)
## Summary
My goal is to become a professional web developer. I want to create useful websites, making peoples life easier. Even if it is a website for cooking recipes. At least it will help them to make a **tasty** food.
## Skills
* Programming languages (basic level of knowledge):
  * JavaScript
  * HTML
  * CSS
  * C
  * Pascal
  * MatLab
* Designing:
  * Adobe Photoshop
## Latest code examples
    const areBracketsBalanced = (str) => {
    let openBrackets = 0;
    let closeBrackets = 0;
    for (let i = 0; i <= str.length - 1; i += 1) {
        openBrackets += (str[i] === '(') ? 1 : 0;
        closeBrackets += (str[i] === ')') ? 1 : 0;
        console.log(openBrackets, closeBrackets);
    }
    if (openBrackets !== closeBrackets || str[0] === ')') return false;
    return true;
    };
    console.log(areBracketsBalanced('()'));