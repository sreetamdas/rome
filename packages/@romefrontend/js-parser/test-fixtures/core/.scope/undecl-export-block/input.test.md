# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > scope > undecl-export-block`

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
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 47
			line: 5
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSBlockStatement {
			directives: Array []
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 1
					index: 27
					line: 3
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: Array [
				JSFunctionDeclaration {
					id: JSBindingIdentifier {
						name: "encrypt"
						loc: Object {
							filename: "input.js"
							identifierName: "encrypt"
							end: Object {
								column: 18
								index: 20
								line: 2
							}
							start: Object {
								column: 11
								index: 13
								line: 2
							}
						}
					}
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 23
							index: 25
							line: 2
						}
						start: Object {
							column: 2
							index: 4
							line: 2
						}
					}
					body: JSBlockStatement {
						body: Array []
						directives: Array []
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 23
								index: 25
								line: 2
							}
							start: Object {
								column: 21
								index: 23
								line: 2
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
								column: 20
								index: 22
								line: 2
							}
							start: Object {
								column: 18
								index: 20
								line: 2
							}
						}
					}
				}
			]
		}
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 18
					index: 46
					line: 4
				}
				start: Object {
					column: 0
					index: 28
					line: 4
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 16
							index: 44
							line: 4
						}
						start: Object {
							column: 9
							index: 37
							line: 4
						}
					}
					exported: JSIdentifier {
						name: "encrypt"
						loc: Object {
							filename: "input.js"
							identifierName: "encrypt"
							end: Object {
								column: 16
								index: 44
								line: 4
							}
							start: Object {
								column: 9
								index: 37
								line: 4
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "encrypt"
						loc: Object {
							filename: "input.js"
							identifierName: "encrypt"
							end: Object {
								column: 16
								index: 44
								line: 4
							}
							start: Object {
								column: 9
								index: 37
								line: 4
							}
						}
					}
				}
			]
		}
	]
}
```