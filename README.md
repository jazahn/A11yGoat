# A11yGoat
[public instance](http://jazahn.github.io/A11yGoat/)

## What is A11yGoat
This is a site that has been made purposely inaccessible as a way to teach people about accessibility.

### A11y?
A11y is a *numeronym*! Cool word, right? It is a tag used for web accessibility in the same way i18n is for internationalization and l10n is localization. Popularized because "accessibility" takes up 10% of a tweet. It's taking the first and last letters and telling you how many letters are in between. **a + (ccessibilit == 11) + y** I can't tell you definitively how it's pronounced, because I don't believe anyone has ever committed to something. I say "Alley", but I don't see why "Ally" wouldn't be just as good. Try not to sweat it.

### Goat?
This I'm borrowing from the [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project) project, which is an open source project that provides a purposely **insecure** site to help teach web security. The "goat", as they explain,  comes from the word scapegoat. They're intention is that "developers should not feel bad about knowing _______" ... "so blame it on the 'goat." I don't think I fully understand that sentiment, but since the inspiration came from WebGoat, A11yGoat made sense.


## How to Run
While you can view it freely on the [github public site](http://jazahn.github.io/A11yGoat/), the intention is for developers to download the code so you can get into the inaccessible files and make changes. It is built with [Jekyll](http://jekyllrb.com/) so that you can simply work with the compiled html version in [_site](https://github.com/jazahn/A11yGoat/tree/gh-pages/_site) without having to deal with any kind of backend. It is


There is no need for a backend language, however, it's not going to run *well* if it's just run from a *file://* so I would recommend something like [Python's SimpleHTTPServer](http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/) or [npm's http-server](https://www.npmjs.com/package/http-server).

## How to Contribute
* As an accesisbility professional

  Please feel free to browse the [public site](http://jazahn.github.io/A11yGoat/) and if you have suggestions or can think of things to add, add them via the [issue tracker](https://github.com/jazahn/A11yGoat/issues)
* As a developer:

  You can make an issue or pull request. We are still early in the project life, so if you've got a better way to do templating (that doesn't involve a server side), or you think they layout would look better with something that effects all pages, please file an issue first so we can discuss.
  
