## What is this repository for? ###

Starter for Spring Boot 2.0 Kotlin applications. 

Contains:
- Gradle multi-module project
- Spring Boot 2.0 setup
- CircleCI 2.0 basic setup
- Tests configuration with MongoDb
- JUnit 5 test examples
- Logging configuration
- Gradle profiles configuration
- Docker compose

Feel free to use for your own projects.

## To run the application with dev profile
`./gradlew bootRun -Pdev`

## To run the tests
`./gradlew test`

## Example call
```
curl http://localhost:8080/test?token=eyJhbGciOiJIUzUxMiJ9.eyJqdGkiOiJhNjQyMjk0NC01ZDFkLTQxODItOGE2ZS1mZGM0NjEwYzhlNTYiLCJzdWIiOiJleGFtcGxlIiwiaWF0IjoxNTIzNzQyNzcxLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgwODAvIiwiZW1haWwiOiJleGFtcGxlQHl1bmlrb3YuY29tIiwicm9sZXMiOlsidXNlciJdfQ.L9eQqG8ggxbZDLxDFAbGND7uIv4DzF7LjSfvi0iq6HT3NshzKed89VQwRU-r_hcd9Tl6644lQCZcilllg2WS0A
```

## Contribution guidelines ###

* Submit pull requests for any changes on the repository. Assign @yyunikov for review.

## LICENSE
MIT License

Copyright (c) 2018 Yuriy Yunikov

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
