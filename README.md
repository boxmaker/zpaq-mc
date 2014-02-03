zpaq-mc
=======

Add midnight commander extfs compatible info generation to [ZPAQ](http://www.mattmahoney.net/dc/zpaq.html)

**BUILD:**
- ```make```

**INSTALL:**
- Copy zpaq to any ${PATH} catalog or in uzpaq script set ZPAQ=(path to zpaq).
- Copy uzpaq to extfs.d
- Add to mc.ext
  ```
  shell/.zpaq
    Open=%cd %p/uzpaq://
  ```
  > **```mc -F``` to show extfs.d and mc.ext path**

- Restart mc
