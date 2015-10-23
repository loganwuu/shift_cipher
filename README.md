# Writing Custom Modules

##### A Drupal website for custom module development code review at Epicodus. (10/23/15)

#### By Logan Wu

## Specs
* The shift value is the number of places to shift each letter over.
* If the shift direction is "right" then you will add the shift value. For example: "a" with a shift value of 1 and a direction of right would become "b". A shift direction of "left" with a shift value of 1 would turn "b" into "a".
* If the shift amount takes you over the bounds of the alphabet then cycle back to the beginning. For example: a shift value of 3 with the direction of right would turn "z" into "c".
* The shift value must be a positive integer
* The shift direction must be either "left" or "right".
* The only special characters that should be allowed in your input phrase are spaces and punctuation.
* Any spaces or punctuation in the input phrase should be ignored and reproduced in the final result without being shifted.
* The final result should be in all lowercase.

Login Info
----------
**Database name:** ```shift_cipher```
username: ```treehouse```
password: ```root```

**Drupal Site Maintenance:**
username: ```Admin```
password: ```root```


## Setup
* Clone the project using the link provided on Github in the Terminal by using ```git clone```.
* Download and run MAMP to connect the server to the project folder.
* Import the ```bookstore.sql.zip``` database on phpMyAdmin.
* open browser to ```localhost:8888``` to view the site.
* Login using the login info provided above.

## Technologies Used

Drupal, PHP, HTML, CSS

### Legal

Copyright (c) 2015 **Logan Wu**

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
