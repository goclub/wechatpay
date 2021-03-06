# 微信支付 API v3 Go SDK - partnertransferbatch

No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

## 总览
本 SDK 由 WechatPay APIv3 SDK 生成器生成。生成器基于 [OpenAPI Generator](https://openapi-generator.tech) 构建。

- API 版本: 0.0.2

## 接口列表

所有URI均基于微信支付 API 地址：*https://api.mch.weixin.qq.com*

服务名 | 方法名 | HTTP 请求 | 描述
------------ | ------------- | ------------- | -------------
*TransferBatchApi* | [**GetTransferBatchByNo**](TransferBatchApi.md#gettransferbatchbyno) | **Get** /v3/partner-transfer/batches/batch-id/{batch_id} | 微信支付批次单号查询批次单
*TransferBatchApi* | [**GetTransferBatchByOutNo**](TransferBatchApi.md#gettransferbatchbyoutno) | **Get** /v3/partner-transfer/batches/out-batch-no/{out_batch_no} | 商家批次单号查询批次单
*TransferBatchApi* | [**InitiateTransferBatch**](TransferBatchApi.md#initiatetransferbatch) | **Post** /v3/partner-transfer/batches | 发起批量转账
*TransferDetailApi* | [**GetTransferDetailByNo**](TransferDetailApi.md#gettransferdetailbyno) | **Get** /v3/partner-transfer/batches/batch-id/{batch_id}/details/detail-id/{detail_id} | 微信支付明细单号查询明细单
*TransferDetailApi* | [**GetTransferDetailByOutNo**](TransferDetailApi.md#gettransferdetailbyoutno) | **Get** /v3/partner-transfer/batches/out-batch-no/{out_batch_no}/details/out-detail-no/{out_detail_no} | 商家明细单号查询明细单


## 类型列表

 - [AuthType](AuthType.md)
 - [CloseReasonType](CloseReasonType.md)
 - [FailReasonType](FailReasonType.md)
 - [GetTransferBatchByNoRequest](GetTransferBatchByNoRequest.md)
 - [GetTransferBatchByOutNoRequest](GetTransferBatchByOutNoRequest.md)
 - [GetTransferDetailByNoRequest](GetTransferDetailByNoRequest.md)
 - [GetTransferDetailByOutNoRequest](GetTransferDetailByOutNoRequest.md)
 - [InitiateTransferBatchRequest](InitiateTransferBatchRequest.md)
 - [InitiateTransferBatchResponse](InitiateTransferBatchResponse.md)
 - [TransferBatchEntity](TransferBatchEntity.md)
 - [TransferDetailCompact](TransferDetailCompact.md)
 - [TransferDetailEntity](TransferDetailEntity.md)
 - [TransferDetailInput](TransferDetailInput.md)
 - [TransferScene](TransferScene.md)
 - [TransferUseType](TransferUseType.md)

