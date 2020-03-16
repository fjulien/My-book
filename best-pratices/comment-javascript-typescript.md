# Style comment for typescript or javascript
Remember pratices how comment my code
## - Resume:
```typescript
// set year only if not the same year as now
    if (dateYear !== nowYear) options.year = 'numeric';

/**
 * Send custom request using fetch api
 * @param nameParams { String } url for post
 * @param nameParams { String } method ...
 * @param nameParams { Object } body in html content
 * @return { Promise }
 */
function ajax(url, method, body) {
    …
}
```

## - Comment inline:
```typescript
// set year only if not the same year as now
if (dateYear !== nowYear) options.year = 'numeric';
```

## - Default comment:
```typescript
/**
 * Descript
 * Params
 * Return
 */
```

## - Wrap comment:
```typescript
/**
 * ...
 */
```

## - @Params:
```typescript
/**
 * @param { Type params} Descript params
 */
```

## - @Return:
```typescript
/**
 * @return { Type return }
 */
```

## - Params type:
```typescript
/**
 * @param { String } url
 // if params is null
 * @param { ?Integer } age
 // All types
 * @param { * } 
 // Params optional
 * @param { Object } [res]
 * @param { Integer } age
 // Default value
 * @param { String } [gender=male]
 // Required value of params
 * @param { String="male, female" } gender
  * @param { String | Int } id

 // Limit size
 * @param { String{..25} } password
 * @param { String{10..25} } password
 * @param { Integer{10000-99999} } zipcode

 //Object 
 * @param { {name: String, age: Integer} }
 
 // Array
 * @param { Object[] } students
 * @param { string[] } studentsNames

 // Callback
 * @param { Function(err<Error | Null>, user<Object>) } callback
 //Number parameter variable
 * @param { ...HTMLElement | ...NodeList }
 
 * @class
 * @classdesc ...
 */
```

## - @ Return type:
```typescript
/**
 * @return { (Number | Error) }

 * @return { Promise }
 * @return { Promise.resolve<String> } articleId
 * @return { Promise.reject<Error> } knex Err or BadRequestError
 */
```
 
#### [Home](https://fjulien.github.io/My-book)
