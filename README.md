# tinytotp

Basic, TinyGo-compatible remix of https://github.com/pquerna/otp

For my use case, the original library resulted in panic from insufficient stack
size, so I extracted just the parts I needed into this library. This library is
only concerned with generating and validating TOTP codes. For features such as
URL and QR code creation, please see the original library mentioned above.
