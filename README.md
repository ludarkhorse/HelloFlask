# HelloFlask
A collection of Flask example applications. Repository for [*Hello, Flask!*](https://zhuanlan.zhihu.com/p/29907260).

## Demos

There are 9 applications in demos directory:

- demos/hello  Basic Flask application
- demos/http  Flask with HTTP
- demos/template Templating with Jinja2
- demos/form  Form handing with Flask-WTF (WTForms)
- demos/database  Database with Flask-SQLAlchemy
- demos/email  Send email with Flask-Mail and SendGrid
- demos/assets  Assets optimize with Flask-Assets
- demos/cache  Cache with Flask-Caching
- and more...

## Run the demo application

Preparation work:
```
$ git clone https://github.com/greyli/helloflask.git
$ cd helloflask
$ pipenv install
$ pipenv shell
```

Run:
```
$ cd demos/hello
$ flask run
```
Now open http://localhost:5000.

You can run other application by replace `demos/hello` with proper path.

## For Chinese Readers of My Flask Book

����ֿ����[��Flask Web����ʵս��](http://helloflask.com/book)��1~6���Լ�13�µ�ʾ������Դ�롣ʾ��������½ڵĶ�Ӧ������£�

- demos/hello  ��Ӧ��1�¡���ʶFlask��
- demos/http  ��Ӧ��2�¡�Flask��HTTP��
- demos/template  ��Ӧ��3�¡�ģ�塷
- demos/form  ��Ӧ��4�¡�����
- demos/database  ��Ӧ��5�¡����ݿ⡷
- demos/email  ��Ӧ��6�¡������ʼ���
- demos/assets  ��Ӧ��13�¡������Ż���
- demos/cache  ��Ӧ��13�¡������Ż���

## License

This project is licensed under the MIT License (see the
`LICENSE` file for details).