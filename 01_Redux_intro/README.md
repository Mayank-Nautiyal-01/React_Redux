### **Introduction to Redux in React**  

Redux is a state management library that helps manage global state in React applications. It provides a **centralized store** to handle application data, making it easier to manage and debug complex state changes.  

### **Why Use Redux?**  
- Prevents **prop drilling** by sharing state across components.  
- Ensures **predictable state updates** with actions and reducers.  
- Helps manage **large-scale applications** with complex data flow.  

2. When to Use Redux?
Redux is useful in scenarios like:

✅ Large-Scale Applications: Where managing state locally in components becomes challenging.
✅ Shared State Across Components: When multiple components need access to the same data.
✅ Frequent State Changes: Apps with dynamic data that change frequently, like e-commerce carts, social media feeds, etc.
✅ Complex Data Flows: When multiple actions modify the same state.

🚫 Avoid Redux If:

Your app has minimal state management needs.

Data can be easily managed using React’s useState and useContext.  

### **How Does Redux Work?**  
1. **Store** – Holds the entire state of the app.  
2. **Actions** – Define the events that update the state.  
3. **Reducers** – Functions that specify how the state changes based on actions.  
4. **Dispatch** – Sends actions to update the store.  
5. **Selectors** – Retrieve state from the store.  

