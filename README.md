# Check Internet connection

Using this package you can get status of user's internet connection.

Just Import the package.


## Usage/Examples

```javascript
import useNetworkStatus from 'react-isonline-checker'

function App() {
  const networkStatus = useNetworkStatus();
 if(networkStatus===false) return <h1>Looks like you are offline</h1>
  return (
    <div className="App">
      <h1>Hello World</h1>
    </div>
  );
}
