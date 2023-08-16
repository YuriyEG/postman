

// АВТОРИЗАЦИЯ ПОЛЬЗОВАТЕЛЯ
POST https://blog.kata.academy/api/users/login: {
  "Network": {
    "addresses": {
      "local": {
        "address": "127.0.0.1",
        "family": "IPv4",
        "port": 55115
      },
      "remote": {
        "address": "94.198.50.185",
        "family": "IPv4",
        "port": 443
      }
    },
    "tls": {
      "reused": true,
      "authorized": true,
      "authorizationError": null,
      "cipher": {
        "name": "TLS_AES_128_GCM_SHA256",
        "standardName": "TLS_AES_128_GCM_SHA256",
        "version": "TLSv1/SSLv3"
      },
      "protocol": "TLSv1.3",
      "ephemeralKeyInfo": {},
      "peerCertificate": {
        "subject": {
          "commonName": "blog.kata.academy",
          "alternativeNames": "DNS:blog.kata.academy"
        },
        "issuer": {
          "country": "US",
          "organization": "Let's Encrypt",
          "commonName": "R3"
        },
        "validFrom": "Jul  9 00:23:29 2023 GMT",
        "validTo": "Oct  7 00:23:28 2023 GMT",
        "fingerprint": "92:66:ED:48:43:B5:21:D1:85:63:1A:FC:2A:4C:83:83:00:E2:E0:58",
        "serialNumber": "03fa66f1b05b0a3194a98f73ad5b43baf175"
      }
    }
  },
  "Request Headers": {
    "content-type": "application/json",
    "authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0ZGQzZmViYzMxZGUxMWIwMGJjYzQ4MyIsInVzZXJuYW1lIjoieXVyaXllZ3RzZyIsImV4cCI6MTY5NzQxMDE0OSwiaWF0IjoxNjkyMjI2MTQ5fQ.4u2nsSCy627t8SZ1WyPnVmKJJqQAUzQpBsKsnHFuW4s",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "postman-token": "733a8a38-0d04-42c4-982e-edb8a1b97282",
    "host": "blog.kata.academy",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive",
    "content-length": "102"
  },
  "Request Body": "{\r\n  \"user\": {\r\n    \"email\": \"yuriygermanovich0202@gmail.com\",\r\n    \"password\": \"pass234445\"\r\n\r\n  }\r\n}",
  "Response Headers": {
    "server": "nginx/1.18.0 (Ubuntu)",
    "date": "Wed, 16 Aug 2023 23:25:12 GMT",
    "content-type": "application/json; charset=utf-8",
    "transfer-encoding": "chunked",
    "connection": "keep-alive",
    "vary": [
      "Accept-Encoding",
      "X-HTTP-Method-Override"
    ],
    "x-powered-by": "Express",
    "access-control-allow-origin": "*",
    "etag": "W/\"121-8K0HFD+COvxrTNEoVuZt5w\"",
    "content-encoding": "gzip"
  },
  "Response Body": "{\"user\":{\"username\":\"yuriyegtsg\",\"email\":\"yuriygermanovich0202@gmail.com\",\"token\":\"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0ZGQzZmViYzMxZGUxMWIwMGJjYzQ4MyIsInVzZXJuYW1lIjoieXVyaXllZ3RzZyIsImV4cCI6MTY5NzQxMjMxMiwiaWF0IjoxNjkyMjI4MzEyfQ.VQpiAKkdq4u6spH4sTHykhoyxfuQjY89wsCeOxXzpEU\"}}"
}

// ПОЛУЧЕНИЕ ДАННЫХ ПОЛЬЗОВАТЕЛЯ

GET https://blog.kata.academy/api/user/: {
  "Network": {
    "addresses": {
      "local": {
        "address": "127.0.0.1",
        "family": "IPv4",
        "port": 54992
      },
      "remote": {
        "address": "94.198.50.185",
        "family": "IPv4",
        "port": 443
      }
    },
    "tls": {
      "reused": true,
      "authorized": true,
      "authorizationError": null,
      "cipher": {
        "name": "TLS_AES_128_GCM_SHA256",
        "standardName": "TLS_AES_128_GCM_SHA256",
        "version": "TLSv1/SSLv3"
      },
      "protocol": "TLSv1.3",
      "ephemeralKeyInfo": {},
      "peerCertificate": {
        "subject": {
          "commonName": "blog.kata.academy",
          "alternativeNames": "DNS:blog.kata.academy"
        },
        "issuer": {
          "country": "US",
          "organization": "Let's Encrypt",
          "commonName": "R3"
        },
        "validFrom": "Jul  9 00:23:29 2023 GMT",
        "validTo": "Oct  7 00:23:28 2023 GMT",
        "fingerprint": "92:66:ED:48:43:B5:21:D1:85:63:1A:FC:2A:4C:83:83:00:E2:E0:58",
        "serialNumber": "03fa66f1b05b0a3194a98f73ad5b43baf175"
      }
    }
  },
  "Request Headers": {
    "content-type": "application/json",
    "authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0ZGQzZmViYzMxZGUxMWIwMGJjYzQ4MyIsInVzZXJuYW1lIjoieXVyaXllZ3RzZyIsImV4cCI6MTY5NzQxMDE0OSwiaWF0IjoxNjkyMjI2MTQ5fQ.4u2nsSCy627t8SZ1WyPnVmKJJqQAUzQpBsKsnHFuW4s",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "postman-token": "d32bf100-4d02-425d-aeb6-bc0ccf7077fc",
    "host": "blog.kata.academy",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive",
    "content-length": "102"
  },
  "Request Body": "{\r\n  \"user\": {\r\n    \"email\": \"yuriygermanovich0202@gmail.com\",\r\n    \"password\": \"pass234445\"\r\n\r\n  }\r\n}",
  "Response Headers": {
    "server": "nginx/1.18.0 (Ubuntu)",
    "date": "Wed, 16 Aug 2023 23:16:17 GMT",
    "content-type": "application/json; charset=utf-8",
    "transfer-encoding": "chunked",
    "connection": "keep-alive",
    "vary": "Accept-Encoding",
    "x-powered-by": "Express",
    "access-control-allow-origin": "*",
    "etag": "W/\"121-aAFXsiPtZGo134TYN00thw\"",
    "content-encoding": "gzip"
  },
  "Response Body": "{\"user\":{\"username\":\"yuriyegtsg\",\"email\":\"yuriygermanovich0202@gmail.com\",\"token\":\"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0ZGQzZmViYzMxZGUxMWIwMGJjYzQ4MyIsInVzZXJuYW1lIjoieXVyaXllZ3RzZyIsImV4cCI6MTY5NzQxMTc3NywiaWF0IjoxNjkyMjI3Nzc3fQ.s3syBVKSYsyjDN0s7L2xvpXJ-sjaOt27v3noDZRq88U\"}}"
}