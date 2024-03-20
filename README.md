# 美孕档案（BumpBook-Server）

## 开发背景

随着宝宝的到来，每次去医院都会进行多项检查，每家医院的手机App上报告单保存的时间各不相同，但是都只能看近期内的报告数据。纸质报告单堆积如山，与缴费、诊疗单等混在一起不好辨别。再加上公司买了保险，生育费用报销需要等生育完成后，一起提交保险公司才可以进行报销。因此，开发此小程序在老婆每次检查完成后，将检查结果，发票进行保存。以便后续使用！

## 基础环境

- jdk >= 1.8
- Mysql >= 5.7
- Maven >= 3.0
- Redis >= 3

## 系统功能

**系统设计思想**：以家庭为单位，首次进入可建立家庭（家庭管理员）。管理员可以进行档案维护；普通用户申请加入家庭。成员加入后，可以浏览、下载家庭所有档案数据，但是无修改权限。

### 系统登录

1. 用户登录：支持小程序用户一键登录

### 主页信息

1. 预产期：根据管理员设置的预产期，计算目前孕周
2. 准妈妈本周情况：根据孕周针对此阶段的健康指导和建议
3. 心理变化：根据孕周了解当前阶段的情绪变化和心理压力，寻找合适的调节方法
4. 关爱提醒：根据孕周提示目前注意事项
5. 饮食建议：根据孕周推荐的饮食搭配和营养摄入
6. 准爸爸能做什么：根据孕周帮助未来爸爸了解他们在每个阶段可以做些什么，共同迎接新生命的到来

### 档案管理

1. 档案新增：新增选择日期的档案
2. 文件上传：上传文件到指定日期
3. 文件删除：长按文件，可删除指定文件
4. 文件预览：单击可进行文件预览

### 个人信息维护

1. 个人信息：用户昵称、头像维护
2. 家庭编号：长按可进行家庭编号复制

### 家庭管理

1. 每人只能加入一个家庭
2. 首次登录账号可以选择新建家庭或加入家庭
3. 管理员可以解散家庭、普通成员只能退出家庭

## 体验地址

![gh_a2fe82ede5a8_258](https://nas.ccqi.icu:15890/images/2024/03/202403191401098.jpg)

## APP截图

<table>
    <tr>
        <td><img src="https://nas.ccqi.icu:15890/images/2024/03/202403191411896.PNG"/></td>
        <td><img src="https://nas.ccqi.icu:15890/images/2024/03/202403191411205.PNG"/></td>
    </tr>
    <tr>
        <td><img src="https://nas.ccqi.icu:15890/images/2024/03/202403191411226.png"/></td>
        <td><img src="https://nas.ccqi.icu:15890/images/2024/03/202403191412646.png"/></td>
    </tr>
</table>