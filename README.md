
### react的相关js库
-- react.js
-- react-dom.js
-- 查找react对应版本的以上两个库如下
- react: https://unpkg.com/react@17.0.1/umd/
- react-art: https://unpkg.com/react-art@17.0.1/umd/
- react-dom: https://unpkg.com/react-dom@17.0.1/umd/
- react-is: https://unpkg.com/react-is@17.0.1/umd/
- react-test-renderer: https://unpkg.com/react-test-renderer@17.0.1/umd/
- scheduler: https://unpkg.com/scheduler@0.20.1/umd/
-- 在html文件中引入以上两个库就可以使用react,但是因为react库又是基于es6语法，所以
我们还需要引入babel进行编译，确保能在多个平台兼容