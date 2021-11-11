# ` npm i reuse-alerts `

> Use this package for extra colors and symbols for your alert messages

## Usage

>const alert = require('cli-alert')

// You can choose between SUCCESS, INFO, WARNING, ERROR

alert()
// Prints: ✖  ERROR  You forgot to do something

alert({ type: 'success', msg: 'Completed!', name: 'Hey' })
// Prints:  ✔  Hey  Completed!

alert({ type: 'info', msg: 'This worked' })
// Prints:  ℹ  INFO  This worked

alert({ type: 'warning', msg: "You didn't add something!" })
// Prints:  ⚠  WARNING  You didn't add something!

alert({ type: 'error', msg: 'Something went wrong' })
// Prints:  ✖  ERROR  Something went wrong 

