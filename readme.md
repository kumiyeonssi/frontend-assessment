Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.

code will render b, a & a properly because it is correct. but using ++ will render NaN meaning not a number but in lowercase because of the function used.
if we were to render this individually, it should be b, a, nan, a