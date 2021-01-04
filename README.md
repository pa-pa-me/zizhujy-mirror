# zizhujy

> My homepage made 10 years ago, ugly but cool

## Story

I made a kind of popular website once url is `http://zizhujy.com`, which got 400 UV daily and I earned some money on that. It's super cool as at that time no online function graphing tool can do what it does, even the great [https://desmos.com/calculator](https://desmos.com/calculator) can not compete it on implicit function graphing. 

But later on the [desmos](https://desmos.com/calculator) evolved so fast and can do much much better than it, so I stopped working on it, and lost the domain, too.

So later I stopped my server and moved it to app harbor (http://zizhujy.apphb.com) as it's free hosting for ASP.NET (zizhujy was made based on ASP.NET MVC).

App harbor is great, but the pain is the free plan can't scale, and it's very slow. But actually the main feature of it is totally static in pure JavaScript, so now I mirrored it and host it as a static site.

## How to mirror

```shell
wget -T 8 -t 2 -mkxKE -e robots=off http://zizhujy.apphb.com
```