## Projektabgabe im Modul "Python for Machine Learning"

# Einleitung

Unabhängig davon, ob es nun um die Entwicklung der Finanzmärkte, der Rohstoffpreise oder des Stromverbrauchs geht - in beiden Fällen ist die Zeit ein wichtiger Faktor im Rahmen der Analyse. Auch im betrieblichen Umfeld hat die Analyse von Daten mit zeitlichem Bezug eine große Bedeutung. So ist es wenig verwunderlich, dass sich Unternehmen in ihren ersten Gehversuchen im KI-Umfeld häufig zunächst mit Zeitreihenanalysen und dem anschließenden Forecasting der Zeitreihendaten beschäftigen.

Der Begriff Zeitreihe stammt aus der Mathematik und beschreibt den zeitlichen Verlauf von Beobachtungen bzw. Messgrößen. Die Vorhersage der zukünftigen Werte einer Messgröße basierend auf der vorhandenen Zeitreihe d.h. mittels historischer Daten, wird als Zeitreihenanalyse bzw. Zeitreihenprognose (Time Series Forecasting) bezeichnet.

Sei es zur Cashflow- oder Umsatzprognose, der Nachfrage- oder Beschaffungsplanung oder im Personalbereich zur besseren Steuerung von Personaleinsatz: Es finden sich entlang der gesamten Wertschöpfungskette überall dort Anwendungsfälle, wo es historische Daten über die Zeit gibt. Das Zeitintervall (jährlich, monatlich, täglich) kann dabei flexibel gewählt und Use-Case-spezifisch angepasst werden.


# Business Understanding / Ziel des Projektes

Rohstoffpreise dienen seit Langem als Frühindikator für wirtschaftliche Entwicklungen, z.B. weltweite Inflationen. Dies liegt an ihrer schnellen und zeitnahen Verfügbarkeit sowie den hochfrequenten Veränderungen. 

In den letzten zwei Jahren waren diese Schwankungen besonders ausgeprägt. Infolge von Lockdownmaßnahmen, Naturkatastrophen und Vorfällen, wie dem Stau im Suezkanal, sind Rohstoffpreise weltweit explosionsartig innerhalb kürzester Zeit gestiegen. Dies stellt Industrieunternehmen und deren Einkäufer sowie Supply-Chain-Controller nahezu täglich vor große Herausforderungen und verlangt immer häufiger und kurzfristiger weitreichende Entscheidungen: <br>
- Steigen die Preise weiter oder sind sinkende Preise zu erwarten? 
- Soll daher bereits heute Nachschub geordert werden oder kann die Bestellung noch einige Tage aufgeschoben werden?

Mit einem entsprechenden Forecasting kann nicht immer eine punktgenaue Vorhersage getroffen werden, jedoch erleichtert es in vielen Fällen die Beantwortung der oben gestellten Fragestellungen und kann als zusätzliche Entscheidungshilfe herangezogen werden.

In der vorliegenden Projektarbeit soll sich am Beispiel von Kupferpreisen der London Metal Exchange (Rohstoffbörse in London) dieser Problemstellung angenommen werden. Dazu kommen verschiedene Algorithmen zur Zeitreihenprognose (englisch "Time series prediction / forecasting") zum Einsatz, die auf ihre Eignung geprüft, beispielhaft implementiert sowie bewertet werden sollen. Es werden sowohl Modelle des klassischen Machine-Learnings als auch aus dem Bereich des aktuell viel diskutierten Deep Learnings mit neuronalen Netzen herangezogen.

# Vorgehensweise

Die Vorgehensweise der vorliegenden Arbeit orientiert sich grundsätzlich am im Data-Science-Umfeld üblichen Modell des CRISP-DMs. CRISP-DM steht für **C**Ross-**I**ndustry **S**tandard **P**rocess for **D**ata **M**ining. Dieses branchenübergreifende Prozess-Modell wurde ab 1996 im Rahmen eines EU-Förderprojekts entwickelt.

Da jedoch der Schwerpunkt dieses Moduls auf dem Machine-Learning-Part liegt, wurden die weiteren Bestandteile - im Wesentlichen das "Data Understanding / Data Exploration" sowie die "Data Preparation / Feature Engineering" - ausgelagert und in separaten Jupyter-Notebooks abgelegt.

Diese sind wie folgt zu finden:

- **Data Scraping / Loading**: [Scraping & Loading](http://htmlpreview.github.io/?https://github.com/andreashrb/Python_for_ML_Project/blob/main/interim_results/1%20-%20Scrapping_Loading_Copper_Economic_Data.html)

- **Data Joining**: [Data Joining](http://htmlpreview.github.io/?https://github.com/andreashrb/Python_for_ML_Project/blob/main/interim_results/2%20-%20Joining_Copper-EconomicData.html)

- **Data Understanding / Data Exploration**: [Data Exploration](http://htmlpreview.github.io/?https://github.com/andreashrb/Python_for_ML_Project/blob/main/interim_results/3%20-%20Data%20Exploration_CopperPrice_CopperStock.html)

- **Data Preparation / Feature Engineering**: [Data Prep & Feature Engineering](http://htmlpreview.github.io/?https://github.com/andreashrb/Python_for_ML_Project/blob/main/interim_results/4%20-%20DataPreparation_FeatureEngineering.html)

- **Modeling and Evaluation**: [Modeling & Evaluation](http://htmlpreview.github.io/?https://github.com/andreashrb/Python_for_ML_Project/blob/main/5%20-%20Main - DataPreprocessing_DataModelling.html)



Andreas Herb & Sebastian Wölk
