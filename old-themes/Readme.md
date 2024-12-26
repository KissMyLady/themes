The built-in CSS will be replaced after update / reinstall, DO NOT MODIFY THEM.

Refer https://support.typora.io/Add-Custom-CSS/ when you want to modify those CSS.
Refer https://support.typora.io/About-Themes/ if you want to create / install new themes. 


主题获取: http://theme.typora.io/

## Drake 系列主题

调整侧边栏
```css
.cm-s-inner .cm-header, .cm-s-inner.cm-header {
    color: #FFD760;
    font-weight: normal;
}

.sidebar-tabs {
    border-bottom: none;
}

/* height light 取消圆角 */
#write mark {
    /*border: .1em solid var(--height-light-border-color);*/
    border: 1px solid var(--height-light-border-color);
    color: var(--height-light-color);
    background-color: transparent;
    padding: .1rem .5rem;
    /*border-radius: 2rem;*/
    border-radius: 0.5px;
    margin: 0 .2rem;
    font-size: .95rem;
}

/* 左边滑动栏 颜色*/
#typora-sidebar {
    font-size: inherit;
    font-family: var(--title-font);
    border-right: 2px solid #6a5e7938;
}

/*左边滑动栏 字体大小 sidebar*/
.file-library-node.file-tree-node.file-node-root {
    font-size: var(--file-tree-text-size);
}

/*右侧滑动 颜色*/
::-webkit-scrollbar-thumb{
    background: rgba(183, 77, 246, 0.3);
}
```


padding的用法
```js
/* 所有边都设置为20px的内边距 */
padding: 20px;

/* 上边和下边为10px，左边和右边为20px的内边距 */
padding: 10px 20px;

/* 上边为10px，右边和左边为15px，下边为20px的内边距 */
padding: 10px 15px 20px;

/* 上边为10px，右边为15px，下边为20px，左边为25px的内边距 */
padding: 10px 15px 20px 25px;
```