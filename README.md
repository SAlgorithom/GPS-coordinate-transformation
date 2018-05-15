# GPS-coordinate-transformation
地图的各种坐标系之间的转换

GPS坐标转换：
WGS-84：是国际标准，GPS坐标（Google Earth使用、或者GPS模块）
GCJ-02：中国坐标偏移标准，Google Map、高德、腾讯使用
BD-09：百度坐标偏移标准，Baidu Map使用

各函数用途如下：
wgs2gcj(wgsLat, wgsLng):
    """
    WGS-84转成GCJ-02
    """
    
gcj2wgs_rough(gcjLat, gcjLon):
    """
    GCJ-02 转 WGS-84 粗略版
    """

gcj2wgs_accurate(gcjLat, gcjLon):
    """
    GCJ-02 转 WGS-84 精确版
    """
    
gcj2bd(gcjLat, gcjLon):
    """
    GCJ-02 转 BD-09
    """
    
bd2gcj(bdLat, bdLon):
    """
    BD-09 转 GCJ-02
    """
    
