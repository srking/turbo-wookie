# Crash when using `MPTweakBind` in conjunction with address sanitizer

This sample app will crash on launch when address sanitizer is enabled.

To enable address sanitizer:

 1. Open 'Product' ... 'Scheme' ... 'Edit scheme...'.
 2. Under 'Runtime Sanitization', ensure that 'Enable Address Sanitizer' is checked.

The app will now crash when launched.
