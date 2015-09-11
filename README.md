# gulp
deep learn gulp and summary

# 安装gulp

sudo npm install -g gulp

第五步：新建Gulpfile文件，运行gulp

安装好gulp后我们需要告诉它要为我们执行哪些任务，首先，我们自己需要弄清楚项目需要哪些任务。

检查Javascript
编译Sass（或Less之类的）文件
合并Javascript
压缩并重命名合并后的Javascript
安装依赖

npm install gulp-jshint gulp-sass gulp-concat gulp-uglify gulp-rename --save-dev
提醒下，如果以上命令提示权限错误，需要添加sudo再次尝试。
新建gulpfile文件

现在，组件都安装完毕，我们需要新建gulpfile文件以指定gulp需要为我们完成什么任务。

gulp只有五个方法： task，run，watch，src，和dest，在项目根目录新建一个js文件并命名为gulpfile.js，把下面的代码粘贴进去：