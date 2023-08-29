# Insurance Management System

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Features](#features)
- [Security](#security)
- [User Interface](#user-interface)
- [Future Considerations](#future-considerations)
- [How to Use](#how-to-use)

## Description

The Insurance Management System is a Flutter application that helps protect users or people against financial loss. It assists in managing cash flow uncertainty when the capacity to pay at the time of losses is significantly reduced, and it decreases the payment of losses that occur during problems or accidents on insured items.

The system allows users to register and add items to the insurance property list in order to obtain insurance coverage for those items. Users then pay a monthly premium based on the insured items. In the event of an accident or problem with an item, users can submit a request to the system to report the situation, and the insurance system can process an insurance payment to cover the user's loss.

## Technologies

- Frontend: Flutter, Dart
- State Management: BLoC (Business Logic Component)
- Architecture: Domain-Driven Design (DDD)
- Backend: Node.js, Nest.js
- Database: MySQL
- Middleware: Multer, JWT (JSON Web Tokens)

## Features

- User registration and personal profile creation
- Adding items to the insurance property list for coverage
- Removing and updating items in the insurance property list
- Viewing and reading items in the system
- Requesting insurance payment for accidents or problems with insured items
- Modifying and removing insurance payment requests
- Admin approval of insurance purchases
- Monthly payment notifications
- Testing functionalities: unit testing, widget testing, integration testing

## Security

The application ensures security through authentication mechanisms, including username and password login. Verification methods are implemented to validate the legality of the provided items.

## User Interface

The Flutter application's user interface is designed to be user-friendly and intuitive. It features a clean and modern layout that allows easy navigation through the various features. The application utilizes appealing colors, icons, and graphics to provide a visually appealing and engaging experience for users.

## Future Considerations

In future iterations, the system can be extended to cover other utilities beyond homes, such as cars, etc.

## How to Use

1. Clone this repository to your local machine.
1. Open the backend directory (`cd backend`), set the database URL in the `.env` file, and run `npm install`. Then start the backend server using `yarn start:dev`.
1. Open the frontend directory (`cd frontend`), run `flutter pub get`, and start the Flutter application using `flutter start`.

Ensure that you have the necessary dependencies and configurations set up to run the application successfully.

Please note that this README provides an overview of the system and its functionalities. For detailed instructions and documentation, refer to the codebase and relevant files within the repository.

| No |   Group Name     |     role                          |
| -- | ---------------- | --------------------------------- |
| 1  |  Fasika Fikadu   | Backend Developer and Integration | 
| 2  | Deribew Shemelis | Backend Developer                 |
| 3  |  Rahel Solomon   | Frontend Developer                | 
| 4  |  Enyew Anberbir  | Frontend Developer and Integration|
| 5  |  Kaleab Tibebu   | Frontend Developer                |

