# Z1 Lib Api Box Client Client Node

Node Feathers service in a macro 

This in an async service with node-persist as the data storage

Documentation under construction.

## Usage

Install

```
yarn add @z1/lib-api-box-client-node
```

Import

```JavaScript

import * from '@z1/lib-api-box-client-node'

const api = createApiClient(props)
```
### Configuration
 * `options`: { } IO socket options (optional)
 * `timeout`: number (optional) IO Socket timeout if call fails
 * `auth`: [config] (optional)
 * `configure`: [callback function] (optional)


[config]: https://docs.feathersjs.com/api/authentication/client.html#configuration
[callback function]: https://docs.feathersjs.com/api/application.html#configure-callback