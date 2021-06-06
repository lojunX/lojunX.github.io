title: 在线工具
hiddendate: true
comments: false
share: false


---


[昵称恶搞工具](./nickutil.html)




计算器工具



<table>  
    <tr>  
      <td><input type="button" value="add"     onclick="setOp('+', 'add');"/></td>  
      <td><input type="button" value="miner"  onclick="setOp('-', 'miner');"/></td>  
      <td><input type="button" value="times"  onclick="setOp('*', 'times');"/></td>  
      <td><input type="button" value="divide" onclick="setOp('/', 'divide');"/></td>  
    </tr>  
</table>  
<table id="tb_calc" style="display:none;">  
     <tr>  
        <td> <input id="x" type="text" style="width:100px" value="" name="x" /></td>  
        <td> <lable id="op"  name="op"></lable> </td>  
        <td> <input id="y" type="text" style="width:100px" value="" name="y" /> </td>  
        <td> <input id="opTips" type="button" value="" onclick="calc();"/> </td>  
        <td> <lable id="z" name="z"></lable> </td>  
    </tr>  
</table>  
