### Steps

```
1. pnpm create ponder
2. cd <created dir>
3. add RPC on .env.local
4. run `pnpm dev`
5. go http://localhost:42069
```

### query example

```
{
  depositEvents(first:5){
    id
    account
    amount
    timestamp
  }
}
```
