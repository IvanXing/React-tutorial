### React 知识点总结

* 声明式开发（操作完数据然后渲染）
* 可以与其它框架并存 （index.html中的root）
* 组件化
* 单向数据流
* 视图层框架（多层组件数据流单向，叠加复杂，复杂情况下加redux flux等数据流框架）
* 函数式编程（功能解耦，便捷于前端自动化测试）


* propTypes 和 defaultProps 
    * 类型检测和默认值

* props state 与 render 函数
    * 当组件的state或者props发生改变时，render函数就会重新执行
    * 当父组件的render函数被运行时，它的子组件的render都将重新运行一次

* 虚拟DOM

