# Components

Components are small pieces of code that can be used for decouple and to prevent repeating code across your app.


## Example

> **Post.jsx**
```js
function Post() {
    return <p>React is awesome</p>
}

export Post
```

Your components can be used inside other components
> **App.jsx**

```js
import { Post } from './Post'

function App() {
    return (
        <>
            <Post />
            <Post />
        </>
    )
}
```