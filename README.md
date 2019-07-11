# Schemat transformacji wybranych encji modelu danych Polish API (wersja 2.1.2)

> Celem niniejszego repozytorium jest przedstawienie schematu transformacji z formatu JSON do formatu XML oraz utworzenie definicji XSD na potrzeby walidacji wybranej encji modelu danych. 


## Info 
Na podstawie modelu danych Polish API (wersja 2.1.2) wyeksportowane zostały 4 definicje klasy wraz z ich referencjami. Każda definicja klasy została zapisana w oddzielnym pliku JSON. Do każdego z nich została utworzona definicja schematu XSD oraz odpowiadający jej przykładowy plik XML, co pozwala na sprawdzenie poprawności walidacji struktury i typu danych. 


## Sposób użycia
Katalog z nazwami definicji klas zawiera zestaw plików XML oraz zlinkowany z nim plik XSD, co pozwala na zwalidowanie struktury za pomocą jakiegokolwiek narzędzia posiadającego funkcję procesowania plików XML. 

## Lista katalogów 

> Każdy z katalogów posiada zestaw plików odpowiadający wydzielonej definicji klasy. 

1. **HoldInfo**:
  * **HoldInfo.json** - plik zawierający definicję klasy HoldInfo (klasa opisująca blokadę na rachunku)
  2. **HoldInfo.xsd** - definicja schematu  
  3. **HoldInfo.xml** - plik testowy zlinkowany z definicją schematu
  
  
* **ItemInfoBase**:
  1. **ItemInfoBase.json** - plik zawierający definicję klasy ItemInfoBase (Klasa bazowa informacji o elemencie (transakcji lub blokadzie))
  2. **ItemInfoBase.xsd** - definicja schematu
  3. **ItemInfoBase.xml** - plik testowy zlinkowany z definicją schematu
  
  
* **PaymentEEARequestBundled**:
  1. **PaymentEEARequestBundled.json** - plik zawierający definicję klasy (Klasa zlecenia przelewu zagranicznego SEPA w ramach paczki)
  2. **PaymentEEARequestBundled.xsd** - definicja schematu
  3. **PaymentEEARequestBundled.xml** - plik testowy zlinkowany z definicją schematu


* **Payor**:
  1. **Payor.json** - plik zawierający definicję klasy (Klasa informacji o płatniku do US)
  2. **Payor.xsd** - definicja schematu
  3. **Payor.xml** - plik testowy zlinkowany z definicją schematu


## Użyte narzędzia

* Altova XML Spy 2019
* Online XSD to XML Converter (https://www.liquid-technologies.com/online-xsd-to-xml-converter)
* Notepad++


