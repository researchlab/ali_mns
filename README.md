# ali_mns

  阿里云消息服务MNS GO语言封装

  - 基于`github.com/souriki/ali_mns` 再次封装
	 - 新增 BatchReceiveMsg(numOfMessages int32, waitseconds ...int64) (respChan BatchMessageReceiveResponse, errChan error)
	 - 新增 ReceiveMsg(waitseconds ...int64) (resp MessageReceiveResponse, err error)
