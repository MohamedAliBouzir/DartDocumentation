# Dart
---
###### Description
<p>
 is a programming language designed for client development, such as for the web and mobile apps. It is developed by Google and can also be used to build server and desktop applications.
</p>
<p>
Dart is an object-oriented, class-based, garbage-collected language with C-style syntax. Dart can compile to either native code or JavaScript. It supports interfaces, mixins, abstract classes, reified generics, and type inference.
</p>
---
# Let us break the glass ceiling

![](https://dart.dev/assets/img/shared/dart/logo+text/horizontal/white.svg)


![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![IOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![GIT](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![VSCode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![VS](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)
---
<p>Welcome to the Dart easy documentation!</p>

---
# Dart Samples :

#### Our First Test :

if you want to try your code here's the link :
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)]()

<p>Every app has a main() function. To display text on the console, you can use the top-level print() function:</p>

```Dart
    void main() {
  print('Hello, World!');
    }
```

###### Variables
```Dart
    var name = 'myName';
    Object type = 'camel Code';
    // type will be a String
    // since we're Learning Dart to develop flutter apps so we must know that changing
    //variable types during execution will rise an error
    //so that's why dart has an other Object type which is dynamic
    dynamic whatEver = 'you can store what ever you want';
```

<p>
as you noticed Dart is a combo of so !
</p>

![Js](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)

<p>
it's not that weird anyways
</p>

let's Try it :
```Dart
dynamic x = 'hi';
print(x); // that will show us hi
x= 20;
print(x); // that will show us 20

// if we used Object or specified the type we won't be able to change it
```
##### assert:
assert main role is to assure samthing
for exemple 
`assert(x<100);` to make sure that x < 100
assert return type is boolean
assert is only used in development phase in purpose of testing 
but in production all asserts will be ignored
we can manipulate assert too :
```Dart
assert(condition /*if true nothing happen and we'll continue*/, MSG /*will be written in console if condition is false*/);
```

##### Functions :
```Dart
//let's create a Function
String sayHello (){
    return 'hello';
}
void main(){
    String hi= sayHello();
    print(hi); //affiche hello
}
```
##### Errow Function :
if we don't have a logic in our functions and we have no input methodes to call then we can create an errow function
    for an exemple :
```Dart
    String sayHello(/*INPUT methodes*/){
        //logic
        return 'hello';
    }
```
then we can easily write it this way :

```Dart
    String sayHello() => 'hello';
```

##### Classes :
```Dart
    class User{
        String x;
        int y;
        /* methodes() */
    }
    
    void main(){
        User x= User();
    }
```
#### extends
```Dart
    class User{
        String name;
        int? age;
        //default constructor:
        User(){
            this.name='Unknowned';
            this.age=null;
        }
        //constructor:
        User(String x,int y){
            this.name=x;
            this.age=y;
        }
    }
    class SuperUser extends User{
        SuperUser():super();
        SuperUser(String,int):super(name,age);
        void publish(){
            print('am a SuperUser');
        }
    }
    void main(){
        User flen = User('flen',10);
        SuperUser falten = User('falten',20);
        SuperUser foulen = SuperUser('foulen',30);
        foulen.publish(); // consol will show am a superUser;
        falten.publish(); // consol will show am a superUser;
        flen.publish(); // consol will show an error
    }
```
this code block will show you a hell of errors so how to solve it ?
```Dart
    class User{
        late String name;
        late int age;
        //constructor:
        User(String name,int age){
            this.name=name;
            this.age=age;
        }
    }
    class SuperUser extends User{
        SuperUser(String,int):super(String,int);
        void publish(){
            print('am a SuperUser');
        }
    }
    void main(){
        User flen = User('flen',10);
        SuperUser foulen = SuperUser('foulen',30);
        foulen.publish();
    }
```

### Setting Environment For Mobile Development

#### Your Device :

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

<p>
Activate The Developer Mode on your Android
</p>

##### Steps :

- Go to "Settings", then tap "About device" or "About phone".

![](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/images/1-how-do-i-turn-on-the-developer-options-menu.png?$ORIGIN_PNG$)

- Scroll down, then tap "Build number" seven times.

Depending on your device and operating system, you may need to tap "Software information", then tap "Build number" seven times.

![](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/images/2-how-do-i-turn-on-the-developer-options-menu.png?$ORIGIN_PNG$)
![](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/images/3-how-do-i-turn-on-the-developer-options-menu.png?$ORIGIN_PNG$)

- Enter your pattern, PIN or password to enable the Developer options menu.


- The "Developer options" menu will now appear in your Settings menu.

Depending on your device, it may appear under Settings > General > Developer options.

![](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/images/4-how-do-i-turn-on-the-developer-options-menu.png?$ORIGIN_PNG$)

- To disable the Developer options menu, tap the switch.

![](https://images.samsung.com/is/image/samsung/assets/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/images/5-how-do-i-turn-on-the-developer-options-menu.gif?$ORIGIN_GIF$)

#### Your Device :

![IOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)

<p>
Activate The Developer Mode on your Iphone
</p>

##### Steps :
- Open Xcode on your MAC.

<p>
If you are opening the program for the first time, you should accept the terms of the license agreement. This will allow you to install the software components and finalize the installation of Xcode.  
</p>

![](https://www.wikihow.com/images/thumb/9/9b/Enable-Developer-Mode-on-an-iPhone-Step-9.jpg/v4-728px-Enable-Developer-Mode-on-an-iPhone-Step-9.jpg.webp)

- Connect your iPhone to Mac.

<p>
Use your USB cable to connect your phone to the computer. 
</p>

![](https://www.wikihow.com/images/thumb/2/2f/Enable-Developer-Mode-on-an-iPhone-Step-10.jpg/v4-728px-Enable-Developer-Mode-on-an-iPhone-Step-10.jpg.webp)

- Go to "Settings" in your Iphone

<p>
It's the gray gear icon on your iPhone's home screen.
</p>

![](https://www.wikihow.com/images/thumb/3/30/Enable-Developer-Mode-on-an-iPhone-Step-11.jpg/v4-728px-Enable-Developer-Mode-on-an-iPhone-Step-11.jpg.webp)

- Scroll down, then tap "Developer"

<p>
When you connect your phone to your computer while running Xcode, you will see this option will automatically show up in your iPhone settings. The fact that you see this feature in your phone's settings means that you have enabled developer mode on your iPhone. You can now build apps, check registries, and play with other developer tweaks on your device.
</p>

![](https://www.wikihow.com/images/thumb/5/5c/Enable-Developer-Mode-on-an-iPhone-Step-12.jpg/v4-728px-Enable-Developer-Mode-on-an-iPhone-Step-12.jpg.webp)

