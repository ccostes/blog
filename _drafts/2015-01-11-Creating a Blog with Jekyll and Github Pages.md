---
published: false
---

### What is Jekyll?
Jekyll takes a collection of posts and pages written in markdown, along with a template for your website, and generates static HTML pages that you can host anywhere. No CMS, no server-side scripting, just you and your content. Because everything is static, pages are super-fast and cheap to host.

### Getting Started
In this article we'll walk through
- Setting up a local Jekyll environment for development
- Creating our first site
- Uploading the site for hosting on Github Pages

I set up my local environment in an EC2 instance on Amazon AWS, but the steps should work as-is on any Debian environment, and by subsituting for other package managers (like apt-get in Ubuntu) in others. 

### Building the Development Environment
The first step to developing Jekyll websites is getting a local environment set up to build sites and verify output before publishing. 