# Card 卡片

通用卡片容器。

## 何时使用

可承载文字、列表、图片、段落等，便于用户浏览内容。

## 示例

<code src="./demos/demo1.tsx"></code>

## Card

### 属性

| 属性            | 说明                | 类型                                                            | 默认值 |
| --------------- | ------------------- | --------------------------------------------------------------- | ------ |
| title           | header 左边区域     | `ReactNode`                                                     | -      |
| extra           | header 右边区域     | `ReactNode`                                                     | -      |
| headerStyle     | header 自定义样式   | `React.CSSProperties`                                           | -      |
| headerClassName | header 自定义类名   | `string`                                                        | -      |
| bodyStyle       | body 自定义样式     | `React.CSSProperties`                                           | -      |
| bodyClassName   | body 自定义类名     | `string`                                                        | -      |
| onClick         | 卡片点击事件        | `(event: React.MouseEvent<HTMLDivElement, MouseEvent>) => void` | -      |
| onHeaderClick   | header 区域点击事件 | `(event: React.MouseEvent<HTMLDivElement, MouseEvent>) => void` | -      |
| onBodyClick     | body 区域点击事件   | `(event: React.MouseEvent<HTMLDivElement, MouseEvent>) => void` | -      |
