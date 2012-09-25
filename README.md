discontinue
===========

A jquery plugin to handle continue ajax requests and provides a simple and powerful 'window' event binding.

keepon
---
keep on ask something to the given `url`, with a `delaty` of 2500 ms between the completed request and the following one:

     $().discontinue.keepon({
        url:"/url/to/bis",
        delay:2500
     });
     


Listen to every event bubbled: 

    $().discontinue.verbose();
