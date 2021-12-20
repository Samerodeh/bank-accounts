# Bank Accounts

## Features

* Create Bank Account
* Deposit & Withdraw Money
* Bank Account Type Support (e.g. Current Account, Savings Account)
* Modern UI with Tailwind CSS

## Requirements

* amqp==5.0.7
* anyio==3.3.4
* argon2-cffi==21.1.0
* asgiref==3.4.1
* attrs==21.2.0
* Babel==2.9.1
* backcall==0.2.0
* backports.entry-points-selectable==1.1.0
* bank-account-validator==0.2
* beautifulsoup4==4.9.3
* billiard==3.6.4.0
* black==21.10b0
* bleach==4.1.0
* CacheControl==0.12.6
* cachy==0.3.0
* celery==5.2.1
* certifi==2021.5.30
* cffi==1.15.0
* charset-normalizer==2.0.4
* cleo==0.8.1
* click==8.0.3
* click-didyoumean==0.3.0
* click-plugins==1.1.1
* click-repl==0.2.0
* clikit==0.6.2
* crashtest==0.3.1
* cryptography==35.0.0
* cycler==0.10.0
* debugpy==1.5.1
* decorator==5.1.0
* defusedxml==0.7.1
* distlib==0.3.3
* Django==3.2.9
* django-celery-beat==2.2.1
* django-timezone-field==4.2.1
* docopt==0.6.2
* entrypoints==0.3
* filelock==3.3.1
* flake8==4.0.1
* html5lib==1.1
* idna==3.2
* ipykernel==6.4.2
* ipython==7.28.0
* ipython-genutils==0.2.0
* jedi==0.18.0
* jeepney==0.7.1
* Jinja2==3.0.2
* Js2Py==0.71
* json5==0.9.6
* jsonschema==4.1.2
* jupyter-client==7.0.6
* jupyter-core==4.8.1
* jupyter-server==1.11.2
* jupyterlab==3.2.1
* jupyterlab-pygments==0.1.2
* jupyterlab-server==2.8.2
* keyring==21.8.0
* kiwisolver==1.3.2
* kombu==5.2.2
* libxml2-python==2.9.12
* lockfile==0.12.2
* MarkupSafe==2.0.1
* matplotlib==3.4.3
* matplotlib-inline==0.1.3
* mccabe==0.6.1
* mistune==0.8.4
* msgpack==1.0.2
* mypy-extensions==0.4.3
* nbclassic==0.3.4
* nbclient==0.5.4
* nbconvert==6.2.0
* nbformat==5.1.3
* nest-asyncio==1.5.1
* notebook==6.4.5
* numpy==1.21.2
* packaging==20.9
* pandas==1.3.4
* pandocfilters==1.5.0
* parso==0.8.2
* pastel==0.2.1
* pathspec==0.9.0
* pexpect==4.8.0
* pickleshare==0.7.5
* Pillow==8.4.0
* pipwin==0.5.1
* pkginfo==1.7.1
* platformdirs==2.4.0
* poetry==1.1.11
* poetry-core==1.0.7
* prometheus-client==0.12.0
* prompt-toolkit==3.0.21
* ptyprocess==0.7.0
* pycodestyle==2.8.0
* pycparser==2.20
* pyflakes==2.4.0
* Pygments==2.10.0
* pyjsparser==2.7.1
* pylev==1.4.0
* pyparsing==2.4.7
* PyPrind==2.11.3
* pyrsistent==0.18.0
* pySmartDL==1.3.4
* python-crontab==2.6.0
* python-dateutil==2.8.2
* pytz==2021.3
* pyzmq==22.3.0
* regex==2021.11.2
* requests==2.26.0
* requests-toolbelt==0.9.1
* scipy==1.7.1
* seaborn==0.11.2
* SecretStorage==3.3.1
* Send2Trash==1.8.0
* shellingham==1.4.0
* six==1.16.0
* sniffio==1.2.0
* soupsieve==2.2.1
* sqlparse==0.4.2
* terminado==0.12.1
* testpath==0.5.0
* tomli==1.2.2
* tomlkit==0.7.2
* tornado==6.1
* traitlets==5.1.0
* typing-extensions==3.10.0.2
* tzlocal==3.0
* urllib3==1.26.6
* vine==5.0.0
* virtualenv==20.9.0
* wcwidth==0.2.5
* webencodings==0.5.1
* websocket-client==1.2.1

## Project Installation

***To install environment and packeges***

```bash
poetry install
```

***Install development dependencies***

```bash
pip install -r requirements.txt
```

***Migrate Database***

```bash
python manage.py migrate
```

***Run the web application locally***

```bash
python manage.py runserver # 127.0.0.1:8000
```

***Create Superuser***

```bash
python manage.py createsuperuser
```

## Images

> Home Page

![homepage](assest/1.png)

> Sign In Page

![signinpage](assest/2.png)

> Admin Link

* Change the hyperlink to admin

![adminlink](assest/3.png)

> Bank Account

![bankaccount](assest/4.png)