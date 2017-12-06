# catch-of-the-day


## for github.io/server

#### package.json

	"homepage": "https://geekster909.github.io/catch-of-the-day-build/"

#### index.js

	const repo = `/${window.location.pathname.split('/')[1]}`;

	<BrowserRouter basename={repo}>