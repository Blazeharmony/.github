# Společná pravidla spolupráce BLAZE HARMONY

Veřejná dohoda a vzory pro lidi a agenty pracující v repozitářích organizace Blazeharmony. Tento repozitář obsahuje pouze obecná pravidla; interní projektová evidence zůstává v příslušných neveřejných systémech.

## Co kde najít

- [CONTRIBUTING.md](CONTRIBUTING.md): dohoda pro zadání, odpovědnost za projekty, přístupy, práci s firemními daty a předání změny.
- [AGENTS.template.md](AGENTS.template.md): jediný zdroj společného agentního jádra v1.1.0 a vzor projektového doplnění.
- [pull_request_template.md](pull_request_template.md): výchozí popis PR „Pro člověka / Pro agenta“.
- [AGENTS.md](AGENTS.md): pokyny pro úpravy tohoto repozitáře.

Správce pro přijetí společných pravidel a merge je Martin Čarek nebo jím výslovně určený lidský správce. Jednotlivé projekty mohou mít vlastního určeného člověka pro merge. Agenti nikdy nemergují.

## Zavedení do projektu

1. Před změnou ověř místní pravidla, odpovědného správce a otevřené PR. Zachovej projektové požadavky a nepřebírej osobní preference jednotlivce jako týmovou dohodu.
2. Schválený společný blok ze vzoru převezmi do kořenového AGENTS.md projektu. Mimo označený blok uveď permalink vzoru v konkrétním commitu přijatém na výchozí větvi tohoto firemního repozitáře.
3. Doplň skutečný účel projektu, odpovědného správce a člověka pro merge, příkazy pro instalaci a ověření, důležité podklady a dohodnutý backlog. Neponechávej prázdná vzorová pole a nezaváděj nástroje, které projekt nepotřebuje.
4. Existující místní CONTRIBUTING a PR šablonu slaď podle potřeb projektu přes jeho vlastní PR. Samotné založení tohoto repozitáře tyto soubory nepřepisuje.
5. Ověř načtení AGENTS.md v používaném nástroji a chování na malé autorizované úloze. Další instrukční formáty přidávej až při doložené potřebě.

GitHub používá výchozí CONTRIBUTING a PR šablonu z veřejného repozitáře .github tam, kde cílový repozitář nemá vlastní odpovídající soubor. Tyto soubory se nekopírují do checkoutu. AGENTS.md se tímto mechanismem automaticky nedistribuuje; musí být součástí konkrétního projektu. Při práci přes API či CLI načti šablonu a vyplň popis PR výslovně. [Dokumentace GitHubu](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Aktualizace a přijetí

Změna společného bloku zvyšuje jeho verzi a prochází PR s důvodem a dopadem. Po lidském merge se aktualizace aktivních projektů připravují přes jejich vlastní PR; přenáší se společný blok a zachovává projektová část. Kopie se samostatně neupravují. Nová agentní verze se neaktivuje vzdáleným načtením bez přijetí v projektu.

Projektový draft lze připravit souběžně. Před jeho přijetím nejprve člověk merguje zdrojový PR; potom aktualizuj permalink na skutečný commit na výchozí větvi a znovu porovnej bloky. Pracovní commit návrhu není schváleným zdrojem.

Dokumenty v otevřeném PR jsou návrhem. Přijetím PR do výchozí větve člověk schvaluje uvedený rozsah společných pravidel; provozní zásahy a změny oprávnění vyžadují samostatnou konkrétní autorizaci. Textová pravidla nenahrazují nastavení GitHubu a sama nezapínají 2FA, ochrany větví, CI ani placený tarif.

## Původ

Výchozím podkladem je [olomouckyorel/.github v přijatém commitu 64f9767cff0891702b221e159c45719e71989eba](https://github.com/olomouckyorel/.github/tree/64f9767cff0891702b221e159c45719e71989eba). Společné agentní jádro v1.1.0 je převzato beze změny; lidská dohoda a úvod jsou přizpůsobeny firemní spolupráci. Další změny tohoto firemního zdroje se přijímají samostatně a změny osobního vzoru je automaticky nepřepisují.
