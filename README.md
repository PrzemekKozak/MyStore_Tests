# Tests of MyStore - online shop
## (Selenium WebDriver with Java and Cucumber)



### *The project includes two automatic tests of the online store functions:*

**1. Test of adding a new address of a registered user and deleting an added address.**
> Cucumber Scenario Outline:
[MyStore_Tests/src/test/resources/features/addNewAddressMyStore.feature](https://github.com/PrzemekKozak/MyStore_Tests/blob/master/src/test/resources/features/addNewAddressMyStore.feature)

> Steps definition:
[MyStore_Tests/src/test/java/steps_definitions/MyStoreAddressSteps.java](https://github.com/PrzemekKozak/MyStore_Tests/blob/master/src/test/java/steps_definitions/MyStoreAddressSteps.java)
___________________________________________________________________________________________________________________________________

**2. Test of the full purchasing process with the ability to choose the quantity and size. [Page Factory and Page Object Model]**
> *In addition, checking the correctness of the discount granted and making a print screen of the purchase confirmation.*

> Cucumber Scenario:
[MyStore_Tests/src/test/resources/features/shoppingMyStore.feature](https://github.com/PrzemekKozak/MyStore_Tests/blob/master/src/test/resources/features/shoppingMyStore.feature)

> Steps definition:
[MyStore_Tests/src/test/java/steps_definitions/MyStoreBuySteps.java](https://github.com/PrzemekKozak/MyStore_Tests/blob/master/src/test/java/steps_definitions/MyStoreBuySteps.java)

> Classes with pages:
[MyStore_Tests/src/test/java/pages/](https://github.com/PrzemekKozak/MyStore_Tests/tree/master/src/test/java/pages)
___________________________________________________________________________________________________________________________________

 **Enviromen:**
 * OS: Ubuntu 18.04.4 LTS
 * Google Chrome 83.0.4103.61 (official) (64-bit)
 * Java version "13.0.2" 2020-01-14
 * IDE: IntelliJ IDEA 2020.1.3 (Community Edition) Plugins:gherkin, cucumber-java
