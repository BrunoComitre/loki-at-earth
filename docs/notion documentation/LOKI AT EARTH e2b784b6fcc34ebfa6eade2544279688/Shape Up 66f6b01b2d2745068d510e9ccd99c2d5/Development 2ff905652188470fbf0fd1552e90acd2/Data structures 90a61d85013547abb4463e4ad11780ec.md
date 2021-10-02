# Data structures

# Structures

## Deck

Example:

```jsx
{
	'id': string,
	'name': string,
	'description': string,
	'tags': [string], // Exemple: algorithm, variables, functions, etc.
	'category': string, // Exemple: java, python, swift, git, etc.
	'cards': [
		{
			'id': string,
			'question': [Block],
			'answer': [Block],
		}
	]
}
```

---