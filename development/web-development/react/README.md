# React

### Code splitting

```jsx
const Component = React.lazy(() => import('./path/to/component'))
```

## Links

[https://github.com/facebook/create-react-app/blob/master/CHANGELOG.md](https://github.com/facebook/create-react-app/blob/master/CHANGELOG.md) - How to update react-scripts

## Higher order components (HOC)
Components that accept other components as props or return other components.
[[programming-terms|Higher order functions]]

```jsx
// App.jsx

const withExtraProps = (component) => {
	const Component = component
	
	return function(props) {
		return <Component {...props} />
	}
}

const App = () => {
	return (
		<h1>App</h1>
	)
}

const AppWithExtra = withExtraProps(App)
export default AppWithExtra


```
