## Positioning

### Relative
- Relative positioning - positioned like usual and then moved by the required delta.

![image](https://github.com/saidali-ibn-zafar/How-Browsers-Work/assets/120341849/fb25e7b5-4ced-483d-a375-265ab4d22ad2)

### Floats

- A float box is shifted to the left or right of a line. The interesting feature is that the other boxes flow around it. The HTML:
  ```html
<p>
  <img style="float: right" src="images/image.gif" width="100" height="100">
  Lorem ipsum dolor sit amet, consectetuer...
</p>
  ```

  ![image](https://github.com/saidali-ibn-zafar/How-Browsers-Work/assets/120341849/688c9e30-04c7-4aa4-aab4-529b74cc1a96)

### Absolute and fixed

![image](https://github.com/saidali-ibn-zafar/How-Browsers-Work/assets/120341849/7200142e-bd9f-4292-b4b2-e92d8169dd5e)

- `**Note**`: ***The fixed box won't move even when the document is scrolled!***
