sdk发送的Client-request中没有指明Content-Type为application/json
结果为:"error":{
            "code":1,
            "detail": "json syntax error(None is not of type 'Object')"
       }

预想结果:"error":{
            "code":2,
            "detail": ""
}