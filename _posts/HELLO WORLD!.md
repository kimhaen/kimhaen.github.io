HELLO WORLD!

最近はTwigの文法について勉強しています。

display parameters value (POST, GET, SESSION) using twig template
--------

For $_POST variables use this :
~~~twig
{{ app.request.parameter.get("page") }}
~~~
For $_GET variables use this :
~~~twig
{{ app.request.query.get("page") }}
~~~
For $_COOKIE variables use this :
~~~twig
{{ app.request.cookies.get("page") }}
~~~
For $_SESSION variables use this :
~~~twig
{{ app.request.session.get("page") }}
~~~
