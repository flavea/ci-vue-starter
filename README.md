# CodeIgniter - Vue.js Starter
> Initial packages to create SPA website with CodeIgniter dan Vue.js

## Detail
1. CodeIgniter `3.1.9` with library `REST_Controller`
2. Vue.js `2.5.17` with webpack templateDibutuhkan
3. Node.js (> 6.0.0) and npm (> 3.0.0)

## Configuration
After `clone` or `download`, you need to install node modules.

1. Install `node_modules`
```
# ci-vue-starter/client

npm install
```

## Cara Menjalankan

1. Development
In this step, we are developing the vue app, codeigniter is not running or used yet. To run this, use the following command (Administrator access might be needed).
```
# ci-vue-starter/client

npm run dev
```

2. Production
After developing the vue app, we can build the app and then run codeigniter

```
# ci-vue-starter/client

npm run build
```

this will generate `dist` folder and `application/views/index.php` file. To run, visit: `{host}/ci-vue-starter/`

## Other
1. All of above commands are run on `CMD` (Windows) or `terminal` on Linux/Mac
2. Contoller `Books` is just an example of REST Controller.
3. In Production, `base` construction might be needed on Routing in Vue for `localhost`. [Reference](https://router.vuejs.org/api/#base)

## Credits
- [Vue.js](https://vuejs.org)
- [CodeIgniter REST Server](https://github.com/chriskacerguis/codeigniter-restserver)

## Lisensi
[MIT](https://github.com/andriannus/ci-vue-starter/blob/master/LICENSE)