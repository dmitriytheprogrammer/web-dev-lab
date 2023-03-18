# Задание по BEM

## Задание 1

```
голова
голова__ухо
голова__нос--сломанный
голова__глаз-голубой
голова__глаз--карий

туловище
туловище__правая-рука--короткий
туловище__левая-рука
туловище__левая-нога
туловище__правая-нога

кисть
кисть__большой-палец
кисть__указательный-палец
кисть__средний-палец--сломанный
кисть__безымянный-палец
кисть__мизинец
```


## Задание 2
### Header

`
section.header>(a.header__logo.logo>img.logo__img)+nav.header__navigation.navigation>ul.navigation__list>li.navigation__item*5>a.navigation__link
`
![header](/img/header.png)


### Cards

`
div.cards>(div.card>img.card__image+a.cards__link+a.cards__link--small)*3
`

![header](/img/cards.png)


### Form

`
div.leadform>h2.leadform__heading+p.leadform__text+(form.form-area>label.form-area__label*5>span.visually-hidden+input.form-area__input)+button.leadform__button
`

![form](/img/form.png)


### Prices

`
div.prices.price>(div.price>img.price__product+h3.price__name+p.price__price)*6
`

![prices](/img/prices.png)
