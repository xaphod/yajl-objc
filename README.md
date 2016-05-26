# Modified by Tim (Xaphod)

Added more parameters in YAJLDocument's callbacks, so that you know the stack-count. In other words, so you can see when a document is finished if you are processing an unending-stream, like when you're using Twitter's stream APIs in iOS.

# YAJL Framework

The YAJL framework is an Objective-C framework for the [YAJL](http://lloyd.github.com/yajl/) SAX-style JSON parser.

## Features

- Stream parsing, comments in JSON, better error messages.
- Parse directly from NSString or NSData.
- Generate JSON from default or custom types.
- Properly handles large numeric types.
- Document style parser.
- Error by exception or out error.

## Links

- The online [API documentation](http://gabriel.github.com/yajl-objc/).
