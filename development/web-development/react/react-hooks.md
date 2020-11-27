# React hooks

## Notes

### useState

```jsx
import React, { useState } from 'react';

export const App = () => {
    const [state, setState] = useState({
        count: 0
    })
    
    return (
        <button
            onClick={
                () => setState(prev => ({...prev, count: state.count + 1}))
            }
        >
            Increment
        </button>
    )
}
```

### useReducer

```jsx
import React, { useReducer } from 'react';

const reducer = (state, action) => {
    switch(action.type) {
        case 'CHANGE_NAME':
            return {...state, name: action.payload.name}
        default:
            return {...state}

export const App = () => {
    const [state, dispatch] = useReducer(reducer, { name: '' })
    
    return (
        <button
            onClick={() => {
                dispatch({
                    action: 'CHANGE_NAME',
                    payload: 'John'
                })
            }}
        >
            Change name
        </button>
    )
```

## Links

* [https://www.youtube.com/playlist?list=PLZlA0Gpn\_vH8EtggFGERCwMY5u5hOjf-h](https://www.youtube.com/playlist?list=PLZlA0Gpn_vH8EtggFGERCwMY5u5hOjf-h)

