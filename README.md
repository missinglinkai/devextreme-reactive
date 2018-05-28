# INTERNAL - HOW TO UPDATE:
1. install on other repo using yarn
2. copy to this branch (grid-material-ui)
3. change columnTitle decalartion on all files:
 3.1. columnTitle: string.isRequired, => columnTitle: oneOfType([object.isRequired, string.isRequired]),
 3.1. defaultProps => columnTitle: ''

# DevExtreme React Grid Material UI

A template suite used to render the React Grid based on Material UI components.

[Website](https://devexpress.github.io/devextreme-reactive/react/grid/)
|
[Demos](https://devexpress.github.io/devextreme-reactive/react/grid/demos/)
|
[Docs](https://devexpress.github.io/devextreme-reactive/react/grid/docs/)

## License

[DevExtreme licensing](https://js.devexpress.com/licensing/).
