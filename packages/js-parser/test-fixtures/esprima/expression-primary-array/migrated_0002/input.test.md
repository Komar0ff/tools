# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-array > migrated_0002`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-primary-array/migrated_0002/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-primary-array/migrated_0002/input.js"
		end: Object {
			column: 10
			index: 10
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/expression-primary-array/migrated_0002/input.js"
				end: Object {
					column: 10
					index: 10
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/expression-primary-array/migrated_0002/input.js"
					end: Object {
						column: 10
						index: 10
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				left: JSAssignmentIdentifier {
					name: "x"
					loc: Object {
						filename: "esprima/expression-primary-array/migrated_0002/input.js"
						identifierName: "x"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				right: JSArrayExpression {
					loc: Object {
						filename: "esprima/expression-primary-array/migrated_0002/input.js"
						end: Object {
							column: 10
							index: 10
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
					elements: Array [
						JSNumericLiteral {
							value: 42
							format: undefined
							loc: Object {
								filename: "esprima/expression-primary-array/migrated_0002/input.js"
								end: Object {
									column: 8
									index: 8
									line: 1
								}
								start: Object {
									column: 6
									index: 6
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```