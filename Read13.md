# The past , Present , & Future OF Local Storage For Web Applications,


Hisotrically , in web applications ccokeies were invented to be used for persistant local storage of small amounts of data :

- Cookies are include with every HTTP request, so slowing down the web application by sneding data over and over.

- Cookies are include with every HTTP request, so sending data encrypted over the internet

- Cookies were limiteed to about 4 KB. 

**Microsoft** Invented **DHTML Behaviors** and include it in internet explorer. One of these behaviors was **User Data** that allow user to to store up to 64 KB.

**Adobe** introduced **Flash Cookies** in 2002, that can store up to 100 KB of data per domain.


## HTML 5 Storage

It is named as web storage , Certain browser also refer to it as “Local Storage” or “DOM Storage.”

### Check for HTML Storage 

function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}


### Using HTML5 Storage 

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

### Tracking Changes In HTML5 Storage 

if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};

* **Storageevent Object**

- key	(string) : the named key that was added, removed, or modified.
- oldValue (any) : the previous value (now overwritten), or null if a new item was added.
- newValue (any) : the new value, or null if an item was removed.
- url*	(string) : the page which called a method that triggered this change.