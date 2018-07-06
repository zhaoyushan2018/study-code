## java26代码示列

```java
public class App {
    
    public static void main(String[] args) {
        
        System.out.println("welcome to visit");
        
    }
    
}
```



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
      <!-- Tell the browser to be responsive to screen width -->
    <meta content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" name="viewport">
    <!-- Bootstrap 3.3.6 -->
    <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
    <link rel="stylesheet" href="dist/css/font-awesome.css">
    <link rel="stylesheet" href="dist/css/style.css">
    <style>
        body {
            margin-top: 60px;
        }
        
    </style>
</head>
<body>
        
	<div class="container">
		<button class="btn btn-primary btn-block" id="btn">
			抽取
		</button>
		<ul class="list-group" id="ul">
		  
		</ul>
	</div>
<script src="plugins/jQuery/jquery-2.2.3.min.js"></script> 
<script>
    $(function(){
    	  var array = [];
	      for(var i = 1; i <= 15; i++) {
	    	  array.push(i);
	      }
	      $("#btn").click(function(){
	            if(array.length == 0) {
	      			alert("完毕");
	      		} else {
		      		var index = parseInt(Math.random() * array.length);
		    	  	var removed = array.splice(index,1);
		    	  	$("#ul").append("<li class=\"list-group-item\">" + removed + "</li>")
	      			
	      		}
	      		
	      });
	      
    });
</script>   
</body>
</html>
```

如果遇到问题请访问[度娘](https://www.baidu.com/)

或者[bing一下](https://cn.bing.com/)

或者[自己玩去把!](http://news.baidu.com/)

[好看的](https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=3692744090,4225836522&fm=173&app=25&f=JPEG?w=500&h=722&s=A51E2777451AE5CC5A6184DB0100C033)



[漂亮的](https://gss3.bdstatic.com/-Po3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike92%2C5%2C5%2C92%2C30/sign=dd3b2cf9dbb44aed4d43b6b6d275ec64/caef76094b36acaf75feb94f7dd98d1001e99c62.jpg)



![哈哈哈][mark](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1530886799552&di=5199aa3503cd60b1962bc942505fce7a&imgtype=0&src=http%3A%2F%2Fimg11.360buyimg.com%2Fcms%2Fjfs%2Ft1087%2F341%2F1419442751%2F392163%2F685504d3%2F559e3649N9de8a2c4.jpg)



