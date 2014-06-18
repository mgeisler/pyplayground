ZeroPy
======

This is a small [ZeroVM][1] demo application. It let's you execute
Python code in the ZeroVM sandbox from your browser. This is very
similar to how the [Go playgroud][2] allows you to edit and execute Go
code directly from your browser.

Deployment
----------

You need access to an installation of [ZeroCloud][3] to use ZeroPy.
You deploy ZeroPy using `zpm`. First clone the repository and create
the `zeropy.zapp` file:

    $ zpm bundle

Then deploy the zapp:

    $ zpm deploy container/zeropy zeropy.zapp

Then load the `index.html` file in your browser and you should be able
to execute Python code.


[1]: http://zerovm.org/
[2]: http://play.golang.org/
[3]: https://github.com/zerovm/zergocloud
[4]: http://docs.zerovm.org/projects/zerovm-zpm/en/latest/
