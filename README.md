# Můj deník (PWA)

Osobní deník pro Android, iOS a Windows.

## Funkce
- Kalendář s týdnem od pondělí do neděle.
- Více událostí za den a kategorie.
- Diktování češtiny do textu, který lze před uložením upravit.
- PIN a šifrování zápisů pomocí Web Crypto (PBKDF2 + AES-GCM).
- Export a import šifrované zálohy JSON.
- Základní offline podpora.

## Spuštění přes GitHub Pages
V repozitáři otevři Settings → Pages, zvol nasazení z větve main a složky /(root). Po zveřejnění otevři adresu Pages a v prohlížeči zvol instalaci nebo přidání na plochu.

## Omezení první verze
- Zápisy se ukládají lokálně v daném prohlížeči/zařízení a jsou šifrované PINem.
- Synchronizace mezi zařízeními zatím není implementována. Pro přenos použij šifrovanou JSON zálohu.
- Odemknutí otiskem prstu zatím není implementováno.
- Diktování závisí na podpoře prohlížeče a oprávnění mikrofonu; rozpoznávání řeči může využívat službu prohlížeče.
- Zapomenutý PIN nelze obejít. Uchovávej bezpečně zálohu.

## Soukromí
Aplikace neposílá zápisy na server. Je-li repozitář veřejný, veřejné jsou soubory aplikace, nikoli místní zápisy. Nevkládej osobní zápisy ani PIN do GitHubu.
