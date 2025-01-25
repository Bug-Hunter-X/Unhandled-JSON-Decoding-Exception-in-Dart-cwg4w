# Unhandled JSON Decoding Exception in Dart

This repository demonstrates a common error in Dart applications: improper handling of exceptions during JSON decoding using the `jsonDecode` function from the `dart:convert` library.

The `bug.dart` file contains code that attempts to fetch data from an API, parse the JSON response, and handle potential errors. However, it doesn't explicitly handle the `FormatException` that can be thrown if the response is not valid JSON.

The `bugSolution.dart` file provides a corrected version of the code that properly handles the `FormatException`, preventing the application from crashing and providing more informative error messages.

This example highlights the importance of robust error handling in asynchronous operations to ensure application stability and provide better user experiences.