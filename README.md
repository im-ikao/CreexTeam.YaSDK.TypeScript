# CreexTeam.YaSDK.TypeScript
Type definition for Yandex SDK
---
You can also go to [Analytics for Yandex Games](https://analytics.creex.team), or [support me](https://boosty.to/creex_team)
Contact me: [Telegram](https://t.me/imikao)

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
