# vue-click-captcha

## 安装

### 1. 安装 vue-click-captcha

```
npm install vue-click-captcha
```

### 2. 部署后端环境

移步至 [clicaptcha-server](https://github.com/chenjacky131/vue-click-captcha) 项目

## 使用

```javascript
import VueClickcaptcha from 'vue-click-captcha'
VueClickcaptcha({
    src: 'http://localhost/clicaptcha.php',  // 后端地址
    success: '验证成功！',  // 成功提示，默认为“验证成功！”
    error: '未点中正确区域，请重试！',  // 错误提示，默认为“未点中正确区域，请重试！”
    callback: () => {
        // 校验成功后执行后续业务
    }
});
```

## 预览效果

![](https://i.loli.net/2019/07/24/5d37fa1ad6a0631208.png)
![](https://i.loli.net/2019/07/24/5d37f9e77ff5f52889.png)
![](https://i.loli.net/2019/07/24/5d37fa41a598430090.png)