## Security Program Management and Oversight

1. ## **Guidelines**:
  Są to rekomendacje i najlepsze praktyki, można powiedzieć, że mało sprecyzowany poradnik, możesz z niego skorzystać ale nie musisz.
  Przykład to "Pracownicy powini być zachęcani aby skorzystać z security awarness program"
3. ## **Policies**:
  Udostępniają zbiór zasad, reguł i wytycznych, które określają, w jaki sposób organizacja chroni swoje zasoby fizyczne jak i cyfrowe, zazwyczaj w bardzo szerokim zakresie. Wyznacza ścieżkę procedurom.
  Przykład: Organizacja jest zaobowiązana do przestrzegania CIA.
  ### Podstawowe polityki:
  - #### AUP(Acceptable Use Policy): Defniuje sposób używaniu zasobów IT w firmie. Dodatkowo przedstawia, czego nie robić podczas uźywania zasobów, aby zachować bezpieczeństwo.
    Przykład: Zakaz pobieranie niezautoryzowanego oprogramowania, zakaz oglądania pornografii.
  - #### Information Security: Ustanawia reguły bezpieczeństwa informacji w firmie.
  - #### Business Continuity: Zabowiąza organizacje do utrzymania ciągłości krytycznych funkcji biznesowych pomimo zakłóceń i przeciwności.
  - #### Disaster Recovery: Skupia się na regeneracji po katastrofach.
  - #### Incident Reponse: Zbiór reguł, które pomogą zidentifikować, zizolować, usunać oraz zregenrować się po incydencie.
  - #### Software Development Life Cycle: Jest to roadmap, który zapewnia jakość, bezpieczeństwo i efektywność podczas tworzenia.
4. ## **Standards**:
  Definiuje konieczne techniczne specyfikacje i najlepsze praktyki podczas implementacji polityki bezpieczeństwa. Są bardziej szczegółowe niż polityki. Dbają o config, procesy i wymagania co do systemów. Odpowiadają na pytanie "Co?" i "Kiedy?".
  Przykład Dane Karty Kredydtowej musi podczas spoczynku, użytku i trasnferu musi być zaszyfrowana, najbardziej złożonym algorytmem na jaki firma musi sobie pozwolić.
  - #### Password Complexity and Password Management: częste zmienianie, nieużywanie tego samego hasła, trudność hasła zależna według NIST, ISO 27001, CIS.
  - #### Access Control: Defniuje kto ma mieć dostęp do systemów,zasobów i danych używająć reguły least privilege. Przykładowy Standard  ISO 27001 ISMS.
  - #### Physical Security: kamery, access badges, vestibules, sensory, ochroniarze, barykady.
  - #### Encryption Standard: szyfrowanie i przechowywanie kluczy, które służą do szyfrowania wrażliwych danych. Wraz z postępem technologicznym musi to być updatowane.
5. ## **Procedures**:
    Instrukcje krok po kroku jak wykonać specyficzne zadanie. Procedury wywodzą się z polityk, są to szczegółowe rozwiazania danych tematów. Daje to klarowność i zrozumienie działania ogólnej polityki. Polityka do przepis, procedura to instukcja.
     - #### Change Management: szczegółowe kroki takie jak propozycja, sprawdzenie, zaakceptowanie, zaimplementowanie oraz dokumetacja zmian infrastrukty i systemów. W celu zapewnianie, że zagrożenie zostało odkryte i poprawione.
     - #### Onboarding/Offboarding: Dawanie i usuwanie pracownikowi dostępu do systemów, danych i infrastruktury.
     - #### Playbooks: Krok po kroku co robić w danej sytuacji. Częstwo używane w SOC. W SOAR są ro Runbooki.
6. ## **External considerations**:
  Są to rzeczy na które trzeba zwrócić uwagę tworząć polityki, procedury i procesy w organizacji.
  - #### Regulatory: Wzdrożenie wraz z data privacy regulation jak PCI-DSSS, HIPAA, GDPR. Ma wpływ na polityki, procedury i procesy w organizacji.
  - #### Legals: Prawo dotyczące leaków danych, eletrocnic discovery, własności intelektualnej.
  - #### Industry: Best practices, polityki i procedury z twojego sektoru organizacji może dać ci dodatkowy Guideliness dla bezpieczeństwa.
  - #### Local/Reginal/National/Global: Każde z tych może mieć impact na organizacje i panujące w nim zasady bezpieczeństwa.
7. ## **Monitoring and revision**:
  - #### Monitoring:
  - Audyty bezpieczeństwa, regularne sprawdzanie access logs i analiza IR plans to podstawa. Ciągły progess i poprawy.
  - #### Revision:
  - Proces updatedów dokumentów odpowiedzialnych za zarządzanie bezpieczeństwem. 
8. ## **Types of governance structures**:
  - #### Cetralnie Sterowana/ Decentralized.
9. ## **Roles and responsibilities for systems and data**
   - #### Data Owner: Posiada legalnie prawa i kompletną kontrolę nad danymi. Zazwyczaj Senior Management, może dawać codzienne obowiązki, ale on za to odpowiada.
   - #### Data Custodian: Odpowiada za przechowywanie, transport i stan danych. Nie decydują, a implementuje reguły i techniczną kontrolę (np. CIA, audit trails, Role Day-to-Day).
   - #### GDPR Data Processor: Neutralana, pubiczny autorytet, agencja itd, która przetwarza dane osobiste polegając na Data Controler.
   - #### GDPR Data Contrler: Osoba lub jednostka, która kontroluje przetwarzanie danych(kontroluje GDPR Data Processor).
   - #### Data Subject: Osoba indiwidualna, która może zostać zidentifikowana poprzez identifikator(np. ID, lokalizacja, genetyka, kultura, środowisko).
   - #### Data Steward: Upewnia się, że kontekst i znaczanie danych jest zrozumiałe oraz zarządzanie danych jest zrozumiane i stosowane. Data Owner daje mu często zadanie sprawdzenia tegp. 
