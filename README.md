[![Netlify Status](https://api.netlify.com/api/v1/badges/3da15bac-f5c3-4c1d-ae5c-abe6bc542014/deploy-status)](https://app.netlify.com/sites/servicemanual/deploys)

# Defence Service Manual

Helping you meet service standards and do your role in Defence.

Install the long-term support (LTS) version of <a href="https://nodejs.org/en/">Node.js</a>, which includes npm.

## Run app for development

### 1. Clone repo

```
git clone https://github.com/defencedigital/moduk-service-manual.git moduk-service-manual
```

### 2. Navigate to project folder

```
cd moduk-service-manual
```

### 3. Install npm packages

```
npm install
```

### 4. Run app
Watch for changes to `CSS`, `JS`, `Images`, `Nunjucks` or `Markdown`. Automatically update the browser, without the need for a manual refresh.

```
npm run dev
```

Visit: <a href="http://localhost:8080">http://localhost:8080</a>

## Build app for production

Render `CSS`, `JS`, `Images`, `Nunjucks`. Compress files and generates `HTML` pages, ready for production. It also performs a [W3C validation](https://validator.w3.org) on `HTML`, to ensure everything is valid.

```
npm run prod
```
