# floworder
floworder er en lokal app for å teste Claude code. 
Det er et ordresystem integrasrt med unimicro

floworder/
│
├── index.html
│
├── css/
│   ├── style.css
│   ├── layout.css
│   ├── theme-dark.css
│   └── components/
│       ├── modals.css
│       ├── tables.css
│       ├── forms.css
│       └── dashboard.css
│
├── js/
│   ├── main.js
│   ├── config.js
│   ├── storage.js
│   ├── auth/
│   │   ├── pkce.js
│   │   └── auth.js
│   ├── api/
│   │   ├── http.js
│   │   ├── unimicro.js
│   │   └── endpoints.js
│   ├── domain/
│   │   ├── customers.js
│   │   ├── products.js
│   │   ├── orders.js
│   │   └── calculations.js
│   ├── ui/
│   │   ├── dom.js
│   │   ├── navigation.js
│   │   ├── modals.js
│   │   ├── tables.js
│   │   ├── dashboard.js
│   │   ├── toasts.js
│   │   └── orderlines.js
│   └── utils/
│       ├── format.js
│       ├── validators.js
│       └── helpers.js
│
├── assets/
│   ├── logo.svg
│   ├── icons/
│   └── fonts/
│
└── service-worker.js     (for PWA)
