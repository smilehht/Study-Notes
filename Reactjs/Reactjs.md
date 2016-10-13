## Reactjs

**ReactDOM.render()**

​	1、ReactDOM.render 是 React 的最基本方法，用于将模板转为 HTML 语言，并插入指定的 DOM 节点。



**JSX语法**

​	1、JSX语法中，允许HTML与Javascript混写



**DOM节点**

​	1、组件并不是真实的 DOM 节点，而是存在于内存之中的一种数据结构，叫做虚拟 DOM （virtual DOM）。只有当它插入文档以后，才会变成真实的 DOM 。根据 React 的设计，所有的 DOM 变动，都先在虚拟 DOM 上发生，然后再将实际发生变动的部分，反映在真实 DOM上，这种算法叫做 [DOM diff](http://calendar.perfplanet.com/2013/diff/) ，它可以极大提高网页的性能表现。



**this.state**

​	1、组件是状态机，会随用户行为的改变而发生变化，这种变化可以保存在this.state对象中。当组件的状态发生变化时，调用this.state方法修改状态值，然后自动调用this.render方法，再次渲染组件。



**组件的生命周期**

* Mounting：已插入真实DOM——componentWillMount()、componentDidMount()
* Updating：正在被重新渲染——componentWillUpdate(object nextProps, object nextState)、componentDidUpdate(object prevProps, object prevState)
* Unmounting：已被移除真实DOM——componentWillUnmount()













