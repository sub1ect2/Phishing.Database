<img src="https://github.com/mitchellkrogza/Phishing.Database/blob/master/dev-tools/phishing-logo.jpg" alt="Phishing Domain Status Testing Repo"/>

# Phishing Domain Database

A Testing Repository for Phishing Domains, Web Sites and Threats.

_______________
#### Version: V0.1.7549
#### ACTIVE Phishing Domains (Tested): [54282](https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-ACTIVE.txt) (88 %)
#### INACTIVE Phishing Domains (Tested): [6781](https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-INACTIVE.txt) (11 %)
#### INVALID Phishing Domains (Tested): [297](https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-INVALID.txt) (0 %)
*****************************
#### Total Phishing URL's Captured: [281695](https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/input-source/ALL-feeds.list) :exclamation: Large File
____________________


## Purpose of this repo?

This is just one of a number of extensive projects dealing with testing the status of harmful domain names and web sites. We test sources of Phishing attacks to keep track of how many of the domain names used in Phishing attacks are still active and functioning. We sort all domains from all sources into one list, removing any duplicates so that we have a clean list of domains to work with.

************************************************
## How do you test?

We make use of the awesome [PyFunceble Testing Suite](https://github.com/funilrys/PyFunceble) written by [Nissar Chababy](https://github.com/funilrys/). Over a year in development this testing tool really provides us with a reliable source of active and inactive domains and through regular testing even domains which are inactive and may become active again are automatically moved back to the active list.

************************************************
## Contributing

If you have a source list of phishing domains why not contribute them to this project for testing? Simply send a PR adding your input source details and we will add the source. 


************************************************
## Contributors

- [Mitchell Krog](https://github.com/mitchellkrogza/)
- [Nissar Chababy](https://github.com/funilrys/)

************************************************
MIT License

Copyright (c) 2018 Mitchell Krog
https://github.com/mitchellkrogza

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
