#useForm Hook

case example:

```
  const initialForm = {
    name: '',
    age: 0,
    email: ''
  }

  const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```

useCounter() // take a default value.