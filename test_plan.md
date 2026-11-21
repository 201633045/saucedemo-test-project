# SauceDemo Web 功能测试计划
## 1. 项目简介
被测系统：SauceDemo 电商练习网站
测试地址：https://www.saucedemo.com
测试目的：练习Web功能测试，完成测试用例设计、缺陷发现与提交，作为软件测试项目。

## 2. 测试范围
登录模块、商品列表模块、商品详情模块、购物车模块、结算下单模块、侧边菜单模块
测试类型：正向功能测试、边界测试、异常场景测试

## 3. 测试环境
操作系统：Windows11
浏览器：Microsoft Edge
测试账号：
- standard_user（正常账号）
- locked_out_user（锁定账号）
- problem_user（存在缺陷账号）
- performance_glitch_user（加载慢账号）
- error_user
- visual_user

## 4. 准入条件
1. 网站可正常访问
2. 全部测试账号可用
3. 页面基础元素加载正常

## 5. 输出物
1. test_cases.xlsx：功能测试用例
2. bug_report.md：缺陷记录
3. screenshots：缺陷截图资源文件夹
4. README.md：项目说明文档

## 6. 退出标准
1. 使用standard_user账号，核心业务主流程（登录→加购商品→结算下单）可以完整跑通
2. 所有设计的测试用例执行完毕，记录实际测试结果
3. 高优先级缺陷全部记录归档
