## Target Output

![](https://cssbattle.dev/targets/6.png)

## Code

```html
<div id="circle">
  <div id="q1" class="quarter"></div>
  <div id="q2" class="quarter"></div>
  <div id="q3" class="quarter"></div>
  <div id="q4" class="quarter"></div>
</div>
<style>
  body {
    background-color: #e3516e;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  #circle {
    width: 200px;
    height: 200px;
    margin-top: -16px;
  }
  .quarter {
    display: inline-block;
    float: left;
    width: 100px;
    height: 100px;
  }
  #q1 {
    background-color: #51b5a9;
    border-radius: 100% 0 0 0;
  }
  #q2 {
    background-color: #fade8b;
    border-radius: 0 100% 0 0;
  }
  #q3 {
    background-color: #f7f3d7;
    border-radius: 0 0 0 100%;
  }
</style>
```

## Metrics

- **722** characters
- **100%** Match
- Score: **600.41**
