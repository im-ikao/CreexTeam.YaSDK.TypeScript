# Yandex Games SDK TypeScript Types

This repository contains TypeScript type definitions for the Yandex Games SDK. The Yandex Games SDK is a set of tools and services provided by Yandex for developing games and interactive experiences.
You can also go to [Analytics for Yandex Games](https://analytics.creex.team), or [support me](https://boosty.to/creex_team)
Contact me: [Telegram](https://t.me/imikao)

## Overview

The Yandex Games SDK TypeScript types repository aims to provide developers with accurate and up-to-date type definitions for the Yandex Games SDK. With these types, developers can benefit from enhanced code completion, static type checking, and improved overall developer experience when working with the Yandex Games SDK in TypeScript projects.

## Features

- Comprehensive type definitions: The repository includes type definitions for all the major components and APIs of the Yandex Games SDK.
- Up-to-date with the latest SDK version: The type definitions are regularly updated to align with the latest version of the Yandex Games SDK, ensuring compatibility and accuracy.
- Improved development experience: By utilizing these TypeScript types, developers can leverage the power of static type checking, enabling early detection of potential errors and providing better autocompletion within their IDEs.
- Easy integration: The types can be easily integrated into TypeScript projects by installing the package;
  
## Usage
Import the necessary types into your TypeScript files:

```tsx
import { YandexGames } from "ysdk";
const sdk = YaGames.init();
```
Start benefiting from enhanced type checking and autocompletion provided by the Yandex Games SDK TypeScript types.

### Ad Display component

```tsx
import { YandexGames } from "ysdk";
const sdk = YaGames.init();

const callbacks = {
      onClose:  function () {},
    };

sdk.adv.showFullscreenAdv({ callbacks });

```

## Contributing

Contributions to this repository are welcome. If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Make sure to follow the contribution guidelines outlined in the repository.

## License

The Yandex Games SDK TypeScript types repository is licensed under the MIT License. Please see the [LICENSE](https://github.com/your-username/your-repository/blob/main/LICENSE) file for more details.

## Resources

- [Yandex Games SDK documentation](https://yandex.ru/dev/games/doc/ru/sdk/sdk-about)

We hope you find these TypeScript types helpful for your Yandex Games SDK development. Happy coding!
