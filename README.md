# burp-json-parameter

## Author

Written by Anthony Marquez ([@BoogeyMarquez](https://twitter.com/boogeymarquez))

## Description


## Building Instructions

Make sure you have `gradle` installed

```bash
brew install gradle
```

Navigate to base of directory, should see `build.gradle` file.

```bash
gradle build
```

You should have a `burp-json-parameter-vXX.jar` file in the `build/lib/` folder.  Load it within Burp and you are good to go.

## Loading Instructions
Launch BurpSuite, go to the Extender tab and then open the Extensions tab and click on "Add". In the dialog window,
select "java" as Extension Type and select the burp-json-parameter-vXX.jar. For further details about BurpSuite extensions, refer
to their [documentation](https://portswigger.net/burp/help/extender.html#loading).
