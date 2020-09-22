# summery
## INTRODUCING HTML5 STORAGE
### So what is HTML5 Storage?
#### Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you
### who to do this???
![store](https://i.ytimg.com/vi/saqXiDYd9dc/hqdefault.jpg)

#### From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object theres two way :
1. ``function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}``

2. ``if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}``

#### the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like ``parseInt()`` or ``parseFloat()`` to coerce your retrieved data into the expected JavaScript datatype.

### Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the ``getItem()`` and ``setItem()`` methods, you can simply use square brackets. For example
``var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);``
### can write it :
``var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;``

### There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).
``interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};``

### Finally, there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).
``interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};``
### hint : If you call key() with an index that is not between 0–(length-1), the function will return null.

