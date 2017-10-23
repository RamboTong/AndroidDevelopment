# React Native props
> Most components can be customized when they are created, with different parameters. These creation parameters are called props.


## 1、属性定义
### 1.1属性默认值
`static defaultPorps{    
prop-name1:prop-value1,   
prop-name2:prop-value2,  
prop-name3:prop-value3  
}
`

### 1.2属性类型设置  
`
static propTypes{
prop-name1:propTypes.string,
prop-name2:propTypes.number,
prop-name3:propTypes.string.isRequired,
}
`

## 2、使用技巧
### 2.1延展操作符  
**定义**   
`var params={prop-name1:prop-value1,prop-name2:prop-value2,prop-name3:prop-value3}  `

**组件中使用**  
`{...params}  `

### 2.2解构赋值
基于延展操作符已经定义params的前提  
**定义**  
`var {prop-name1,prop-name2}=params  `

**组件中使用**  
`prop-name1={prop-name1} ` 
`prop-name2={prop-name2}`  




