# DigiWtal Frontend

Eigenstaendiges Frontend fuer DigiWtal. Es startet als technische Kopie des
bisherigen Sport-Voice-Frontends und kann ab jetzt unabhaengig weiterentwickelt
werden. Inhalte, Navigation, Medien und Einstellungen kommen aus der ueber
`CMS_API_URL` zugeordneten CMS-Instanz.

## Lokal starten

1. `.env.example` nach `.env` kopieren und `CMS_API_URL` setzen.
2. `php -S localhost:8002 index.php` starten.

`.env`, Cache, Logs, Schluessel und sonstige Laufzeitdaten bleiben lokal.
