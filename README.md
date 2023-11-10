# Virtual CV
## mgr inż. Michał Kowalczyk

*Kto pracował w budowlance, ten w cyrku się nie śmieje ;)*

**I completed the YouCode - Frontend developer from scratch programming course**

- Java Script
- Html
- CSS
- Git Hub
- Markdown

![mgr inż](https://i.postimg.cc/4s2qJW9s/mgr.jpg)

Here is some of the js code for my Virtual-CV website:

```
{
    const calculatePrice = () => {
        const price = document.querySelector(".js-price")
        price.addEventListener("submit", (event) => {
            event.preventDefault();

            const powUz = document.querySelector(".js-PU");
            const cenaOdMetra = 250;
            const cena = cenaOdMetra * powUz.value;
            const finalPrice = document.querySelector(".js-finalPrice");
            finalPrice.innerText = cena;
        });
    }

    calculatePrice ();
}
```
Link do strony: https://hirazuku.github.io/My-virtual-CV/