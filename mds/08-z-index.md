## Layered representation

- The z-index property in CSS controls the stacking order of positioned elements along the z-axis, determining which elements appear on top when they overlap in the document layout.

```html
<style type="text/css">
  div {
    position: absolute;
    left: 2in;
    top: 2in;
  }
</style>

<p>
  <div
    style="z-index: 3;background-color:red; width: 1in; height: 1in; ">
  </div>
  <div
    style="z-index: 1;background-color:green;width: 2in; height: 2in;">
  </div>
</p>
```

![image](https://github.com/saidali-ibn-zafar/How-Browsers-Work/assets/120341849/44c50321-02b7-469a-84b4-3eb7294b5572)





