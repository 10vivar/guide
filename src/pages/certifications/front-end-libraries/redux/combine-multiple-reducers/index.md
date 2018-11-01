Let’s break the instructions down to figure exactly what it’s asking.

  1. Finish writing the rootReducer() function using the Redux.combineReducers() method.
  2. Assign counterReducer to a key called count and authReducer to a key called auth.

Great! so now do the steps!

finish writing the function passing an object argument with count and auth keys.

```
const rootReducer = Redux.combineReducers({
  count: counterReducer,
  auth: authReducer
});
```


