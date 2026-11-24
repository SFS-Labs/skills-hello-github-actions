# Hello GitHub Actions — Notizen

Der Workflow `.github/workflows/welcome.yml` begrüßt neue Pull Requests mit einem
Kommentar. Ausgelöst wird er durch das Ereignis `pull_request` vom Typ `opened`.

Dieser Branch existiert, um den Pull-Request-Schritt der Übung erneut und in der
richtigen Reihenfolge auszulösen: Der Schritt-Workflow war beim ersten PR noch
deaktiviert, sodass das Ereignis verpuffte.
