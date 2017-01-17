## cnIDCardNumberValidation
中国公民身份证号码合法性校验

## SUPORT
- node.js
- require.js
- sea.js

## API
```javascript
/**
 * 身份证号码校验
 * @param  {String} idStr - 身份证号码
 * @return {false|Object} - 合法则返回信息(省，生日，性别)，否则 false
 */
cnIDCardNumberValidate(str)
```

## USAGE
```javascript
    console.log(cnIDCardNumberValidate('51010119840310628x'))
    console.log(cnIDCardNumberValidate('110108199611240189'))
    console.log(cnIDCardNumberValidate('14062319821229451X'))
    console.log(cnIDCardNumberValidate('411281197408104056'))
    console.log(cnIDCardNumberValidate('372324196912030043'))
    console.log(cnIDCardNumberValidate('440902198301240076'))
    console.log(cnIDCardNumberValidate('431381197606166011'))
    console.log(cnIDCardNumberValidate('910207198905061687'))
```

