# react-table-lumbini

A simple table component to create a table using data as array of objects.

### install package using npm
> npm install react-table-lumbini

### Import Component

> import Table from "react-table-lumbini"

### Use Array of Object for table data



> const data = [ <br/>
>	{id: 1, name: 'John', age: 20}, <br/>
>	{id: 2,	name: 'Jane', age: 21}, <br/>
>	{id: 3,	name: 'Joe', age: 22} <br/>
> ]

use tableData props to use table data. Keys of object is used as header and values are placed into the table body.

### Example:

```
import Table from "react-table-lumbini"

const data = [
	{id: 1,	name: 'John', age: 20},
	{id: 2,	name: 'Jane', age: 21},
	{id: 3,	name: 'Joe', age: 22}
]

function App() {
	return (
		<Table tableData={data} />
	)
}

ReactDOM.render(<App />,document.getElementById("#root"))

```


