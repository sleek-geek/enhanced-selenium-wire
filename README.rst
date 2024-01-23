Enhanced Selenium Wire 
=============

This fork simply fixed the open issue with filedescriptor out of range: (https://github.com/wkeeling/selenium-wire/issues/434)
The solution I did was simply implement using Poll instead of Select to improve efficency. This is very useful when using Selenium Wire with Async.
