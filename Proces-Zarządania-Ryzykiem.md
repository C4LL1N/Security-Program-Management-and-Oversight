## Risk Management Process
--- 
1) ### Risk Identification:
   Proces identyfikacji zagrożenia i podatności w naszym systemie takie jak Cyber Threats, system failure, naturalne katastrofy.
2) ### Risk Assessment:
   Identifying, analyzing, evaluating and prioritizing potencjalnego ryzyka. W skrócie cały Risk Management.
   - #### Ad hoc tkzw Na rządanie: jak coś jest nowego albo coś wymaga.
   - #### Recurring: Co jakiś okres czasu(np. Annually, quarterly).
   - #### One-Time: bardziej formalny Ad-Hoc w odpowiedzi na Incydent Bezpieczeństwa lub Prośbę Zarządu.
   - #### Continous: Zazwyczaj zautomatyzowane jak Codzienne proste Skany
4) ### Risk Analysis:
   - #### Quantitative:
   Skupiamy się wartości pieniężnej zasobów oraz potencjalnych stratach:
   - Asset Value(AV): Wartość gotówkowa danej rzeczy. Nie powinno się wydać więcej na ochrone niż warta jest dana rzecz.
   - Exposure Factor(EF): Jest to procent jaki AV może stracić poprzez atak. 
   -  Single Loss Expectancy(SLE): Pojedyczne zrealizowane ryzyko na danym assecie. SLE = AV * EF
   - Annualized Rate of Occurance(ARO): Jest to częstwotliwość z jaką zagrożenie(ryzyko) wystąpi w ciągu roku. ARO = (ile_razy)/(na_ile_lat)
   - Annualized Loss Expectancy: Roczne straty na Assecie przez ataki. ALE = ARO * SLE
   Przykład: Jabłko o wartości 5 zł atakuje robak dwa razy w roku. Za każdym razem zjada 50% jabłka. AV = 5zł * EF = 50%, SLE = 2.5 zł
  ARO=2/1=2, ALE=2*2.5zł = 5zł <- zagrożenie jest bardzo poważne, zjada nam cały profit.
   - #### Qualitative:
     Daje System Oceny zazwyczaj w formie macierzy. Mniej dokładny i szczegółowy zazwyczaj w low/med/high.
   - #### Probability: Prawdopodobieństwo na zdarzenie od 0 do 1
   - #### Liekhood: Szansa do przytrafienie się zagrożenia oznaczane jako "high", "medium", "low", "rare".
5) ### Risk Register 
   Risk Register to lista zagrożeń + ich skutków + plan, jak się przed nimi bronić. Zazwyczaj posiada szczeguły takie jak:
   Risk ID, Description, Probability, Impact, Severity, Response, Owner.
   - ##### Key Risk Indicators(KRIs):
     Są to mierzalne metryki które sygnalizują potencjalna zmiane w prawdopodobieństwie i impakcie ryzyka. Monitorowanie KRIs pozwoli na wczesne wykrycie, eskalacje i poprawe.
   - #### Risk Owner:
     Każde ryzyko powinno być przypisane do właściela, typowo dla osoby lub departamentu odpowiedzialnego za zarządzenia i mitigacje ryzyka.
   - #### Risk Threshold:
     Odopwiada za poziom tolerancji ryzyka ustablilizowanego przez organizacje, czyli po jakim ryzyku musimy podjąć akcje.
7) ### HeatMap/RiskMatrix
   Powstaje poprzez Risk register przykład:
<img width="512" height="568" alt="risk matrix" src="https://github.com/user-attachments/assets/5ef1865b-7260-4ea3-963b-ddd7e1376a5f" />
8) ### Riks appetite vs Risk Tolerance:
   - #### Risk Appetite opisuje ilość ryzyka jakie organizacja jest w stanie zakaceptować bez mitigacji. Używa się tego, żeby zdefinować risk threshold. Mamy 3 poziomy risk appetite:
   - Expansionary: duże ryzyko równa się duża nagroda.
   - Neutral: zbalansowane podjeście
   - Conservative: małe-ryzyko żeby było tak dobrze jak jest teraz
   - #### Risk Tolerance jest to zdolność lub większa odporność to podjęcia ryzyka.
9) ## Risk management strategies:
   - ### Risk Transfer: Transferujemy ryzyko na jakaś inna firmę 3party-vendor od której kupujemy ubezpieczenie
   - ### Risk Acceptance: Nic nie robimy  i akceptujemy ryzyko wraz ze stratą:
   - Exception: zdokumentowane i zatwierdzone risk acceptance, które będziemy mieli przez jakiś zdefniowany okres czasu.
   - Exemption: formalna decyzja nad zakceptowaniem ryzyka. ponieważ mitygacja jest niepraktyczna lub nie możliwa.
   - ### Risk Mitigation: Poprawiamy bezpieczeństwo jak tylko możemy, zawsze zostaje jakieś ryzyko i tak na końcu, bo zredukwaliśmy je tylko.
   - ### Risk Avoidance: Usuwamy całkowicie ryzyko, bo cena akceptacji lub mitigacji jest mniejsza niż benefity z serwisu.
10) ## Risk Reporting: Zarząd decyduje które kontrole zaimplementować i które ryzyko zaakceptować.
11) ## Business Impact Analysis(BIA):
    Posiada dwie ważne rzeczy:
    - ### Cost-Benefit Analysis(CBA): Quantitative method benfitów z ich kosztami, żeby zdeterminować jaka decyzja będzie najbardziej profitowa
    - ### Return on Ivestment(ROI).
    - ### Recovery Point Objective(RPO): Maksymalna dopuszczalna utrata danych pomiędzy ostanim backupem i katastrofą
    - ### Recovery Time Objective(RTO): Ile czasu ma team, żeby serwis działał.
    - ### Mean Time Between Failures(MTBF): Ile czasu pomiędzy katastrofą
    - ### Mean Time To Repair(MTTR): Ile czasu zajmie naprawa. 
