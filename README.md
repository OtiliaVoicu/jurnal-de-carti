# Jurnal de cărți

1. Descriere: Aplicație web pentru adăugarea și afișarea recenziilor de cărți.
2. Tehnologii: HTML, CSS și JavaScript.
3. URL API: `https://jsonplaceholder.typicode.com/posts`
4. GET: Preia lista de înregistrări de la endpoint-ul `/posts`.
5. POST: Trimite datele formularului în format JSON, folosind `Content-Type: application/json`.
6. CORS: Folosesc API-ul JSONPlaceholder, care permite cereri cross-origin; nu am configurat un proxy propriu.
7. Status 200: Cererea GET a reușit; afișez lista primită.
8. Status 201: Cererea POST a reușit; afișez un mesaj de confirmare și actualizez lista din interfață.
9. Status 4xx/5xx sau eroare de rețea: Afișez un mesaj de eroare utilizatorului.
10. Observație: JSONPlaceholder este un API demonstrativ; datele trimise prin POST nu sunt salvate permanent.# jurnal-de-carti
