# Currency converter
## Michał Kowalczyk

This is my version of currency converter, which you can use to calculate from euro to PLN, using the most recent exchange rate.

Here is the js code for my currency converter website:

```
{
    const calculateValue = (event) => {
        event.preventDefault();

        const amount = document.querySelector(".js-A");
        const exchangeRate = document.querySelector(".js-eR");
        const value = amount.value * exchangeRate.value;
        const finalValue = document.querySelector(".js-finalValue");
        finalValue.innerText = value;
    };

    {
        const money = document.querySelector(".js-currency")
        money.addEventListener("submit", calculateValue)
    }
}
```
Link for my website: https://hirazuku.github.io/currency-converter/