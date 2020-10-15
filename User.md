# Some situations about user's name and email
### **github: user's name is yuguanfeng;  user's email is 754346783@qq.com.** 
### **git in windows: user's name is ygf; user's email is 754346783@qq.com.(global setting)**
### **git in ubuntu: user's name is yuguanfeng; user's email is 754346783@qq.com.(global setting)**

## it is modified just in the website try to figure out the user's name marked when committed directly in the website.
> *it turns out to be as yuguanfeng, the name when sign in Github.<1.yuguanfeng 754346783@qq.com>*

## it is modified in the vscode in windows but still commited through git bash instead of in vscode.
> *it turns out to be as ygf, the name of git in windows.<2.ygf 754346783@qq.com>*

## it is modified in the vscode in windows and change the user's name to Ygf in current repository but still commited through git bash instead of in vscode.
> *it turns out to be as Ygf, the name of git in current repository.<3.Ygf 754346783@qq.com(this is not be committed)>*

## it is modified in the vscode in windows and change both the name and email, the name is Ygf and the email is 18145646512@163.com but still commited through gi bash instead of in vscode.
> *it turns out to be as Ygf, so it's nothing about the email, but it's still different from the one above.<4.Ygf 18145646512@163.com>*

## it is modified in the vscode in windows and change both the name and email at the same time, the name is YGf and the email is yuguanfeng43@163.com but still commited through gi bash instead of in vscode.
> *it turns out to be as YGf.<5.YGf yuguanfeng43@163.com>*

## what if the email is not a email-format, just like "12345"?
> *it works well and still is marked as YGf, so the user's email haves no effect<6.YGf 12345>*

## how will it be like if in ubuntu?
> *it turns out to be same as that in windows.<6.YGf 12345>*

## How many authors are identified by github?
> *it turns out to be five authors<1 2 4 5 6>. One name and one email together decide the author. And it must be commited. And only the first author is verified. I think if the user's name and email of git in windows or ubuntu are set like that in github, it can also be verified. But not being verified doesn't arise any problem.<6.YGf 12345>*  