# Expo Managed Workflow: Accessing Native Modules

This repository demonstrates a common error in Expo's managed workflow: attempting to directly access or modify native modules.  Expo's managed workflow is designed for simplicity and ease of development, but it restricts direct access to native modules for security and maintainability reasons. This example shows how the error manifests and how to work around it using Expo's provided APIs.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Observe the error in the console (if applicable). 

## Solution

Instead of directly interacting with native modules, you should use Expo's APIs or libraries which provides access to the relevant functionalities.