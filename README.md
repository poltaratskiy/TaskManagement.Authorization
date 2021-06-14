# TaskManagement.Authorization

This project provides API for requesting token with Authorization service, verify and allow or deny access to resources.

Algoright of this library is:
1. If user is not authenticated: go to auth service, authenticate and return token, put it in cookies;
2. Verify token, return flag depending on access.