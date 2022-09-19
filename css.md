el-button

/*鼠标点击后移开，恢复本身样式*/
.buttonDiv, .buttonDiv:focus:not(.buttonDiv:hover){ 
  margin-right: 12px;
  border: 1px solid #2794f8;
  border-radius: 2px;
  box-shadow: 0 2px 4px 0 #f4f4f4;
  color: #2794f8;
  background: white;
}
<img src="https://img-blog.csdnimg.cn/20210312112607776.png#pic_center">

/*鼠标悬浮，没有按下；鼠标按下后抬起，没有移开*/
.buttonDiv:focus, .buttonDiv:hover{
  background: #eaf5ff;
  border: 1px solid #2794f8 !important;
  color: #2794f8;
}
<img src="https://img-blog.csdnimg.cn/20210312113215492.png#pic_center">
/*鼠标按下，没有抬起*/
.buttonDiv:active {
  background: #2794f8;
  color: white;
}
<img src="https://img-blog.csdnimg.cn/20210312113256361.png#pic_center">
