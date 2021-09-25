# How to log in and get cookies
- It's very simple! Provided by [Flying1008](https://github.com/flying1008)

```
First of all you need to know your Mi account number (not phone number) and its password
```
```
https://account.xiaomi.com/pass/serviceLoginAuth2?_json=true&sid=micoapi&locale=zh_CN&user=</userId>&hash=</password>
```
```
Replace </userId> with your Mi account number, and replace </password> with the uppercase MD5(32) value of your password
```
```
In the end you will get a complete link, using a POST request, you will get the Token you need
```