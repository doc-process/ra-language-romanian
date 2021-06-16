# Romanian Messages for React-Admin

Romanian messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

## Installation

```sh
npm install --save @docprocess/ra-language-romanian
```

or

```sh
yarn add @docprocess/ra-language-romanian
```

## Usage

```js
import romanianMessages from "ra-language-romanian";
import polyglotI18nProvider from "ra-i18n-polyglot";

const messages = {
    ro: romanianMessages,
};
const i18nProvider = polyglotI18nProvider((locale) => messages[locale]);

<Admin locale="ro" i18nProvider={i18nProvider}>
    ...
</Admin>;
```

## License

This translation is licensed under the MIT License.
