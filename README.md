![AFeedly](http://i.imgur.com/HUyU7Bo.png)

#iOS Feedly API Client

Feedly API Client framework lets you authenticate by OAuth and connect Feedly APIs by returning Objective-C models. 

**Under heavily development**

##Installation

First add pod to your `Podfile` ;

```bash
pod 'AFeedly', '~> 0.0'
```

and install your pods by running command

```bash
pod install
```

Initialize your client once with your Feedly Application ID and Secret obtained from Feedly 

```obj-c
    [[AFLClient sharedClient] initWithApplicationId:@"yourApplicationIdHere" andSecret:@"yourSecretCodeHere"];
```

you may also be running on feedly sandbox enviroment. For detailed information please visit [http://developer.feedly.com/v3/sandbox/](http://developer.feedly.com/v3/sandbox/)

Additionally you can use experimental `sync with server` feature by adding:

```obj-c
[[AFLClient sharedClient] setIsSyncWithServer:YES];
```

##Usage

--TODO--

##License
This code is distributed under the terms and conditions of the MIT license.

##Author
Alkim Gozen 
[@alkimake](https://twitter.com/alkimake)
