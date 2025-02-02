# Snapshot report for `test/config/loader.js`

The actual snapshot is saved in `loader.js.snap`.

Generated by [AVA](https://avajs.dev).

## throws an error if both configs are present

> error message

    'Conflicting configuration in ava.config.js and package.json'

## throws if configFile option is not in the same directory as the package.json file

> error message

    'Config files must be located next to the package.json file'

## throws if configFile option has an unsupported extension

> error message

    'Config files must have .js, .cjs or .mjs extensions'

## does not support require() inside config.js files

> error message

    'Error loading ava.config.js: require is not defined'

## throws an error if a config factory returns a promise

> error message

    'ava.config.js exported a promise or an asynchronous factory function. You must enable the ’asyncConfigurationLoading’ experiment for this to work.'

## throws an error if a config exports a promise

> error message

    'ava.config.js must export a plain object or factory function'

## throws an error if a config factory does not return a plain object

> error message

    'Factory method exported by ava.config.js must return a plain object'

## throws an error if a config does not export a plain object

> error message

    'ava.config.js must export a plain object or factory function'

## throws an error if a .js config file has no default export

> error message

    'ava.config.js must have a default export, using ES module syntax'

## throws an error if a config file contains `ava` property

> error message

    'Encountered ’ava’ property in ava.config.js; avoid wrapping the configuration'

## throws an error if a config file contains a non-object `nonSemVerExperiments` property

> error message

    'nonSemVerExperiments from ava.config.js must be an object'

## throws an error if a config file enables an unsupported experiment

> error message

    'nonSemVerExperiments.unsupported from ava.config.js is not a supported experiment'

## throws an error if both .js and .cjs configs are present

> error message

    'Conflicting configuration in ava.config.js and ava.config.cjs'

## refuses to load .mjs config

> error message

    'AVA cannot yet load ava.config.mjs files'
