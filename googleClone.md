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

