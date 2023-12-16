# Rally Canary Website 🇮🇨

A project for all [CCRA]('https://fcautomovilismo.com/') fans from the Canary Islands.

<div style='width:520px'>
    <img src='img/portada.jpg'>
</div>

_The objetive is build a website where people can see information about Rallyes in the Canary Islands. The project will be developed with Django to continue learning this tool that I'm using in my studies_
<br>
<br>

> [!NOTE]
> This project is for educational purposes only and there are likely to be errors in the code.

## Starting 🚀

_This section will help you to have a copy of the project in your local computer in case you want to work, change or test something_

The project is still **under development**, so there will be **no documentation on the deployment** of the project yet.

### Installation and requirements 🔧

_You can check requirements of the project on the [requirements.txt file](requirements.txt)_

Because the project will be done with Django-Python, we will need a Python Virtual Enviroment to install all dependencies. You can run in a terminal the following commands:

```console
$ python -m venv .venv --prompt mysite
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

If something goes wrong make sure you have Python installed or or else try to launch the command indicating the version of Python:

```console
$ python3.X -m venv .venv --prompt mysite
```

> [!TIP]
> In case of doubts you can see [the documentation](https://docs.python.org/3/library/venv.html)

Some functionalities will involve the use of sensitive information, so we will use a `.env` file for this purpose. This file must be out of version control so you will need to create one. In the project (mostly in the settings.py file) there will be calls to a config function of the prettyconf library, all these calls are the information that the `.env` file must contain.

## Contriburion 🖇️

Feel free to contribute to the project in any way you want <3. I will be happy to receive help from experienced people to correct mistakes and learn, as I said the project will be a help to continue taking my first steps with Django. 😊

## License 📄

The project is under MIT License - you can see [LICENSE](LICENSE) for more details
