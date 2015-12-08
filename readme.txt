这是一道100~200分的windows简单逆向。
FLAG格式：
falg：HCTF{1234567890xx1234}
falg：HCTF{UareS0cLeVer1234}

Console_FLAG为多flag生成器。

//
代码流程：
CheckRemoteDebuggerPresent一个简单的反调试。
开2个线程不断的去修改一个用于比较的数值。
movewindow实现按钮3点变换。
先减去	char maomaomao[] = "316754"; 验证HCTF{			}
然后进行一次编码，二叉查找表中内容，其实很简单。
进行一次写死的换位。
亦或比较上面线程修改的数值。
返回you got it














