# Review-a-PR-MR
- remove <code>screen.debug()</code>
- please include <code>plugin:import/typescript</code> in .eslintrc.cjs file to remove eslint errors, This site was built using [GitHub Pages](https://ankur171.hashnode.dev/eslintrccjs).
- do not try to pull out constants, enums or interfaces in a seperate directory from the inside of a namespace because it would be better if all the related types, enums and interfaces are grouped together inside the namespace rather than fragmented in different directories.
- <code>describe(‘DisplayName’, () => {});</code>, A convention we use here is to wrap a component name in tags, i.e. <DisplayName />

- <strong>do not use hook 👇 after a conditional return statement.</strong>

```javascript
const handleSomething = () => {
  if(state) {
    return <Spinner />;
  }
};

useEffect(() => {
  // ...something
},[]);
```
- Do not use <code>refetch</code> when you get a fresh data from API.
  - Because ... in progress...

- **Leave Site?** <- you can not change the header message coming in the browser's alert box. This is the expected behaviour.
