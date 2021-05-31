# Checklist for Facebook functions Sign Up, Log In, Forgot Paswword

## Sign up 
1. **Smoke test** — valid input.
2. **Critical path** — registration without one of parameters (e-mail/telephone number).
3. **Extended** —  invalid input, limits for password, empty fields. Work with functionality in different states: close page with entered data.

## Log in
1. **Smoke test** — valid input, correct pairs "email-password", "telephone number-password".
2. **Critical path** — pairs "correct login-incorrect password" and "incorrect login-correct password".
3. **Extended** —  invalid input, empty fields.

## Forgot password
1. **Smoke test** — valid input.
2. **Critical path** — try to log in with an old password, after a new one was generated.
3. **Extended** —  try a new password, which was a password in this account. Invalid input, empty fields.
