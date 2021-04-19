# Calcolo della media con Promise.all

Per calcolare la media è necessario disporre di tutti i dati. Con una "map" viene costruito un array di Promise che vengono avviate concorrentemente. Al termine, una "reduce" sui risultati ottenuti restituisce la loro media. Attenzione: la API key nel codice non è valida. Accedere al servizio https://openweathermap.org/ e registrarsi per ottenerne una gratuitamente.

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/js-sswall)