# Search for a machine

## Test Description

 We test for correct functionality of the machine search within the app. The search is tested at all points and with all possible search parameters.
 ***

### Precondition

* user is logged in
* use the Rest APIs /search endpoint to get the result

***

## Scenario 1 Number search

A user searches for "123" on the machine overview page and result must correcpond to restAPI's search result.

### S1: Input

* When pressing on the search bar on the machine overview page
* AND type in "123"
* AND press the search button right to the space bar.

### S1: Expected Result

* [ ] Then a loading bar appears for less then 3 seconds
* [ ] AND the machine list shows the same results as our Rest APIs /search endpoint.

***

## Scenario 2 String search

A user searches for "BICES" on the machine overview page and result must correcpond to restAPI's search result.

### S2: Input

* When pressing on the search bar on the machine overview page
* AND type in "BICES"
* AND press the search button right to the space bar.

### S2: Expected Result

* [ ] Then a loading bar appears for less then 3 seconds
* [ ] AND the machine list shows the same results as our Rest APIs /search endpoint.

***

## Scenario 3 Mix of String and number search

A user searches for "37aa" on the machine overview page and result must correcpond to restAPI's search result.

### S3: Input

* When pressing on the search bar on the machine overview page
* AND type in "37aa"
* AND press the search button right to the space bar.

### S3: Expected Result

* [ ] Then a loading bar appears for less then 3 seconds
* [ ] AND the machine list shows the same results as our Rest APIs /search endpoint.

***
