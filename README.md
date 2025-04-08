<div align="center">

[![Avatar](https://avatars.githubusercontent.com/u/55276797?v=4)](https://github.com/FurryR)

# 🐺 熊谷 凌

> _随风飘散。_

</div>

<div align="center">

[<img src="./res/icons/discord.svg" alt="Discord" width="50" />](https://discord.com/users/im_furryr)&nbsp;&nbsp;&nbsp;&nbsp;[<img src="./res/icons/telegram.svg" alt="Telegram" width="50" />](https://t.me/DevRinOwO)&nbsp;&nbsp;&nbsp;&nbsp;[<img src="./res/icons/twitter.svg" alt="X (formerly Twitter)" width="50" />](https://x.com/im_furryr)&nbsp;&nbsp;&nbsp;&nbsp;[<img src="./res/icons/mention.svg" alt="Email" width="50" />](mailto:awathefox@gmail.com)

</div>

```typescript
import { Nullqwertyuiop } from 'https://github.com/Nullqwertyuiop'

function final(target: Object, key: string | symbol, descriptor: PropertyDescriptor) {
  descriptor.writable = false
}

class FurryR extends Nullqwertyuiop {
  readonly name: string = '熊谷 凌'
  description: string = '什么都写的全栈(?)工程师'
  name: number = 16
  constructor() {
    super('谨以此纪念他的存在')
  }
  get status(): string {
    return '编写自己的博客'
  }
  @final
  get beloved(): never {
    throw new Error('不谈')
  }
}
```
