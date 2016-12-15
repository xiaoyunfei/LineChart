# LineChart
这是一个简单实用的折线图，使用灵活，提供了丰富的自定义属性，还支持左右滑动，支持折点点击以及X轴刻度点击，下面看一下自定义属性：
1、    //xy坐标轴颜色
    private int xylinecolor = 0xffe2e2e2;
    //xy坐标轴宽度
    private int xylinewidth = dpToPx(1);
    //xy坐标轴文字颜色
    private int xytextcolor = 0xff7e7e7e;
    //xy坐标轴文字大小
    private int xytextsize = spToPx(12);
    //折线图中折线的颜色
    private int linecolor = 0xff02bbb7;
    //x轴各个坐标点水平间距
    private int interval = dpToPx(50);
    //背景颜色
    private int bgcolor = 0xffffffff;
    //是否在ACTION_UP时，根据速度进行自滑动，没有要求，建议关闭，过于占用GPU
    private boolean isScroll = false;
    
    下面再看看效果吧：
    
   
   ![image](https://github.com/xiaoyunfei/LineChart/blob/master/img/gif_20161215_141019.gif)   
