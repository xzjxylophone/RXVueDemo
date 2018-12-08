引用子组件的格式：

<editor :needBlank='true'
:inputText="fillingQuestionData.body.stem.body"
@editorEmit="onChangeStem"
@countBlank="onChangeBlank">
</editor>

当前

推荐使用:inputText

不推荐使用:input-text



this  推荐使用 that，不推荐使用self



临时 的 缩写： 推荐tmp，不推荐使用temp

tmpIndex， tmpValue， tmpKey 



vue文件名：

TalXXX.vue



Vue子组件：



props 输入参数：

inputXXX， 参数必须有type和default



computed

computedXXX



// props

// data

// comput



Vue文件中methods的代码顺序：

/* action */

所有html自带事件放在一起， 并以 XXXOnClick命名

或者  XXXOnChange

/* component1 emit */

收到子组件的emit

/* component2 emit */

收到子组件的emit

/* public */

需要开发的

/ * output */

所有需要对外提供的，并以 outputXXX命名

/* private */

所有内部使用到的函数， privateXXXXX， 可以加可以不加，看情况

/* ajax */

所有有关网络请求的



子组件需要对父组件的回调

XXXEmit



数组变量的命名：

推荐： XXXArray

不推荐：XXXArr, XXXList



vue 方法放置顺序
1.components

2.props

3.data

4.created

5.mounted

6.activited

7.update

8.beforeRouteUpdate

9.methods

10.filter

11.computed

12.watch



vue 文件中html、js、css三部分放置顺序

1. template
2. script
3. style



