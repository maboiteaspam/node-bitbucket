# Global





* * *

## Class: BitBucket


**$apis**:  , The list of loaded API instances
**$request**:  , The request instance used to communicate with GitHub
### BitBucket.authenticate(login, token) 

Authenticate a user for all next requests

**Parameters**

**login**: `String`, BitBucket username

**token**: `String`, BitBucket private token

**Returns**: `BitBucket`, fluent interface

### BitBucket.authenticateToken(login, token) 

Authenticate a user for all next requests using an API token

**Parameters**

**login**: `String`, BitBucket username

**token**: `String`, BitBucket API token

**Returns**: `BitBucket`, fluent interface

### BitBucket.authenticatePassword(login, password) 

Authenticate a user for all next requests using an API token

**Parameters**

**login**: `String`, BitBucket username

**password**: `String`, BitBucket password

**Returns**: `BitBucket`, fluent interface

### BitBucket.authenticateOAuth(oauth, accessToken, accessTokenSecret) 

Authenticate a user for all next requests using an API token

**Parameters**

**oauth**: `OAuth`, Authenticate a user for all next requests using an API token

**accessToken**: `String`, Authenticate a user for all next requests using an API token

**accessTokenSecret**: , Authenticate a user for all next requests using an API token

**Returns**: `BitBucket`, fluent interface

### BitBucket.deAuthenticate() 

Deauthenticate a user for all next requests

**Returns**: `BitBucket`, fluent interface

### BitBucket.get(route, parameters, requestOptions, callback) 

Call any route, GET method
Ex: api.get('repos/show/my-username/my-repo')

**Parameters**

**route**: `String`, the GitHub route

**parameters**: `Object`, GET parameters

**requestOptions**: `Object`, reconfigure the request

**callback**: `msg:&#39;&#39;`, (err, body{})

**Returns**: `Request`

### BitBucket.&#39;delete&#39;(route, parameters, requestOptions, callback) 

Call any route, DELETE method
Ex: api.delete('repos/show/my-username/my-repo')

**Parameters**

**route**: `String`, the GitHub route

**parameters**: `Object`, GET parameters

**requestOptions**: `Object`, reconfigure the request

**callback**: `msg:&#39;&#39;`, (err, body{})

**Returns**: `Request`

### BitBucket.post(route, parameters, requestOptions, callback) 

Call any route, POST method
Ex: api.post('repos/show/my-username',
       {'email': 'my-new-email@provider.org'})

**Parameters**

**route**: `String`, the GitHub route

**parameters**: `Object`, POST parameters

**requestOptions**: `Object`, reconfigure the request

**callback**: `msg:&#39;&#39;`, (err, body{})

**Returns**: `Request`

### BitBucket.getRequest() 

Get the request

**Returns**: `Request`, a request instance

### BitBucket.getUserApi() 

Get the user API

**Returns**: `UserApi`, the user API

### BitBucket.getUsersApi() 

Get the users API

**Returns**: `UsersApi`, the users API

### BitBucket.getRepoApi() 

Get the repo API

**Returns**: `RepoApi`, the repo API

### BitBucket.getSshApi() 

Get the ssh API

**Returns**: `SshApi`, the SSH API

### BitBucket.getEmailApi() 

Get the email API

**Returns**: `EmailApi`, the email API



* * *










