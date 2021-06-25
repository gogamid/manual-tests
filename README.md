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

- [ ] [model name view](IOS/Map/Windowed/modelNameView.md )
- [ ] [redirection to navigation](IOS/Map/Windowed/navigationRedirection.md)
- [ ] [info button](IOS/Map/Windowed/infoButton.md )
- [ ] [screen switch to full](IOS/Map/Windowed/fullScreenButton.md )

### Full-Screen

- [ ] [view model name](IOS/Map/Full-Screen/modelNameView.md )
- [ ] [navigation redirection to](IOS/Map/Full-Screen/navigationRedirection.md )
- [ ] [button info](IOS/Map/Full-Screen/infoButton.md )
- [ ] [type change map](IOS/Map/Full-Screen/mapTypes.md )
- [ ] [back to windowed map](IOS/Map/Full-Screen/switchToWindowedMap.md)

## All Machines

- [ ] [refreshing list of machines](IOS/All-Machines/refresh.md)
- [ ] [tap on machine name to open general page](IOS/All-Machines/clickOnMachineName.md)
- [ ] [switching to attention section of machines](IOS/All-Machines/switchToAttentionSection.md)

## Attention

- [ ] [refreshing list of machines](IOS/Attention/refresh.md)
- [ ] [tap on machine name to open general page](IOS/Attention/clickOnMachineName.md)
- [ ] [attention symbols and their quantity correct](IOS/Attention/attentionSymbols.md)
- [ ] [tap on problematic symbol to open relevant page](IOS/Attention/redirectToRespectiveSymbolPage.md)