# Risk Management Process

## 1) Risk Identification
Proces identyfikacji zagrożeń i podatności w naszym systemie, takich jak:
- Cyber Threats  
- System failure  
- Naturalne katastrofy  

---

## 2) Risk Assessment
Proces identyfikowania, analizowania, oceniania i priorytetyzowania potencjalnego ryzyka. W skrócie – cały Risk Management.

- **Ad hoc (na żądanie):** dla nowych zagrożeń lub wyjątkowych sytuacji  
- **Recurring:** okresowe, np. annually, quarterly  
- **One-Time:** formalny ad-hoc w odpowiedzi na incydent bezpieczeństwa lub prośbę zarządu  
- **Continuous:** zazwyczaj zautomatyzowane, np. codzienne proste skany  

---

## 3) Risk Analysis

### Quantitative
Skupia się na wartości pieniężnej zasobów oraz potencjalnych stratach:  
- **Asset Value (AV):** wartość gotówkowa zasobu  
- **Exposure Factor (EF):** procent wartości AV, który może zostać utracony w wyniku ataku  
- **Single Loss Expectancy (SLE):** SLE = AV × EF  
- **Annualized Rate of Occurrence (ARO):** częstotliwość wystąpienia ryzyka w ciągu roku  
- **Annualized Loss Expectancy (ALE):** ALE = ARO × SLE  

**Przykład:**  
Jabłko warte 5 zł atakuje robak dwa razy w roku, zjadając za każdym razem 50% jabłka:  
- AV = 5 zł  
- EF = 50%  
- SLE = 2,5 zł  
- ARO = 2/1 = 2  
- ALE = 2 × 2,5 zł = 5 zł  

### Qualitative
- System oceny zazwyczaj w formie macierzy: low/medium/high  
- **Probability:** prawdopodobieństwo zdarzenia (0–1)  
- **Likelihood:** szansa wystąpienia zagrożenia (high/medium/low/rare)  

---

## 4) Risk Register
Lista zagrożeń + ich skutków + plan ochrony. Zawiera m.in.:  
- Risk ID  
- Description  
- Probability  
- Impact  
- Severity  
- Response  
- Owner  

### Key Risk Indicators (KRIs)
Mierzalne metryki sygnalizujące zmianę w prawdopodobieństwie lub impakcie ryzyka.  

### Risk Owner
Każde ryzyko przypisane do osoby lub departamentu odpowiedzialnego za zarządzanie i mitigację.  

### Risk Threshold
Poziom tolerancji ryzyka ustalony przez organizację – określa, kiedy należy podjąć akcję.  

---

## 5) HeatMap / Risk Matrix
Powstaje w oparciu o Risk Register.  
![risk matrix](https://github.com/user-attachments/assets/5ef1865b-7260-4ea3-963b-ddd7e1376a5f)

---

## 6) Risk Appetite vs Risk Tolerance

- **Risk Appetite:** ilość ryzyka, które organizacja jest w stanie zaakceptować bez mitigacji  
  - Expansionary: duże ryzyko = duża nagroda  
  - Neutral: zbalansowane podejście  
  - Conservative: minimalne ryzyko, bezpieczeństwo utrzymane  
- **Risk Tolerance:** zdolność organizacji do podjęcia ryzyka  

---

## 7) Risk Management Strategies

- **Risk Transfer:** przenosimy ryzyko na inną firmę (np. ubezpieczenie)  
- **Risk Acceptance:** akceptujemy ryzyko  
  - Exception: dokumentowane, zatwierdzone na określony czas  
  - Exemption: formalna decyzja o akceptacji ryzyka, jeśli mitigacja nie jest możliwa  
- **Risk Mitigation:** redukcja ryzyka  
- **Risk Avoidance:** całkowite usunięcie ryzyka  

---

## 8) Risk Reporting
Zarząd decyduje, które kontrole zaimplementować i które ryzyko zaakceptować.  

---

## 9) Business Impact Analysis (BIA)

### Cost-Benefit Analysis (CBA)
Metoda ilościowa porównująca koszty i korzyści, aby podjąć najbardziej profitową decyzję  

### Return on Investment (ROI)

### Recovery Point Objective (RPO)
Maksymalna dopuszczalna utrata danych między ostatnim backupem a katastrofą  

### Recovery Time Objective (RTO)
Czas, w jakim system musi wrócić do działania  

### Mean Time Between Failures (MTBF)
Średni czas między awariami  

### Mean Time To Repair (MTTR)
Średni czas naprawy systemu  

