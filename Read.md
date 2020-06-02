1)componentWillMount is executed before rendering, on both the server and the client side.

2)componentDidMount is executed after the first render only on the client side. This is where AJAX requests and DOM or state updates should occur.

3)shouldComponentUpdate should return true or false value. This will determine if the component will be updated or not. This is set to true by default.

4)componentDidUpdate is called just after rendering.

5)componentWillUnmount is called after the component is unmounted from the dom. 