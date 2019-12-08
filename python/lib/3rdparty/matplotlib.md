# <center>  Matplotlib 绘图集锦
Matplotlib官网：http://matplotlib.org/

## 一、Matplotlib的三层 API

Matplotlib 的 API 有三层结构，分别为 `FigureCanvas`、`Renderer`、`Artist` 。其中，
**前两者**负责处理计算机底层（后端 Backends）的绘图操作（如使用PostScript绘制PDF，
**后者**负责处理所有的高层结构（前端 frontend）的绘制和布局（如处理图表、文字和曲线等）。 


+ `matplotlib.backend_bases.FigureCanvas （画板）`：绘制图形的区域；
+ `matplotlib.backend_bases.Render （渲染器）`：将绘制的图渲染（展示）在屏幕上的对象；
+ `matplotlib.artist.Arist （画家）`：能通过 Render 在 FigureCanvas 上 Arist的对象。


|col1|col2|col3|
|---|---|---|
|--|--|--|
