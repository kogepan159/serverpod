A library for Dart developers.

Created from templates made available by Stagehand under a BSD-style
[license](https://github.com/dart-lang/stagehand/blob/master/LICENSE).

## Usage

A simple usage example:

```dart
import 'package:dart_test_server_client/dart_test_server_client.dart';

main() {
  var awesome = new Awesome();
}
```

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: http://example.com/issues/replaceme

Start your Serverpod server by running:
    cd dart_test_server/dart_test_server_server
    serverpod run

You can also start Serverpod manually by running:
    cd dart_test_server/dart_test_server_server
    docker-compose up --build --detach
    dart bin/main.dart