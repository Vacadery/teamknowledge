

# React

```js
function  handleSubmit(event) {
	event.preventDefault()
	const {
		username: { value: username },
		password: { value: password }
	} =  event.target
	onLogin(username, password)

}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM4MDgyNDQyNywtNDM3MjM1MDUxXX0=
-->