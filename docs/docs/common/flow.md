# 前端开发流程

---

- 需求确定。
- 开发、自测、提测。
- 可能出现问题。
- 关注线上质量。

## 需求确定

- 提出不理解及不合理的需求，以免后面反复开发修改。
- 清楚流程。
  - 页面跳转。
- 数据状态变化。
- 交互设计确认。

## 开发、自测、提测

- 设计稿完成度

  - 基础界面：颜色，间距，字体大小，不同屏幕自适应。
  - 边界处理：比如内容溢出，换行。
  - 状态：按钮（normal, loading, disabled, hover）

- 开发

  - 需求功能完成。
  - 关注状态变化。
  - 图片优化。
  - 代码压缩。

- 联调

  - 接口是否调通。
  - 接口文档。字段说明。
  - 异常错误处理。
  - 防呆处理。（空白页）

- 自测
  - 提前发到测试环境，功能验证。

自测表格（Example）

| 模块 |    用例    |           预期结果 | 优先级 | 前端是否完成 | 接口是否完成 | 备注 |
| ---- | :--------: | -----------------: | -----: | -----------: | -----------: | ---: |
| 登录 | 手机号为空 | 提示：请输入手机号 |     高 |           ok |           ok |      |

## 可能出现问题，及时反馈

- 视觉稿/交互稿未按时提供。
- 需求变更。产品及时通知，PRD 更新。
- 后台接口未按时、按质完成。
- bug 有好多，但修改不及时。

## 关注线上质量

发布之前：

- 缓存。静态资源版本号更新。
- 关注项目发布顺序。

发布之后：

- 功能是否正常运行？
- 各项指标是否正常？比如 tongji.js、错误监控数据、\_pwk 和 wst 等。
- 有哪些可以优化的点？
- 。。。