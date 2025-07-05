# Virtual Payment Terminal
A virtual payment terminal for payments, developed by Go.

---

## Used Tools:

- [Chi](https://github.com/go-chi/chi)
- [Chi Cors](https://github.com/go-chi/cors)
- [Stripe Go](https://github.com/stripe/stripe-go)

---

## How to run?

### 1- Install Make

#### for mac:
```bash
brew install make
```

#### for windows:
```bash
choco install make
```

### 2- Copy Makefile-for-mac or Makefile-for-windows (depends on your os) to Makefile

### 3- Paste your secret and publish stripe key in the STRIPE_SECRET STRIPE_KEY in Makefile

### 4- Run this command for start the project:
```bash
make start
```

### 5- You can see payment page on http://localhost:4000/virtual-terminal

### 6- If you want to stop the project, use this command:
```bash
make stop
```