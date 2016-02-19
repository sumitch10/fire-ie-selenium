One of the way of getting Locators

# Introduction #

This is not any way similar to Selenium-IDE.

Problem:
My webApplication supporting only InternetExplore , I am not able to get the element details(since Selenium-IDE is only plugin available for Firefox).

Solutions:
1. Using Internet Developer tools.
> But with this we can't get xpath. This can be helpful only when all the webelements having either Id/Name.

2. Using fire-ie-selenium
> We can able to get not only ID,Name but also Xpath.
> When any section available in a frame , we will get the elements respective FrameId / Name.