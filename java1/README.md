# Java I – Pasaporta digjitale

## Përshkrimi

Në këtë detyrë kam krijuar një pasaportë digjitale për një personazh të sajuar me emrin Arta Orbita, e cila paraqitet si udhërrëfyese e një kampusi imagjinar.

Projekti përmban faqen kryesore `index.html`, faqen `rreth.html` dhe stilizimin me `style.css`.

## Si hapet projekti

1. Hap repository-n në Visual Studio Code.
2. Hap folderin `java1`.
3. Hap `index.html` me Live Server.
4. Përmes lidhjes "Rreth Artës" mund të hapet faqja `rreth.html`.
5. Përmes lidhjes "Kthehu te pasaporta" mund të kthehemi në `index.html`.

## Testimi

### Testi 1 – Hapja e faqes kryesore

Hyrje: Hapja e `index.html` me Live Server.

Rezultati i pritur: Faqja kryesore duhet të hapet pa gabime.

Rezultati i marrë: Faqja u hap me sukses.

### Testi 2 – Lidhja te rreth.html

Hyrje: Klikimi i lidhjes "Rreth Artës".

Rezultati i pritur: Duhet të hapet `rreth.html`.

Rezultati i marrë: `rreth.html` u hap me sukses dhe nuk u shfaq gabimi 404.

### Testi 3 – Lidhja e kthimit

Hyrje: Klikimi i lidhjes "Kthehu te pasaporta".

Rezultati i pritur: Duhet të hapet përsëri `index.html`.

Rezultati i marrë: `index.html` u hap me sukses.

## DevTools – Network

Dokumenti `index.html` u kontrollua përmes DevTools → Network.

- Request URL: http://127.0.0.1:5500/java1/index.html
- Request Method: GET
- Status Code: 304 Not Modified
