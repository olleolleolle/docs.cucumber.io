---
menu:
- about
source: https://github.com/cucumber/cucumber/wiki/Get-in-touch/
title: Get in touch
---

Got questions? Here is where you can get in touch:

- [IRC](irc://irc.freenode.net/cucumber) ([log](http://irclogger.com/cucumber/))
- [Mailing list (Google Groups)](https://groups.google.com/group/cukes)
- [Github Issues](https://github.com/cucumber/cucumber/issues/) (Bug reports, feature requests, patches)
- [stackoverflow](https://stackoverflow.com/questions/tagged/cucumber)

If you file a Github issue without following the "Before you ask" guidelines below, your ticket may be closed as invalid. If that happens, just comment on the ticket with the missing information to have it reopened.

If you contact a developer directly you may not get an answer. If you do get an answer, the answer will most likely be cc'ed to the mailing list. Open source development also means open communication.

## Before you consider asking

Try the latest released gem:

```
gem update cucumber
```

## Before you ask

It's impossible to give a meaningful answer to "Cucumber doesn't work - what's wrong?" -style questions. You have to tell us more.

Most people use Cucumber in more or less complex environments where a lot of other code is involved. Various web frameworks, many different ruby gems and your own code. There are many different ways you can [run Features](/cucumber/running-features/) and many things that can go wrong - and quite often it has nothing to do with Cucumber at all.

So when you ask a question, please tell us:

- What Cucumber version you're using: `cucumber --version`
- What other gems and versions you're using: `gem list`
- What command you ran
- What the output, error message and full backtrace was: Feed Cucumber with `--backtrace --verbose` and rake with `--trace`.
- What output you had expected.
- What relevant code you have. Don't *describe* your code in twelve furlongs of prose, just show it. Please don't paste code in emails, use: <http://gist.github.com/>
- And finally, tell us how to reproduce the error, as described on the [Contributing](/about/contributing/) page.
