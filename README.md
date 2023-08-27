Terdapat error saat submit username dan password pada halaman /register. ini pesan errornya :
/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/index.js:31
  const { username, password } = req.body
          ^

TypeError: Cannot destructure property 'username' of 'req.body' as it is undefined.
    at /Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/index.js:31:11
    at Layer.handle [as handle_request] (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/layer.js:95:5)
    at next (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/route.js:144:13)
    at Route.dispatch (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/route.js:114:3)
    at Layer.handle [as handle_request] (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/layer.js:95:5)
    at /Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/index.js:284:15
    at Function.process_params (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/index.js:346:12)
    at next (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/index.js:280:10)
    at expressInit (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/middleware/init.js:40:5)
    at Layer.handle [as handle_request] (/Users/ahmadkhairolmaulidi/Documents/FullStack/AUTH/auth_demo/node_modules/express/lib/router/layer.js:95:5)

Node.js v20.5.1
[nodemon] app crashed - waiting for file changes before starting...


