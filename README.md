## bootstrap-chat—Facebook-like chat UI

Some basic HTML, CSS, and JavaScript to create a Facebook-like chat UI.

```javascript
var window = chat.createWindow({title: 'Ryan'});

window.addMessage({name: 'Ryan', message: 'Hello, buddy!'});

chitchat.on('message', function (from, message) {
    chat.findWindow({name: from}).addMessage({name: from, message: message});
});
```

