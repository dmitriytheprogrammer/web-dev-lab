# Задание по BEM

## Задание 1

```
голова__ухо
голова__нос--сломанный
голова__глаз-голубой
голова__глаз--карий


туловище__правая-рука--короткий
туловище__левая-рука
туловище__левая-нога
туловище__правая-нога


кисть__большой-палец
кисть__указательный-палец
кисть__средний-палец--сломанный
кисть__безымянный-палец
кисть__мизинец
```


## Задание 2
### Header

`
section.header>div.header__wrapper>(a.header__logo.logo>img.logo__img)+nav.header__navigation>ul.navigation__list>li.navigation__item*5>a.navigation__link
`
![header](/img/header.png)


### Cards

`
div.cards-wrapper>ul.cards__list>li.cards__item*3>img.cards__image+a.cards__link*2
`

![header](/img/cards.png)


### Form

`
(h2.leadform__heading+p.leadform__text+form.leadform__form>label.leadform__label*5>span.visually-hidden+input.leadform__input)+button.leadform__button
`

![form](/img/form.png)


### Prices

`
div.prices-wrapper>(img.prices__product+h3.prices__name+p.prices__price)*6
`

![prices](/img/prices.png)
