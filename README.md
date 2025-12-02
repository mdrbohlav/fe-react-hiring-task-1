# Frontend Vývojář - Praktický Úkol 1

## Popis úkolu

Vytvořte registrační formulář s validací a responsivním layoutem. Jedná se o čistě frontendový úkol - data z formuláře stačí vypsat do konzole prohlížeče.

## Požadavky

### Funkční požadavky

Formulář musí obsahovat následující pole:

- **Email** (povinné)
  - Validace
  
- **Jméno** (nepovinné)
  
- **Příjmení** (nepovinné)
  
- **Heslo** (povinné)
  - Minimální délka 8 znaků
  
- **Checkbox pro souhlas s podmínkami** (povinné)

### Layout a responzivita

- **Desktop (≥768px)**: Dvousloupcový layout
- **Mobile (<768px)**: Jednosloupcový layout
- Každé input pole musí mít přiřazený popisek
- Design může být minimalistický (rozumně žádný) - prioritou je funkčnost a čistý kód

### Validace

- Všechna povinná pole musí být vyplněna před odesláním
- Validace se spustí při pokusu o odeslání formuláře
- Chybové zprávy se zobrazí u příslušných polí
- Formulář lze odeslat pouze pokud jsou všechna pole validní

### Odeslání formuláře

Po úspěšné validaci vypište do konzole prohlížeče objekt s těmito daty:

```json
{
  "email": "priklad@email.cz",
  "name": "Jan",
  "surname": "Novák",
  "password": "TajneHeslo123",
  "termsAccepted": true
}
```

**Poznámka**: Heslo samozřejmě v reálné aplikaci nikdy neposílejte v plain textu - tento úkol slouží pouze k demonstraci frontendu.

## Technické požadavky

- Protože používáme React, je na něm tato šablona založena, ale není třeba používat jakoukoliv jeho funkcionalitu.
- Lze využít v projektu jsou nainstalováné knihovny TailwindCSS verze 3, ESLint a prettier.
- Kód by měl být čistý, čitelný a dobře strukturovaný, komentáře jsou povoleny.

## Hodnotící kritéria

Budeme hodnotit:

1. **Funkčnost** - Splňuje formulář všechny požadavky?
2. **Kvalita kódu** - Je kód čitelný a rozumně strukturovaný?
3. **Responsivita** - Funguje layout správně na různých velikostech obrazovky?
4. **Validace** - Je validace správně implementována a uživatelsky přívětivá?
5. **Přístupnost** - Je formulář přístupný pro všechny uživatele?

## Časový odhad

Předpokládaná doba na vypracování: **1 hodina**

Pokud nestíháte, lze buď popsat v komentáři, jak byste pokračovali, nebo se doptáme, nemusíte dokončit vše na 100 %.

## Bonus body (nepovinné)

- TypeScript

---

Hodně štěstí! 🚀
