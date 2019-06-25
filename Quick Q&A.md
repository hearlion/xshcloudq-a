# 小帅操作系统Q&A

- [Q 1: 在upgrade中,点击保存,无页面保存应该怎么办?](#q-1---upgrade------------------)
- [And More ?](#and-more--)

## Q 1: 在upgrade中,点击保存,无页面保存应该怎么办?

​	通过检查以下几种情况确认问题所在:

- 检查云端(`hcloud`) 酒店管理-->酒店管理 该酒店是否在**编辑**中,
- 检查云端(`hcloud`) 酒店管理-->酒店品牌 该**酒店品牌**是否在编辑中.
- 检查云端(`hcloud`) 酒店管理-->酒店管理 该酒店是否配置了**布局** 应用 基础配置
- 检查酒店端(`hclient`) 设置-->系统设置 **一键同步** 是否显示`全部更新完成` 若显示`全部更新失败` 需要确认酒店服务器,是否有tomcat文件操作权限,酒店key配置是否正确.若响应很久之后提示`全部更新失败`需重试,等待资源下载完成.
- 若以上未能解决问题微信`新系统加班小分队`@我+酒店名称+云端服务器地址

## And More ?

For more questions or feedbacks, please contact us by:

- Email: <hearlion@qq.com>
- weChat: shanghanggg
- tg: @shangh
