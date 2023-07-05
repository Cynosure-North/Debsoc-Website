Domain name registered with regery.com, login is the contact@vicdebsoc google account

# Why did I chose Jekyll
Primarily for the jekyll-datapages-generator plugin. My personal preferred SSG as I write this is Hugo, but it has no mechanism to generate pages from csv data without using a wrapper script this is a pain.
Jekyll is also fairly simple, popular enough, and easy to deploy to Github Pages.

# Why did I chose Gitlab
Firstly are principle/practical concerns around open source freedoms. As is stands the full stack is open source, meaning we should be insulated from corporate manouvers. In the worst case it's fairly easy to stand up a gitlab instance, compared to migrating everything from github.
Secondly is short term practical concerns. Github does not have PKCE support for OAuth 2. Because of this there is currently no way to implement a login with github button statically. That is a pain. Gitlab does have that so wee don't have to rely on service like Netlify, which would increase complexity and dependency scope. 