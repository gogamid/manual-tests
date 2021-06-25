# Testing IOS and Android app

## Description

Manual tests of our natively developed apps are performed for Android via Firebase and for iOS via TestFlight. Release candidates of the versions to be published are provided via these tools and must be tested at short notice.

## Motivation

In order to be able to guarantee a structured and reliable manual test execution, we will create a documentation of the tests. These will be carried out for release candidates and only if they are successful will the related release be published.
The tests must be written in a way that allows people outside the industry but technically skilled to perform these tests.
This test documentation will later be used to build automatic tests, e.g. via tools like "Appium".

## Checklist

<hr />

# IOS

## Map

### Windowed

- [ ] [model name view](./IOS/Map/Windowed/modelNameView.md )
- [ ] redirection to navigation
- [ ] info button
- [ ] switch to full screen

### Full-Screen

- [ ] model name view
- [ ] redirection to navigation
- [ ] info button
- [ ] change map type
- [ ] back to windowed map


