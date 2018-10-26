# ic-snippets

# Function stubs

## ic-fnStorageSupport
Checks if local storage is supported.

## ic-fnCoSet
Set a Cookie with a given cookieName, cookieValue and expire in days. Example x.setCookie('key', 'value', 10);

## ic-fnCoRead
Reads a Cookie Value, returns the value or null if there is no cookie, example: x.readCookie('key') 

## ic-fnCoDel
Deletes a cookie with a given name, example: x.delete('key')

## ic-fnPoll
Poll until condition is met

## ic-fnAnon
Abbreviation: self-invoking anonymous function stub

# Event Listener

## ic-evListener
Event-Listener stub

## ic-evDispatch
Event-Dispatcher stub

# DataLayer

## ic-dl
Null-safe access of DataLayer properties

## ic-dlPageData
safe access of Adobe pageData (should this get an AA?)

# Adobe

## ic-aaProd
access Adobe products

## ic-aaPre
Adobe preTrackCallback stub

# Others

## ic-forProd
For loop through all products in pageData