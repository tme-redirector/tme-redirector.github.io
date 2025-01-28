# tme-redirector
This is an HTML page with a script that processes the phone number passed in the URL and redirects the visitor to https://t.me/%

The actions it performs are simple:
1) Strip all irrelevant symbols leaving only `+` and digits
2) Prepend +38 if needed (for Ukraine; you can fork and change the code to yours)
3) Redirect to Telegram with the formatted contact phone number