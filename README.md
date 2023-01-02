# playwright-nodejs

playwright를 활용한 tag research

## 참고 URL

---

✅ URL: https://playwright.dev/docs/intro

1️⃣ 초기 코드 세팅

```
mkdir playwright-nodejs
```

2️⃣ playwright code install

```
yarn create playwright
```

```
✔ Do you want to use TypeScript or JavaScript? · TypeScript
✔ Where to put your end-to-end tests? · tests
✔ Add a GitHub Actions workflow? (y/N) · false
✔ Install Playwright browsers (can be done manually via 'yarn playwright install')? (Y/n) · true
```

3️⃣ url 접근하여 해당 click tag tracking<br/>
관련 URL : https://playwright.dev/docs/codegen-intro

```
npx playwright codegen demo.playwright.dev/todomvc
```

4️⃣ cli 실행

```
yarn start
```

Done 🔥
