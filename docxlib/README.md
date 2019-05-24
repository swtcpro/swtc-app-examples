# 无差别联盟连支持

## [增强](../docswtc)
## 安装
```bash
# npm install swtc-x-lib
```

## 使用 (nodejs)
```javascript
const Factory = require('swtc-x-lib').Factory  // or import { Factory } from 'swtc-x-lib'
// 井通库
const RemoteJ = Factory('jingtum')  // or const RemoteJ = Factory('swt')
// 相应组件
// const WalletJ = RemoteJ.Wallet
// const TransactionJ = RemoteJ.Transaction
// const RequestJ = RemoteJ.Request
// const AccountJ = RemoteJ.Account
// const OrderBookJ = RemoteJ.OrderBook
// const utilsJ = RemoteJ.utils
// 商链库
const RemoteB = Factory('bizain')   // or const RemoteB = Factory('bwt')
// 相应组件
// const WalletB = RemoteB.Wallet
// const TransactionB = RemoteB.Transaction
// const RequestB = RemoteB.Request
// const AccountB = RemoteB.Account
// const OrderBookB = RemoteB.OrderBook
// const utilsB = RemoteB.utils
```

## 文档和实例
### 按照如上方式引用后可以直接使用井通的文档和实例
#### [实例](../)
#### [lib](../docswtc)

## 参与及WEB使用
1. fork github.com/swtcca/swtc-x-lib 
2. clone
3. npm install
4. npm run tsc
5. npm run test
6. build static web version
   - `npm run build`
   - `npm run build:production`
   - located at dist/
   - library name is `swtc_x_lib`

## 缺陷
1. swtc-api 尚未支持联盟链
2. solidity 尚未支持联盟链
