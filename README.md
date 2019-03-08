<!doctype html>
    <html>
    <head>
    <meta charset="utf-8">
    <title>无标题文档</title>
    </head>
     
    <body>
    <script language="JavaScript">
    function ecldj(hits)
    {
    	if(hits==0){
    	show_alert.style.display = "none";
    	i=1
    	}
    	else if(hits==1){
    	setTimeout("showsa();",1000);
    	}
    }
    function showsa()
    {
    i=i-1
    document.title="本窗口将在"+i+"秒后自动关闭!";
    if(i>0){
       ecldj(1);
      //setTimeout("showsa();",1000);
      show_alert.style.display = "";//关闭  
      }
    else{
      show_alert.style.display = "none";  //显示
      }
     }
      var i=3
      ecldj(1);
     function close_alert(){ecldj(0);}//关闭
    </script>
    <div id="show_alert"  style="position:absolute; width:202px; height:196px; z-index:1; left: 90px; top: 162px; background-color: #EAF1F4; layer-background-color: #EAF1F4; border: 1px none #000000;">
      <table width="298" border="0" cellspacing="0" cellpadding="0">
        <tr>
          <td><a href="javascript:;" onclick="close_alert();">close</a></td>
        </tr>
        <tr>
          <td> </td>
        </tr>
        <tr>
          <td> </td>
        </tr>
      </table>
    </div>
    </body>
    </html>

