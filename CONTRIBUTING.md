# Pravidla spolupráce

GitHub uchovává stav rozpracované i dokončené práce. Konkrétní zadání určuje rozsah a schválení; konzultace ani audit samy nepovolují implementaci či publikování.

## Pravidla pro agenty

Jediným zdrojem společného agentního jádra je [AGENTS.template.md](AGENTS.template.md). Projekt je přebírá do svého AGENTS.md a doplňuje místní postupy. Jádro obsahuje hranice oprávnění, řešení konfliktů, ochranu secrets, izolaci práce a ověřování. Tato lidská dohoda je neopakuje jako druhou úplnou kopii; postup zavedení a aktualizace je v [README](README.md).

Merge provádí člověk určený pro konkrétní projekt. Agent nikdy nemerguje a textová pravidla nenahrazují technická oprávnění a ochrany větví. Autor commitu ani další token téhož účtu samy neprokazují oddělenou identitu.

## Odpovědnost, přístupy a firemní data

- Každý projekt ve svém README nebo AGENTS.md určí odpovědného správce a člověka oprávněného přijímat změny. U malého projektu může jít o tutéž osobu. Zastupování musí být výslovně určené; samotné technické oprávnění nenahrazuje dohodnutou odpovědnost.
- Přístup přiděluje pověřený lidský správce podle potřeb projektu. Založení úkolu ani povolení upravit kód neopravňuje měnit členství, role, přístupy aplikací nebo viditelnost repozitáře. Při změně spolupráce správce prověří, zda přístupy stále odpovídají potřebě.
- Do veřejných repozitářů patří pouze obsah určený ke zveřejnění. Přístupové údaje, osobní údaje, neveřejné firemní dokumenty, zákaznická data a provozní výpisy do tohoto veřejného repozitáře nepatří.
- Před předáním neveřejných firemních dat externí službě nebo AI nástroji ověř schválený nástroj, potřebný rozsah dat a autorizaci. Samotný přístup do repozitáře není souhlas s jejich předáním dalším službám. Při nejasnosti pokračuj s anonymizovaným nebo syntetickým podkladem, pokud to úkol umožňuje.
- Tato dohoda nepřiděluje oprávnění, nevynucuje 2FA ani ochranu větví a neschvaluje licence či náklady. Skutečné nastavení se ověřuje zvlášť.

## Zadání a předání

- Jeden výsledek má jednu aktivní větev/PR a jednoho vlastníka zápisu. Navazující práce pokračuje v existujícím PR; po merge začíná nový úkol z aktuální výchozí větve.
- **„Ulož to jako rozpracované.“** Commit, push a vytvoření či aktualizace Draft PR včetně popisu. Neoznačovat jako ready a nemergovat.
- **„Připrav to k začlenění.“** Dokončit dohodnutý rozsah, ověřit jej, commitnout, pushnout a připravit PR ke kontrole včetně popisu. Nemergovat. Výslovný pokyn ponechat draft platí do odvolání.
- Stav práce a důležitá diagnostická zjištění patří do existujícího PR/Issue. Skutečný backlog eviduj v dohodnutém systému; každý nápad nepotřebuje Issue.

## Popis Pull Requestu

Použij [šablonu](pull_request_template.md) i při vytvoření přes API či CLI. Platí také pro draft.

- **Pro člověka:** Dvě až čtyři věty: co se mění, proč a co má člověk zkontrolovat či rozhodnout. Tato část musí sama vysvětlit smysl změny; nepotřebuje hashe ani výpisy skriptů.
- **Pro agenta:** Cíl, hotovo, aktuální stav a vlastník zápisu, větev a ověřený commit, draft/ready, skutečně provedené kontroly, zbývající práce, další krok, rizika a potřebná rozhodnutí.

Před předáním aktualizuj obě části podle skutečného stavu. Rozliš fakta, hypotézy a neověřené části; nálezy z review rozděl na blokující a doporučení a dolož jejich dopad.

Automatické odstranění pracovní větve po merge závisí na nastavení konkrétního repozitáře; tato dohoda je sama nezapíná.
