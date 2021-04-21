

``` bash
$ npm install  weex-toolkit -g  // 建议使用淘宝源cnpm  有可能出现下载失败问题
$ weex create <项目名称>  
// 注意：选择选项是：a. 是否安装依赖，选择 yes
	               b.模板的时候，选择 taobao / npm 其中一个创建失败，weex repair  -- 重新选择，换另一个即可
$ cd my-project 
$ npm start
```

## How to use less/sass/pug

Take `sass` for example:

```
$ npm i node-sass sass-loader --save
```

Then, you just need to change the `style` tag as: `<style lang="sass"><style>`.

## How to create your own template

See [How-to-create-your-own-template](https://github.com/weex-templates/How-to-create-your-own-template).