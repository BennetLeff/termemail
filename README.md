# Termemail
termemail is a Python script that lets you send emails from your terminal.
# Usage
termemail comes with a built in help command (-h) but it's usage is also described as follows:

```
./main.py -f example-sender@gmail.com 
          -t example-recipient@gmail.com 
          -s Test! 
          -b "This email was sent from my commandline!"
```
Where `f` is the sender's email address, `-t` is the recipient's email address, `-s` is the subject and `-b` is the email body. 
Both `-s` and `-b` are optional. Currently attachments are not supported however I don't believe it would be difficult to add them. 
# License
MIT License

Copyright (c) 2016 Bennet Leff

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
