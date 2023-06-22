# 🗒️ Class 28 - Component Lifecycle / `useEffect` Hook

## Readings

### `useEffect` hook

- What is the main intended use case for the useEffect hook?
    > The `useEffect` is a React hook that lets us specify a side effect we want to occur that is caused by rendering vs an event.

- How does the effect’s logic interact with the component?
    > The setup function runs after a component is added or is mounted onto the page. with every re-render where the dependencies change, the effect would have to run a cleanup code and then a setup code.

- What is the importance of the return value from the effect’s logic function?
    > The return is important for the cleanup code logic. It runs the cleanup code a final time after the component is removed.
