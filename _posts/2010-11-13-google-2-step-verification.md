---
date: 2010-11-13 13:29:34
title: Google帐户的两步验证
layout: post
tags:
    - Google
    - 网络安全
categories:
    - 电脑
---
两步验证简单说就是每当你第一次在一台电脑/其他设备上登录Google帐户，除了密码之外，还需输入一个仅能通过你的手机获取的验证码。两者全对才能登录。

开启这种验证方法，首先你要注册两个移动设备(一个备用)，比如iPhone，然后将他们作为获取验证码的设备。在你的Google帐户下可以随时删除或更改这两个设备。

两步验证启用成功后，Google会发给你10个备用验证码。这10个验证码均可以用作上述的第二步验证。但每个验证码只能用一次，也就是激活一台电脑。所以别人不可能偷偷的用你的密码在其他电脑上登录。

对于iChat客户端或iPhone上的邮箱这种第三方软件，你需要输入一个访问码（注，不是上面说的验证码），这个访问码可以在Google帐户里的信任网页列表里生成。

![](http://pic.ztpala.com/wp-content/uploads/2010/11/Screen-shot-2010-11-13-at-1.15.00-PM.png)

针对每个软件生成不同的访问码，这样可以随时拒绝某个软件的访问。而且这个访问码只有在生成的时候显示一次，保证了安全性。至于web程序，尤其是那种让你直接填gmail密码的网站，不要用访问码，当然更不要透露Google密码，安全的网站会跳转到Google网页验证，得到相关的权限。

这种验证比原来的仅密码验证安全了不少，如果想在你的电脑之外的设备上登录，比如知道你的密码，并且拿到你用来取回密码的手机或者消耗一个备用验证码。

但是不知为何（非web程序）不能根据产品来区分权限，而必须允许获取所有数据，比如iPad/iPhone上的Reader阅读器。
