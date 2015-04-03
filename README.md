# gifview
-----
<p>
android中现在没有直接显示gif的view,只能通过mediaplay来显示，且还常常不能正常显示出来，为此写了这个gifview，其用法和imageview一样
</p>
<br/>
<p>libs/: 存放封装好的jar包。</p>

<p>添加了另一种Gifview2（较好用）与ImageView和其他View唯一的区别在于加了一个gif属性。</p>

```xml
    <?xml version="1.0" encoding="utf-8"?>  
    <resources>  
      
        <declare-styleable name="GifView">  
            <attr name="gif" format="reference" />  
            <attr name="paused" format="boolean" />  
        </declare-styleable>  
        <declare-styleable name="CustomTheme">  
            <attr name="gifViewStyle" format="reference" />  
        </declare-styleable>  
      
    </resources>
```