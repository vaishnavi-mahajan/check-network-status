# Check Internet connection

Using this package you can get status of user's internet connection.

Just Import the package.


## Install

```js
npm i check-user-network-status
```

#### ◎ Import
```js
import useNetworkStatus from 'check-user-network-status';
```

#### ◎ Usage
```js
function App() {
 const networkStatus = useNetworkStatus();
 if(networkStatus===false) return <h1>Looks like you are offline</h1>
}
```

## ◎ Examples

```javascript
import useNetworkStatus from 'check-user-network-status';

function App() {
  const networkStatus = useNetworkStatus();
 if(networkStatus===false) return <h1>Looks like you are offline</h1>
  return (
    <div className="App">
      <h1>Hello World</h1>
    </div>
  );
}
```