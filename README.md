networq:vps
====

This is the "networq:vps" package for [NetworQ](https://github.com/networq).

## Types

This package defines the following types that you can use in your own Networq:

### networq:vps:plan type

Fields:

  * `provider`: *networq:vps:provider*
  * `specs`: *string*
  * `pricing`: *string*

### networq:vps:server type

Fields:

  * `name`: *string*
  * `account`: *networq:vps:account*
  * `plan`: *networq:vps:plan*

### networq:vps:location type

Fields:

  * `provider`: *networq:vps:provider*

### networq:vps:account type

Fields:

  * `name`: *string*
  * `provider`: *networq:vps:provider*

### networq:vps:provider type

Fields:



