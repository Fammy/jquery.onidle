#jquery.onidle

## What is it?
jquery.onidle is a jQuery plugin that allows you to fun code when a series of events stop firing.
For example, when a user stops typing in or leaves a textbox, fire off validation.

## How to use it?
1. Include [jquery.onidle-1.0.0.min.js](jquery.onidle/blob/master/jquery.onidle-1.0.0.min.js) in your project. Bundling encouraged!
2. Call the following code:
```javascript
$(':text').onidle('focusout blur keyup change', 250, function() {
    // Only called once when events haven't fired for 250 milliseconds
});
```

## Samples?
[Samples](jquery.onidle/blob/master/samples.html)!