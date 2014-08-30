![image_squidhome@2x.png](http://sailsjs.org/images/bkgd_squiddy.png)

# Parse API Adapter

Provides easy access to [`Parse`](https://parse.com) from Sails.js & Waterline.

This module is a Waterline/Sails adapter, an early implementation of a rapidly-developing, tool-agnostic data standard.  Its goal is to provide a set of declarative interfaces, conventions, and best-practices for integrating with all sorts of data sources.  Not just databases-- external APIs, proprietary web services, or even hardware.

Strict adherence to an adapter specification enables the (re)use of built-in generic test suites, standardized documentation, reasonable expectations around the API for your users, and overall, a more pleasant development experience for everyone.


### Installation

- This adapter is not yet on npm. To install, put the following codes in your package.json:
```javascript
"dependencies": {
  "sails-parse-adapter": "tommy60703/sails-parse.git",
  ...
}
```  
Then run `npm install`.

- Or you can just download the files and put it in your project.


### Usage

Set up your Parse configuration at config/connections.js as following:  

```javascript
parse: { 
	adapter: 'sails-parse-adapter', 
	appId: 'your-app-id', 
	restKey: 'your-rest-key'
} 
```

This adapter exposes the following methods:

- `find()`
- `create()`
- `update()`
- `destroy()`



### Interfaces

>TODO:

- Make it more stable
- test!
- Documentation


### Contribution

- This adapter is still in early development. You are welcome to report bugs or make pull request.

### More Resources

- [Stackoverflow](http://stackoverflow.com/questions/tagged/sails.js)
- [#sailsjs on Freenode](http://webchat.freenode.net/) (IRC channel)
- [Twitter](https://twitter.com/sailsjs)
- [Professional/enterprise](https://github.com/balderdashy/sails-docs/blob/master/FAQ.md#are-there-professional-support-options)
- [Tutorials](https://github.com/balderdashy/sails-docs/blob/master/FAQ.md#where-do-i-get-help)
- <a href="http://sailsjs.org" target="_blank" title="Node.js framework for building realtime APIs."><img src="https://github-camo.global.ssl.fastly.net/9e49073459ed4e0e2687b80eaf515d87b0da4a6b/687474703a2f2f62616c64657264617368792e6769746875622e696f2f7361696c732f696d616765732f6c6f676f2e706e67" width=60 alt="Sails.js logo (small)"/></a>

