# CatWrt-MirrorsConf

一键替换原有腾讯源为 CatWrt 软件源，并且带有禁用源选项，为源服务器省流。


**示例**

以 x86_64 举例

```bash
# 开启

rm -rf /etc/opkg/distfeeds.conf && /wget -P /etc/opkg  https://fastly.jsdelivr.net/gh/miaoermua/CatWrt-MirrorsConf@main/amd64/distfeeds.conf


# 关闭

rm -rf /etc/opkg/distfeeds.conf && /wget -P /etc/opkg  https://fastly.jsdelivr.net/gh/miaoermua/CatWrt-MirrorsConf@main/disabled_conf/distfeeds.conf

```