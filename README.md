# React InstantSearch E-commerce UI

Giao dien e-commerce duoc code bang React + TypeScript + Vite, bam sat demo chinh thuc cua Algolia React InstantSearch:

https://instantsearchjs.netlify.app/examples/react/e-commerce/search/?free_shipping=true

## Cong nghe

- React 19
- TypeScript
- Vite
- React InstantSearch
- Algolia Search API

## Chuc nang

- Tim kiem san pham theo thoi gian thuc
- Loc theo danh muc, thuong hieu, gia, free shipping va rating
- Sap xep san pham theo do lien quan hoac gia
- Chon so luong ket qua moi trang
- Phan trang
- Giao dien responsive cho desktop va mobile

## Cai dat

```bash
npm install
```

## Chay project

```bash
npm run dev
```

Sau do mo URL Vite hien thi trong terminal, thuong la:

```text
http://127.0.0.1:5173/
```

Neu port 5173 dang duoc su dung, Vite se tu dong chuyen sang port khac, vi du `5174`.

## Build production

```bash
npm run build
```

Thu muc build se duoc tao tai:

```text
dist/
```

## Cau truc chinh

```text
.
├── App.tsx
├── App.css
├── App.mobile.css
├── Theme.css
├── components/
├── utils/
├── assets/
├── routing.ts
├── index.tsx
├── index.html
├── package.json
└── vite.config.mjs
```

## Nguon tham khao

- Demo goc: https://instantsearchjs.netlify.app/examples/react/e-commerce/search/?free_shipping=true
- Source goc: https://github.com/algolia/instantsearch/tree/master/examples/react/e-commerce
