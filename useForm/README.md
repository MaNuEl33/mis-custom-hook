# useForm Hook

Ejemplo: 

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }

    const [ formValues, handleInputchange, reset ] = useForm( initialForm )
```