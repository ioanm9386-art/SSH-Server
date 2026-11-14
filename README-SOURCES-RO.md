# SSH Server — surse recuperate v1.7.9

Arhiva `SSH-Server-v1.7.9-Source.zip` conține sursele complete recuperate din pachetul Windows de test v1.7.9. Extrage folderul `ssh-server` pentru a consulta și compila proiectul.

Aceasta este o publicare a surselor existente. Nu reprezintă lansarea v2.1, nu schimbă versiunea instalată și nu publică încă un catalog online App Store.

- Motorul aplicației: Go; cerințele sunt în `go.mod`.
- Interfața: directorul `web`.
- Aplicația Windows și instalatorul: directorul `desktop`; instrucțiuni în `desktop/BUILD-WINDOWS.ps1` și documentele incluse.
- Teste: fișierele Go și directoarele `tests` și `scripts`.
- Licența și notificările: `LICENSE`, `COPYING` și notificările din `desktop/assets/licenses`.

Verificare efectuată pe sursele recuperate: `go test ./...` a trecut. Nu s-a testat din nou instalatorul pe Windows și nu s-au modificat servere reale.

Funcțiile LiveCam, limitările SN/P2P și matricea producătorilor sunt descrise în `README-v1.7.9-RO.md` din arhivă. Semnarea digitală a executabilului/instalatorului nu este disponibilă în această versiune de test.

SHA-256 al arhivei: `e651bd62492b5239ae86554edc12945bc81ec3a3946b7ef41d6027b76a3887fb`.
