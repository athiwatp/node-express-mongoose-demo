A demo app in node.js illustrating CURD operations using Express, mongodb, mongoose, stylus and Jade

## Steps
  [Install mongodb](http://www.mongodb.org/display/DOCS/Building+for+Linux)    
  [Install node.js](https://github.com/joyent/node/wiki/Installation)    
  Install npm : `curl http://npmjs.org/install.sh | sh`    
  `git clone git://github.com/madhums/nodejs-express-mongoose-demo.git noobjs`    
  `cd noobjs`    
  `npm install`    
  `node app.js`    
  [http://localhost:3000/](http://localhost:3000/)    
  
## v2.0 has the following changes
  * Uses MVC (`models`, `views`, `routes`)
  * Uses [stylus](http://learnboost.github.com/stylus/)
  * Custom error handlers (check `settings.js`)
  * [changelog](https://github.com/madhums/nodejs-express-mongoose-demo/compare/v1.0...v2.0)
  
## Contributors
  [M Fazle Taher](https://github.com/mftaher)
  
## Todo demos
  * <del>MVC architecture using express</del>
  * <del>Custom error handling in express</del>
  * <del>Routing in express</del>
  * <del>CURD operations using mongoose orm and mongodb</del>
  * <del>Use of [stylus](http://learnboost.github.com/stylus/)</del>
  * user authentication
    * [mongoose-auth](https://github.com/bnoguchi/mongoose-auth)
    * [everyauth](https://github.com/bnoguchi/everyauth)
  * map-reduce
  * embedded documents in mongoose
  * using of middlewares in mongoose
