# Sample API Server

## Introduction

We are going to write a minimal API server for reviewing concepts like JWT, Monitoring, HTTP Server, etc. with Golang.

## Definition

Your API server must has authentication, and users must use the `/login` endpoint to get a JWT token.
Just like kubernetes this token contains the user information but permissions are stored elsewhere
and are checked in each request.
