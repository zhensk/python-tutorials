```sh
$ echo '#!/bin/sh' > my-script.sh
$ echo 'echo Hello World' >> my-script.sh
$ chmod 755 my-script.sh
$ ./my-script.sh
Hello World
$
```

上面这段代码中，`echo`是打印的意思，而`>`是重定向的意思，`chmod`是修改权限的意思。`shell`脚本以`.sh`为结尾。

```sh
#!/bin/sh
# This is a comment!
echo Hello World	# This is a comment, too!
```

以上为`my-script.sh`中的代码，可以学习一下如何写注释。

```sh
$ chmod a+rx my-script.sh
$ ./my-script.sh
```

想要将`shell`脚本变成可执行的，可以使用以上语句。

```sh
grep "mystring" /tmp/myfile
```

这句的意思是将在`/tmp/myfile`中的`"mystring"`字符串搜索出来。

```sh
#!/bin/sh
# This is a comment!
echo Hello World        # This is a comment, too!
```

以上是`first.sh`中的代码。可以使用以下代码执行：

```sh
$ chmod 755 first.sh
$ ./first.sh
Hello World
$
```

得到结果：

```sh
$ echo Hello World
Hello World
$
```