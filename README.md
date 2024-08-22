# freeipapi
JavaScript library for freeipapi.com
# main
```js
async function main(){
    const {freeipapi} = require('./freeipapi');
    const ipapi= new freeipapi();
    let req=await ipapi.my_ip()
    console.log(req)
}
main()
```
