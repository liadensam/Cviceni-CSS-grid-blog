# Cvičení: CSS grid blog

Za úkol máš nakódovat design podle grafického návrhu. Jedná se o stránku s článkem na blogu o zdravém jídle. Na výsledný vzhled projektu v plné velikosti se podívej na obrázku [zadani/ukazka-vysledku.png](zadani/ukazka-vysledku.png).

Hlavní pointa tohoto úkolu je ukázat, jak jde (relativně) komplexní design nakódovat pomocí CSS gridu s naprostým minimem kódu. Více v sekci [Cíl úkolu](#Cíl-úkolu).

![Ukázka výsledku](zadani/ukazka-vysledku-zmensena.png)

## Cíl úkolu

Cílem projektu je procvičit si použití různých technik:

- **CSS grid**
  - tento úkol má ukázat, jak díky CSS gridu můžeme nakódovat celou stránku s naprostým minimem kódu, protože se můžeme spolehnout na to, jak grid automaticky rozmisťuje prvky do mřížky, i když mu poskytneme jen minimum nezbytných informací
  - stačí totiž, když jednotlivým prvkům (odstavcům, nadpisům, citátům, obrázkům, apod.) **nastavíš, ve kterém sloupci (na které linii) mají v mřížce začínat a končit**. Nemusíš se starat o řádky. Grid bude prvky umisťovat postupně a bude si potřebné řádky přidávat sám.
  - není potřeba do HTML nic přidávat - tentokrát zkus prostě stylovat přímo HTML značky (odstavcem, nadpisy, obrázky). Jen několik prvků, které to nezbytně potřebují, mají přidanou CSS třídu.
- **Responzivní webdesign**
  - v tomto úkolu jde především o ukázání možností gridu, takže když stránku nakóduješ jen v počítačové verzi podle grafického zadání, tak to úplně stačí
  - máš-li čas a chceš trénovat, zkus vymyslet, jak by mohla vypadat mobilní a tabletová verze tohoto zadání a nakóduj je

## Grafické zadání

Vše potřebné (rozměry, použitá písma, apod.) najdeš na obrázku _zadani/zadani-ukolu.png_. Použité barvy máš připravené v CSS souboru _style.css_.

![zadání úkolu](zadani/zadani-ukolu.png)
