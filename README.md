# Schemat transformacji wybranych encji modelu danych Polish API (wersja 2.1.2)

> Celem niniejszego repozytorium jest przedstawienie schematu transformacji z formatu JSON do formatu XML oraz utworzenie definicji XSD na potrzeby walidacji wybranej encji modelu danych. 


## Info 
Na podstawie modelu danych Polish API (wersja 2.1.2) wyeksportowane zostały 4 definicje klasy wraz z ich referencjami. Każda definicja klasy została zapisana w oddzielnym pliku JSON. Do każdego z nich została utworzona definicja schematu XSD oraz odpowiadający jej przykładowy plik XML, co pozwala na sprawdzenie poprawności walidacji struktury i typu danych. 


## Lista katalogów 

> Każdy z katalogów posiada zestaw plików odpowiadający wydzielonej definicji klasy. 

1. **HoldInfo**:
  * &nbsp;**HoldInfo.json** - plik zawierający definicję klasy HoldInfo (klasa opisująca blokadę na rachunku)
  * &nbsp;**HoldInfo.xsd** - definicja schematu  
  * &nbsp;**HoldInfo.xml** - plik testowy zlinkowany z definicją schematu
  
  
2. **ItemInfoBase**:
  * &nbsp;**ItemInfoBase.json** - plik zawierający definicję klasy ItemInfoBase (Klasa bazowa informacji o elemencie (transakcji lub blokadzie))
  * &nbsp;**ItemInfoBase.xsd** - definicja schematu
  * &nbsp;**ItemInfoBase.xml** - plik testowy zlinkowany z definicją schematu
  
  
3. **PaymentEEARequestBundled**:
  * &nbsp;**PaymentEEARequestBundled.json** - plik zawierający definicję klasy (Klasa zlecenia przelewu zagranicznego SEPA w ramach paczki)
  * &nbsp;**PaymentEEARequestBundled.xsd** - definicja schematu
  * &nbsp;**PaymentEEARequestBundled.xml** - plik testowy zlinkowany z definicją schematu


4. **Payor**:
  * &nbsp;**Payor.json** - plik zawierający definicję klasy (Klasa informacji o płatniku do US)
  * &nbsp;**Payor.xsd** - definicja schematu
  * &nbsp;**Payor.xml** - plik testowy zlinkowany z definicją schematu


## Użyte narzędzia

* Altova XML Spy 2019
* Online XSD to XML Converter (https://www.liquid-technologies.com/online-xsd-to-xml-converter)
* Notepad++


