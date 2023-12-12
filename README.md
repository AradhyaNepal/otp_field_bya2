## What extra it have?
It have better:
* Select box with old OTP and type new without pressing backspace.
* If you want backspace, do not loose your "focus" to previous box.
* Going to next.
* Easily paste OTP into the text field
* And overall better user experience.

Your user will love it if you implement it, because of user experience it provide while typing OTP.

## Credit
This package is made by modifying this package [Original Package](https://pub.dev/packages/otp_text_field).

View original package documentation for more reference.

[Youtube](https://www.youtube.com/watch?v=pavccVhnSg4)

## Example
```
    final OtpFieldController controller =
    OtpFieldController(); // From original otp_text_field package
    String _otp = "";
```

```
OTPFieldByA2(
      length: 6,
      controller: controller,
      fieldStyle: FieldStyle.box,
      outlineBorderRadius: 6,
      fieldWidth: 40,
      onChanged: (otpValue) {
        setState(() {
          _otp = otpValue;
        });
      },
      style: TextStyle(
        fontSize: 18,
        color: Colors.black,
        fontWeight: FontWeight.w600,
      ),
),
```



## Note
The package is still on development phase, so other more features which increases UX comming soon.
After that I will update the documentation too.
