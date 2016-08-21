###Simple,lightweight and easy to use jQuery handle count plugin, it can minus num, plus num, edit num with validation.
####params
* minimum //the minimum number(Number)
* maximize //the maximize number(Number)
* writable //is the input can write manually(String|Number|Boolean)
* onChange //when the counter is changing(function)
* onMinimum //when the counter reached minimum number(function)
* onMaximize //when the counter reached maximize number(function)

####Example
```
var options = {
    minimum: 1,
    maximize: 10,
    onChange: valChanged,
    onMinimum: function(e) {
        console.log('reached minimum: '+e)
    },
    onMaximize: function(e) {
        console.log('reached maximize'+e)
    }
}
```
$('#handleCounter').handleCounter(options)
</code>

