CRT-gnome SHADERS SETUP

![alt text](http://www.revista.espiritolivre.org/wp-content/uploads/2016/03/mame-logo.png "Screenshot")

* Add the following lines to the bottom of your mame.ini

```elixir
gl_glsl                   1
gl_glsl_filter            1
glsl_shader_mame0         /home/user/macname/Documents/mame/osd/shader/glsl_plain
glsl_shader_mame1         /home/user/macname/Documents/mame/osd/CRT-geom
```

* Note: macname your username.
