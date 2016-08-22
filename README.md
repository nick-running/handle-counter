###Simple,lightweight and easy to use jQuery handle count plugin, it can minus number, plus number, edit number with validation.
####params
* minimum //the minimum number**(Number)**
* maximize //the maximize number**(Number)**
* writable //is the input can write manually**(String|Number|Boolean)**
* onChange //when the counter is changing**(function)**
* onMinimum //when the counter reached minimum number**(function)**
* onMaximize //when the counter reached maximize number**(function)**

####Example
```
var options = {
    minimum: 1,
    maximize: 10,
    onChange: valChanged,
    onMinimum: function(num) {
        console.log('reached minimum: '+num)
    },
    onMaximize: function(num) {
        console.log('reached maximize'+num)
    }
}
$('#handleCounter').handleCounter(options)
function valChanged(num){
        console.log('current number is '+num)
}
```
</code>

