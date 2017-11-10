# React Native state
>  state实现组件的动态刷新  
>  可读可写


## 1、属性定义
### 1.1 state关键字,状态默认值
`state{    
prop-name1:prop-value1,   
prop-name2:prop-value2,  
prop-name3:prop-value3  
}
`

### 1.2 构造器中定义state 
`
construtor(props){
super(props);
this.state{
state-name:state-value,
}
}
`

## 2、使用技巧
通过this.setState()方法来更新state，调用该方法后，React会重新渲染相关的UI。  
`
this.setState({
this.state.state-name:state-value-update
})
`



