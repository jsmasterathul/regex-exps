# regex-exps
##My experiments with regex



Some tips that should be kept in mind while writting a regular expression

**1) Square brackets starting with a caret: [^...] find all characters except the given ones.**

 [^aeou] - any character except ‘a’,’e’,’o’,’u’
 
 [^0-9] - any non-digit, same as \D
 
 [^\s] - any not-a-space, same as \S
 
 **2. The dot (.) matches anything (except for a newline).**
 
 **3. The positive lookahead (?=) asserts regex_1 to be immediately followed by regex_2.**

