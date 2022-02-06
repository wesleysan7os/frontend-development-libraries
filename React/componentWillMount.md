```javascript
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
  }
  componentWillMount() {
    console.log('this does not exists')
  }
  render() {
    return <div />
  }
};
```