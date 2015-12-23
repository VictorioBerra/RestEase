v1.0.6
------

 - Support .NET 4.0 (using Microsoft.Net.Http and Microsoft.Bcl.Async as dependencies)
 - URL Encode path parameters

v1.0.5
------

 - Allow custom serialization of query parameters and query maps
 - Add `[SerializationMethods]` attribute, to specify the default serialization method for bodies and query parameters
 - Move to using a builder pattern for `RestClient`, to make specifying custom serializers/deserializations/configuration easier.
   The old methods are still present, but are marked as deprecated. Please upgrade to the new methods (suggested by the deprecation messages).

v1.0.4
------

 - Fix race condition when creating implementations (#4)

1.0.3
-----

 - Allow interface headers in interface inheritance (#3)
 - Add missing `RestClient.For` overloads

1.0.2
-----

 - Allow interface inheritance (#3)

1.0.1
-----

 - `JsonRequestBodySerializer` sets a default Content-Type header of `application/json`

1.0.0
-----

 - Initial Release