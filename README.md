# Chat widget - version 2

*Inspired from [ts.chat](https://github.com/TheSmiths-Widgets/ts.chat).*

A small chat view (list of messages and text area to send new ones).

## How to install

Clone this repo into your ```app/widget``` folder.

## Dependencies

None :)

## How to use it

In your view:

```xml
<Alloy>
    <View class="container">
        ...
        <View id="chatWrapper">
            <Widget id="chat" src="ts.chat2"></Widget>
        </View>
        ...
    </View>
</Alloy>
```

In your controller:

```javascript
// TODO
});
```

Bonus, in your tss file:

```css
".container" : {
    width: Ti.UI.FILL,
    height: Ti.UI.FILL
}

"#chatWrapper" : {
    height: Ti.UI.FILL,
    width: Ti.UI.FILL
}
```

## TODO

- Add some customization
    - Allow to add more buttons at the bottom (like in the Hangout app from Google)
    - Allow to change the send button (image or text)
    - Enable i18n
- Each button would raise its own event when pressed
- Generate the documentation into ```gh-pages```
- Create a sample app into ```sample```

[![wearesmiths](http://wearesmiths.com/media/logoGitHub.png)](http://wearesmiths.com)