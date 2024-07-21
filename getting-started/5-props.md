# Props

Similiar to html attributes, react allows you to share data between components using props.

## Example

> **Post.jsx**
```js
// props: { author: "", content: "" }
function Post(props) {
    return (
        <>
            <strong>{props.author}</strong>
            <p>{props.content}</p>
        </>
    )
}

export Post
```

Your components can be used inside other components
> **App.jsx**

```js
import { Post } from './Post'

function App() {
    const posts = [
        {
            author: "Ariel Evangelista",
            content: "React is awesome"
        },
        {
            author: "Ariel Evangelista",
            content: "Never stop learning"
        }
    ]
    return (
        <>
            {
                posts.map((post) => (
                    <Post author={post.author} content={post.content} />
                ))
            }
        </>
    )
}
```