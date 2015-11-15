# [fit] Learn Once Write Everywhere

---

# C for Clojure

---

# C for Complex

---

# JK

# [fit] Clojure is awesome!

---

# Github Stars

ClojureScript: 5261
Clojure: 4696

---

# 2007

![inline](./images/iphone_1_release.jpg)

[^1]: http://www.technologytell.com/apple/80187/steve-jobs-wanted-Wi-Fi-Spectrum-for-Apples-first-iPhone/

---

# 2008

![inline](./images/app_store.png)

[^1]: https://cdn2.iconfinder.com/data/icons/ios7-inspired-mac-icon-set/1024/_app_store_5122x.png

---

# Objective-C

```objectivec
#import <Foundation/Foundation.h>

int main (int argc, const char * argv[])
{
  NSAutoreleasePool *pool = [[NSAutoreleasePool alloc] init];
  NSLog (@"Hello, World!");
  [pool drain];
  return 0;
}
```

---

# Xcode

![inline](./images/xcode.png)

[^1]: http://313e5987718b346aaf83-f5e825270f29a84f7881423410384342.r78.cf1.rackcdn.com/1411058188-xcode-6-header.png

---

# Mobile Version

![inline](./images/nytimes-mobile.png)

[^1]: https://abmmediablog.files.wordpress.com/2013/06/nytimes-mobile.png

---

# PhoneGap

![inline](./images/phonegap.png)

[^1]: http://phonegap.com/css/images/graphic_build_bot.png

---

# RubyMotion

![inline](./images/ruby-motion.png)

[^1]: http://i.imgur.com/mndCd.png

---

# React Native

![inline](./images/react-native.png)

[^1]: https://fbcdn-dragon-a.akamaihd.net/hphotos-ak-xaf1/t39.2365-6/11057107_805781416175147_684201729_n.png

---

# React

A JavaScript library for building user interfaces

---

# React

Declaritive

---

# React

JSX Components

---

# React

```js
var CommentBox = React.createClass({
  render: function() {
    return (
      <div className="commentBox">Hello, world! I am a CommentBox. </div>
    );
  }
});
```

---

# React Native

---

# React Native

Hybrid Apps

---

# React Native

Tooling

---

![inline](./images/React-Native-Flow.png)

---

# React Native

```js
var React = require('react-native');
var { Image, StyleSheet, Text, View } = React;

var ReactNative = React.createClass({
    render: function() {
	return (
	    <View style={styles.row}>
	    <Image
	    source={{uri: 'http://facebook.github.io/react/img/logo_og.png'}}
		    style={styles.image}
			   />
	    <Text style={styles.title}> </Text>
	    </View>
	);
    });
```

---

# React Native

```js
var styles = StyleSheet.create({
    image: { width: 40, height: 40, marginRight: 10 },
    text: { flex: 1, justifyContent: 'center'},
});
```

---

# ClojureScript

---

# om

```clj
(defn widget [data owner]
  (reify
    om/IRender
    (render [this]
      (dom/h1 nil (:text data)))))
```

---

# om.next

```clj
(defn widget [data owner]
  (reify
    om/IRender
    (render [this]
      (navigator-ios {:style {:flex 1}
 :initialRoute {:component (om/build search owner) :title "Search"}}))))
```

---

# reagent

```clj
(def row-comp
  (r/reactify-component
    (fn[props]
      (let [row (props :row)]
        (print props)
          [touchable-highlight {:style {:border-top-width 1 :border-color "#000"} :on-press #(alert "list" (str @row))} [text @row]]))))
```

---

# Ambly

A ClojureScript REPL into iOS JavaScriptCore.

---

# Ambly Demo

---

# Natal

Bootstrap ClojureScript-based React Native apps

---

# Natal Demo

---

#  Workflow

---

# Downsides

---

# Dependencies

LOTS

---

# New Tech

---

# Resources

* http://cljsrn.org
* https://facebook.github.io/react-native/
* Me

---

# Pair With Me

* Twitter: @jearvon
* Email: j.dharrie@gmail.com
* Podcast: http://turing.cool
