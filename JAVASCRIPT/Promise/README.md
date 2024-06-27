# Promise

When a function completes, a callback function provides a nice solution for handling the corresponding return. However, one of our goals is for related operations to run sequentially, so we end up waiting for results with the callback function. If we had a structure where we could give a word - promise - while waiting for the results, we could proceed once we get the desired outcome or handle another task if we encounter an error. This is where the Promise structure comes into play.

A Promise is a JavaScript object that represents the result of an operation. The Promise object takes two parameters: Resolve and Reject, ensuring that operations specified by Resolve are performed in positive outcomes and those specified by Reject in negative outcomes. The Promise structure handles successful results with `.then()` and handles errors with `.catch()`.

Asynchronous transactions are operations that allow other transactions to continue while waiting for one transaction to be completed. Promises are an object that represents the value that will be returned upon successful completion or failure of an operation.

```javascript
function fetchData() {
    return new Promise(function(resolve, reject) {
        // Simulated asynchronous data fetching operation
        setTimeout(function() {
            let data = { name: 'John', age: 30 };
            resolve(data); //Data successfully retrieved, resolve called
// Example for error case: reject(new Error('Data could not be fetched.'));
        }, 2000); // Operation will be completed in 2 seconds
    });
}

// 
Promise usage
fetchData()
    .then(function(data) {
        console.log('Veri alındı:', data);
        // Additional operations can be performed with the data obtained here
    })
    .catch(function(error) {
        console.error('Hata oluştu:', error.message);
        // Actions to be taken in case of an error
    });
```