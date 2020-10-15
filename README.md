<a href="https://github.com/Solido/awesome-flutter">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

# Flutter Interview Questions

This file contains a number of Flutter interview questions. 

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions.


<a href="https://github.com/whatsupcoders/Flutter-Interview-Questions/blob/master/Source.md">
<div style="text-align: center">
    <table>
        <tr>
            <td style="text-align: center">
                    <img src="https://github.com/whatsupcoders/Flutter-Interview-Questions/blob/master/assets/Flutter%20Thumbnail.png" width="800"/>
            </td>            
      </tr>
  </table>
  </div>
</a>


---
Title: Flutter Interview Questions
---

* What is the difference between a `StatelessWidget` and a `StatefulWidget` in Flutter?
As we all know the flutter app consists of widgets only, these are broadly classified into two types: 

Stateless Widget
Stateful Widget
Stateless Widget:
 Stateless widgets are the widgets that don’t change i.e. they are immutable. Its appearance and properties remain unchanged throughout the lifetime of the widget. In simple words, Stateless widgets cannot change their state during the runtime of the app, which means the widgets cannot be redrawn while the app is in action. 
Examples: Icon, IconButton, and Text are examples of stateless widgets. 
Stateful Widget: 
Stateful Widgets are the ones that change its properties during run-time. They are dynamic i.e., they are mutable and can be drawn multiple times within its lifetime. It can change its appearance in response to events triggered by user interactions or when it receives data. 
Examples : Checkbox, Radio Button, Slider, InkWell, Form, and TextField are examples of Stateful widgets. 
* Explain the  Stateful Widget Lifecycle?
  https://www.developerlibs.com/2019/12/flutter-lifecycle-widgets.html
* When do you use the `WidgetsBindingObserver`?
  https://medium.com/@marcoleong.developer/lifecycle-in-flutter-widgetsbindingobserver-2eb782236f8b
* What is Flutter tree shaking?
  https://medium.com/flutter/optimizing-performance-in-flutter-web-apps-with-tree-shaking-and-deferred-loading-535fbe3cd674#:~:text=Tree%20shaking%20by%20default,generated%20by%20the%20dart2js%20compiler.&text=Tree%20shaking%20is%20the%20process,is%20guaranteed%20to%20be%20executed.
* What is a `Spacer` widget?
  https://medium.com/@yubarajpoudel708/spacer-widget-f3bf1e9a4316
* What is the difference between hot restart and hot reload?
  https://flutter.dev/docs/development/tools/hot-reload
* What is an `InheritedWidget`? List some examples.
  https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html
* Why is the `build()` method on `State` and not `StatefulWidget`s?
https://github.com/flutter/flutter/issues/8794
* What is a pubspec file in Dart?
* How is Flutter native?
* What is a `Navigator` and what are `Routes` in Flutter?
* What is a `PageRoute`?
* Explain `async`, `await` and `Future`s.
* How can you update a `ListView` dynamically?
* What is a `Stream`?
* What are keys in Flutter and when should you use it?
* What are `GlobalKeys`?
* When should you use `mainAxisAlignment` and `crossAxisAlignment`?
* When can you use `double.INFINITY`?
* What is `Ticker`, `Tween` and `AnimatedBuilder`?
* What is ephemeral state?
* What is an `AspectRatio` widget used for?
* How would you access `StatefulWidget` properties from its State?
* Is there a suggested limit to the number of `FloatingActionButton`s a screen can have? Give a reason(s) for your answer
* Mention two or more operations that would require you to use or return a Future.
* What is the purpose of a `SafeArea`?
* When to use a `mainAxisSize`?
* SizedBox VS Container?
* List the Visibility widgets in flutter and the differences? 
* Can we use Color and `Decoration` property simultaneously in the Container? Explain
* Inorder for the CrossAxisAlignment.baseline to work what is another property that we need to set?
* when should we use a `resizeToAvoidBottomInset`? 
* What is the difference between 'as','show' and 'hide' in an import statement?
* What is the importance of a `TextEditingController`?
* Why do we use a `Reverse` property in a Listview?
* Difference between a `Modal` and `Persistent` BottomSheet with an example?
* How is an Inherited Widget different from a Provider?
* What is an `UnmodifiableListView`?
* Difference between these operators "?? and ?."
* What is the purpose of `ModalRoute.of()`?
* Difference between a `Navigator.pushNamed` and `Navigator.pushReplacementNamed`?
* Difference between a `Single Instance` and `Scoped Instance` ?


Title: Animation Interview Questions
---

* What is a `vsync`?
* When does the animation reach `completed` or `dismissed` status?
* Difference between `AnimationController and Animation?
* When to use a `SingleTickerProviderStateMixin` and `TickerProviderStateMixin`?
* Define a `TweenAnimation` ? 
* State the importance of a `Ticker` ?
* Why do we need a `mixins` ?

Title: FireStore Interview Questions
---

* Difference between getDocuments() vs snapshots()?

## Getting Involved

  1. [How to Contribute](https://github.com/whatsupcoders/Flutter-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/whatsupcoders/Flutter-Interview-Questions/blob/master/LICENSE.md)

## Contributors:

This project is currently maintained by:

- [@whatsupcoders](https://github.com/whatsupcoders)


Feeling inspired? Check our [Contributing guide](https://github.com/whatsupcoders/Flutter-Interview-Questions/blob/master/CONTRIBUTING.md) to get started!
