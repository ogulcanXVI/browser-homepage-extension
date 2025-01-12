The "Browser Homepage Extension" provides real-time Bitcoin statistics and local weather updates tailored to your location.

Experience it [here](https://homepage-extension.netlify.app).

![Screenshot (1)](https://github.com/user-attachments/assets/32baca44-7766-4fb0-ae0c-2e034dd2938f)

JavaScript concepts covered in this code:

### 1. **Variables and Constants**
   - Use of `let` and `const` to define variables and constants (`weatherAPIKey`, `unsplashAPIKey`).

### 2. **Async/Await and Promises**
   - `async` functions and `await` keywords for handling asynchronous operations like API calls.
   - Use of `fetch()` to make HTTP requests.
   - Error handling with `try...catch`.

### 3. **Template Literals**
   - Dynamic string creation using backticks (``) and `${}` for embedding variables (e.g., URLs, HTML content).

### 4. **DOM Manipulation**
   - Modifying the DOM using `document.getElementById`, `innerHTML`, `textContent`, and `style`.

### 5. **API Integration**
   - Integration with external APIs such as:
     - **Unsplash API** for random background images.
     - **CoinGecko API** for cryptocurrency data.
     - **OpenWeatherMap API** for weather data.

### 6. **Geolocation API**
   - Using `navigator.geolocation.getCurrentPosition` to get the user's current location.

### 7. **Error Handling**
   - Gracefully handling errors with `try...catch` blocks.
   - Checking the response status using `res.ok`.

### 8. **Interval and Time Functions**
   - Using `setInterval` to update the time every second.
   - Displaying the current time with `toLocaleTimeString`.

### 9. **Object and Array Destructuring**
   - Accessing specific properties from API response objects (e.g., `data.weather[0].icon`).

### 10. **Dynamic Styles**
   - Changing the `backgroundImage` of the document dynamically.

### 11. **String Methods**
   - Using string methods for formatting (e.g., `${Math.round(data.main.temp)}º`).

### 12. **HTTP Request and Response Handling**
   - Parsing JSON responses with `res.json()`.
