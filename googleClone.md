# 참고해주세요!

- HTML
```
           <table>
                <tr>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                </tr>
                <tr>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                </tr>
                <tr>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                    <td><canvas class="googleApp_Block" width="4" height="4"></canvas></td>
                </tr>
            </table>
```


- CSS

```

table, td, tr {
    display: flex;
    width: 15px;
    
  }
  
tbody {
    cursor: pointer;
}
tbody:hover .googleApp_Block {
    background-color: black;
}

```

- 결과

<img src="./google/img/googleApp.PNG">

- Hover

<img src="./google/img/googleApp_Hover.PNG">




# 말풍선

- HTML
```

```


- CSS

```

.arrow_box {
    display: none;
    position: absolute;
    width: 100px;
    padding: 8px;
    left: 0;
    -webkit-border-radius: 8px;
    -moz-border-radius: 8px;  
    border-radius: 8px;
    background: #333;
    color: #fff;
    font-size: 14px;
  }
  
  .arrow_box:after {
    position: absolute;
    bottom: 100%;
    left: 50%;
    width: 0;
    height: 0;
    margin-left: -10px;
    border: solid transparent;
    border-color: rgba(51, 51, 51, 0);
    border-bottom-color: #333;
    border-width: 10px;
    pointer-events: none;
    content: " ";
  }
  
```