# MTTPP_Projekt

Napisala sam 5 test case-ova (Prijava korisnika, Odjava korisnika, Pretraga pomoću tražilice, Dodavanje artikala u košaricu i Povećanje količine artikala u košarici) koji sadrže detaljno opisane korake na temelju kojih će se snimiti testovi.
Koristeći Katalon Recorder browser proširenje, snimila sam sve test slučajeve. Nakon snimanja sam reproducirala test slučajeve kako bih vidjela hoće li se ispravno izvršiti, a zatim sam exportala u skripte C#(WebDriver + NUnit).
U Visualu sam kreirala NUnit Test Project, instalirala potrebne pakete (NUnit, NUnit.Analyzers, NUnit3TestAdapter, Selenium.Support, Selenium.WebDriver, Selenium.WebDriver.GeckoDriver) i dodala exportane skripte.
Nakon Build-a sam pokrenula testove u Test Exploreru. Svi testovi su se ispravno izvršili.
