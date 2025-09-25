# PVA4 - Programování a vývoj aplikací
## Cvičení 02: Výstup v PHP a kombinace s HTML

## Obsah

1. Přejmenuj vstupní stránku `cover.html` na `index.php`, aby se automaticky načetl po otevření `http://localhost/PVA4/PHP_02_VystupHtml/`.
2. Nahraď statický text PHP výstupem - Upravte hlavičku webové stránky, aby se všechny všechny řádky bloku <head> generovaly příkazem `echo` a nebo `print` (všechny textové uzly v hlavičce vyrábí PHP)
3. Do tagu nadpisu 1 vložte php kód, který vypíše na stránku text `Hello World!` a vyzkoušejte výstup.
4. Vytvořte druhou stránku ***O mě*** - kopii webové stránky a uložte ji pod názvem aboutme.php V tomto souboru prozatím nepracujte. 
5. Deklarujte proměnou `authorName`. Hodnota proměnné bude Vaše jméno.
6. Upravte meta tag `Author` tak, aby obsah vycházel z `authorName`
7. V navigaci změň text odkazu About Me na About <tvoje_jméno> pomocí deklarované proměnné.
8. Ve souboru aboutme.php upravte nadpis H1 na hodnotu hodnotu `About authorName`. 
9. Upravte odkazy menu obou souborů tak, aby fungovaly obousměrně.
10. Do aboutme.php přidej proměnné age, city, hobbies a vypiš je pěkně formátované v `<section>`.
11. Definuj `define("APP_VERSION", "1.0")` a zobraz verzi webu v patičce.
