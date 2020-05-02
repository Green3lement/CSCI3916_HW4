# CSCI3916_HW4
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/6cbb49c689b8ec678f39#?env%5BHomework3%5D=W3sia2V5Ijoie3t0b2tlbn19IiwidmFsdWUiOiJKV1QgZXlKaGJHY2lPaUpJVXpJMU5pSXNJblI1Y0NJNklrcFhWQ0o5LmV5SnBaQ0k2SWpWbE5qWmhOV0V4WmpneE1EaGtOREpsTUdKalpUZzVOeUlzSW5WelpYSnVZVzFsSWpvaWVtRmphQ0lzSW1saGRDSTZNVFU0TXpjNE5qWTJOSDAucFBiX2JqR0FDRXltVHVwNEwxTHFONDhGVVNCazRMRU1BeU5vVVZPaHNLQSIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoidG9rZW4iLCJ2YWx1ZSI6IkpXVCBleUpoYkdjaU9pSklVekkxTmlJc0luUjVjQ0k2SWtwWFZDSjkuZXlKcFpDSTZJalZsTm1Kak1HSXpZak14WW1KaU5USTVPVGxtTlRBNU1pSXNJblZ6WlhKdVlXMWxJam9pZW1GamFDSXNJbWxoZENJNk1UVTRORE13TURreU9IMC55S0ZLYlBfUll0ekQ5MUNleE9RcXVMN0JndER0TzlpWUxhM3V4N25rT3YwIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJyYW5kb21QYXNzd29yZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJyYW5kb21Vc2VybmFtZSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX1d)

https://kvanstehw4.herokuapp.com/

This is the error i have been getting:

Error is:  MongooseError [MongooseServerSelectionError]: connection <monitor> to 54.188.38.219:27017 closed

2020-05-02T01:33:19.931289+00:00 app[web.1]:     at new MongooseServerSelectionError (/app/node_modules/mongoose/lib/error/serverSelection.js:22:11)

2020-05-02T01:33:19.931289+00:00 app[web.1]:     at NativeConnection.Connection.openUri (/app/node_modules/mongoose/lib/connection.js:808:32)

2020-05-02T01:33:19.931316+00:00 app[web.1]:     at Mongoose.connect (/app/node_modules/mongoose/lib/index.js:333:15)

2020-05-02T01:33:19.931318+00:00 app[web.1]:     at Object.<anonymous> (/app/Users.js:7:10)

2020-05-02T01:33:19.931318+00:00 app[web.1]:     at Module._compile (internal/modules/cjs/loader.js:1133:30)

2020-05-02T01:33:19.931319+00:00 app[web.1]:     at Object.Module._extensions..js (internal/modules/cjs/loader.js:1153:10)

2020-05-02T01:33:19.931319+00:00 app[web.1]:     at Module.load (internal/modules/cjs/loader.js:977:32)

2020-05-02T01:33:19.931319+00:00 app[web.1]:     at Function.Module._load (internal/modules/cjs/loader.js:877:14)

2020-05-02T01:33:19.931319+00:00 app[web.1]:     at Module.require (internal/modules/cjs/loader.js:1019:19)

2020-05-02T01:33:19.931319+00:00 app[web.1]:     at require (internal/modules/cjs/helpers.js:77:18)

2020-05-02T01:33:19.931320+00:00 app[web.1]:     at Object.<anonymous> (/app/auth_jwt.js:5:12)

2020-05-02T01:33:19.931320+00:00 app[web.1]:     at Module._compile (internal/modules/cjs/loader.js:1133:30)

2020-05-02T01:33:19.931320+00:00 app[web.1]:     at Object.Module._extensions..js (internal/modules/cjs/loader.js:1153:10)

2020-05-02T01:33:19.931320+00:00 app[web.1]:     at Module.load (internal/modules/cjs/loader.js:977:32)

2020-05-02T01:33:19.931320+00:00 app[web.1]:     at Function.Module._load (internal/modules/cjs/loader.js:877:14)

2020-05-02T01:33:19.931321+00:00 app[web.1]:     at Module.require (internal/modules/cjs/loader.js:1019:19) {

2020-05-02T01:33:19.931321+00:00 app[web.1]:   reason: TopologyDescription {

2020-05-02T01:33:19.931321+00:00 app[web.1]:     type: 'ReplicaSetNoPrimary',

2020-05-02T01:33:19.931321+00:00 app[web.1]:     setName: null,

2020-05-02T01:33:19.931322+00:00 app[web.1]:     maxSetVersion: null,

2020-05-02T01:33:19.931322+00:00 app[web.1]:     maxElectionId: null,

2020-05-02T01:33:19.931322+00:00 app[web.1]:     servers: Map {

2020-05-02T01:33:19.931322+00:00 app[web.1]:       'cluster0-shard-00-01-bugxf.mongodb.net:27017' => [ServerDescription],

2020-05-02T01:33:19.931322+00:00 app[web.1]:       'cluster0-shard-00-02-bugxf.mongodb.net:27017' => [ServerDescription],

2020-05-02T01:33:19.931323+00:00 app[web.1]:       'cluster0-shard-00-00-bugxf.mongodb.net:27017' => [ServerDescription]

2020-05-02T01:33:19.931323+00:00 app[web.1]:     },

2020-05-02T01:33:19.931323+00:00 app[web.1]:     stale: false,

2020-05-02T01:33:19.931323+00:00 app[web.1]:     compatible: true,

2020-05-02T01:33:19.931323+00:00 app[web.1]:     compatibilityError: null,

2020-05-02T01:33:19.931324+00:00 app[web.1]:     logicalSessionTimeoutMinutes: null,

2020-05-02T01:33:19.931324+00:00 app[web.1]:     heartbeatFrequencyMS: 10000,

2020-05-02T01:33:19.931324+00:00 app[web.1]:     localThresholdMS: 15,

2020-05-02T01:33:19.931324+00:00 app[web.1]:     commonWireVersion: null

2020-05-02T01:33:19.931324+00:00 app[web.1]:   },

2020-05-02T01:33:19.931325+00:00 app[web.1]:   [Symbol(mongoErrorContextSymbol)]: {}

2020-05-02T01:33:19.931325+00:00 app[web.1]: }
