## Project Overview
RSS Feed Reader coded with Javascript ES6.
In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included Jasmine and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

### Why this Project
Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

### What will I learn?
You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

### What tests are written to check
View the [Review Standards] of the Subscriber Reader Project (https://review.udacity.com/#!/projects/3442558598/rubric)（查看订阅阅读器项目的[评审标准](https://review.udacity.com/#!/projects/3442558598/rubric)）
* Write a test that iterates through all sources in the allFeeds object to ensure that there are linking fields and the link is not empty.（编写一个测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的）
* Write a test that iterates through all the sources in the allFeeds object to ensure that there is a name field and is not empty.（编写一个测试遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。）
* Write a test case to ensure that the menu elements are hidden by default. You need to analyze html and css to figure out how we implemented the hide/show menu elements.（写一个 "The menu" 的测试用例，保证菜单元素默认是隐藏的。分析 html 和 css 来搞清楚是怎么实现隐藏/展示菜单元素的。）
* Write a test case to ensure that the menu will switch to the visible state when the menu icon is clicked. This test should contain two expectations: whether the menu is displayed when the icon is clicked, and hidden when clicked again.（写一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation ： 当点击图标的时候菜单是否显示，再次点击的时候是否隐藏。）
* Write a test to ensure that the loadFeed function is called and works fine, that is, there is at least one element of .entry in the .feed container element.（写一个叫做 "Initial Entries" 的测试用例，保证 loadFeed 函数被调用而且工作正常，即在 .feed 容器元素里面至少有一个 .entry 的元素。）
* Write a test case called "New Feed Selection"（写一个叫做 "New Feed Selection" 的测试用例）
* Writing a test ensures that the content will really change when a new source is loaded with the loadFeed function.（写一个测试保证当用 loadFeed 函数加载一个新源的时候内容会真的改变）

### How to run
Download repository to your computer and open it in your browser. Open file index.html in browser. The test results will be displayed at the bottom of the page.

### Licenese
see LICENSE
