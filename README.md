# Thanks for viewing my Project ✨

![ a main page screenshot](./images/screen2.png)
<br />

## :star: Live Deployment: (https://katarzynadworak.github.io/online-shop/)
<br />

## Main goal of my work was to:
- code **Responsive Web Design (RWD)** site 📱
- do it in a way that it **looks decent on mobiles, tablets and desktops** 🖥️
- use **semantic HTML** (BEM) 📝
- make project **as readable as it is possible** (clean code, many directories, BEM) 📖
<br />

## Solutions provided in the project
**1.** I used in this project modern CSS functions like **min(), max(), and clamp()** to create a responsive and adaptive design. These functions help ensure that the layout and elements adjust smoothly across different screen sizes and resolutions.

- Responsiveness: Elements adjust dynamically to the screen size, providing a consistent and user-friendly experience across different devices.
- Maintainability: Using these functions even reduces the need for numerous media queries, simplifying the CSS code.
- Design Consistency: Ensures a consistent look and feel, regardless of the screen size, by setting appropriate limits on property values.
- This approach leverages the power of modern CSS to create a more efficient, scalable, and maintainable codebase.

Key Features:

**Clamp() Function:** ensures the margin values are responsive and stay within the defined minimum and maximum limits, adapting to different screen sizes.

    .header__logo {
    margin: clamp(15px, 2vw, 30px) 12px 12px clamp(10px, 2vw, 25px);
    padding: 2px;
    }

**Min() Function:** sets the font size to be responsive, choosing the smaller value between 4% of the viewport width and 15px, ensuring readability across devices.

    .nav__item {
        margin: 11px;
        font-size: min(4vw, 15px);
        position: relative;
        transition: font-weight 0.3s ease, letter-spacing 0.3s ease, transform 0.3s ease;
    }

**Max() Function:** ensures that the margin is at least 10px, but can grow to 2% of the viewport width, providing a flexible and responsive layout for different screen sizes.

    .benefits__img-1, .benefits__img-2, .benefits__img-3 {
        width: 115px;
        height: 115px;
        border-radius: 19px;
        margin: max(10px, 2vw) auto;
        padding: 33px;
    }

**2.** I used CSS code to provide a clean and **functional hamburger menu** that is hidden off-screen by default and smoothly slides into view when the associated checkbox is checked, providing an intuitive and responsive navigation experience for mobile users.

    .nav__menu {
        background-color: #2c2c2c;
        border-radius: 0 0 20px 20px;
        border-bottom: 2px solid #37ebed;
        display: block;
        padding: 20px;
        position: absolute;
        right: 0;
        text-align: center;
        transform: translateX(150%);
        transition: .4s linear;
        top: 100%;
        width: 100%;
        z-index: 1;
    }
      
    .header__input:checked ~ .nav__menu {
        display: block;
        transform: translateX(0%);
    }
      
    .header__hamburger {
        background-color: #f2f4f4;
        cursor: pointer;
        height: 3px;
        position: relative;
        width: 30px;
    }
      
    .header__hamburger::after {
        content: '';
        background-color: #f2f4f4;
        height: 3px;
        position: absolute;
        transform: translateY(-10px);
        width: 30px;
    }
      
    .header__hamburger::before {
        content: '';
        background-color: #f2f4f4;
        height: 3px;
        position: absolute;
        transform: translateY(10px);
        width: 30px;
    }
   
**3.** I also used **Grid** to provide flexibility to footer elements – they can be stretched in one row as well as arranged in two or one column.

<br />
<br />

## 🛠️ Languages and Tools used: 


<img align="left" alt="HTML5" width="50px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />

<img align="left" alt="CSS3" width="50px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />

<img align="left" alt="Git" width="50px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />

<img align="left" alt="GitHub" width="50px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />

<img align="left" alt="Terminal" width="50px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />

<img align="left" alt="Visual Studio Code" width="50px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />

<br />
<br />
<br />
<br />

## :blue_heart:  You can find me on:
<br/>

[<img align="left" alt="Mateusz Sowa LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />](https://www.linkedin.com/in/katarzynadworakk/)

 
<br />

### Thanks
To Colorlib [colorlib.com](https://colorlib.com) for free templates.


OD DEVMENTOR:
## Opis projektu

Wszystkie niezbędne grafiki masz przygotowane w katalogu `images`. Znajdziesz tam m.in. [pliki SVG](https://pl.wikipedia.org/wiki/Scalable_Vector_Graphics). W VS Code ich podgląd uzyskasz dzięki rozszerzeniu [SVG](https://marketplace.visualstudio.com/items?itemName=jock.svg).

Font, który jest używany w projekcie, to [Montserrat](https://fonts.google.com/specimen/Montserrat).

Tło w górnej części strony to gradient: 
`background: radial-gradient(rgb(194, 74, 126), rgb(105, 86, 235));`

Jeśli chcesz dokładnie odwzorować położenie poszczególnych elementów, możesz użyć rozszerzenia do Chrome o nazwie [PerfectPixel](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi). Pozwoli Ci ono osadzić przedstawiony wyżej plik poglądowy (lokalizacja: `./assets/demo.png`) jako tło dla tworzonej strony.

> **Uwaga!** Możliwe, że w powyższym rozszerzeniu będziesz musiał użyć odpowiedniej skali obrazu wykorzystywanego jako podgląd. Jest to zależne od [ustawień systemowych](https://pliki.wiki/blog/jak-korzystac-ze-skalowania-ekranu-w-systemie-windows-10/). Zazwyczaj jednak domyślne ustawienia wtyczki dobrze się sprawdzają i poza jej instalacją nie musisz nic robić.

Strona nie musi być wykonana zgodnie z pierwowzorem 1:1. Ważne, aby na pierwszy rzut oka było widać, że jest to ten sam projekt. 

Pamiętaj, że przedstawiona grafika to element statyczny, a strona internetowa to element dynamiczny, który powinien dobrze wyglądać w różnych rozdzielczościach / na różnej wielkości monitorach. Część z nich może mieć szerokość ekranu 1280px, a inna 1440px itp. Na razie jednak skup się na odwzorowaniu zamieszczonego w zadaniu widoku. Innymi rozdzielczościami zajmiemy się w kolejnym module.

## Propozycja podziału

Poniżej zamieszczam propozycję podziału strony na poszczególne grupy:

- wiersz (`width: 100%`) – kolor zielony
- wyśrodkowanie (`max-width: 1150px`) – kolor niebieski
- komórka (wiele elementów w jednej linii) – kolor pomarańczowy.

Nie musisz się od tego stosować – to jedynie moja koncepcja, która ma Ci pomóc w utworzeniu odpowiedniej struktury.

![](./assets/demo-info.png)

&nbsp;

> :warning: Jeśli nie posiadasz materiałów do tego zadania, to znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/p/html-and-css-basics/).


&nbsp;

> ⭐ ***README** to coś więcej niż opis. Poprzez nie **pokazujesz swoje mocne strony** – swoją dokładność, sposób myślenia i podejście do rozwiązywania problemów. Niech Twoje README pokaże, że masz **świetne predyspozycje do rozwoju!***
> 
> 🎁 *Zacznij od razu. Skorzystaj z **[szablonu README i wskazówek](https://github.com/devmentor-pl/readme-template)**.* 
