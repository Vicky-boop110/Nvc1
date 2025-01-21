import React, { useState } from 'react';  
const MyComponent = () => {  
  const [count, setCount] = useState(0);  
  
  const handleIncrement = () => {  
    setCount(count + 1);  
  };  
  
  return (  
    <div>  
      <p>Count: {count}</p>  
      <button onClick={handleIncrement}>Increment</button>  
    </div>  
  );  
};  
