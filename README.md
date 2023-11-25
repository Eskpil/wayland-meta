# Meta repos for my wayland adventures

I enjoy working with wayland. I think it is a good technical implementation of a compositing system. So naturally I have
started a lot of projects around wayland and its awesome ecosystem. The goal is to have a complete self written desktop
environment tailor-made for wayland.

## Compositor environment

My environment will be hosting its own compositor built with hybrid usage in mind. You can read more about in its
repository [Nora](https://github.com/Eskpil/nora)

## Surface creation library

The creation on wayland windows etc. is pretty trivial but requires some boilerplate, I have created a library to
abstract away the boilerplate and give users a natural way to interact with the compositor. You can read more about that
in its repository [Aylin](https://github.com/Eskpil/aylin)

## Flutter embedder library

![demo](https://github.com/Eskpil/isabel/blob/master/assets/demo-screenshot.png)

In 2023 there is a magnitude of application toolkits to choose from. I have experimented with tons of them, and I have
found that flutter gives a perfect balance between performance and developer productivity. The default flutter embedder 
for linux bases itself on [GTK](https://gtk.io) which is tailor-made for [GNOME](https://gnome.org) it causes the 
experience of my environment to feel inconsistent. That is why I have decided to write my own flutter embedder which is 
made exactly for what I want my environment to achieve. Read more about it in its repo 
[Isabel](https://github.com/Eskpil/isabel)