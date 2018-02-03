# api

阿里提供的bin验证接口
https://ccdcapi.alipay.com/validateAndCacheCardInfo.json?_input_charset=utf-8&cardNo=待验证卡号&cardBinCheck=true

true：{"bank":"CMB","validated":true,"cardType":"DC","key":"待验证卡号","messages":[],"stat":"ok"}

false: {"validated":false,"key":"待验证卡号","stat":"ok","messages":[{"errorCodes":"CARD_BIN_NOT_MATCH","name":"cardNo"}]}
       {"validated":false,"key":"aaaaaa","stat":"ok","messages":[{"errorCodes":"PARAM_ILLEGAL","name":"cardNo"}]}
