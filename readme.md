# Pronostieken

## Hoe gebruik je de WebApp?
###### Op mijn website kunnen mensen die geïnteresseerd zijn in voetbal pronsotieken doen. Dit gaat wel alleen op de matchen van Play-off1. Je kan 3 Verschillende waarden meegeven zoals O(verwinning), G(elijk), V(erlies).

### Build-up
- Composer geinstalleerd (vereiste), voer dan `composer install` uit.
- Je moet je database aanmaken via `php artisan migrate:refresh --seed`.
- Dan moet je een nieuwe `.env` file met de correcte gegevens met behulp van de `.env.example`.
- Start de WebApp dan met het commando `php artisan serve`.

### Waar het allemaal is misgelopen!
Ik heb de standaard lay-out van Laravel behouden en de bedoeling was dat je 1 user kon aanmaken met 1mail adres. Het probleem was dat ik geen verbinding kon maken met mijn database en zo geen gegevens kon verzenden. Ik vindt dit wel jammer want ik had zeker een eindresultaat willen publiceren.
