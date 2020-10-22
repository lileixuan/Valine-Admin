Valine Admin 是 [Valine 评论系统](https://deserts.io/diy-a-comment-system/)的扩展和增强，主要实现评论邮件通知、评论管理、垃圾评论过滤等功能。支持完全自定义的邮件通知模板。基于Akismet API实现准确的垃圾评论过滤。此外，使用云函数等技术解决了免费版云引擎休眠问题，支持云引擎自动唤醒，漏发邮件自动补发。兼容云淡风轻及Deserts维护的多版本Valine。

## 配置说明

本仓库fork自用户 DesertsP 的 Valine-Admin 库

配置请参考原文档 [Valine 评论系统](https://github.com/DesertsP/Valine-Admin#readme)

## 修改内容

> 以下是本库修改的内容

- 站长通知优化
- 样式调整
  - 改为彩虹背景
  - 兼容移动端
  - 添加`返回顶部`按钮
- LeanCloud自动部署
- ...

更多请参考 [Commits记录](https://github.com/qinxs/Valine-Admin/commits/master)

## License

[MIT License](https://github.com/panjunwen/LeanComment/blob/master/LICENSE)
