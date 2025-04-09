# flex-yeo

install
```
yarn add flex-yeo
npm install flex-yeo
```

```js
import { Flex } from 'flex-yeo';

const App = () => {
  return (
    <Flex
      width="100vw"
      height="100vh"
      justifyContent="center"
      alignItems="center"
      gap={40}
      isColumn
    >
      <div style={{ background: 'tomato', padding: '20px' }}>Box 1</div>
      <div style={{ background: 'skyblue', padding: '20px' }}>Box 2</div>
    </Flex>
  );
};

export default App;
```

https://www.npmjs.com/package/flex-yeo
