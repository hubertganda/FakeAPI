# FakeAPI
Fake API for prototyping purpose using [typicode json-server](https://jsonplaceholder.typicode.com/)

### Usage
```
https://my-json-server.typicode.com/hubertganda/FakeAPI/[endpoint]
```

### Endpoint
__/login__
```
{
  status: "success",
  token: "token": "RYUsZoL16PQ1qOohw1HWJ72xclWgkacq4TdnJDGX"
}
```
[test it here](https://my-json-server.typicode.com/hubertganda/FakeAPI/login)

__/me__
```
{
  id: 1,
  name: "Hubert Ganda",
  picture: "https://vignette.wikia.nocookie.net/disgaea/images/8/8d/PramD4portrait.jpg/revision/latest?cb=20110819215323&path-prefix=en"
}
```
[test it here](https://my-json-server.typicode.com/hubertganda/FakeAPI/me)

__/users__
```
[
  {
    "id": 1,
    "name": "Hubert Ganda",
    "picture": "https://vignette.wikia.nocookie.net/disgaea/images/8/8d/PramD4portrait.jpg/revision/latest?cb=20110819215323&path-prefix=en",
    "active": 1
  },
  {
    "id": 2,
    "name": "Effene Herry",
    "picture": "https://vignette.wikia.nocookie.net/disgaea/images/2/20/Dark_Lord_Valvoga.png/revision/latest/scale-to-width-down/180?cb=20160930181407&path-prefix=en",
    "active": 1
  },
  {
    "id": 3,
    "name": "Andreas Pangaribuan",
    "picture": "https://vignette.wikia.nocookie.net/disgaea/images/6/6b/Art-51.jpg/revision/latest/scale-to-width-down/185?cb=20100822203237&path-prefix=en",
    "active": 1
  },
  {
    "id": 4,
    "name": "Robert Arifin",
    "picture": "https://vignette.wikia.nocookie.net/disgaea/images/4/42/Mk-king-drake-the-third.jpg/revision/latest/scale-to-width-down/180?cb=20090626071502&path-prefix=en",
    "active": 1
  }
]
```
[test it here](https://my-json-server.typicode.com/hubertganda/FakeAPI/users)
