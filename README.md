<!DOCTYPE html>
<html lang ="ko">
  <head></head>
  <body>
    <style>
      li{list-style:none;}
      .colorBtn{
        width:100px;
        height:36px;
        background-color:green;
        color:white;
        text-align: center;
        line-height: 36px;
        cursor: pointer;
        border-radius:3px;

      }
    </style>
    <form>
      <ul>
        <li><input type = "text"></li>
        <li><input type = "password"></li>
        <li>
          <label><input type="radio" name="fruit" id="orange">오렌지</label>
          <label><input type="radio" name="fruit" id="orange">사과</label>       
          <label><input type="radio" name="fruit" id="orange">바나나</label>        
        </li>
        <li>
          <label><input type="checkbox" name="fruit" id="orange">오렌지</label>
          <label><input type="checkbox" name="fruit" id="orange">사과</label>       
          <label><input type="checkbox" name="fruit" id="orange">바나나</label>        
        </li>
        <li><div class="colorBtn">버튼입니다</div></li>
      </ul>
     
    </form>

  </body>
</html>
