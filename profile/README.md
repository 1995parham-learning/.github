# Hello 👋, Welcome to my hands-on learning repositories

Here I gather my learning repositories. I use these repositories
to learn new languages and technologies, so these repositories may
not be complete, working properly and idiomatic.

Feel free to contribute 😊

## Useful Links

Because of the sanctions many online sync services are not available in my country, so I am listing
useful URLs here to refer them just by clicking them.
There are libraries, tutorials, etc. which personally prefer them,
and you may find some examples in this organization about them.

### Python

#### Configuration

I love the way we can configure Golang application **WITH TYPES**, but this library
is python seems nice to me.

- <https://github.com/dynaconf/dynaconf> <https://www.dynaconf.com/>

#### HTTP Frameworks

Sometimes I don't want to set up the giant Django so, I have these options:

- <https://sanic.dev/en/>
- <https://flask.palletsprojects.com/en>

#### HTTP Client

- <https://requests.readthedocs.io/en/latest/>

#### Django

The Django itself

- <https://docs.djangoproject.com/en>

It has built-in support for GIS event.

Writing REST API in a Django application:

- <https://www.django-rest-framework.org/api-guide/serializers/>
- <https://www.django-rest-framework.org/api-guide/fields>
- <https://www.django-rest-framework.org/api-guide/parsers/>
- <https://www.django-rest-framework.org/api-guide/views/>

Semi-automatic documentation for the REST APIs:

- <https://github.com/tfranzel/drf-spectacular>

#### Tests

In python you need a library for testing in Python:

- <https://docs.pytest.org/en/stable/index.html>

But in Django you don't need anything and Django already
has what you need.

#### Standard CLI

- <https://click.palletsprojects.com/en>

#### Advanced Console UIs

- <https://github.com/Textualize/rich>

### Golang

#### Configuration

Personally I love to have all configuration well-defined and structured,
the thing that I couldn't achieve with [viper](https://github.com/spf13/viper),
so I prefer:

- <https://github.com/knadh/koanf>

#### Standard CLI

Having multiple sub-command for things like migrations, insert initiation data, etc.

- <https://github.com/spf13/cobra>

There is also another options, but I use it rarely:

- <https://github.com/urfave/cli>

#### HTTP Frameworks

There are multiple frameworks in Go:

- <https://gofiber.io/> <https://github.com/gofiber/fiber>
- <https://echo.labstack.com/> <https://github.com/labstack/echo>

#### Telemetry

I want to use a single library for all the logging, metrics and tracing
but until that day we have:

- <https://github.com/prometheus/client_golang>
- <https://github.com/open-telemetry/opentelemetry-go>
- <https://github.com/uber-go/zap>

Please note that for using open-telemetry you may need multiple packages,
so install them from an example.

#### Advanced Console UIs

/pterm/ is useful when you need colors, and you need them easy, and fast.

- <https://github.com/pterm/>

but when you need more:

- <https://github.com/charmbracelet/bubbletea>
- <https://github.com/gizak/termui>

#### Tests

- <https://github.com/stretchr/testify>

#### ORM

/gorm/ is easy and fun, but you also prefer to write down your queries like man.

- <https://github.com/go-gorm/gorm> <https://gorm.io/>

#### Redis

the popular and backward-compatible redis library that has /context/:

- <https://github.com/go-redis/redis>

this new library is also fun on new versions of redis:

- <https://github.com/rueian/rueidis>
