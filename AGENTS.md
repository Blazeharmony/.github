# Práce se společnými pravidly

- Pro práci v tomto repozitáři načti společný blok v [AGENTS.template.md](AGENTS.template.md), [CONTRIBUTING.md](CONTRIBUTING.md) a postup v [README.md](README.md). Projektová pole šablony jsou vzor, ne instrukce k jinému projektu.
- Správce pro přijetí pravidel a merge je Martin Čarek nebo jím výslovně určený lidský správce. Agent PR nikdy nemerguje.
- Repo je veřejné: patří sem pouze obecná pravidla a šablony. Neukládej sem interní seznamy projektů či účtů, skutečná nastavení přístupů, citlivá data ani provozní evidenci.
- Zdroj společného agentního bloku je AGENTS.template.md. Při změně jeho obsahu zvyš verzi; označený blok nekopíruj jako druhý zdroj do dalších dokumentů. Projektové doplnění se mění mimo společný blok.
- Před předáním zkontroluj diff, relativní odkazy, shodu převzatého bloku s připnutým zdrojem a `git diff --check`. Tento dokumentační repozitář nemá testovací aplikaci ani zavedené povinné CI.
- Změna pravidel sama neautorizuje zápis do ostatních projektů, produkční zásah, změnu přístupů nebo placený běh. Aktualizace projektu se přijímá samostatným PR podle README.
