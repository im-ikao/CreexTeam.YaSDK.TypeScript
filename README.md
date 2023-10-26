# CreexTeam.YaSDK.TypeScript
Type definition for Yandex SDK

## Getting started

Here’s an example of how to import and initialize sdk

```tsx
import { YandexGames } from "ysdk";
const sdk = YaGames.init();
```

### Ad Display component

```tsx
import { YandexGames } from "ysdk";
const sdk = YaGames.init();

const callbacks = {
      onClose:  function () {},
    };

sdk.adv.showFullscreenAdv({ callbacks });

```
