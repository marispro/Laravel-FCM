# LaravelFCM\Response\GroupResponseContract | Laravel / Lumen package for Firebase Cloud Messaging    

## [Laravel / Lumen package for Firebase Cloud Messaging](../../index.md)

- [Classes](../../classes.md)
- [Namespaces](../../namespaces.md)
- [Interfaces](../../interfaces.md)
- [Traits](../../traits.md)
- [Index](../../doc-index.md)
- [Search](../../search.md)

>interface

>    [LaravelFCM](../../LaravelFCM.md)` / `[Response](../../LaravelFCM/Response.md)` / `(GroupResponseContract)
## GroupResponseContract

interface **GroupResponseContract** [View source](https://github.com/code-lts/Laravel-FCM/blob/main/src/Response/GroupResponseContract.php)



Interface GroupResponseContract.


### Methods

|   |   |   |   |
|---|---|---|---|
|int|<a name="#method_numberSuccess"></a>numberSuccess()|Get the number of device reached with success.||
|int|<a name="#method_numberFailure"></a>numberFailure()|Get the number of device which thrown an error.||
|array|<a name="#method_tokensFailed"></a>tokensFailed()|Get all token in group that fcm cannot reach.||


### Details
<a name id="method_numberSuccess"></a>

### 
 int **numberSuccess**()

[at line 15](https://github.com/code-lts/Laravel-FCM/blob/main/src/Response/GroupResponseContract.php#L15)

Get the number of device reached with success.        

#### Return Value

|   |   |
|---|---|
|int|

<a name id="method_numberFailure"></a>

### 
 int **numberFailure**()

[at line 22](https://github.com/code-lts/Laravel-FCM/blob/main/src/Response/GroupResponseContract.php#L22)

Get the number of device which thrown an error.        

#### Return Value

|   |   |
|---|---|
|int|

<a name id="method_tokensFailed"></a>

### 
 array **tokensFailed**()

[at line 29](https://github.com/code-lts/Laravel-FCM/blob/main/src/Response/GroupResponseContract.php#L29)

Get all token in group that fcm cannot reach.        

#### Return Value

|   |   |
|---|---|
|array|

_Generated by [Doctum, a API Documentation generator and fork of Sami](https://github.com/code-lts/doctum)._