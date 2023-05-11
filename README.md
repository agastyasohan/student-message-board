# Student Message Board - Group 38

## Code Organization

The code is organized into three folders: **backend**, **frontend** and **database**.

student-message-board/
├── backend/
│   ├── controllers/
│   │   ├── authentication_controller.js
│   │   ├── message_controller.js
│   │   ├── user_controller.js
│   │   └── ...
│   ├── models/
│   │   ├── message.js
│   │   ├── user.js
│   │   └── ...
│   ├── routes/
│   │   ├── authentication_routes.js
│   │   ├── message_routes.js
│   │   ├── user_routes.js
│   │   └── ...
│   ├── middlewares/
│   │   ├── authentication_middleware.js
│   │   └── ...
│   ├── utils/
│   │   ├── authentication_utils.js
│   │   └── ...
│   └── app.js
├── frontend/
│   ├── lib/
│   │   ├── main.dart
│   │   ├── screens/
│   │   │   ├── home_screen.dart
│   │   │   ├── login_page.dart
│   │   │   ├── signup_page.dart
│   │   │   ├── user_profile.dart
│   │   │   ├── post_list_screen.dart
│   │   │   ├── post_details_screen.dart
│   │   │   └── ...
│   │   ├── models/
│   │   │   ├── user.dart
│   │   │   ├── post.dart
│   │   │   └── ...
│   │   ├── app_state.dart
│   │   ├── widget_test.dart
│   │   └── ...
│   ├── assets/
│   │   ├── css/
│   │   ├── js/
│   │   └── ...
│   ├── pubspec.yaml
│   └── ...
└── database/
    ├── migrations/
    │   ├── 20210512_create_users_table.sql
    │   ├── 20210515_create_messages_table.sql
    │   └── ...
    ├── seeds/
    │   ├── 20210512_seed_users.sql
    │   ├── 20210515_seed_messages.sql
    │   └── ...
    └── ...

## Setup

There are two stages to setting up the application to run, given that the database is already created and populated.

### backend

In a terminal window, type the following from the root directory:

```
$ cd backend
$ npm i
$ npm run server
```

This will start the Node.js server to handle database requests.

### frontend

1. In Chrome/Chromium based browsers, install the [Dart Debug Extension](https://chrome.google.com/webstore/detail/dart-debug-extension/eljbmlghnomdjgdjmbdekegdkbabckhm).
2. In VS Code, install the [Flutter extension](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter). 
3. Open **frontend/lib/main.dart** in VS Code and run in debug mode on a webserver. This will render the web application on the browser.
4. Click the Dart Debug icon when asked, to complete the rendering and view the application.
