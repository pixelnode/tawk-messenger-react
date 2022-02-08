<p align="center">
    <img width="250"
        src="./images/tawk-react-logo.png"
        alt="Tawk React logo">
</p>

<br/>

## Features
* Using React Hooks
* Documented and self-explaining methods
* Small size without any external libraries
* All Javascript API methods are available
* Maintained by the [tawk.to](https://www.tawk.to/) team.

<br/>

## Installation
The plugins are available in node and yarn package managers.
```bash
# Node
npm install @tawk.to/tawk-messenger-react

# Yarn
yarn add @tawk.to/tawk-messenger-react
```

<br/>

## Quickstart
Import the **tawk-messenger-vue** in your main component. The **propertyId** and **widgetId** will
be found on your tawk Dashboard.

Log in to your account and go to **Administration > Channels > Chat Widget**.

Using the API will need
to use the **useRef** to access the object functions from the **tawk-messenger-react** component.

```js
import TawkMessengerReact from '@tawk.to/tawk-messenger-react';

function App() {
    return (
        <div className="App">
            <TawkMessengerReact
                propertyId="property_id"
                widgetId="default"/>
        </div>
    );
}
```

<br/>

## Documentation
This project includes a `docs` folder with more details on the following:
1.  [How to Use](docs/how-to-use.md)
1.  [API Reference](docs/api-reference.md)

<br/>

## Other JS frameworks we support
- [Vue Js](https://github.com/tawk/tawk-messenger-vue)
- [Angular Js](https://github.com/tawk/tawk-messenger-angular)
- [Ember Js](https://github.com/tawk/tawk-messenger-ember)

<br/>

## Frequently Asked Questions

**Where can I find more information and support?**

Visit our [help center](https://help.tawk.to) or reach out in the chat on our [website](https://tawk.to).

**Where can I submit a suggestion or report a bug?**

Just message us on our [website](https://tawk.to). Our agents are available to assist you 24/7.