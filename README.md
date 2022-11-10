## Question schema
```javascript
{
	id: "1",
	title: "Lorem ipsum dolor sit amet ",
	shortContent: "Proin rutrum metus at massa tincidunt ultricies. Mauris laoreet sagittis sodales.",
	content: ``,
	user: {
		id: "1",
		fullName: "Từ Trọng Đức"
	},
	createdTime: "2022-09-08 03:13:10",
	comments: [
		{
			id: "1",
			fullName: "Vũ Thị Thuỳ Dương",
			createdTime: "2022-09-08 06:46:10",
			avatar: "",
			content: `<p><span>auris nunc turpis, facilisis quis purus non, sollicitudin cursus enim. Integer non tortor bibendum, euismod orci nec, fermentum urna.</span></p>`
		},
		{
			id: "2",
			fullName: "Trần Bảo Long",
			createdTime: "2022-09-08 06:46:10",
			avatar: "",
			content: `<p><span >auris nunc turpis, facilisis quis purus non, sollicitudin cursus enim. Integer non tortor bibendum, euismod orci nec, fermentum urna.</span></p>`
		}
	],
	requestedAnswer: [
		{
			id: "1",
			fullName: "Vũ Thị Thuỳ Dương",
			createdTime: "2022-09-08 06:46:10",
			avatar: ""
		}
	],
	price: 10000,
	subject: {
		id: 1,
		name: "test"
	},
	major: {
		id: 2,
		name: "test"
	}
	},
```

## Majors schema
``` javascript
{
	majors: [
		{
			id: 1,
			name: "test",
			subjects: [
			{
				id: 1,
				name: "test subject"
			}
	]
	}
]
}
```
