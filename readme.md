# wanzhuanqt 玩转Qt

An example of using Qt5 conan package in a GUI project.

## Compile

```sh
cd wanzhuanqt
mkdir build
cd build
conan install --build missing ..
conan build ..
```

## Run

```sh
bin/wanzhuanqt
``

You should be able to see an analog clock app.