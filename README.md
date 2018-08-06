# RSharp - Simple.

### License: Apache License 2.0

### Note on RSharp.Signed

The `RSharp` package is now signed so there is no need to install `RSharp.Signed`, which is obsolete from v160.0.0.

### Features

* Assemblies for .NET 4.5.2 and .NET Standard 2.0
* Easy installation using [NuGet](http://nuget.org/packages/RSharp) for most .NET flavors (signed)
* Automatic XML and JSON deserialization
* Supports custom serialization and deserialization via ISerializer and IDeserializer
* Fuzzy element name matching ('product_id' in XML/JSON will match C# property named 'ProductId')
* Automatic detection of type of content returned
* GET, POST, PUT, PATCH, HEAD, OPTIONS, DELETE, COPY supported
* Other non-standard HTTP methods also supported
* OAuth 1, OAuth 2, Basic, NTLM and Parameter-based Authenticators included
* Supports custom authentication schemes via IAuthenticator
* Multi-part form/file uploads
