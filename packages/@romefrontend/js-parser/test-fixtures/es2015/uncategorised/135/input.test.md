# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 135`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 78
			index: 78
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "input.js"
					identifierName: "A"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 6
						index: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 78
					index: 78
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 78
						index: 78
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "get"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "foo"
								loc: Object {
									filename: "input.js"
									identifierName: "foo"
									end: Object {
										column: 24
										index: 24
										line: 1
									}
									start: Object {
										column: 21
										index: 21
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 24
									index: 24
									line: 1
								}
								start: Object {
									column: 21
									index: 21
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 29
								index: 29
								line: 1
							}
							start: Object {
								column: 10
								index: 10
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 29
									index: 29
									line: 1
								}
								start: Object {
									column: 27
									index: 27
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 26
									index: 26
									line: 1
								}
								start: Object {
									column: 24
									index: 24
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 10
								index: 10
								line: 1
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 24
									index: 24
									line: 1
								}
								start: Object {
									column: 10
									index: 10
									line: 1
								}
							}
						}
					}
					JSClassMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "foo"
								loc: Object {
									filename: "input.js"
									identifierName: "foo"
									end: Object {
										column: 44
										index: 44
										line: 1
									}
									start: Object {
										column: 41
										index: 41
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 44
									index: 44
									line: 1
								}
								start: Object {
									column: 41
									index: 41
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 50
								index: 50
								line: 1
							}
							start: Object {
								column: 30
								index: 30
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 50
									index: 50
									line: 1
								}
								start: Object {
									column: 48
									index: 48
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 30
								index: 30
								line: 1
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 44
									index: 44
									line: 1
								}
								start: Object {
									column: 30
									index: 30
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 47
									index: 47
									line: 1
								}
								start: Object {
									column: 44
									index: 44
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "v"
									loc: Object {
										filename: "input.js"
										identifierName: "v"
										end: Object {
											column: 46
											index: 46
											line: 1
										}
										start: Object {
											column: 45
											index: 45
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 46
												index: 46
												line: 1
											}
											start: Object {
												column: 45
												index: 45
												line: 1
											}
										}
									}
								}
							]
						}
					}
					JSClassMethod {
						kind: "get"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "foo"
								loc: Object {
									filename: "input.js"
									identifierName: "foo"
									end: Object {
										column: 58
										index: 58
										line: 1
									}
									start: Object {
										column: 55
										index: 55
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 58
									index: 58
									line: 1
								}
								start: Object {
									column: 55
									index: 55
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 63
								index: 63
								line: 1
							}
							start: Object {
								column: 51
								index: 51
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 63
									index: 63
									line: 1
								}
								start: Object {
									column: 61
									index: 61
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 60
									index: 60
									line: 1
								}
								start: Object {
									column: 58
									index: 58
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 51
								index: 51
								line: 1
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 58
									index: 58
									line: 1
								}
								start: Object {
									column: 51
									index: 51
									line: 1
								}
							}
						}
					}
					JSClassMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "foo"
								loc: Object {
									filename: "input.js"
									identifierName: "foo"
									end: Object {
										column: 71
										index: 71
										line: 1
									}
									start: Object {
										column: 68
										index: 68
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 71
									index: 71
									line: 1
								}
								start: Object {
									column: 68
									index: 68
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 77
								index: 77
								line: 1
							}
							start: Object {
								column: 64
								index: 64
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 77
									index: 77
									line: 1
								}
								start: Object {
									column: 75
									index: 75
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 64
								index: 64
								line: 1
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 71
									index: 71
									line: 1
								}
								start: Object {
									column: 64
									index: 64
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 74
									index: 74
									line: 1
								}
								start: Object {
									column: 71
									index: 71
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "v"
									loc: Object {
										filename: "input.js"
										identifierName: "v"
										end: Object {
											column: 73
											index: 73
											line: 1
										}
										start: Object {
											column: 72
											index: 72
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 73
												index: 73
												line: 1
											}
											start: Object {
												column: 72
												index: 72
												line: 1
											}
										}
									}
								}
							]
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```