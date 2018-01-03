Welcome to the LESS-CSS wiki!

less:

compile to less
intro programming featues to css
looks and feel like css

ie.valid less

<head>
<link rel="stylesheet/less" type="text/css" href="css/my.less>
<script src="js/less.js" type="text/javascript"></script>
<script src="css/less.css" type="text/javascript"></script>
</head>

.less:
<link rel="stylesheet/less" type="text/css" href="styles.less" />
<script src="less.js" type="text/javascript"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/less.js/2.7.2/less.min.js"></script>


my.less:

@import "init.css"
@main-color: Pink;

html
{
}
body
{
background:@main-color;
}

less on the server:

support server:

node.js
asp.net


node:

->@ npm install install
->var less=require('less');
->less.render(lessContents,
            function(e,css){
            console.log(css);
            });

















