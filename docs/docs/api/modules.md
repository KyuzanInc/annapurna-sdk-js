---
id: "modules"
title: "@kyuzan/annapurna-sdk-js"
sidebar_label: "Table of contents"
custom_edit_url: null
hide_title: true
---

# @kyuzan/annapurna-sdk-js

## Table of contents

### Classes

- [AnnapurnaSDK](classes/annapurnasdk.md)

## Type aliases

### BigNumber

Ƭ **BigNumber**: ethers.BigNumber

Defined in: [types/BigNumber.ts:3](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/BigNumber.ts#L3)

___

### Item

Ƭ **Item**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`authorAddress` | *string* |
`buyerAddress` | *string* \| *null* |
`currentBidderAddress`? | *string* \| *null* |
`currentPrice`? | *number* |
`description` | *string* |
`endAt`? | Date |
`imageURL` | *string* |
`initialPrice`? | *number* |
`itemId` | *string* |
`name` | *string* |
`networkId` | *1* \| *4* |
`price`? | *number* |
`signature` | *string* |
`startAt`? | Date |
`tokenId` | *number* |
`tokenURI` | *string* |
`tradeType` | *fixedPrice* \| *auction* |

Defined in: [types/Item.ts:1](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/Item.ts#L1)

___

### ItemLog

Ƭ **ItemLog**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`accountAddress` | *string* |
`createAt` | Date |
`price` | *number* |
`transactionHash` | *string* |
`type` | *bought* \| *bid* |

Defined in: [types/ItemLog.ts:1](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/ItemLog.ts#L1)

___

### NetworkId

Ƭ **NetworkId**: *1* \| *4*

Defined in: [types/NetworkId.ts:1](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/NetworkId.ts#L1)

___

### Token

Ƭ **Token**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`author` | *string* |
`contractAddress` | *string* |
`description` | *string* |
`image` | *string* |
`imageIpfsURI` | *string* |
`name` | *string* |
`tokenId` | *number* |
`tokenURI` | *string* |

Defined in: [types/Token.ts:1](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/Token.ts#L1)

___

### WalletInfo

Ƭ **WalletInfo**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`address` | *string* |
`balance` | [*BigNumber*](modules.md#bignumber) |

Defined in: [types/WalletInfo.ts:3](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/WalletInfo.ts#L3)

___

### WalletSetting

Ƭ **WalletSetting**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`fortmatic` | *object* |
`fortmatic.key` | *string* |

Defined in: [types/WalletSetting.ts:1](https://github.com/KyuzanInc/annapurna-sdk-js/blob/ec1c32d/src/types/WalletSetting.ts#L1)
