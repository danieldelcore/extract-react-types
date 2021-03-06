# babel-plugin-extract-react-types

> A Babel plugin to store the types of React components as a property on the component for documentation

## Install

```bash
yarn add babel-plugin-extract-react-types pretty-proptypes
```

## Usage

`.babelrc`

```json
{
  "plugins": ["babel-plugin-extract-react-types"]
}
```

```jsx
import SomeComponent from 'somewhere';
import Props from 'pretty-proptypes';

<Props heading="My Component" component={SomeComponent} />;
```

## Inspiration

- [babel-plugin-react-docgen](https://github.com/storybooks/babel-plugin-react-docgen)
