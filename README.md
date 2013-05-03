### Hello world Erlang web app on cloudControl

#### Install cctrlapp

~~~
$ pip install cctrl
~~~

#### Clone repository

~~~bash
$ git clone https://github.com/mkorszun/erlang_example_app.git ; cd erlang_example_app
~~~

#### Create application

~~~bash
$ cctrlapp APP_NAME create custom --buildpack https://github.com/cloudControl/buildpack-erlang-kernel.git
~~~

#### Push

~~~bash
$ cctrlapp APP_NAME/default push
~~~

#### Deploy

~~~bash
$ cctrlapp APP_NAME/default deploy
~~~

#### Test it

**http://APP_NAME.cloudcontrolled.com/**