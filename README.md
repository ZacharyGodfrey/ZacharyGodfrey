# Hi, I'm Zach.

I'm a senior software engineer based in Florida and I've been building software since 2013. My current tech stack consists of Typescript and Postgres on AWS, but I've also got a history of working in the .NET world with C# and SQL Server.

You can reach me via email at zchr@gdfr.me.

## My Current Side Project

I'm calling the project [microlith](https://github.com/ZacharyGodfrey/microlith) (micro + monolith).

The software industry moves quickly, and sometimes I think we're too quick to demonize what used to be standard practice in favor of the hot new thing of the day. I'm all for following best practices in my day job, but in my spare time I like to experiment with those "legacy" ideas in order to see if we've thrown the baby out with the bath water. I enjoy intentionally doing things the "wrong way" in order to see if I can find something of value.

Right now the hot thing in software is to break down old, monolithic applications into multiple microservices. There are obvious advantages to this new architecture when you have a large and growing application being built by multiple teams, but I think we're often too quick to run to this new way of doing things and we fall into the trap of premature optimization. My current side project is an intentionally monolithic web app.

I'm building this project to test my hypothesis that a monolithic app can actually be better than microservices for apps that don't yet require massive scale. By better, I mean that monolithic apps can (when done well) offer a simplicity that microservices just can't and that simplicity leads to faster implementation of new features and an easier time tracking down the source of bugs.

With microservices, you often run into the "Mario problem" - your queen is in another castle. When a bug occurs, you'll often want to follow the flow of data through your application, but this can be tricky when you're having to cross network boundaries and look into several different repositories. In order to test out changes locally, you often have to spin up multiple services that didn't change so that you can test the one service that did change.

With a monolithic application, everything is in one repository that runs as a single service and the data flow is just a series of method calls. As long as the code is organized and written well, this simplicity seems to offer us a much better development experience.
