# LaravelFCM\Sender\HTTPSender | Laravel / Lumen package for Firebase Cloud Messaging    

## [Laravel / Lumen package for Firebase Cloud Messaging](../../index.md)

- [Classes](../../classes.md)
- [Namespaces](../../namespaces.md)
- [Interfaces](../../interfaces.md)
- [Traits](../../traits.md)
- [Index](../../doc-index.md)
- [Search](../../search.md)

>class

>    [LaravelFCM](../../LaravelFCM.md)` / `[Sender](../../LaravelFCM/Sender.md)` / `(HTTPSender)
## HTTPSender

abstract class **HTTPSender**


    
    
    

### Properties

|   |   |   |   |
|---|---|---|---|
|<a name="property_client"></a>protected <abbr title="GuzzleHttp\ClientInterface">ClientInterface</abbr>|$client|The client used to send messages.||
|<a name="property_url"></a>protected string|$url|The URL entry point.||
|<a name="property_logger"></a>protected <abbr title="Monolog\Logger">Logger</abbr>|$logger|The logger.||
### Methods

|   |   |   |   |
|---|---|---|---|
||<a name="#method___construct"></a>__construct(<abbr title="GuzzleHttp\ClientInterface">ClientInterface</abbr> $client, $url, <abbr title="Monolog\Logger">Logger</abbr> $logger)|Initializes a new sender object.||


### Details
<a name id="method___construct"></a>

### 
  **__construct**(<abbr title="GuzzleHttp\ClientInterface">ClientInterface</abbr> $client, $url, <abbr title="Monolog\Logger">Logger</abbr> $logger)

at line 37    
    

Initializes a new sender object.        

#### Parameters

|   |   |   |
|---|---|---|
|<abbr title="GuzzleHttp\ClientInterface">ClientInterface</abbr>|$client|||$url||<abbr title="Monolog\Logger">Logger</abbr>|$logger|
_Generated by [Doctum, a API Documentation generator and fork of Sami](https://github.com/code-lts/doctum)._