# flutter_login

Complete Guide here: https://www.back4app.com/docs/flutter/parse-sdk/users/flutter-login

## Introduction

This is a project starter kit which uses the Flutter plugin for Parse Server to perform login/logout using ParseUser class for your Flutter App.

## Prerequisites

- Flutter version 2.2.x or later
- Android Studio or VS Code installed (with Plugins Dart and Flutter)
- A Flutter app created and connected to Back4app.

## Context

At the core of many apps, user accounts have a notion that lets users securely access their information. Parse provides a specialized User class that automatically handles much of the functionality required for user account management. With this class, you’ll be able to add user account functionality to your app.

ParseUser is a subclass of the ParseObject, and has the same features. All the methods that are on ParseObject also exist in ParseUser. The difference is that ParseUser has some special additions specific to user accounts. ParseUser has several properties that set it apart from ParseObject:

username: The username for the user (required).
password: The password for the user (required on signup).
email: The email address for the user (optional).
You are free to use an email address as the username. Ask your users to enter their email, but fill it in the username property — ParseUser will work as normal.

In this template we use the Flutter plugin for Parse Server to manage users using ParseUser class creating a user registration and login feature for your Flutter App.

## Getting Started

This project is a starting point for a Flutter SignUp/Login application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
