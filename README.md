# personium-ex-mailsender

## About

This is a [Personium](http://personium.io)'s Engine extension for sending SMTP emails.

## Usage

```
    var mailObj = {
        "to":[{"name":"John Doe","address":"john.doe@example.com"}],
        "from": {
            "address" : "admin@example.com",
            "name"    : "Admin Office"
        },
        "reply-to": {
            "address" : "admin@example.com",
            "name"    : "Admin Office"
        },
        "envelope-from": "admin@example.com",
        "subject": "Greetings",
        "text": "Hello\n Thank you!",
        "charset": "utf-8"
    };
    var sender = new dc.extension.MailSender();
    sender.send(mailObj);
```

## License

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Copyright 2016 FUJITSU LIMITED
```
