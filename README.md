
# Installation

go get github.com/effortlessdevsec/jron

##  Usage
- ` cat all.js | jron | js beautify 

##  for searching anything (like token , api_key , password)

  cat all.js | jron | js beautify | grep --colour -C 1 "api_key"

