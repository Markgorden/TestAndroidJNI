TestAndroidJNI
==============

首先为什么要用C++写android程序呢？主要是因为java写的android程序太容易被发编译，相对于java编译后的dex文件，底层的native so更加不容易被反编译，所以为了安全起见，可以将一些程序的逻辑写到C++里面，下面我们就写一个activity，其中核心内容都写在C++里面。我们写一个演示界面，其中后台发一条短信（所有逻辑都在C++中）。现在一些安全公司把代码全都写到C++中，我做的主要是为了安全~
