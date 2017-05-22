### 说明

增加了在后台设置音乐外链的功能，其它的基本和[原版](https://github.com/kabukky/journey)一样

### 安装

    go get github.com/wataxiwaX/journey
    cd $GOPATH/src/github.com/wataxiwaX/journey
    go build
    
### 外链用法

在后台设置里可以看到SongUrl输入框，输入音乐外链链接就行了，例如默认的`<南方姑娘> --赵雷`的外链html代码:

    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86    src="//music.163.com/outchain/player?type=2&id=202373&auto=1&height=66"></iframe>
    
只需要输入src属性的值就可以了，即输入`//music.163.com/outchain/player?type=2&id=202373&auto=1&height=66`
